Hi Everyone this is the readme file for my project.Below are some of the steps that I followed:

## PART-1 : LIBRARIES USED:

1. To load the dataset, perform operations and plotting the results, we have used the libraries:
-- Numpy, pandas and matplotlib

2. To perform the machine learning we need to import some of the below libraries:
-- XGBoost,RandomForestRegressor, DecisionTree (machine learning libraries)
-- train_test_split(to split the datasets)

3. To evaluate the results:
-- We have used r2_score, as this is a regression problem

## PART-2: MOTIVATION OF THE PROJECT:

This dataset is way useful because we can analyze some of the questions like :

-- Which are the top 20 most expensive locations in texas

-- How the price varies with Property type

-- Variation of Price with number of baths

-- Futher more we will also see which is the best machine learning algorithm.

## PART-3 : STRUCTURE OF THE PROJECT:

For this project we have -- 1. code file: Redfin_Dataset_Analysis.ipynb
                         -- 2. Dataset : redfin_2021-01-09-11-41-32.csv (which I downloaded from there website)
                         -- 1 readme file, where all the important steps are documented
                         
## PART-4: SUMMARY:

Now we will answer the questions as stated in part-2:

-- Which are the top 20 most expensive locations in texas?

Ans: Upon doing the analysis we found out that Armstrong, followed by Highland Park Acreage are the most expensive ones

-- How the price varies with Property type>

Ans: Upon analysis we see that Multi- Family (5_ units) are more costly as compared to others

-- Variation of Price with number of bath?

Ans: The common observation that we have is that as more the number of baths more being the Price of property

-- Which are the top predictors or imp features?

Ans: We find out that: DAYS ON MARKET, PT_Multi-Family(2-4), BATHS & AGE are the best features

-- Which is the best Machine Learning algorithm?

Ans: We find out that Xgboost has the best performance(r-squared = 0.93), as compared to Decision Tree Regressor and Random Forest Regressor

## PART-5: Acknowledgments

This dataset has been downloaded from https://www.redfin.com/ website directly
