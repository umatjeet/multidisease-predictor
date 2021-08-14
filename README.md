# Multiple Disease Predictor

## About

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:

- Diabetes
- Breast Cancer
- Kidney Disease
- Pneumonia

## Models with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Diabetes       | Machine Learning Model   | 98.25%   |
| Breast Cancer  | Machine Learning Model   | 97.25%   |
| Kidney Disease | Machine Learning Model   | 99%      |
| Pneumonia      | Deep Learning Model(CNN) | 95%      |

## NOTE

==> You can access the website live at: https://kvg-disease-predictor.herokuapp.com <br>
==> Python version 3.6.8 was used for the whole project.<br>
==> You can find all the models in [models](https://github.com/umatjeet/multidisease-predictor/tree/main/models) folder.

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.


3. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle.

- [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
- [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
- [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## Links for Python Notebooks used for model creation

- [Notebooks](https://github.com/umatjeet/multidisease-predictor/tree/main/Python%20Notebooks)
