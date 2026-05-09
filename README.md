Milestone 2 : https://colab.research.google.com/drive/1T8kwykV-W0NY8enOHiXPpmhDzKZSol0f?usp=sharing

Milestone 3 : https://colab.research.google.com/drive/1HUoy7F-IzBwj31ZRLXx2cYY68htEuARH?usp=sharing



# Customer Churn Prediction Project

This repository contains the implementation of a machine learning pipeline to predict customer churn. The project is divided into two major milestones covering the end-to-end data science lifecycle, from data exploration to model deployment.

## 📌 Project Overview
Customer churn occurs when customers stop doing business with a company. Predicting this behavior allows businesses to take proactive measures to retain high-value customers. This project utilizes demographic, account, and behavioral data to build a predictive classification model.

---

## 📂 Project Structure

### [Milestone 2: Exploratory Data Analysis & Preprocessing](https://colab.research.google.com/drive/1T8kwykV-W0NY8enOHiXPpmhDzKZSol0f?usp=sharing)
This notebook focuses on understanding the data and preparing it for modeling.
* **Data Cleaning:** Handling null values, duplicates, and correcting data types.
* **EDA:** Visualization of churn drivers using histograms, box plots, and correlation heatmaps.
* **Feature Engineering:** * One-Hot Encoding for categorical variables.
    * Feature Scaling (Standardization/Normalization).
    * Addressing class imbalance.

### [Milestone 3: Model Development & Evaluation](https://colab.research.google.com/drive/1HUoy7F-IzBwj31ZRLXx2cYY68htEuARH?usp=sharing)
This notebook focuses on the machine learning implementation and optimization.
* **Model Training:** Implementing algorithms such as Logistic Regression, Random Forest, and XGBoost/Gradient Boosting.
* **Evaluation:** Using Confusion Matrices, ROC-AUC curves, Precision-Recall, and F1-score to assess performance.
* **Hyperparameter Tuning:** Utilizing `GridSearchCV` to optimize model parameters for better accuracy and generalization.

---

## 🛠️ Tech Stack
* **Environment:** Google Colab / Jupyter Notebook
* **Languages:** Python 3.x
* **Libraries:** * `pandas`, `numpy` (Data Processing)
    * `matplotlib`, `seaborn` (Data Visualization)
    * `scikit-learn` (Machine Learning)

## 🚀 How to Use
1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/churn-prediction.git
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  **Run the Notebooks:** Start with Milestone 2 for data prep, then proceed to Milestone 3 for modeling.

---
