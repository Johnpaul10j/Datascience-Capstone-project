### 🚀 SpaceX Falcon 9 Landing Prediction

### Data Science Capstone Project

## 📌 Project Overview

This project focuses on predicting the successful landing of SpaceX Falcon 9 first-stage boosters using machine learning techniques. Rocket reusability is a key strategy for reducing launch costs, and being able to predict landing success in advance can support better mission planning and risk assessment.

Using historical launch data collected from the SpaceX public API, this project applies data analysis, visualization, and supervised machine learning to build and evaluate predictive models.

## 🎯 Problem Statement

Not all Falcon 9 launches result in successful first-stage landings. Failed landings increase operational costs and mission risk.
The goal of this project is to answer the question:

Can we predict whether a Falcon 9 first-stage booster will successfully land based on launch-related features?

This is framed as a binary classification problem.

## 📊 Data Source

Source: SpaceX REST API

Data Type: Historical launch records

Key Features Include:

Payload mass

Orbit type

Launch site

Booster version

Mission outcome

Target Variable:

Landing Outcome (Success / Failure)

## 🧹 Data Collection & Preparation

The project involved:

Collecting raw data from the SpaceX API

Cleaning and handling missing values

Encoding categorical variables

Standardizing numerical features

Preparing datasets for machine learning models

## 📈 Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand patterns and relationships in the data. Key findings include:

Certain orbits show higher landing success rates

Payload mass has a measurable impact on landing outcomes

Launch site plays a significant role in success probability

Visualizations were used extensively to support these insights.

## 🤖 Modeling Approach

Multiple classification algorithms were trained and evaluated to identify the best-performing model:

Logistic Regression

Support Vector Machine (SVM)

Decision Tree

K-Nearest Neighbors (KNN)

A train-test split strategy was used to evaluate model performance fairly.

## 🏆 Results
Model	Accuracy
Logistic Regression	0.8333
SVM	Lower
Decision Tree	Lower
KNN	Lower

✅ Logistic Regression achieved the highest accuracy (83.33%) on the test dataset.

The model was selected due to its strong performance, simplicity, and interpretability.

## 🔍 Key Insights

Launch characteristics significantly influence landing success

Logistic Regression effectively captured the relationship between features and outcomes

Model interpretability makes it suitable for real-world decision support

## 💡 Business / Operational Impact

This model can be used as an early-stage risk assessment tool to:

Estimate landing success probability before launch

Support mission planning decisions

Reduce financial risk associated with failed recoveries

## ⚠️ Limitations & Future Work

Limited dataset size

No inclusion of real-time weather data

Future improvements could include:

Additional launch parameters

Ensemble or deep learning models

Continuous model updates with new launches

## 🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

SpaceX REST API

📁 Repository Structure
├── Data Collection
├── Data Wrangling
├── Exploratory Data Analysis
├── SQL Analysis
├── Machine Learning
└── README.md

## 👤 Author

Umeh johnpaul
Aspiring Data Scientist | Machine Learning Enthusiast

## 📌 Final Note

This project demonstrates an end-to-end data science workflow — from data collection and exploration to modeling, evaluation, and actionable insights — using real-world aerospace data.
