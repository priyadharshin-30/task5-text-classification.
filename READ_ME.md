Task 5 - Consumer Complaint Text Classification

Objective
Perform text classification on consumer complaint data into 4 categories:
1. Credit reporting, repair, or other personal consumer reports  
2. Debt collection  
3. Consumer Loan  
4. Mortgage

 Model Used:
 Logistic Regression (multi-class)
        - Trained on TF-IDF vectorized complaint text using the Scikit-learn library.

Steps Followed
1. Data loading and cleaning  
2. Text preprocessing (lowercasing, punctuation removal, stopword removal)  
3. Feature extraction with TF-IDF  
4. Model training using Logistic Regression  
5. Evaluation using accuracy, classification report, and confusion matrix  
6. Sample predictions on new complaints

Results
- Accuracy: 90.67%
- Model: Logistic Regression  
- Evaluation Metrics: Precision, Recall, F1-score

Screenshots:
1.Dataset Head
<img width="1121" height="476" alt="image" src="https://github.com/user-attachments/assets/c6fb53e8-7f79-4518-8f56-85cac2d1f005" />
2.Accuracy & Classification Report
<img width="820" height="430" alt="image" src="https://github.com/user-attachments/assets/8b370ed7-a686-418f-9713-da70990e2d28" />
3.Confusion Matrix
<img width="813" height="665" alt="image" src="https://github.com/user-attachments/assets/9a38c951-a796-4849-9831-dc41590f47fe" />
4.Predictions
<img width="883" height="595" alt="image" src="https://github.com/user-attachments/assets/7508d789-ab10-4a33-b03b-dfd7066e8958" />

How to Run:
In bash
pip install -r requirements.txt
jupyter notebook task5.ipynb
