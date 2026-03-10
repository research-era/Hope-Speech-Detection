**SJM_MINDS@Dravidianlangtech@ACL2026:Machine Learning Approaches for Hope Speech Detection in Code-Mixed Tulu**

This repository contains the implementation of the system developed for the **Hope Speech Detection Shared Task** at DravidianLangTech @ ACL 2026.

The task focuses on identifying different types of encouraging and discouraging speech in code-mixed Tulu social media text.

---

## **Task 1: Coarse-Grained Hope Tone Classification**

The goal of Task 1 is to classify text into the following categories:

- Encouraging
- Discouraging
- Uninvolved
- Blended Tone

Two experimental runs were submitted for this task.

### **Run 1**
- Model: Logistic Regression  
- Feature Representation: TF-IDF (max_features = 5000)

### **Run 2**
- Model: Linear Support Vector Classifier (LinearSVC)  
- Feature Representation: TF-IDF with unigram and bigram features  
- Text preprocessing applied (lowercasing, removing URLs, mentions, hashtags, and punctuation)

Implementation file: `Task1.ipynb`

---

## **Task 2: Fine-Grained Hope Type Classification**

The goal of Task 2 is to classify text into the following categories:

- Optimistic hope
- Realistic hope
- Inspiring hope
- Fading hope
- Hopelessness

### **Run 1**
- Model: Logistic Regression  
- Feature Representation: TF-IDF  

Implementation file: `Task2.ipynb`

---

## **Dataset**

The dataset provided by the shared task organizers includes:

- Training data  
- Development data  
- Test data  

The dataset is not included in this repository and should be obtained from the official shared task organizers.

---

## **Libraries Used**

The implementation uses the following Python libraries:

- pandas  
- numpy  
- scikit-learn  
- re  

Install the required libraries using:
pip install pandas numpy scikit-learn

---

## **Running the Code**

Open the notebooks and execute the cells sequentially.

Task 1 implementation:
Task1.ipynb

Task 2 implementation:
Task2.ipynb

---

## **Output**

The system generates prediction files for submission to the shared task leaderboard.

Output files for Task 1:

-SJM_MINDS_Tulu_run1.csv

-SJM_MINDS_Tulu_run2.csv

Output file for Task 2:

-SJM_MINDS_Tulu.csv

---

## **Author**

Anonymous (for double-blind review)

---

## **License**

This repository is shared for research and academic purposes.

