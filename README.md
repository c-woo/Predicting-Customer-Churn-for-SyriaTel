

# Predicting Customer Churn for SyriaTel

For a business, the cost of acquiring new customers is typically high when compared to retaining existing customers. Because of this, managing customer churn is an essential requirement of a successful business. Customer churn is the percentage of customers that stopped using your company’s product or service during a ceratin time frame. Of course retaining all your customers is an impossible task, however, being able to predict which customers might leave in the future gives businesses valuable insights into their customers and their business.

We’ll be looking at data from SyriaTel, a telecommunications company, to try and predict whether or not a customer will churn.

## Models used for predictions

I'll be running the data through a couple different models to see which one yields the best results. 

The models I'll be using are:<br>
* Logistic Regression
* Random Forest
* XGBoost

## Logistic Regression

### Evaluation Metrics

Precision:  40% <br>
Recall:  78.4% <br>
Accuracy:  79.1% <br>
F1-Score:  53% <br>

<img src='https://i.imgur.com/Mc8IK0l.png'>

## Random Forest

### Evaluation Metrics

Precision:  82.9% <br>
Recall:  77.6% <br>
Accuracy:  94.2% <br>
F1-Score:  80.2% <br>

<img src='https://i.imgur.com/npww6GT.png'>

## XGBoost

### Evaluation Metrics

Precision:  81.7% <br>
Recall:  78.4% <br>
Accuracy:  94.1% <br>
F1-Score:  80% <br>

<img src='https://i.imgur.com/dQDjFoe.png'>

## Conclusion

After running the data through all three models, XGBoost was found to be the best model for predicting customer churn. Although XGBoost and Random Forest have similar evaluation metrics, Random Forest had some overfitting to the training data which is why XGBoost is the better model to use.
