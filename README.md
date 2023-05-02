# ML_Project
Deplying Machine Learning Algorithms to predict the occurance of stroke in a person.

# Problem Statement
Stroke is the second largest cause of mortality worldwide and remains an enormous health burden for individuals. Hypertension, heart illness, diabetes and dysregulation of glucose metabolism, atrial fibrillation, and lifestyle variables are some of the controllable risk factors of stroke. The objective of our project is to successfully predict a person’s likelihood of suffering a stroke based on potentially modifiable risk variables by applying machine learning methods to big data sets. This may be done by analyzing medical records using machine learning models to find patterns that are related to the risk of stroke. 

# About the dataset
The dataset we use consists of 5111 rows and 12 columns. <br> 
● Id : Unique Identifier. <br> 
● Gender : "Male", "Female" or "Other".<br> 
● Age : Age of the patient.<br> 
● Hypertension : 1 if the patient has hypertension or 0 if not.<br> 
● Heart_disease : 1 if the patient has a heart disease or 0 if not.<br>  ● Ever_married : "No" or "Yes". <br> 
● Work_type : "Never_worked", "Children", "Govt_job", "Private", “Self_emp".<br> 
● Residence_type : "Rural" or "Urban". <br> 
● Avg_glucose_level : Average glucose level in blood. <br> 
● Bmi : body mass index. <br> 
● Smoking_status : "Formerly smoked", "Never smoked", "Smokes" or "Unknown". <br> 
● Stroke : 1 if the patient will have a stroke or 0 if not. 

# ML Algorithms Used
Decision Trees <br> 
Random Forest <br> 
Logistic Regression <br> 
Naive Bayes <br> 
SVM <br> 
KNN <br> 
Neural Networks MLP 

# Libraries and Frameworks Needed
scikit-learn <br> 
numpy <br>
mathplotlib <br> 
seaborn 

# SETUP
1.Download the repository usiing the "git clone" command.<br> 
2.Upload the "stroke_prediction.ipynb" file to google colab.<br> 
3.Upload the "healthcare-dataset-stroke-data.csv" file to the runtime.<br>
4.Copy and Paste the relative path of the dataset to """ stroke_data=pd.read_csv(**'/healthcare-dataset-stroke-data.csv'**) """ <br>
5.Run the colab file.
