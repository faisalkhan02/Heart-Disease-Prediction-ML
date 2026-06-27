# ❤️ Heart Disease Prediction using Supervised Machine Learning

## 📌 Project Overview

This project predicts whether a patient is likely to have heart disease using supervised machine learning classification algorithms. The objective is to assist in the early identification of heart disease by analyzing patient medical attributes such as age, blood pressure, cholesterol level, chest pain type, and other clinical features.

---

## 🎯 Problem Statement

Heart disease is one of the leading causes of death worldwide. Early diagnosis can help healthcare professionals provide timely treatment and improve patient outcomes. This project develops a binary classification model to predict the presence or absence of heart disease using patient health data.

---

## 📂 Dataset

* **Dataset:** Heart Disease Prediction Dataset
* **Source:** Kaggle (Derived from the UCI Heart Disease Cleveland Dataset)
* **Records:** 270
* **Features:** 13 Input Features + 1 Target Column
* **Target Variable:**

  * **0** = Absence of Heart Disease
  * **1** = Presence of Heart Disease

---

## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── data/
│   └── Heart_Disease_Prediction.csv
│
├── model/
│   ├── logistic_regression_model.pkl
│   ├── random_forest-model.pkl
|   ├── scaler.pkl
│   └── svm_model.pkl
│    
│
├── notebook/
│   └── Heart_Disease_Prediction.ipynb
│
├── results/
│   ├── target_distribution.png
│   ├── age_distribution.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   └── model_performance_comparison.png
│
├── README.md
└── requirements.txt
```

---

## ⚙️ Methodology

The project follows the complete supervised machine learning workflow:

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Saving Trained Models (.pkl)

---

## 🤖 Machine Learning Models Used

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest Classifier

---

## 📊 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📈 Results

| Model                  | Accuracy   |
| ---------------------- | ---------- |
| Logistic Regression    | **85.19%** |
| Support Vector Machine | **81.48%** |
| Random Forest          | **81.48%** |

**Best Performing Model:** Logistic Regression

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/faisalkhan02/Heart-Disease-Prediction-ML.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run all cells to reproduce the results and generate the trained model files.

---

## 📌 Conclusion

This project demonstrates the complete machine learning pipeline for predicting heart disease using supervised learning techniques. Logistic Regression achieved the best performance with an accuracy of **85.19%**, making it the most effective model for this dataset. The project highlights how machine learning can support early disease prediction and assist healthcare professionals in making informed decisions.

---

## 🚀 Future Scope

* Hyperparameter tuning for better performance.
* Test on larger and more diverse datasets.
* Deploy the model using Flask or Streamlit.
* Explore advanced ensemble and deep learning models.

---

## 👨‍💻 Author

**Faisal Khan**

Master of Computer Applications (MCA)

KIET Group of Institutions, Ghaziabad

