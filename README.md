🧠 OIBSIP_Data_Analytics_Task7

💳 Fraud Detection Using Machine Learning on Credit Card Transactions

---

📌 Project Overview

This project focuses on detecting fraudulent transactions using machine learning techniques. Fraud detection is a critical task in financial systems, as it helps in preventing financial losses and ensuring secure transactions.

In this project, a dataset of credit card transactions is analyzed, and a classification model is developed to distinguish between normal and fraudulent transactions.

---

🎯 Objectives

- Analyze credit card transaction data
- Identify patterns in fraudulent transactions
- Handle class imbalance in the dataset
- Build a machine learning classification model
- Evaluate model performance using appropriate metrics

---

📂 Dataset Information

- Total Transactions: 284,807
- Total Features: 31
- Features V1–V28 are anonymized (PCA transformed)
- Other features: Time, Amount
- Target Variable:
  - 0 → Normal Transaction
  - 1 → Fraudulent Transaction

---

🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

🧹 Data Preprocessing

- Checked for missing values (none found)
- Verified data types and structure
- Identified class imbalance in the dataset
- Applied undersampling technique
- Created a balanced dataset with equal fraud and normal transactions

---

⚖️ Class Imbalance Handling

Original Dataset:

- Normal: 284,315
- Fraud: 492

After Undersampling:

- Normal: 492
- Fraud: 492

This significantly improved the model’s ability to learn patterns from both classes.

---

🤖 Model Building

A Logistic Regression model was used for classification.

Steps:

- Split data into training and testing sets (80:20)
- Trained the model on training data
- Tested the model on unseen data

---

📊 Model Evaluation

- Accuracy: 94%
- High precision and recall for both classes
- Confusion Matrix shows very few misclassifications

👉 The model performs effectively in detecting fraudulent transactions.

---

📈 Visualization

- Confusion Matrix used for performance evaluation
- Clearly shows correct and incorrect predictions

---

💡 Final Insights & Recommendations

- The dataset was highly imbalanced initially
- Undersampling helped balance the dataset effectively
- The model performs well in detecting fraud cases
- Clean dataset and structured features improved performance

👉 Recommendation:
Use advanced techniques like SMOTE, Random Forest, or XGBoost to further improve model performance.

🙌 Conclusion

The fraud detection model successfully identifies fraudulent transactions with high accuracy. This project demonstrates how machine learning can be effectively used to enhance financial security systems.

📁 Project Structure

OIBSIP_Data_Analytics_Task7

fraud_detection.ipynb

report.pdf

README.md

📬 Connect with Me

🔗 LinkedIn: https://www.linkedin.com/in/simran-s-2116303b9?utm_source=share_via&utm_content=profile&utm_medium=member_android
🔗 GitHub: https://github.com/simran04-hub
