# *India Coffee Market Intelligence & Consumer Adoption ML Project*

# *Overview*

This repository contains a comprehensive, multi-module machine learning project designed for engineering students. 
The project evaluates market opportunities, consumer behavior, and adoption potential for a tea-producing company in India entering the coffee market through a strategic partnership with the Brazilian coffee company 3 Corações.

# *Project Architecture*

The end-to-end pipeline spans data ingestion, feature engineering, modeling, validation, and strategic decision-making:

Consumer/Market Data 
        |
       EDA
        |
     Cleaning 
        |
Feature Engineering
        |
    ML Models
        |
    Validation
        |
Segments & Predictions
        |
Opportunity Analysis
        |
Launch Recommendation

# *Modules & Technical Scope*

1. Customer Segmenation
   * Algorithms: K-Means / Agglomerative Hierarchical Clustering.
   * Features: Age, city, income, coffee frequency, tea frequency, monthly coffee spend, coffee format, café visits, price sensitivity, and premium preference.
   * Student Outputs: Cluster visualizations, dendrograms (for hierarchical clustering), silhouette scores, cluster profiles, and business interpretations (clusters must be named only after analyzing their statistics).

2. New Coffee Brand Adoption Prediction (Classification)
   * Target Variable: Will_Buy_New_Brand (0/1) derived from survey or historical campaign data.
   * Candidate Features: Age, income, coffee frequency, coffee spend, current brand, café visits, price sensitivity, premium preference, origin interest, and product format
   * Models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting / XGBoost.
   * Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix, and Probability Calibration.

3. Coffee Spending Prediction (Regression)
   * Target Variable: Monthly Coffee Spend (estimated expenditure based on demographic and behavioral variables).
   * Evaluation Metrics: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R^2 Score.  

4. Coffee Market / Demand Trend Forecasting (Time Series / Regression)
   * Scope: Study trends in coffee, specialty coffee, cold coffee, or RTD coffee using time-indexed sales, search interest, or survey demand.
   * Methods: Moving Average, Linear Trend, ARIMA, Prophet, and LSTM (advanced).

5. City-wise Coffee Market Opportunity (Clustering / Scoring / Classification)
   * Scope: Construct city-level features including coffee interest, young population share, income indicators, café density, premium spending, e-commerce penetration, and competitor presence.

6. Market Entry Recommendation Engine
   * Integrates evidence from segmentation, adoption probabilities, spending potential, trends, and city opportunities into a transparent, weighted, and validated ranking model.

7. Testing the Brazilian Partnership (Experimentation)
   * Treats the 3 Corações partnership as a testable hypothesis using a controlled survey experiment comparing purchase intentions with and without partnership/origin information.
   * Hypothesis: Partnership information increases purchase intention among selected consumer groups.

# *Pipeline Sequence*

Consumer Segmentation
         |
Adoption Classification 
         |
 Spending Regression
         |
 Trend Forecasting 
         |
City Opportunity
         |
Market Entry Recommendation   
