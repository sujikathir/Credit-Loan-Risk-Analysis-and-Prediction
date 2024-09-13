# Loan Default Risk Analysis

![](https://github.com/AkilsuryaS/Loan-Default-Risk-Analysis/blob/main/images/Cover%20pic.jpeg)

### Dataset description

The dataset is from the U.S. Small Business Administration (SBA) The U.S. SBA was founded in 1953 on the principle of promoting and assisting small enterprises in the U.S. credit market (SBA Overview and History, US Small Business Administration (2015)). Small businesses have been a primary source of job creation in the United States; therefore, fostering small business formation and growth has social benefits by creating job opportunities and reducing unemployment. There have been many success stories of start-ups receiving SBA loan guarantees such as FedEx and Apple Computer. However, there have also been stories of small businesses and/or start-ups that have defaulted on their SBA-guaranteed loans.  

**The project will include following tasks:**
- Load dataset. Don't use "index" column for training.
- Clean up the data:
    - Encode/replace missing values
    - Replace features values that appear incorrect
- Encode categorical variables
- Split dataset to Train/Validation/Test
- Add engineered features
- Train and tune ML model
- Provide final metrics using Test dataset
- Provide a scoring function that can be used to score new data. You can test your scoring function on the provided "scoring" dataset.

 The goal of using Linear models is to be able to interpret the results via coefficients, and PCA/TruncatedSVD will make use of coefficients unusable for interpretation.

 ### Types of models to train

Your final submission should include single model. 
The model set you should try to come up with best model per type of model:
1. Identify best model from: Sklearn Logistic Regression - try all combinations of regularization
2. Identify best model from: H2O-3 GLM - try different combinations of regularization

**Evaluation metric: AUCPR**

