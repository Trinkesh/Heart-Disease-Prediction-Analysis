# Heart-Disease-Prediction-Analysis


Heart diseases is a term covering any disorder of the heart. Heart diseases have become a major concern to deal with as studies show that the number of deaths due
to heart diseases have increased significantly over the past few decades in India, in fact it has become the leading cause of death in India.
Thus preventing Heart diseases has become more than necessary. Good data-driven systems for predicting heart diseases can improve the entire research and prevention process,
making sure that more people can live healthy lives. This is where Machine Learning comes into play. Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.
[kaggle project](https://www.kaggle.com/ronitf/heart-disease-uci)

![medical-stethoscope-and-mask-composed-with-red-foiled-4386466](https://user-images.githubusercontent.com/62785642/87222572-49dbbb00-c392-11ea-976a-e05ee1ab158a.jpg)

The project is made to predict heart disease analysis using machine learning algorithms and to analysis using visualization.
project implemented three machine lerning model using sklearn.RandomForest,knneighbores,Logestic Reggresion algorithams been used to perform heart disease analysis.

[The dataset I used from kaggle](https://www.kaggle.com/ronitf/heart-disease-uci)

[heart-Disease data set Uci archive](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

You can download any both dataset are same.  

![silhouette-photo-of-man-leaning-on-heart-shaped-tree-744667](https://user-images.githubusercontent.com/62785642/87222598-9cb57280-c392-11ea-9a39-2fecbf856641.jpg)

The dataset consites of 14 features.(All information taken from uci public dataset archive)


Only 14 feature used:
1. age
2. sex
3. cp
4. trestbps
5. chol
6. fbs
7. restecg
8. thalach
9. exang
10.oldpeak
11.slope
12.ca
13.thal
14.num (the predicted attribute)

Age : displays the age of the individual.
Sex : displays the gender of the individual using the following format : 1 = male 0 = female.

Chest-pain type : displays the type of chest-pain experienced by the individual using the following format : 1 = typical angina 2 = atypical angina 3 = non - anginal pain 4 = asymptotic

Resting Blood Pressure : displays the resting blood pressure value of an individual in mmHg (unit)

Serum Cholestrol : displays the serum cholestrol in mg/dl (unit)

Fasting Blood Sugar : compares the fasting blood sugar value of an individual with 120mg/dl. If fasting blood sugar > 120mg/dl then : 1 (true) else : 0 (false)

Resting ECG : 0 = normal 1 = having ST-T wave abnormality 2 = left ventricular hyperthrophy

Max heart rate achieved : displays the max heart rate achieved by an individual.

Exercise induced angina : 1 = yes 0 = no

ST depression induced by exercise relative to rest : displays the value which is integer or float.

Peak exercise ST segment : 1 = upsloping 2 = flat 3 = downsloping

Number of major vessels (0-3) colored by flourosopy : displays the value as integer or float.

Thal : displays the thalassemia : 3 = normal 6 = fixed defect 7 = reversable defect

Diagnosis of heart disease : Displays whether the individual is suffering from heart disease or not : 0 = absence 1,2,3,4 = present.

## Prediction:
The two inputs of the prediction component are the model and the prediction set. The prediction result shows the predicted data, actual data, and the probability of different results in each group.

### Evaluation:
The confusion matrix, also known as the error matrix, is used to evaluate the accuracy of the model.
