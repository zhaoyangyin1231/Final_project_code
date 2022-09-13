# Final_project_code

## Code overview
The project is to build a model for Denmark power price inference.

## Requirements
-	Python == 3.8
-	scikit-learn == 1.0.1
-	numpy == 1.21.2
-	pandas == 13.4
-	gensim == 4.0.1
-	Keras == 2.3.1

## Datasets
-	Power price data and causal variable data from internet: data_raw.csv
-	Data after pre-processing and interpolation: data_final_ad.csv
-	Data for future five years: predicted_future.csv

## Code organization
The code separated for pre-processing, correlation analysis and various model building:
-	Data pre-processing: Interpolation
-	Correlation analysis and univariant linear regression: Correlation_analysis_and_linear_regression
-	Linear regression: linear_regression
-	Nonlinear regression: Nonlinear_regression
- Facebook prophet algorithm: fbprophet_model

