# Lung Cancer Prediction

## Overview
This project focuses on predicting the likelihood of lung cancer based on various health and lifestyle factors. Using a dataset containing features such as age, smoking habits, symptoms, and medical history, a machine learning model was developed to classify individuals as high-risk or low-risk for lung cancer. The goal is to assist healthcare professionals in early diagnosis and intervention.

## Objectives
- Analyze the relationship between health/lifestyle factors and lung cancer.
- Build a predictive model to classify individuals based on their risk of lung cancer.
- Evaluate the performance of the model using appropriate metrics.

## Dataset
The dataset contains the following features:
- **GENDER**: Gender of the individual.
- **AGE**: Age of the individual.
- **SMOKING**: Smoking habits (Yes/No).
- **YELLOW_FINGERS**: Presence of yellow fingers (Yes/No).
- **ANXIETY**: History of anxiety (Yes/No).
- **PEER_PRESSURE**: Peer pressure to smoke (Yes/No).
- **CHRONIC DISEASE**: History of chronic disease (Yes/No).
- **FATIGUE**: Presence of fatigue (Yes/No).
- **ALLERGY**: History of allergies (Yes/No).
- **WHEEZING**: Presence of wheezing (Yes/No).
- **ALCOHOL CONSUMING**: Alcohol consumption habits (Yes/No).
- **COUGHING**: Presence of chronic coughing (Yes/No).
- **SHORTNESS OF BREATH**: Presence of shortness of breath (Yes/No).
- **SWALLOWING DIFFICULTY**: Difficulty in swallowing (Yes/No).
- **CHEST PAIN**: Presence of chest pain (Yes/No).
- **LUNG_CANCER**: Target variable indicating the presence or absence of lung cancer (Yes/No).

## Methodology
1. **Data Preprocessing**:
   - Handled missing values and encoded categorical variables.
   - Normalized numerical features (e.g., age) for better model performance.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of features and their relationship with the target variable.
   - Used visualizations to identify trends and correlations.

3. **Feature Selection**:
   - Identified the most significant features contributing to lung cancer prediction using techniques like correlation analysis and feature importance.

4. **Model Building**:
   - Split the dataset into training and testing sets.
   - Trained multiple machine learning models (e.g., Logistic Regression, Random Forest, XGBoost).
   - Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.

5. **Model Evaluation**:
   - Selected the best-performing model based on evaluation metrics.
   - Analyzed the confusion matrix and ROC-AUC curve for deeper insights.

## Tools Used
- **Python**: For data preprocessing, analysis, and model building.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning algorithms and evaluation.
- **Matplotlib/Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive coding and documentation.

