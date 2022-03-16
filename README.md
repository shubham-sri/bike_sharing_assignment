# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
- The objective here is to predict the share demand on the basis of diffrent indenpent veriable
- We have too may independent columns are provided in dataset, but few of them are highly corr. and few are unncesary. I just droped them.
- There are few categrorical columns so I added dummay veriable for categorirical
- For numerical veriables I used min-max scaling
- After droppping feature I finally achived a model with R-squared of 0.81 on training and 0.76 in test data
- VIF and p-value are low after final feature selection

## Conclusions
- **workingday, season_2, season_3, season_4, mnth_3, mnth_5, mnth_6, mnth_8, mnth_9, mnth_10, weekday_6, yr** have +ve contribution i.e. when these value increases then sharing count increases bu some amount
- **weathersit_2, weathersit_3, windspeed** have -ve contribution i.e. when these values increases then sharing count decresses
- **conts** - it is non-zero i.e. LR model is not pass throgh origin
- 74-75% of test value are covered with this model, hence its a good number which showing that we can use in real time data


## Technologies Used
- pandas - 
- numpy -
- matplotlib -
- seaborn -
- statsmodels -
- sklearn - 


## Acknowledgements
Give credit here.
- Anscombe’s Quartet - [link](https://medium.com/analytics-vidhya/anscombes-quartet-an-importance-of-data-visualization-856b3d1bd403).
- Pearson Correlation - [link](https://www.sciencedirect.com/topics/computer-science/pearson-correlation)
- Q-Q plot - [link](https://towardsdatascience.com/q-q-plots-explained-5aa8495426c0)


## Contact
Created by [@shubham-sri](https://github.com/shubham-sri) - feel free to contact me!