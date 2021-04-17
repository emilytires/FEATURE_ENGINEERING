FEATURE_ENGINEERING

  This is a part of the data analytics and machine learning process that data scientists spend most of their time on. There are many important steps in data preprocessing, such as data cleaning, data transformation, feature extraction and feature selection. Data cleaning and transformation are methods used to remove outliers and standardize the data so that they take a form that can be easily used to create a model.
  
  In this repo, we will dive into the topics respectively OUTLIER HANDLING, MISSING HANDLING, ENCODING, FEATURE SCALING, FEATURE EXTRACTION.
  
 1. Outliers : They are unusual values in a dataset

         1.1 Catching Outliers Methods : Boxplot, outlier_thresholds, check_outlier, grab_outliers

        1.2 Solving Outlier Problem : drop , re-assignment with thresholds, local outlier factor

  2. Missing Values 

    2.1 Catching Missing Values

    2.2 Solving Missing Problem : drop , fill in using lambda and apply function, assign missing values with scikit-learn, fill in categorical variable bracket
  
    2.3 Advanced Analytics : structure and randomness review, missing_vs_target
  
   2.4 Other missing variable techniques :
     If total none rate is equal or less than 0.05 then use simple method (like mean, median, mode...)
     If total none rate is equal or less than 0.25 then use tree based method 
     If total none rate is equal or less than 0.50 then use model 
   
  3. Encoding

    3.1 Label Encoding
   
    3.2 One Hot Encoding
   
    3.3 Rare Encoding

  4. Feature Scaling

    4.1 StandardScaler
  
    4.2 RobustScaler
   
    4.3 MinMaxScaler
   
    4.4 Log
   
    4.5 Numeric to Categorical

  5. Feature Extraction

  6. End to End Application
