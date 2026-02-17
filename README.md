Air Quality Prediction using Machine Learning

Project Overview
This project predicts air pollution levels using real-time Indian Air Quality dataset.  
A Machine Learning model is trained to estimate pollutant average values based on location and pollutant measurements.

Dataset
Source: data.gov.in

Features used:
- Country
- State
- City
- Station
- Latitude & Longitude
- Pollutant type
- Pollutant min & max values
- Date & Time features (year, month, day, hour)

Target:
- pollutant_avg

Machine Learning Models Used
1. Linear Regression
2. Random Forest Regressor (Final Model)

Random Forest performed better and was saved as the final model.

Model Performance

Random Forest Results:
- R² Score: 0.94
- MSE: 133.97

This indicates strong prediction accuracy.

Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

Project Files
- Air_Quality_AI.ipynb: Complete ML workflow
- Air_Quality_Database.csv: Dataset
- air_quality_model.pkl: Trained model

Future Improvements
- Deploy model using Streamlit
- Add real-time API prediction
- Improve feature engineering

Author
Anusha Roshan Netrakar
