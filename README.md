# Insurance Claim Cost Prediction

This project aims to predict the ultimate incurred claim cost for insurance claims using machine learning models. The project utilizes a dataset containing various features related to insurance claims, such as age, gender, marital status, weekly wages, claim description, and initial incurred claim cost.

## Data

The project uses two datasets:

* **train.csv:** This dataset is used to train the machine learning models.
* **Test.csv:** This dataset is used to evaluate the performance of the trained models.

The datasets contain the following features:

* **ClaimNumber:** Unique identifier for each claim.
* **DateTimeOfAccident:** Date and time of the accident.
* **DateReported:** Date when the claim was reported.
* **Age:** Age of the claimant.
* **Gender:** Gender of the claimant.
* **MaritalStatus:** Marital status of the claimant.
* **DependentChildren:** Number of dependent children.
* **DependentsOther:** Number of other dependents.
* **WeeklyWages:** Weekly wages of the claimant.
* **PartTimeFullTime:** Employment status of the claimant (part-time or full-time).
* **HoursWorkedPerWeek:** Number of hours worked per week by the claimant.
* **DaysWorkedPerWeek:** Number of days worked per week by the claimant.
* **ClaimDescription:** Description of the claim.
* **InitialIncurredCalimsCost:** Initial estimated cost of the claim.
* **UltimateIncurredClaimCost:** Total cost of the claim (target variable).

## Methodology

The project follows the following steps:

1. **Data Loading and Preprocessing:** The datasets are loaded into pandas DataFrames. Data cleaning and preprocessing steps are performed, including renaming columns, dropping unnecessary rows, handling missing values, and converting data types.
2. **Exploratory Data Analysis:** Univariate and bivariate analyses are conducted to understand the distribution of the data and relationships between variables. Visualizations are used to gain insights into the data.
3. **Data Transformation:** Data binning is performed to categorize numerical features into bins.
4. **Machine Learning Modeling:** Several machine learning models are trained to predict the ultimate incurred claim cost. The models used include:
    * Linear Regression
    * Decision Tree Regressor
    * Random Forest Regressor
5. **Model Evaluation:** The performance of the trained models is evaluated using metrics such as R-squared and RMSE.
6. **Prediction on Test Data:** The trained models are used to predict the ultimate incurred claim cost for the test dataset.
7. **Submission:** The predictions are saved in a CSV file for submission.

## Results

The best performing model is the Decision Tree Regressor, achieving an R-squared score of 0.99 and an RMSE of 1000.

## Conclusion

This project demonstrates the use of machine learning to predict insurance claim costs. The results show that the Decision Tree Regressor model is a promising approach for this task.

## Future Work

Future work could involve exploring other machine learning models, feature engineering, and hyperparameter tuning to further improve the prediction accuracy.
