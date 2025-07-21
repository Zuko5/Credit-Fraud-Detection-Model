# Credit Card Fraud Detection

This project is a machine learning-based solution for detecting fraudulent credit card transactions. It leverages a logistic regression model to classify transactions as either legitimate or fraudulent using a highly imbalanced dataset.

## 🔍 Objective

To build a classification model that accurately detects credit card fraud from transactional data, helping financial institutions minimize losses and improve transaction security.

## 📁 Dataset

- The dataset used is obtained from an open-source repository.
- It contains anonymized features resulting from PCA transformation due to confidentiality issues.
- The target variable is:
  - `0` → Legitimate transaction
  - `1` → Fraudulent transaction
- The dataset is highly imbalanced with a very small percentage of fraudulent transactions.

## 🛠️ Dependencies

The following Python libraries are used:

```bash
numpy
pandas
scikit-learn
opendatasets
```

## 📊 Steps Involved

1. **Data Loading** – Dataset is downloaded and loaded using `opendatasets`.
2. **Exploratory Data Analysis (EDA)** – Class distribution and feature correlation are inspected.
3. **Preprocessing** – Features and labels are separated and the data is split into training and testing sets.
4. **Model Training** – Logistic Regression model is trained on the processed data.
5. **Model Evaluation** – Accuracy is computed on both training and test sets to evaluate performance.

## 🧠 Model Used

- **Logistic Regression**  
  Selected due to its simplicity and interpretability for binary classification tasks.

## ⚖️ Handling Class Imbalance

As the dataset is highly imbalanced, accuracy alone is not sufficient. While the current notebook mainly evaluates using accuracy, future iterations can include metrics like:
- Precision
- Recall
- F1-Score
- ROC-AUC

## 📌 Future Improvements

- Implementing advanced models like Random Forest, XGBoost.
- Using SMOTE or other resampling techniques to handle class imbalance.
- Adding confusion matrix and ROC curve visualizations.

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Install the required libraries using pip.
3. Run the notebook in a Jupyter environment or Google Colab.
