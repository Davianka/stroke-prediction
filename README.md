According to the WHO, Stroke is the second leading cause of death globally. This dataset is used to predict whether a patient is likely to get a stroke based on parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.
# Predicting Stroke
According to the WHO, Stroke is the second leading cause of death globally. This dataset is used to predict whether a patient is likely to get a stroke based on parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

Here is the Data Dictionary for this dataset:
1) id: unique identifier 
2) gender: "Male", "Female" or "Other" 
3) age: age of the patient 
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension 5
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease 
6) ever_married: "No" or "Yes
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban" 
9) avg_glucose_level: average glucose level in blood 
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not *Note: "Unknown" in smoking_status means that the 

There is an imbalance in the dataset stroke and no stroke. 4700 "no Stroke" to 206 "stroke". I will be using Smote to help the model Train better.   

My best results were Smote Decision Tree, the accuracy was about 93%, however, it predicted a lot of false negatives.  Using a Decision tree gave good accuracy results but I wasnt happy with the amount of false negatives, so I added Smote for Decision Tree and it lowered the testing accuracy but also lowered the false negatives.

Interesting Trends.  
People who suffered stroke on average are older than those who did'nt have one
![image](https://user-images.githubusercontent.com/87108987/184285473-ff730b63-5d74-4ea6-b313-597e8eca2ef8.png)
Another trend is those with hypertension  were more likely to have a stroke than those who don't have hypertension.
![image](https://user-images.githubusercontent.com/87108987/184287929-e6b0daa3-3fdd-450c-9522-f24f516890a1.png)



contact info:
Davianka Lopez-Wynn
daviwynn@gmail.com
davianka.lopez@gmail.com
