# 🚀 Rainfall-prediction-using-AI-techniques 🌧️🌧️
![maxresdefault_0ihPWqs max-1300x1300](https://github.com/Gauravonthemixx/Text-Analytics-of-TED-Talks/assets/91785440/9be2926b-7023-4644-a230-9b828b786f04)

<img width="591" alt="Screenshot 2024-03-21 at 01 54 31" src="https://github.com/Gauravonthemixx/Text-Analytics-of-TED-Talks/assets/91785440/c8f39dba-6b31-4be5-87a8-31b777e3ea88">


## :pencil: Description:
* This project focuses on leveraging artificial intelligence (AI) techniques to analyze historical weather data and predict rainfall occurrences in Australia. 
* By examining various environmental factors such as temperature, humidity, wind patterns, and cloud cover, the project aims to develop a robust predictive model for forecasting rain occurrences on the next day. 
* The ultimate goal is to showcase the potential of AI in weather analysis and prediction, contributing to more accurate and reliable weather forecasts for different sectors relying on weather information.

## :hourglass: Dataset:
* The dataset used in this analysis consists of historical weather data collected from various locations in Australia spanning from 2009 to 2017. 
* It contains 22 independent features, including measurements recorded at two different times of the day (9 am and 3 pm), such as temperature, rainfall, wind speed, humidity, and atmospheric pressure. Additionally, the dataset includes a binary target variable indicating whether it will rain tomorrow. 
* With 145,460 data points, this dataset serves as a valuable resource for studying weather patterns and predicting rainfall occurrences.
* Dataset is available at https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package/code 🔗.

## 💻 Requirements:


* Python programming environment
* Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
* Jupyter Notebook or Google Colab for code execution
  
```
# Importing essential libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder
```
## :pencil: Methods:


### Data Preprocessing: 
* Label encoding for categorical variables, handling missing values, and feature selection using mutual information.
### Addressing Class Imbalance:
* Resampling techniques, specifically oversampling the minority class (rain) to achieve a balanced dataset.
  
### Model Implementation:
* Baseline Model: Decision Tree classifier
* Enhanced Models: Bagging classifier and Random Forest classifier
* Model Evaluation: Performance evaluation using classification metrics such as F1-score, precision, and recall.

## 🎯 Results:


![download](https://github.com/Gauravonthemixx/Text-Analytics-of-TED-Talks/assets/91785440/69bc8a97-775e-4d07-80e3-58c0f5b5f5c1)

![download (1)](https://github.com/Gauravonthemixx/Text-Analytics-of-TED-Talks/assets/91785440/72fa47cf-3f62-4c9c-8f12-f57ac4c7d529)

### Baseline Model:
* Initial F1-score of 79%, with significant class imbalance favoring the majority class (no rain).
### Enhanced Model: 
* Substantial improvements in F1-score to 93% after feature selection and resampling techniques.
### Decision Tree Classifier: 
* Comparable performance to Random Forests with better computational efficiency, achieving an F1-score of 93%.
### Implications:
* AI techniques demonstrate significant potential in weather forecasting, providing accurate predictions for rain occurrences and supporting informed decision-making in various sectors.
