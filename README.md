# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using various machine learning models. The goal is to build and evaluate different classification models to accurately identify fraudulent transactions from a given dataset.

---
## 📖 Dataset

The dataset used for this project contains transactions made by credit cards in September 2013 by European cardholders. It presents transactions that occurred in two days, with 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

You can download the dataset from the following link:
[Link to Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?select=creditcard.csv)

---
## 🤖 Models Used

The following machine learning models have been implemented and evaluated in this project:

* **Logistic Regression**
* **K-Nearest Neighbors (KNN)**
* **Decision Tree**
* **Support Vector Machine (SVM)**

---
## ⚙️ Setup and Usage

To run the notebooks in this project, you need to have Python and Jupyter Notebook installed. You can follow these steps to set up the environment and run the code:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mrigyank-roy/credit-card-fraud-detection.git](https://github.com/mrigyank-roy/credit-card-fraud-detection.git)
    ```

2.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

4.  **Open the notebook files** (`.ipynb`) and run the cells to see the implementation and results of each model.

---
## 📊 Results

The performance of the models on the test data is as follows:

* **Logistic Regression Accuracy:** 91.87%
* **K-Nearest Neighbors (KNN) Accuracy:** 93.75%
* **Decision Tree Accuracy:** The notebook provides precision, recall, and f1-score, with an overall accuracy of approximately 99.93% on the test set.
* **Support Vector Machine (SVM) Accuracy:** 94.59%

