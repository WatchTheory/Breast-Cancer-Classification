# Breast-Cancer-Classification


## Problem 
- Analyze Breast Cancer dataset and apply feature scaling using StandardScaler.
- Build KNN Model to predict the respective classes.


## Summary 

### Data Cleaning
No missing values were present, the last column was dropped during data cleaning


### Key Visualizations
Include key visualization that highlight and uncover key insight.


#### Visualization 1:

This vionplot suggest that `1 = Malignant` and `0 = Benign`, that benign have a wider axis and malignant have a larger sharpe, suggestion that malignant tumors tend to have larger worst case scenario.

![pairplot](/images/pairplot.png)



## Models Scores

| Model                            | Traing Score | Testing Score |
| -------------------------------- | ------------ | ------------- |
| KNeighbors Regressor             | 0.86         | 0.87          |
| Hist Gradient Boosting Regressor | 0.92         | 0.85          |
| Random Forest Regressor          | 0.96         | 0.84          |


As you can the `Hist Gradient Regressor` did very well in the training but came it second place when testing. 
`Random Forest Regressor`also did excellent, but came in third place. This does lead me to believe overfitting might have occur.
So fine-tuning the models more may be a good idea.
In the future I would like to try more models and see if I can get the model score higher.

## Conclusions/ Recommendations



