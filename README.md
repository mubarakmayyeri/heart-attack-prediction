# Heart Attack Prediction with Machine Learning
This machine learning project is focused on predicting the occurrence of heart attack in patients. The dataset used for this project contains 303 rows and 13 columns, including attributes such as age, sex, cholesterol level, and other factors that may impact the occurrence of a heart attack. The goal of this project is to use an SVM classifier to accurately predict the occurrence of heart attacks.

## Dataset
The dataset contains 303 rows and 13 columns, where each row represents a patient and each column represents an attribute of that patient. The attributes are as follows:

* age: The age of the patient in years
* sex: The gender of the patient (0 for female, 1 for male)
* cp: Chest Pain type (1= typical angina, 2= atypical angina, 3= non-anginal pain, 4= asymptomatic)
* trtbps: Resting blood pressure (in mm Hg)
* chol: Cholesterol level (in mg/dl)
* fbs: Fasting blood sugar (0 for less than 120mg/dl, 1 for greater than 120mg/dl)
* restecg: Resting electrocardiographic results (0= normal, 1= having ST-T wave abnormality, 2= showing probable or definite left ventricular hypertrophy)
* thalachh: Maximum heart rate achieved
* exng: Exercise induced angina (0= no, 1= yes)
* oldpeak: ST depression induced by exercise relative to rest
* slp: Slope of the peak exercise ST segment (1= upsloping, 2= flat, 3= downsloping)
* caa: Number of major vessels (0-3) colored by fluoroscopy
* thall: Thalium stress test result (0-3)

The output variable is 'output', which indicates whether the patient has had a heart attack (1) or not (0).

## SVM Classifier

An SVM classifier was trained on the dataset to predict the occurrence of heart attacks. The classifier was able to achieve an accuracy score of 78%, indicating that it is able to make accurate predictions. However, based on the confusion matrix [[18 9], [4 29]], it can be observed that the model has misclassified 13 out of 58 patients.

* True Positive (TP): 29, model predicted patient having heart attack and the patient actually had a heart attack
* False Positive (FP): 9, model predicted patient having a heart attack but the patient actually didn't have a heart attack
* False Negative (FN): 4, model predicted patient not having a heart attack but the patient actually had a heart attack
* True Negative (TN): 18, model predicted patient not having a heart attack and the patient actually didn't have a heart attack

## Conclusion
Although the SVM classifier was able to achieve a 78% accuracy rate in predicting heart attacks in the given dataset, it is important to keep in mind that the model's error rate of 22% can have serious implications for the health of patients.

As a result, it is crucial for patients to prioritize their overall well-being by leading a healthy lifestyle, seeking medical attention promptly if they experience any symptoms related to heart disease, and following their healthcare provider's advice. This machine learning project emphasizes the significance of early detection and treatment in mitigating the risk of heart disease and highlights the continued need for research and innovation in this area.
