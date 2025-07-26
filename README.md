# YBI-foundation-Internship-Project
# 🎓 Chance of Admission Prediction

This Jupyter Notebook leverages machine learning to predict a student's chance of admission into graduate programs, based on academic and extracurricular features. It’s part of the YBI Foundation internship project series, built using Python and popular ML libraries.

---

## 🚀 Key Features

- Data preprocessing and exploratory analysis
- Data visualization with **matplotlib** and **seaborn**
- Model training using **Linear Regression** (plus potentially other regressors)
- Evaluation via **R² score**, **MAE**, and **RMSE**
- Sample prediction using user-provided input values

---

## 📊 Dataset

- The notebook reads a dataset (e.g. `Admission_Predict.csv`) containing features such as:
  - GRE score
  - TOEFL score
  - University Rating
  - SOP / LOR strength
  - CGPA
  - Research experience
  - Target: Chance of Admission percentage

*(Please include your actual dataset filename or path)*

---

## 🧠 Workflow

1. Read the dataset into a pandas DataFrame  
2. Perform data cleaning, feature engineering, and scaling  
3. Visualize correlations and distributions  
4. Split into training and testing data using **train_test_split**
5. Train a **Linear Regression** model (optionally Decision Tree, Random Forest)
6. Evaluate performance using **R²**, **MAE**, and **RMSE**
7. Provide interactive prediction examples (e.g. via input() or Streamlit interface)

---

## 📝 How to Run

```bash
git clone https://github.com/Ayushgit51/YBI‑foundation‑Internship‑Project.git
cd YBI‑foundation‑Internship‑Project
conda create -n admission python=3.8
conda activate admission
pip install -r requirements.txt
jupyter notebook Chance_of_Admission.ipynb
