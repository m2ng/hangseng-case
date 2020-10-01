# Hang Seng Case Competition

## About
(Kaggle Competition) Prudential Life Insurance Assessment

See the corresponding [Kaggle page](https://www.kaggle.com/c/prudential-life-insurance-assessment/).

## Data description

In this dataset, you are provided over a hundred variables describing attributes of life insurance applicants. The task is to predict the "Response" variable for each Id in the test set. "Response" is an ordinal measure of risk that has 8 levels.

## File descriptions

-   train.csv - the training set, contains the Response values
-   test.csv - the test set, you must predict the Response variable for all rows in this file
-   sample_submission.csv - a sample submission file in the correct format

## Data fields
-   Id: A unique identifier associated with an application.
-   Product_Info_1-7: A set of normalized variables relating to the product applied for
-   Ins_Age: Normalized age of applicant
-   Ht: Normalized height of applicant
-   Wt: Normalized weight of applicant
-   BMI: Normalized BMI of applicant
-   Employment_Info_1-6: A set of normalized variables relating to the employment history of the applicant.
-   InsuredInfo_1-6: A set of normalized variables providing information about the applicant.
-   Insurance_History_1-9: A set of normalized variables relating to the insurance history of the applicant.
-   Family_Hist_1-5: A set of normalized variables relating to the family history of the applicant.
-   Medical_History_1-41: A set of normalized variables relating to the medical history of the applicant.
-   Medical_Keyword_1-48: A set of dummy variables relating to the presence of/absence of a medical keyword being associated with the application.
-   Response: This is the target variable, an ordinal variable relating to the final decision associated with an application