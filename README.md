# Predict-graduate-admission-chances-in-KNIME

This project is built with KNIME to predict graduate admission chances using learning methods for regression. 

The dataset contains several parameters which are considered important during the application for Masters Programs. The parameters included are : 1. GRE Scores ( out of 340 ) 2. TOEFL Scores ( out of 120 ) 3. University Rating ( out of 5 ) 4. Statement of Purpose and Letter of Recommendation Strength ( out of 5 ) 5. Undergraduate GPA ( out of 10 ) 6. Research Experience ( either 0 or 1 ) 7. Chance of Admit ( ranging from 0 to 1 )

In order to predict the target label, 4 different models were used:
Linear Regression, Polynomial Regression- Maximum degree of 2, Random Forest- 100 classifiers on 7 attributes, and Tree Ensemble - 100 classifiers on 7 attributes.

Linear regression model performed better among all the other regression models with R2 value of 0.816. 10 fold cross validation with Leave-one-out approach yielded the best results. 

## Conclusions
Applicants with high CGPA, GRE score and TOEFL score has higher chances of getting an admit to the Masters program. Linear regression model fits better with the given dataset and gives high accuracy.

## Acknowledgements
This dataset is inspired by the UCLA Graduate Dataset. The test scores and GPA are in the older format. The dataset is owned by Mohan S Acharya.

