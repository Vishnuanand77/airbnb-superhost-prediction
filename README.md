# Airbnb Superhost Prediction

## Project Overview
This project aims to predict whether an Airbnb host will become a Superhost based on various features of their listings and hosting behavior. The analysis is based on a dataset of 74,111 Airbnb listings in New York City, with 13,000 Superhosts identified.

## Business Problem
- Airbnb Superhosts are hosts who provide exceptional experiences to their guests
- Superhost status is a key differentiator in the competitive Airbnb market
- Understanding factors that contribute to Superhost status can help hosts improve their performance
- Airbnb can use this information to better support hosts in achieving Superhost status

## Data Analysis
The dataset includes various features such as:
- Host characteristics (response rate, acceptance rate, etc.)
- Listing attributes (price, room type, amenities, etc.)
- Location-based features
- Review metrics
- Booking statistics

## Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Feature engineering
   - Data normalization

2. **Feature Selection**
   - Correlation analysis
   - Feature importance ranking
   - Dimensionality reduction

3. **Model Development**
   - Multiple machine learning models tested:
     - Logistic Regression
     - Random Forest
     - XGBoost
     - Neural Networks
   - Cross-validation for model evaluation
   - Hyperparameter tuning

4. **Model Evaluation**
   - Accuracy metrics
   - Precision and Recall
   - ROC curves
   - Feature importance analysis

## Key Findings
- Most important factors for Superhost status:
  1. Host response rate
  2. Host acceptance rate
  3. Review scores
  4. Listing price
  5. Location characteristics
- Model achieved high accuracy in predicting Superhost status
- Clear patterns emerged in what makes a successful Superhost

## Business Impact
- Hosts can use insights to improve their chances of becoming Superhosts
- Airbnb can develop targeted support programs for hosts
- Better understanding of what makes a successful listing
- Potential for improved guest satisfaction


## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib/Seaborn
- Jupyter Notebooks

## Getting Started
1. Clone the repository
2. Install required dependencies
3. Run the Jupyter notebooks in order
4. Review the analysis and findings