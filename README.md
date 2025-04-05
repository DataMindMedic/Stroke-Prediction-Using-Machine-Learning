# 🧠 Stroke Prediction Using Machine Learning

This project aims to predict the likelihood of a stroke in individuals based on health and demographic data. It uses supervised machine learning techniques on a real-world healthcare dataset to assist in early stroke detection and prevention.

## 📚 Dataset

- Source: `healthcare-dataset-stroke-data.csv`
- Records: 5110 rows × 12 columns
- Target variable: `stroke` (0 = No Stroke, 1 = Stroke)

## 🔍 Features Include:

- `gender`
- `age`
- `hypertension`
- `heart_disease`
- `ever_married`
- `work_type`
- `Residence_type`
- `avg_glucose_level`
- `bmi`
- `smoking_status`

## ⚙️ Project Workflow

1. **Data Cleaning**  
   - Handled missing values (e.g., BMI)
   - Removed or replaced outliers if needed

2. **Feature Engineering**  
   - Encoded categorical variables
   - Created new features 

3. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions, correlations, and stroke rates by feature

4. **Model Training & Evaluation**  
   - Trained machine learning models (e.g., Logistic Regression, Random Forest)
   - Evaluated using accuracy, precision, recall, F1-score

5. **Result Interpretation**  
   - Identified key predictors of stroke

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 🚀 How to Run

1. **Clone this repo**:
   ```bash
   git clone https://github.com/EunMic9192/stroke-prediction.git
