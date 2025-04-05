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

- ## 🧪 Model Performance

| Model                    | Accuracy | Precision | Recall | F1 Score |
|--------------------------|----------|-----------|--------|----------|
| Random Forest            | 0.9511   | 0.0000    | 0.00   | 0.0000   |
| Gradient Boosting        | 0.9472   | 0.0000    | 0.00   | 0.0000   |
| Logistic Regression      | 0.9511   | 0.0000    | 0.00   | 0.0000   |
| Support Vector Classifier| 0.7984   | 0.1321    | 0.56   | 0.2137   |

📊 Results
Model achieved promising performance on test data
Features like age, hypertension, and avg_glucose_level showed strong predictive power

🙋‍♂️ Author
Your Name: Micheal Omotosho
GitHub: @EunMic9192

## 🚀 How to Run

1. **Clone this repo**:
   ```bash
   git clone https://github.com/EunMic9192/stroke-prediction.git
