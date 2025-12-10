# timeseries_sunspots_prediction
In this project, we develop a machine learning model to predict sunspot activity based on historical data. Sunspots are temporary phenomena on the Sun's photosphere that appear as spots darker than the surrounding areas. They are associated with solar magnetic activity and can influence space weather.
## Dataset
The dataset used in this project is sourced from the [Solar Influences Data Analysis Center (SIDC)](http://sidc.be/silso/datafiles). It contains monthly sunspot numbers from 1749 to the present.
## Project Structure
- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks for data exploration and model development.
- `models/`: Saved machine learning models.
  
  In the notebook we test two strategy for time series forecasting: Direct Multi-step forecasting and Recursive Multi-step forecasting with multiple types of models: LSTM, GRU, CNN and Dense Neural Networks.
  