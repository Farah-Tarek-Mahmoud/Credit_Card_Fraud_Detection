# Credit Card Fraud Detection - README

## Project Overview
The objective of this project is to detect fraudulent credit card transactions using a heavily imbalanced dataset. With only 0.17% of transactions classified as fraud, this project focused on overcoming class imbalance while ensuring high sensitivity to fraudulent cases.

---

### Key Features of the Dataset
- **Transaction Details**: Scaled feature set based on PCA transformation.
- **Outcome**: Class label (1: Fraudulent, 0: Non-Fraudulent).

---

## Project Workflow

### 1. Data Preprocessing
- **Exploratory Data Analysis (EDA)**:
  - Visualized transaction distributions to identify patterns.
- **Data Cleaning**:
  - Removed irrelevant features and duplicates.

### 2. Balancing the Dataset
- Applied multiple techniques:
  - Oversampling minority class using **SMOTE**.
  - Undersampling the majority class to create balanced training data.

### 3. Model Training
- Models Used:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- Hyperparameter tuning conducted with **GridSearchCV**.

### 4. Model Evaluation
- Performance Metrics:
  - Precision, Recall, F1-Score
  - Area Under the Precision-Recall Curve
  - Confusion Matrix

### 5. Key Outcomes
- Random Forest and Gradient Boosting achieved high precision and recall for fraud detection.

---

## Conclusion
The project demonstrates the effectiveness of using advanced sampling techniques and ensemble models for fraud detection in highly imbalanced datasets.
