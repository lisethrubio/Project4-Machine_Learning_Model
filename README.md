# Project4-Machine_Learning_Model

## Fitness Bootcamp Body Performance Data Model

 At Fitness Bootcamp, we are a healthcare-focused gym committed to helping our members achieve their fitness goals. We use supervised machine learning model to classify members into two categories based on their Biometrics and Fitmetrics. This optimized model helps us tailor personal training sessions to maximize each member's fitness and health outcomes.

## Our Machine Learning Classification Model

We aim to develop a supervised machine learning model to predict member classifications into two distinct categories (A & D) based on body performance data. These categories are stratified, with Class A representing the highest fitness level and Class D representing the lowest. The body performance data analyzes key measurements such as physical and fitness measurements. Once a member is classified into a category, Fitness Bootcamp recommends a tailored number of personal training sessions to ensure that the program aligns with the member's specific health and fitness needs. The gym’s goal is to determine the optimal number of sessions that can be recommended for everyone, based on their classification, to maximize their fitness outcomes.


## Features:
- Age: 20 to 64 years
- Gender: F (Female), M (Male)
- Height: Height in centimeters
-	Weight: Weight in kilograms
-	Body Fat Percentage: Percentage of body fat
-	Diastolic Blood Pressure: Minimum diastolic blood pressure (in mmHg)
-	Systolic Blood Pressure: Minimum systolic blood pressure (in mmHg)
-	Grip force: A measure of the maximum strength of an individual's hand and forearm muscles when squeezing a grip dynamometer.
-	Sit and bend forward (cm): A flexibility test that measures the distance an individual can reach forward while sitting with legs extended, often used to assess lower back and hamstring flexibility.
-	Sit-ups count: The number of sit-ups an individual can perform in a set time period, used to assess core strength and endurance.
-	Broad jump (cm): The distance an individual can jump forward from a standing position, measuring explosive leg strength and power.


## Label Set

- Classification columns:  
  -	Class A: Best performance
  -	Class D:  Not best performance 

## Source of Dataset

https://www.kaggle.com/datasets/kukuroo3/body-performance-data?resource=download

## Data Model Implementation and Optimization

-	Python Pandas 
-	Python Matplotlib 
-	Google Colab
-	Scikit-learn Machine Learning library  


## Limitations of the Model :
Biometrics are often considered more important than fitness measurements when testing body performance because they provide objective, individualized data related to a person's overall health status, risk factors, and physiological characteristics. While Fitmetrics, such as “grip strength” or “sit-up counts”, assess specific physical abilities, biometrics like “body fat %”, “blood pressure”, and “body composition” offer insights into underlying health conditions, metabolic efficiency, and potential medical risks, contributing to a more comprehensive understanding of health. However, given that the random forest analysis suggests biometrics have less weight in our model compared to fitmetrics, we face limitations in predicting classifications, as the model currently places more importance on fitness metrics.

## Future Approches :

The strategies that can help create a more balanced model that appropriately considers both biometrics and fitness metrics are:

-	Creating new features combining biometrics and fitness metrics to capture their relationships.
-	Standardizing all features to ensure equal importance in the model.
-	Adjusting the model to give more importance to biometrics by oversampling or modifying feature importance thresholds.
-	Training separate models for biometrics and fitness metrics, then combining their outputs.
-	Adjusting model parameters to reduce sensitivity to fitness metrics.
-	Collecting more diverse data to better capture biometric patterns.

## Tasks: 

-	Derilee Walters: cleaning, machine learning model
-	Steven Quintero: machine learning model 
-	Kim Aissa: cleaning, machine learning model
-	Liseth Rubio: presentation, machine learning model
