# End-to-End Telecom Customer Churn Prediction with Explainable AI
![dashboard](assets/title.png) 

## Project Overview 
Successful customer churn prediction depends on having access to the factors that genuinely influence a customer's decision to leave / switch. Crucial information like the volume of customer complaints, whether those complaints were resolved satisfactorily, the company's adoption of new technologies, the effectiveness of its customer engagement and promotional campaigns, and whether its pricing and fees remain competitive are often among the strongest drivers of churn. If these variables are absent from the training dataset, the machine learning model is forced to rely on indirect or weak proxies, such as telecom provider, gender, city, state, date of registration, number of calls made, data usage, payment method, and monthly bills. While these features may exhibit some statistical association with churn, they oftentime fail to represent the underlying business and customer experience factors that actually influence a customer to switch providers. As a result, even sophisticated machine learning models may deliver only modest predictive performance because the most informative variables are simply unavailable.
Therefore, evaluating the quality and relevance of a dataset should be the first step before investing significant time in model development. A well-designed machine learning algorithm cannot compensate for missing business-critical information. 

## Dataset 

[Dataset](https://www.kaggle.com/datasets/jpacse/datasets-for-churn-telecom/) 

[City Coordinates](https://simplemaps.com/data/us-cities) 

![dashboard](assets/simplemap_us_cities.png) 

## Folder Structure 
```bash
telecom-churn-prediction/
│
├── assets/
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_model_training.ipynb
│
├── src/
│   ├── __init__.py
│   ├── preprocessing.py
│   ├── train.py
│   └── inference.py
│
├── models/
│   └── rf_model.joblib
│
├── data/
│   └── servicearea_lookup.json
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```
