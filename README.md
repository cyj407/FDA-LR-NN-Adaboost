# Fundamental Data Analysis - Logistic Regression, Neural Networks, Adaboost
## Dataset
- [S&P 500](https://www.sharecast.com/index/SP_500/prices/download)
    - Training set (02-Jan-2009~29-Dec-2017)
    - Test set (02-Jan-2018~31-Dec-2018)
- [Google Stock Price](https://www.kaggle.com/medharawat/google-stock-price)

## Predict Result
- Predict Close Price is up or down.
- [Report](https://github.com/cyj407/FDA-hw3-1/blob/master/Report.pdf)
### S&P 500
- Accuarcy : Adaboost(83%) > Logistic Regression(82%) > Neural Networks(80%)
- [Code](https://github.com/cyj407/FDA-hw3-1/blob/master/S%26P500_lr_nn_boost.ipynb)
### Google Stock Price
- Accuracy : Logistic Regression(75%) > Adaboost(65%) > Neural Networks(60%)
- [Code](https://github.com/cyj407/FDA-hw3-1/blob/master/GoogleStockDataset.ipynb)


## Requirements
- sklearn
- pandas
- keras
- jupyter notebook