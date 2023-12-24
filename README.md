# Stroke-Prediction

Description of the dataset :
A stroke is a medical emergency, and prompt treatment is crucial. Early action can reduce brain damage and other complications.

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.

This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relevant information about the patient.

Attribute Information :
id: unique identifier
gender: "Male", "Female" or "Other"
age: age of the patient
hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
ever_married: "No" or "Yes"
work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
Residence_type: "Rural" or "Urban"
avg_glucose_level: average glucose level in blood
bmi: body mass index
smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
stroke: 1 if the patient had a stroke or 0 if not
Note: "Unknown" in smoking_status means that the information is unavailable for this patient

Source :
The dataset is associated with a research paper which is based on the Electronic Health Record (EHR) controlled by McKinsey & Company.Click here: McKinsey Analytics Online Hackathon - Healthcare Analytics

The study : please click here :IEEE Xplore-Text PDF

The true source of the data is confidential, giving the sensitive content. The data is only for educational purposes.

The goal of our project is to predict whether an individual will suffer a stroke or not, by building multiple models and choosing the best performing one. To help us find the variables that are most indicative of the possibility of having a stroke or not, we will perform multiple data visualizations. And after that we will build our models and evaluate their performance to choose the best one in the end.

To accomplish this, we will proceed by the following steps :

Finding the missing data and dealing with it.
We will explore our data using visualizations to answer questions like, what variable makes a person more likely to suffer from a stroke ?
We will try to extract insights from the previous step, that will help us understand the data more.
Plotting all the variables to get a general overview, to find interesting trends and features of the data.
We will construct our predictive model, using a random forest model and a logistic regression model.
In the end, we will choose the model with the best accuracy.
