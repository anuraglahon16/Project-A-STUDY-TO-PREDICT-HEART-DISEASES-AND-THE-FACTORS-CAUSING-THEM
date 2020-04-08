# Project : A STUDY TO PREDICT HEART DISEASES AND THE FACTORS CAUSING THEM


Overview of the Dataset

Python Packages

Handling missing data

Data Understanding and EDA

Feature Selection

Modeling and Evaluation

## Introduction¶
World Health Organization has estimated 12 million deaths occur worldwide, every year due to Heart diseases. Half the deaths in the United States and other developed countries are due to cardio vascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high risk patients and in turn reduce the complications. This research intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk using logistic regression

## Data Preparation
Source The dataset is publically available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Variables Each attribute is a potential risk factor. There are both demographic, behavioral and medical risk factors.

## Demographic:
• male: 1 means male and 0 means female(categorical)

• Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

## Behavioral
• Current Smoker: whether or not the patient is a current smoker (Nominal)

• Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

## Medical( history)
• BP Meds: whether or not the patient was on blood pressure medication (Nominal)

• Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

• Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

• Diabetes: whether or not the patient had diabetes (Nominal)

## Medical(current)
• Tot Chol: total cholesterol level (Continuous)

• Sys BP: systolic blood pressure (Continuous)

• Dia BP: diastolic blood pressure (Continuous)

• BMI: Body Mass Index (Continuous)

• Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)

• Glucose: glucose level (Continuous)

## Response variable ( target)
• 10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)

## Documentation:
[Project Documentation](https://github.com/anuraglahon16/Project-A-STUDY-TO-PREDICT-HEART-DISEASES-AND-THE-FACTORS-CAUSING-THEM/blob/master/Project%20documentation%20Final.docx)

## Python file :
[Python Project file](https://github.com/anuraglahon16/Project-A-STUDY-TO-PREDICT-HEART-DISEASES-AND-THE-FACTORS-CAUSING-THEM/blob/master/Project%20.ipynb)

## Project Presentation file :
[Presentation file] (https://github.com/anuraglahon16/Project-A-STUDY-TO-PREDICT-HEART-DISEASES-AND-THE-FACTORS-CAUSING-THEM/blob/master/Presentation.pptx)

## Video :
https://www.youtube.com/watch?v=WsLfQEeY2-8&t=202s

## Blog :
https://medium.com/@anuraglahonmba/a-study-to-predict-heart-diseases-and-the-factors-causing-them-838f5fbb382a


## Summary
1.For the given dataset, Logistic Regression performs better on testing dataset than KNN classifier and Random Forest Classifier.

2.The Logistic Regression model accuracy is 85.84 %. So, the model does a good job in predicting whether the patient has 10-year risk of future coronary heart disease (CHD).

3.The accuracy of Logistic Regression is 85.84% and the model is not overfitting or underfitting.
