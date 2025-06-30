# Heart-Disease-Prediction
Heart disease is one of the leading causes of death globally, and early prediction of heart disease can help save lives through timely intervention. This project applies data science and analytics techniques to predict the likelihood of heart disease in patients based on various clinical features. Using machine learning models trained on medical datasets, this tool aims to assist healthcare professionals in risk assessment and decision-making.

OBJECTIVES

 Analyze patient health data to identify important risk factors
 Apply machine learning algorithms to build predictive models
 Evaluate models for accuracy and reliability
 Provide a user-friendly prediction interface (optional)
Support data-driven decision-making for preventive healthcare

DATASET

The project uses a standard heart disease dataset (such as the Cleveland Heart Disease dataset from the UCI Machine Learning Repository), containing features including:

Age

Sex

Chest pain type

Resting blood pressure

Cholesterol level

Fasting blood sugar

Resting ECG results

Maximum heart rate achieved

Exercise-induced angina

ST depression (oldpeak)

Slope of the peak exercise ST segment

Number of major vessels colored by fluoroscopy

Thalassemia

Heart disease diagnosis (target variable)

Methodology
Data Preprocessing

Handling missing values

Data normalization and encoding categorical features

Feature selection to identify the most relevant attributes

Exploratory Data Analysis (EDA)

Statistical summary of the dataset

Visualizations (histograms, heatmaps, correlation plots) to understand relationships

Model Building

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine

K-Nearest Neighbors

(Optional: XGBoost, Neural Networks)

Model Evaluation

Confusion matrix

Accuracy, precision, recall, F1-score

ROC curve and AUC

Prediction

Testing the trained models on unseen data

Comparing model performance

RESULTS

The best-performing model was evaluated and demonstrated promising predictive power, capable of classifying heart disease risk with high accuracy. The analysis also highlighted the most important risk factors, such as chest pain type, maximum heart rate, and ST depression.


HOW TO RUN

Clone the repository

git clone https://github.com/santwanaBehera/Heart-Disease-Prediction.git
cd heart-disease-prediction
Install dependencies

pip install -r requirements.txt
Run the Jupyter notebook

jupyter notebook
or execute the Python script:

python heart_disease_prediction.py


CONCLUSION

This project demonstrates the power of data science and machine learning to tackle critical healthcare challenges. By identifying patterns in patient data, the system provides a predictive tool that can support clinicians in assessing heart disease risk, potentially leading to earlier interventions and better outcomes.


FUTURE SCOPE

Integrate the model into a web or mobile application

Deploy the model on cloud platforms

Use larger and more diverse datasets

Incorporate time-series patient monitoring data


ACKNOWLEDGMENT


UCI Machine Learning Repository

Scikit-learn, Pandas, Matplotlib, Seaborn

Medical researchers and healthcare professionals
