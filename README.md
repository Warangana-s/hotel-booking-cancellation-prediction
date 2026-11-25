# Hotel Booking Cancellation Prediction

A machine learning project focused on predicting hotel booking cancellations using historical booking data.

## Project Overview

This project explores how machine learning can help hotels identify bookings that are more likely to be cancelled. We used the Hotel Booking Demand dataset and developed classification models to predict booking cancellation outcomes.

## Dataset

- Original records: 119,390
- Original features: 32
- Target variable: `is_canceled`
- Problem type: Supervised Binary Classification
- Dataset: [Hotel Booking Demand – Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

## Machine Learning Models

We compared the following classification models:

- Logistic Regression
- Decision Tree
- Random Forest
- Histogram Gradient Boosting

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Optuna

## Methodology

- Exploratory Data Analysis
- Data cleaning and preprocessing
- Feature engineering
- Chronological training, validation and test splitting
- Prevention of data leakage
- Classification model training and comparison
- Hyperparameter optimisation using Optuna
- Model evaluation using multiple performance metrics

## Final Model Results

The tuned Histogram Gradient Boosting model was selected for final testing.

| Metric | Test Score |
|---|---:|
| Accuracy | 79.04% |
| Precision | 71.91% |
| Recall | 77.05% |
| F1-score | 74.39% |
| ROC-AUC | 0.8815 |
| PR-AUC | 0.8266 |

## Project Type

University Group Project – IT3091 Machine Learning

Sri Lanka Institute of Information Technology (SLIIT)

## Author

Role: Problem & Data Lead

My primary contribution to this group project was defining the hotel booking cancellation problem and leading the exploratory data analysis (EDA).

Business Problem Formulation: Identified hotel reservation management as the key business context and defined cancellation-risk prediction as the project's primary objective. Established one booking record as the unit of analysis and is_canceled as the prediction target.

Dataset Understanding: Examined the Hotel Booking Demand dataset, consisting of 119,390 records and 32 original features, covering City and Resort hotels from 2015–2017.

Exploratory Data Analysis: Investigated cancellation distributions, deposit types, lead times, special requests, country categories, missing values, duplicate records, and temporal cancellation patterns.

Evidence-Based Insights: Identified important patterns, including the 99.4% cancellation rate for non-refundable bookings, the difference in median lead time between cancelled and non-cancelled bookings, and the potential significance of repeated booking records.

Temporal Evaluation Strategy: Documented the chronological training, validation, and testing approach to ensure that later bookings were used to evaluate predictions on future data.

Critical Interpretation: Highlighted dataset limitations and distinguished statistical associations from reliable business conclusions, particularly when interpreting unusual cancellation patterns.

Key Learning: Developed a stronger understanding of business problem framing, data quality assessment, exploratory analysis, temporal validation, and translating analytical findings into practical decision-support insights.
## Future Improvements

- Improve probability calibration.
- Evaluate model performance across different time periods.
- Explore additional feature engineering approaches.
- Investigate the practical impact of cancellation-risk predictions.
