# Regression Analysis Paper 
## Abstract 
In recent years, there is a growing interest for analysts and investors to assess the financial risk in film production. This study utilizes multiple linear regression analysis to predict the financial success of films and investigate the relationship between screens and year. The results demonstrate that a possible linear regression model consists of ratings, budget, screens, sequel, and aggregate followers as the predictors. Using this model, we achieved a mean gross income of $76,444,805 for predicting all films and only one film. Further, we found that year has no effect on screens in predicting mean gross income and there is a positive linear relationship between them. 

## Dataset 
The conventional and social media (CSM) 2014 and 2015 dataset was obtained from UC Irvine Machine Learning Repository. The original source of the data is from Youtube, Twitter, and IMDB (Ahmed, Jahangir, Afzal, Majeed,& Siddiqi, 2015). This dataset was provided by Mehreen Ahmed from the National University of Sciences and Technology, Islamabad, Pakistan (Ahmed et al., 2015). He is also the data collector who utilized the modules, Data Collector and Predictive Engine to obtain the data. Originally, the purpose of this dataset was for predictive analysis on the success of movies using machine learning algorithms (Ahmed et al., 2015). There are a total of 14 features in the dataset with some missing datas. The attributes include movie name, year, genre, budget, number of screens, sequel, ratings, gross income, sentiment score, number of comments, number of dislikes, number of likes, number of views, and aggregate actor followers. The categorical data include movie name and genre while the year belongs to ordinal data. There are a total of 11 features that are numerical data. There are only two unique variables to year which are 2014 and 2015. There are 231 unique variables for movie names and 15 unique variables representing different genres of the movie. This dataset represents only the movies that are within the diverse sources of IMDB, Wikipedia, Youtube, and Twitter (Ahmed et al., 2015). Hence, the data overrepresents American films and underrepresents movies produced and released in other countries.

## Regression Methods  
Exploratory analysis was conducted initially using scatterplots and added variable plots to observe some relationships that exist amongst the variables in the dataset. To answer the first question of interest a model selection using various methods such as backwards selection, regsubsets and summary table will be carried out. The influential index plot will be used to determine outliers, high leverage points, and ultimately, influential points. A diagnostics check using residuals and fitted plot and Q-Q plot was conducted to ensure there are no violations to the assumptions: linearity, equal variance, normality, and independence. To resolve the violations, the power transformation method and the box-Cox method will be used. To improve the regression model, the analysis of variance table may be used to determine the usefulness of interaction terms to be added to our model. The model devised would be used to calculate the confidence interval, prediction interval, and mean gross income. The anova table and scatter plot diagrams are used to determine the relationship between mean gross income and screens in 2014 and 2015.

## Results 
Through regression analysis, a possible multilinear regression model to predict mean gross income of movies has ratings, budget, screens, sequel, and aggregate followers as the predictors. Our results are accurate to a certain extent as the current regression model is only able to explain 69.7% of variability in mean gross income for movies and it does not violate any regression assumptions. The value of the predicted mean gross income for all movies and for one movie is the same which is $76,444,805. There is no interaction between screens and year while we found a positive linear relationship between screens and gross income. The scatter plot shows that the regression line for 2014 is above the regression line for 2015 which reflects a greater mean gross income for movies in 2014. 
