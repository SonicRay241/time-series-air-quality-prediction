# Time Series Air Quality Prediction with LSTM

This project demonstrates a deep learning model for predicting **air temperature** based on historical air quality and environmental data. The model is built with **PyTorch** using an LSTM (Long Short-Term Memory) architecture and visualized with **Matplotlib**.

## 🚀 Overview

The goal of this project is to forecast **temperature** in real time by learning patterns from air pollutant levels and meteorological features.

Key input features include:

* Air pollutants: PM2.5, PM10, NO, NO2, NOx, NH3, SO2, CO, Ozone, Benzene, Toluene, Xylene
* Meteorological data: RH (Relative Humidity), WS (Wind Speed), WD (Wind Direction), SR (Solar Radiation), BP (Barometric Pressure), VWS (Variance of Wind Speed), RF (Rainfall)
* Target variable: **Temperature (Temp)**

The pipeline includes:

* Data preprocessing with **Pandas** and **Sklearn**
* LSTM model training and evaluation with **PyTorch**
* Data visualization with **Matplotlib**

## 🧰 Tech Stack

* **Python 3.9+**
* **PyTorch** – deep learning framework for LSTM model
* **Pandas / NumPy** – data preprocessing and handling
* **Matplotlib** – visualization of data
* **Sklearn** - data preprocessing and model testing
## ✨ Features

* Forecasts air temperature from **multi-feature time series data**
* LSTM-based deep learning model for sequence prediction
* Visualization of predictions vs. actual values with **Matplotlib**
* Extensible to additional features and forecasting horizons

## 📈 Model Performance

The LSTM model achieved the following evaluation metrics on the test dataset:

* **MAE**: 2.01
* **MSE**: 6.28
* **R² Score**: 0.66

These results indicate the model captures meaningful temporal dependencies in the data, though further optimization could improve accuracy.

## 📄 License

This project is licensed under the [MIT License](https://github.com/SonicRay241/time-series-air-quality-prediction/main/blob/LICENSE).
