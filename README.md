# Potential Data sets for Prediction
![electrocardiogram-36732](https://user-images.githubusercontent.com/125017784/230833923-0714860a-dca3-4971-bed7-eda5e18125ad.png)

## Heart Failure Prediction Data Set
![Screenshot 2023-04-09 215313](https://user-images.githubusercontent.com/125017784/230834016-01a54c5d-dd9d-4657-bbef-0a27e183af1d.png)

source: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

**TARGET: HeartDisease**  

- What does one row represent? (A person?  A business?  An event? A product?)
  
  * One row represents a **person**.

-  Is this a classification or regression problem?
 
   * This is a **Classification** Problem.

- How many features does the data have?

  * A total of **12 features**.

-  How many rows are in the dataset?
 
   * A total of **918** patients/rows

-  What, if any, challenges do you foresee in cleaning, exploring, or modeling this dataset?

   * We have a clean data.
   * Exploring the data will is a trick as we can see EKG on the data.
   * Choosing a model will a big challenge as I'm not sure if we have enough data to make a good prediction.
   
   
   
## Stroke Prediction Dataset
![Screenshot 2023-04-09 215632](https://user-images.githubusercontent.com/125017784/230834248-c8fac665-57b2-4448-9cd0-833ef8112dda.png)

source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

**TARGET: stroke**

- What does one row represent? (A person?  A business?  An event? A product?)
    * One row represents a **person**.

-  Is this a classification or regression problem?
   * This is a **Classification** Problem.

- How many features does the data have?
   * A total of **11 features**.

-  How many rows are in the dataset?
    * a total of **5110** patients/rows

-  What, if any, challenges do you foresee in cleaning, exploring, or modeling this dataset?
    * In cleaning the data, I need to choose between:
     1. Dropping 3.93% rows with missing values leaving us 4909 rows or sample.
       - Drop rows with missing values </br>
        con: This would result in a significant loss of data. </br> +5% missing values per column would too great to justify this option, however -5% missing values would justify this option.
     2. Imputing stragety = 'median' on the missing values to save the 3.94% samples or data. </br>
       - Impute missing values using the 'median' value of the column </br>
        pro: This is less affected by outliers than strategy = 'mean'.
     * 'Unknown' Smoking Status will also be a challenge on exploring the data.

