# AI/ML Project - Insurance Claim Anticipation

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/142757865-09060edf-1d5b-41e7-9d5e-0139c46899e7.jpg" style="width: 1000px;"/></p>

### Description:

A simple yet challenging project, to anticipate weather the insurace will be claimed or not.
The complexity arises due the fact that dataset has less samples, & is slightly imbalanced.
Can you overcome these obstacles & build a good predictive model to classify them?

**This data frame contains the following columns:**

* age : age of policyholder
* sex: gender of policy holder (female=0, male=1)
* bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 25
* steps: average walking steps per day of policyholder
* children: number of children / dependents of policyholder
* smoker: smoking state of policyholder (non-smoke=0;smoker=1)
* region: the residential area of policyholder in the US (northeast=0, northwest=1, southeast=2, southwest=3)
* charges: individual medical costs billed by health insurance
* insuranceclaim: yes=1, no=0

This is "Sample Insurance Claim Prediction Dataset" which based on "[Medical Cost Personal Datasets][1]" to update sample value on top.

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification model to predict weather the insurance will be claimed or not.
- Also fine-tune the hyperparameters & compare the evaluation metrics of vaious classification algorithms.

### <center> Stractegic Plan of Action:
**We aim to solve the problem statement by creating a plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Data Manipulation
5. Feature Selection/Extraction
6. Predictive Modelling
7. Project Outcomes & Conclusion
  
### Some Visuals of the Project:

**1. Target Variable Distribution**
  
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/142758058-1ca7e77d-9227-4eb5-a5da-4fd43872ffcb.png" /></p>

**2. Categorical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/141759248-04c88851-7edc-46c6-8ae4-3c5498ef7061.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/141759303-b614aa1f-4923-437b-b927-06e795c4b4ae.png)
![image](https://user-images.githubusercontent.com/54996245/141759315-c15fd9a9-81fa-4901-b6c4-65245379491d.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/141759549-7182de06-ef04-45b1-b17f-172b89aa8ecf.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/141759612-f7c76d72-5b27-4c0e-b209-bbfea185db04.png)

**6. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/141759715-06c1d620-fba5-406c-8968-b94494ce2b8c.png)

**7. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/141759915-f8195733-0f5c-40f7-a442-6fb8d079ac09.png)


**8. ML Algorithm's Scores for the Dataset**
![image](https://user-images.githubusercontent.com/54996245/142758050-7ac78f20-47f5-4c1c-b1e4-25df8b572da3.png)
![image](https://user-images.githubusercontent.com/54996245/142758046-3a9d358a-7dc3-4595-b64e-0c95ba4eaf56.png)


### Here are some of the key outcomes of the project:
- The Dataset was small totally around 1338 samples & after preprocessing 17% of the datasamples were dropped. 
- The samples were highly imbalanced, hence SMOTE Technique was applied on the data to  balance the classes, adding 5.5% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the featureset.
- Feature Selection/Eliminination was carried out and appropriate features were shortlisted.
- Testing multiple algorithms with fine-tuning hyperparamters gave us some understanding on the model performance for various algorithms on this specific dataset.
- The boosting & ensemble algorithms perform the best on the current dataset, followed by Nearest Neighbours Algorithm.
- Yet it wise to also consider simpler model like Logistic Regression as it is more generalisable & is computationally less expensive.
