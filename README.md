# 🫀 Heart Disease Prediction - EDA

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Heart Disease dataset.  
The goal is to study patient health records, analyze key risk factors, and visualize relationships between features and the presence of **heart disease**.

---

## 📂 Dataset
The dataset contains patient health information with the following features:

- **Age** → Age of the patient  
- **Sex** → Gender (M/F)  
- **ChestPainType** → Type of chest pain (e.g., typical angina, asymptomatic, etc.)  
- **RestingBP** → Resting blood pressure (mm Hg)  
- **Cholesterol** → Serum cholesterol level (mg/dL)  
- **FastingBS** → Fasting blood sugar > 120 mg/dL (1 = True, 0 = False)  
- **RestingECG** → Resting electrocardiogram results  
- **MaxHR** → Maximum heart rate achieved  
- **ExerciseAngina** → Exercise-induced angina (Y/N)  
- **Oldpeak** → ST depression induced by exercise relative to rest  
- **ST_Slope** → The slope of the peak exercise ST segment  
- **HeartDisease** → Target variable (1 = presence of heart disease, 0 = absence)  

---

## 🔎 EDA Workflow
The analysis includes:

1. **Data Cleaning & Preprocessing**  
   - Checked missing values, duplicates, and data types  
   - Encoded categorical variables (Sex, ChestPainType, RestingECG, ExerciseAngina, ST_Slope)  

2. **Univariate Analysis**  
   - Distribution plots for Age, Cholesterol, RestingBP, MaxHR, Oldpeak  
   - Countplots for categorical variables (Sex, ChestPainType, ExerciseAngina, etc.)  

3. **Bivariate Analysis**  
   - Boxplots of numerical variables vs. HeartDisease  
   - Countplots of categorical variables vs. HeartDisease  

4. **Correlation Analysis**  
   - Correlation heatmap for numerical variables  
   - Key patterns across features and target  

5. **Insights**  
   - Patients with **asymptomatic chest pain** show higher heart disease prevalence  
   - **Older age** and **higher cholesterol** are linked to increased risk  
   - Low **MaxHR** and high **Oldpeak** strongly correlate with heart disease  
   - Exercise-induced angina is a significant predictor  

---

## 🛠️ Tech Stack
- **Python**
- **Pandas**, **NumPy** for data analysis  
- **Matplotlib**, **Seaborn** for visualization  

---

## 📊 Example Visualizations
- Age distribution and its relation to heart disease  
- ChestPainType vs HeartDisease countplots  
- Correlation heatmap of numeric features  
- Boxplots (Cholesterol, RestingBP, Oldpeak vs. HeartDisease)  

---

## 📌 Conclusion
This EDA provides insights into risk factors contributing to **heart disease**.  
Findings indicate strong associations with **age, cholesterol, chest pain type, and exercise-induced angina**, which can support further **predictive modeling**.  

---

## 🚀 Future Work
- Apply machine learning models for classification (Logistic Regression, Random Forest, XGBoost)  
- Perform feature engineering for improved accuracy  
- Compare predictive results across models  
