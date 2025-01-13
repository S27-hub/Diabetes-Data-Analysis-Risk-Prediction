# Diabetes-Data-Analysis-Risk-Prediction
The objective is to analyze the data and build a machine learning model to predict the risk of diabetes.This project focuses on analyzing and predicting the risk of diabetes using machine learning techniques. The dataset used contains various features that help in identifying the risk factors associated with diabetes. The goal is to build a predictive model to determine whether an individual is at risk of developing diabetes.

# Details of dataset
The dataset includes various features that are essential in predicting diabetes risk, focusing on a mix of demographic, lifestyle, and health metrics. Features like Weight, Blood Glucose, and Physical Activity are numerical variables that contribute directly to calculating diabetes risk, while categorical variables like Diet Quality and Medication Adherence provide important context to the user's lifestyle and habits. Together, these features help create a comprehensive profile of each user, allowing for accurate predictions and personalized health recommendations.

# Data Dictionary
Below are the columns included in the dataset, along with descriptions of each:
   User ID: 
      Unique identifier assigned to each user to ensure data privacy and tracking.
   Data: 
      Represents the specific date for each record, indicating the time-series nature of the dataset.
   Weight (kg): 
      The user's body weight in kilograms. Weight is a significant factor in determining obesity-related risks.
   Height (cm): 
      Height of the user, measured in centimeters. This, combined with weight, helps calculate BMI, a key predictor of diabetes risk.
   Blood Glucose (mg/dL): 
      The user's blood glucose level in milligrams per deciliter. This is one of the most crucial indicators for diagnosing diabetes, with values typically ranging between 70 and 300 mg/dL.
   Physical Activity (minutes/day):
      The daily duration of physical activity, measured in minutes. Physical activity plays a critical role in managing blood glucose levels and reducing diabetes risk.
   Diet Quality: 
      A categorical variable describing the quality of the user's diet, labeled as either 'healthy' or 'unhealthy'. Diet plays an important role in diabetes prevention and management.
   Medication Adherence:
      Indicates the extent of the user's adherence to prescribed medication, categorized as 'good' or 'poor'. Proper adherence is crucial for managing blood glucose levels effectively.
   Stress Level: 
      The stress level reported by the user, categorized as 'low', 'medium', or 'high'. Chronic stress can significantly impact blood glucose levels and contribute to diabetes risk.
   Sleep Duration (hours): 
      The number of hours the user sleeps each day. Adequate sleep is vital for maintaining overall health and stabilizing blood sugar levels.
   Hydration Status: 
      Indicates whether the user is adequately hydrated, with values of 'yes' or 'no'. Proper hydration supports optimal body function, which includes maintaining blood glucose balance.
   BMI: 
      Body Mass Index, calculated using the weight and height of the user. BMI is an important indicator of whether an individual is underweight, of normal weight, overweight, or obese, which is directly linked 
   to diabetes risk.
   Risk Score: 
      The calculated risk score for each user, generated based on various health metrics. This score helps categorize users into different risk levels:
       -Low Risk (< 30): Users are considered to have a low likelihood of developing diabetes.
       -Moderate Risk (30-60): Users are given preventive advice to lower their risk.
       -High Risk (> 60): Users are at high risk and receive urgent recommendations to manage their condition.

# Steps Involved

    Data Preprocessing:
        Handle missing values (replacing zero values with NaN or using appropriate imputation techniques).
        Normalize/scale the data (to ensure features have a similar scale for modeling).
        Split the data into training and testing sets.

    Exploratory Data Analysis (EDA):
        Visualize relationships between features and the target variable (Outcome).
        Use statistical plots (histograms) to identify patterns  in the dataset.
        Correlation matrix to understand how features are related to each other.

    Feature Engineering
        To improve the model performance by creating the new features and transform existing ones to enhance prediction.
        Created a new column named Category.
        
    Model Building:
        Applied machine learning algorithms such as Logistic Regression, to predict the risk of diabetes.
        
    Model Evaluation:
        Evaluate the model using classification metrics like Accuracy, Precision, Recall, F1-Score, and AUC-ROC curve.
        Visualize the ROC curve to assess the model’s ability to differentiate between the two classes.

    Risk Prediction:
        Once the model is trained and evaluated, it can be used to predict the likelihood of diabetes for new, unseen individuals based on their medical and physical attributes.
