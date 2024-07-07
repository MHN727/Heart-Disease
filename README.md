# Heart-Disease
# **Notebook's Author**
- **Project:** Heart Disease
- **Author Name:** Mohammad Hamza Noor
- **Email:** mhamzanoor727@gmail.com

# **Before we dive in:**
If you enjoyed my work, please consider upvoting this kernel. Your support motivates me to delve deeper into the subject and explore more accurately. Thank you for being a part of this wonderful community!  
Feel free to connect with me on my gmail. I look forward to connecting with fellow data enthusiasts like you!
# `Goal of the Analysis`
1. `Data Preparation:`

    `Cleaning and Preprocessing:`
    Ensure the dataset is free of inconsistencies, missing values, and outliers to improve model accuracy.

    `Feature Engineering:`
    Transform or create features to enhance model performance.

    `Data Splitting:`
    Divide the dataset into training and testing sets for model validation.

2. `Exploratory Data Analysis (EDA):`
    Gain insights into the data, understanding relationships and distributions that might influence model selection and performance.

3. `Model Training:`
    Selection of Models: Choose a diverse set of models to compare. This might include decision trees, random forest and XGboost


4. `Model Evaluation and Comparison:`

    `Evaluation Metrics:`
    Utilize metrics such as accuracy, precision, recall, F1-score,to assess each model's performance.

5. `Predictive Performance:`
    Determine which model performs best on the test data based on the chosen evaluation metrics.

6.  `Insights and Conclusion:`
    Draw conclusions from the model comparisons and provide insights into which models are most effective for predicting heart disease in this specific dataset.
# Models to be trained

I will be training the following models on the dataset:

1. Decision Tree
2. Random Forest
3. XGBoost
# Evaluation Metrics:

The performance of these models will be assessed using the following metrics, which are crucial for determining their effectiveness in a clinical setting:

1. Accuracy Score
2. Precision Score
3. Recall Score
4. F1 Score
# `About the Dataset`
The UCI Heart Disease dataset comprises a series of attributes designed to forecast the likelihood of heart disease in individuals. Each record in this dataset corresponds to a distinct patient, with the columns detailing diverse health-related characteristics and the presence or absence of heart disease.
### `Attribute Information:`
1. id: (Unique id for each patient)

2. age: (Age of the patient in years)
   
3. origin: (place of study)
   
4. sex: (Male/Female)
   
5. cp: chest pain type includes:
      - typical angina
      -  atypical angina
      -  non-anginal
      -  asymptomatic

6. trestbps: resting blood pressure (in mm Hg on admission to the hospital)

7. chol: Serum Cholesterol in mg/dl
   
8.  fbs: if fasting blood sugar > 120 mg/dl
   
9.  restecg: resting electrocardiographic results -- Values include:
       - normal
       - stt abnormality
       - lv hypertrophy
    
10. thalach: maximum heart rate achieved
    
11. exang: exercise-induced angina (True/ False)
    
12. oldpeak: ST depression induced by exercise relative to rest
    
13. slope: the slope of the peak exercise ST segment
    
14. ca: number of major vessels (0-3) colored by fluoroscopy
    
15. thal: Thalassemia Categories includes
       - normal
       - fixed defect
       - reversible defect
    
16. num: the predicted attribute diagnosis of heart disease

`Acknowledgements:`

- Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
- University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
- University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
- V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.


