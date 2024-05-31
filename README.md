# classification traffic Situation
  ![traffic Image]()

- This project aims to classify traffic conditions as low, normal, high, or heavy using K-Nearest Neighbors (KNN), decision trees, random forest, gradient boosting and XGBoost.
- I plan to conduct an exploratory data analysis (EDA) on my dataset, followed by data preprocessing and then building the models.
  
  # The Data Set
  - The dataset is stored in a CSV file format on this repo (above)
  - This dataset contains traffic data with the following columns:
    - Time: The specific time of the traffic observation.
    - Date: The date of the traffic observation.
    - Day of the Week: The day of the week when the data was recorded.
    - CarCount: The number of cars counted during the observation period.
    - BikeCount: The number of bikes counted during the observation period.
    - BusCount: The number of buses counted during the observation period.
    - TruckCount: The number of trucks counted during the observation period.
    - Total: The total count of all vehicles (cars, bikes, buses, and trucks) during the observation period.

# EDA And Data Preprossing
![traffic Image](https://github.com/germeengehad/classify-traffic-conditions/blob/main/download.png)
- Data Exploration: I explored the dataset to understand its structure, distributions, and key characteristics.
- Target Encoding: I performed target encoding to convert categorical target variables into numerical values.
- Handling Missing Values: I addressed missing values by applying appropriate techniques to ensure data integrity.
- Handling Multicollinearity: I identified and managed multicollinearity to improve the performance of predictive models.
- Applying ANOVA and Chi-Square Tests: I conducted ANOVA and Chi-square tests to assess the significance of different features.
- Encoding Categorical Data: I encoded categorical features into numerical format to prepare the data for machine learning algorithms.

# Model Building
- Data Preparation steps:
  1)  Data Separation as X and Y=(Traffic_Situation)
  2)  Split the data into training and test sets .
  3)  Handling the imbalanced data by appling oversampling to the training data
  4)  Scale the data
- Tried different models and used hyperparameter tuning with grid search to find the best parameters.

  # Models Performance 
- KNN Model: Accuracy = 97%
- Decision Tree Model: Accuracy = 97%
- Random Forest Model: Accuracy = 98%
- Gradient Boosting Model: Accuracy = 95%
- XGBoost Model: Accuracy = 93%

  # Pickel The Best Model
- Importing Pickle
- Saving the Model
- Loading the Model


  
      
