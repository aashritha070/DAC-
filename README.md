## Hi there! Welcome to my repo.
## Vehicle Price predictions using MULTIVARIATE LINEAR REGRESSION
### so the aim of this task is to predict the prices of vehicles with the help of few features like enginsize, horsepower , curbweight etc.

## STEP 1:
   Import libraries(basic ones like numpy,pandas,matplot and seaborn)
   and then we do basic analysis using these libraries for major features from the dataset.
   we then check the mean and median and conclude that the data is skewed i.e non-normal
  
## STEP 2:
    we form a correlation matrix and see for the features with highest correlation(i.e nearing 1 or -1).
    we then drop the rest with lesser correlations and find the correlation within these selected features and narrow down to the final 3.
    
## STEP 3:
    after narrowing down the final features to be used as predictors,
    we use OLS regression to find the R^2 values and P-values.
    p-value helps you determine the significance of your results.
    The relation is statistically significant if p value is less than 0.05.
    R^2 measures goodness of the fit. Higher R2 score means our model fits the data better. 
    But, with increasing number of features, R2 also increases. So, we need to be careful.

## STEP 4:
    From the above observations, we can select one of the predictors with  highest R2 value and P value of 0
     The reason for selecting just one of the above predictors is due to high amount of multicollinearity between them. 
    We shall drop the rest and also the ones with low correlation.
    
## STEP 5:
    now we  look at the correlations of the variables left.
    we chose a feature with highest R^2 in step 4. we add more features to that model and see if the R^2 value imporoves.
   
   
##  Conclusion :
    we then finally look at the model which gives us the best fit i.e highest R^2 after adding subsequent features and predict the price based on those predictors 
    
    
##  Thank You!
    
    
