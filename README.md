# solid-waste-management-using-LSTM
This project was intended to forecast the bin volume for next 7 days based on history pattern observed and also provided an optimized collection process to save resources and get the optimal value.

The Objective:
  1. History Data Generation.
  2. Real Time Data Generation.
  3. LSTM Multi-step Multivariate Forecast Model Training.
  4. Forecast Test Data Generation.
  5. LSTM prediction script for 7 days forecast of bin fill level.
  6. Route Optimisation.
  
### History Data Generation
A history dataset has been generated using real life scenarios to train the model and identify the pattern while forecasting.

### Real Time Data Generation
A similar script as above has been used to generate data on a daily basis using schedulers to automaticaly generate everyday data and store it in their respective db's.

#### LSTM MULTISTEP MULTIVARIATE FORECASTING
Based on the data generated, a LSTM model with multiple layers has been trained for forecasting the percentage of bin fill level for every hour, for the next 7 days from now.
  
#### Forecast Data Generation
Custom funtcions has been written to generate data based on time(hourly) for the next 7 days.

#### LSTM Prediction Script
On the generated data the prediction script was made, which is used to give the predictions as requested.

#### Route Optimisation
Based on the predicted bins for a particular day, an optimised collection route is generated, which shows which bins to be collected at first to get the shortest distance travelled for completing the collection process.
