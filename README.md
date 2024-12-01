# Heart Disease Prediction

This project uses **Data Science** and **Machine Learning** techniques to predict the probability of a patient having heart disease or a heart attack. The objective is to provide insights into the key factors influencing heart disease and develop a high-performing predictive model.

---

## **Problem Context**

Heart disease is the leading cause of death in the United States, claiming approximately 647,000 lives annually. Common risk factors include:
- High blood pressure
- High cholesterol
- Smoking
- Diabetes
- Lifestyle habits and environment

The project aims to address these challenges using open-source data and machine learning to create a robust prediction model.

---

## **Objective**
1. **Prediction**: Build the best-performing model to determine the probability of heart disease.
2. **Insights**: Identify the most important drivers contributing to heart disease or attacks.

---

## **Dataset**
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset) and includes the following features:

### **Data Dictionary**
- `HeartDiseaseorAttack`: Target variable (1 = heart disease, 0 = no heart disease)
- **Key Features**:
  - `HighBP`, `HighChol`, `Smoker`, `Diabetes` (binary indicators)
  - `BMI`: Body Mass Index (numeric)
  - `MentHlth`, `PhysHlth`: Mental and Physical Health (0-30 scale)
  - `Fruits`, `Veggies`: Diet habits (binary)
  - `Age`, `Education`, `Income`: Binned into numeric buckets
  - `Sex`: Gender of the patient
  - `HvyAlcoholConsump`: Heavy alcohol consumption (binary)

---

## **Approach**

1. **Exploratory Data Analysis (EDA)**:
   - Univariate and multivariate analyses to explore data distributions and correlations.
   - Feature engineering to create new insights.

2. **Data Preprocessing**:
   - Handled class imbalance with oversampling and undersampling.
   - Scaled and encoded features for modeling.

3. **Model Training**:
   - Experimented with various binary classification models.
   - Utilized precision-recall curves to determine optimal thresholds.

4. **Evaluation**:
   - Tested all models on the same hold-out dataset.
   - Published performance metrics including accuracy, precision, recall, and F1-score.

5. **Key Insights**:
   - Identified critical features contributing to heart disease.

---

## **Tech Stack**
- **Languages**: Python
- **Libraries**: 
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
- **Tools**: Jupyter Notebook
