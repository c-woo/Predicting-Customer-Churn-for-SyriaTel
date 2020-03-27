

# Predicting Customer Churn for SyriaTel

For a business, the cost of acquiring new customers is typically high when compared to retaining existing customers. Because of this, managing customer churn is an essential requirement of a successful business. Customer churn is the percentage of customers that stopped using your company’s product or service during a ceratin time frame. Of course retaining all your customers is an impossible task, however, being able to predict which customers might leave in the future gives businesses valuable insights into their customers and their business.

We’ll be looking at data from SyriaTel, a telecommunications company, to try and predict whether or not a customer will churn.

## Models used for predictions

I'll be running the data through a couple different models to see which one yields the best results. The models I'll be using are:
*Logistic Regression
*Random Forest
*XGBoost

## Logistic Regression

### Evaluation Metrics

Precision:  0.4
Recall:  0.784
Accuracy:  0.7913669064748201
F1-Score:  0.5297297297297298

<img src='https://i.imgur.com/Mc8IK0l.png'>

## Random Forest

### Evaluation Metrics

Precision:  0.8290598290598291
Recall:  0.776
Accuracy:  0.9424460431654677
F1-Score:  0.8016528925619835

<img src='https://i.imgur.com/npww6GT.png'>

## XGBoost

### Evaluation Metrics

Precision:  0.8166666666666667
Recall:  0.784
Accuracy:  0.9412470023980816
F1-Score:  0.7999999999999999

<img src='https://i.imgur.com/dQDjFoe.png'>

## Conclusion

After running the data through all three models, XGBoost was found to be the best model for predicting customer churn. Although XGBoost and Random Forest have similar evaluation metrics, Random Forest had some overfitting to the training data which is why XGBoost is the better model to use.
