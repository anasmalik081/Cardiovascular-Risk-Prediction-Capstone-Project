# Cardiovascular-Risk-Prediction-Capstone-Project
![github](https://github.com/anasmalik081/Cardiovascular-Risk-Prediction-Capstone-Project/assets/84465546/5eba1d01-8e7a-44dd-b652-8b875736af26)
### Project tile - Cardiovascular Risk Prediction
### Description:
This is a supervised (classification) machine learning capstone project on Cardiovascular risk prediction given by [Alma Better](https://www.almabetter.com/).

![github](https://github.com/anasmalik081/Cardiovascular-Risk-Prediction-Capstone-Project/assets/84465546/5eba1d01-8e7a-44dd-b652-8b875736af26)

### Problem statement:
Cardiovascular diseases (CVDs) are the leading cause of death globally, taking an estimated 18.6 million lives each year, which accounts for 33% of all the global deaths. CVDs are a group of disorders of the heart and blood vessels and include coronary heart disease, cerebrovascular disease, rheumatic heart disease and other conditions. More than four out of five CVD deaths are due to heart attacks and strokes, and one third of these deaths occur prematurely in people under 70 years of age.

It is important to detect cardiovascular disease as early as possible so that management with counselling and medicines can begin.

Our main aim here is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).


![card](https://github.com/anasmalik081/Cardiovascular-Risk-Prediction-Capstone-Project/assets/84465546/901f74ac-6eaf-4882-a69a-e176308d75de)

![github](https://github.com/anasmalik081/Cardiovascular-Risk-Prediction-Capstone-Project/assets/84465546/5eba1d01-8e7a-44dd-b652-8b875736af26)

### Note: Dataset is provided by the company, Alma Better.

### Dataset description:
The dataset is from ongoing cardiovascular study on people of the town Framingham, Massachusetts. The dataset provides the patients information(Sex, Age, is_smoking, cigs_per_day, BP_Meds, Prevalent Stroke, Prevalent hyp, Diabetes, Tot Chol, Sys BP, Dia BP, BMI, Heart Rate)

Attribute Information:
  * age - Patient's age.
  * education - Patient's education.
  * sex : gender(Male or Female).
  * is_smoking - currently patient is a smoker or not.
  * cigsPerDay - Cigarettes smoked per day by patient.
  * BPMeds - Patient taking BP meds or not.
  * prevalentStroke - If the patient has the history of stroke.
  * prevalentHyp - If the patient has the history of hypertention.
  * diabetes - Patient has diabetes or not.
  * totChol - Total cholestrol level.
  * sysBP - Blood Pressure measure.
  * diaBP - Blood Pressure measure.
  * BMI - Patient's body mass index.
  * heartRate - Heart Rate measure.
  * glucose - Glucose Level.
  * TenYearCHD - Future 10 year risk of CHD("0" means No and "1" means Yes.)

![github](https://github.com/anasmalik081/Cardiovascular-Risk-Prediction-Capstone-Project/assets/84465546/5eba1d01-8e7a-44dd-b652-8b875736af26)

### Project Flowchart:

1. Initial preparations(Loading the dependencies and the data)

2. Data Inspection
 
3. Data Wrangling
     * Handling null values.
     * Handling duplicate values.
     * Removing Outliers.
       
4. Exploratory Data Analysis (EDA)

5. Feature engineering
     * Feature encoding
     * Grouping columns for better understanding.
     * Checking correlation for feature removal.
     * Checking the distribution of the data.

6. Pre processing of the data
     * Dealing with class imbalance.
     * Splitting and scaling the data.

7. Model implementation
     * Logistic Regression
     * Decision Tree Classifier
     * Random Forest Classifier
     * XGBoost Classifier
     * K-Nearest Neighbors
     * Naive Bayes Classifier
     * Support Vector Machine Classifier

8. Model explainability

![github](https://github.com/anasmalik081/Cardiovascular-Risk-Prediction-Capstone-Project/assets/84465546/5eba1d01-8e7a-44dd-b652-8b875736af26)

### Conclusion:

1. EDA insights:
     * People in the age group of 40-65 are more at risk of coronary heart disease in future 10 years.
     * Male Patients are more at risk of coronary heart disease as compared to female patients.
     * People who smoke regularly are more likely to get affected from coronary heart disease.
     * People who take blood pressure medication are more at risk of coronary heart disease.
     * Overweighted person or person who have high body mass index have greater chance to get affected by coronary heart disease.
     * If glucose level is high then it is a risk factor of coronary heart disease.
     * Person who have history of hypertention are more at risk of coronary heart disease.

2. Results from ML models:
     * Logistic Regression gave 67 % accuracy on training dataset and 66 % accuracy on test dataset.
     * Decision Tree gave 74 % accuracy on training dataset and 72 % accuracy on test dataset.
     * Random Forest gave 76 % accuracy on training and 74 % accuracy on test.
     * XGBoost gave 100 % accuracy on training and 89 % accuracy on test.
     * K Nearest Neighbors gave 90 % accuracy on training and 83 % accuracy on test.
     * Naive Bayes gave 60 % accuracy on training dataset and 63 % accuracy on test dataset.
     * Support Vector gave 82 % accuracy on training and 76 % accuracy on test.

3. Challenges faced:
     * Feature engineering.
     * Handling class imbalance.
     * Choosing model explainability techniques.

![github](https://github.com/anasmalik081/Cardiovascular-Risk-Prediction-Capstone-Project/assets/84465546/5eba1d01-8e7a-44dd-b652-8b875736af26)

**For further information you can check the google colab file added in the repository.**

**If you find any mistakes or have any suggestions for me, please reach out to me, all the criticism is heartly welcomed.**

**You can also reach out to me for project collaborations.**

**My Email Id - anasmalik081@gmail.com**

**My LinkedIn profile - [Anas Malik](https://www.linkedin.com/in/anas-malik-01/)**

### Thankyou for tagging along to the end.
