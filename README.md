# Data Science project 
The Data source is diverse. It will elaborate more details on each project's readme file

## crowdfunding marketing data set
- Source of data : Datacamp
- Analyze data for marketing campaign 
- Creating a single visualization to explore the data
- Including  following 3 questions
  - top 3 categories in terms of total donation
  - type of device the most contribution
  - age braket should tarket
  
  
 ## Hospital readmission
 - Source of data : Datacamp
 - Analyze hospital readmission 
 - Including  following 3 questions
    - The most common primary diagnosis by age group
    - The effect of a diabetes diagnosis on readmission rates
    - Groups of patients should the hospital focus their follow-up efforts to better monitor patients with a high probability of readmission
 #### Summary
 - Circulatory is the most common primary diagnosis above age 50s but age of 40s are more diagnosis as other reason.
 - The second and the third diagnosis are other and respiratory.
 - Unlike some doctors' belief in relationship between readmission and diabetes, there are no correlation between readmission and diabetes
 - Number of lab procedure, number of medication, times in hospital, number of procedure, outpatient and inpatient features are important feature to predict whether       or not patients' readmissions.
 - Patients who has higher number of inpatient are higher chance to readmission but  lower number of inpatient is less likely to readmitted to the hospital.
 - The number of emergency and outpatient numbers are the same as inpatient feature explanation. Patients who often carries in emergency and visit the hospital as          outpatient are more likely to be readmitted compared to those are not. 
 - On the other, number of medications feature can interpret opposite perspective. Those who often prescribe medicine are less likely to be readmitted than those who      are not. 

#### Limitation
- The accuracy score of model is not high enough. Hence it requires search hyperparameters to enhance its prediction score. 
- In Here, the only one model is used for prediction of readmission of patients. It will be more powerful if it uses other models such as logistic regression, KNN which are different methodology to predict problems. 
