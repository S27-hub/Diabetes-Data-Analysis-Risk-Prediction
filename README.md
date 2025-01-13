# Diabetes-Data-Analysis-Risk-Prediction
The objective is to analyze the data and build a machine learning model to predict the risk of diabetes.This project focuses on analyzing and predicting the risk of diabetes using machine learning techniques. The dataset used contains various features that help in identifying the risk factors associated with diabetes. The goal is to build a predictive model to determine whether an individual is at risk of developing diabetes.

# Details of dataset
The dataset includes various features that are essential in predicting diabetes risk, focusing on a mix of demographic, lifestyle, and health metrics. Features like Weight, Blood Glucose, and Physical Activity are numerical variables that contribute directly to calculating diabetes risk, while categorical variables like Diet Quality and Medication Adherence provide important context to the user's lifestyle and habits. Together, these features help create a comprehensive profile of each user, allowing for accurate predictions and personalized health recommendations.



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
