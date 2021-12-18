# used cars prediction in Saudi Arabia
The goal of this project is to build the best model that can do a good prediction of used car price in Saudi Arabia 
i scraped data from sayarah website by selenuim and beautiful soup 
the data size is more than 8000 rows a 11 features 

# Data Distribution 
![download-7](https://user-images.githubusercontent.com/78117752/146582673-a0331d2e-8961-4e01-a652-99181d513b2b.png)
based on EDA phase there is no correlation between features each others and between features with traget ,so we should use ploynomial regression 
and then display multicollinearity  by variance inflation factor and handled outliers 

# models 
i applayied ploynomial regression with degree=4 and the linear regression score 0.64 and lassoCV score was      Ridge score was 
and then take importance features from coefficient of lasoo to retrain model again 

our data set include more inexpensive cars and less expensive cars for that could be a good predictive model for inexpensive cars 


