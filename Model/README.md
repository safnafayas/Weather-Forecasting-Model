# Weather Forecasting

This project focuses on building a weather forecasting system using historical weather data for Toronto. Several regression models are applied to predict weather variables based on preprocessed meteorological data.

## 📁 Project Structure

```
Weather-Forecasting/
├── Data/
│   ├── raw_toronto_weather_data.csv
│   ├── preprocessed_toronto_weather_data.csv
│   └── Readme.md
│
├── Model/
│   ├── WeatherForecasting.ipynb
│   ├── WeatherForecasting_2.ipynb
│   ├── WeatherForecasting_LT.ipynb
│   ├── WeatherForecasting.html
│   └── Readme.md
│
└── README.md
```

## 📌 Objectives

* Preprocess and explore historical weather data.
* Predict key weather parameters (e.g., temperature, humidity) using regression techniques.
* Evaluate and compare model performance using appropriate metrics.

## 📊 Data Description

The dataset contains hourly/daily weather measurements for Toronto, including:

* Temperature
* Humidity
* Wind speed
* Atmospheric pressure
* Visibility
* Precipitation

**Files**:

* `raw_toronto_weather_data.csv`: Unprocessed data.
* `preprocessed_toronto_weather_data.csv`: Cleaned and transformed data.

More details are in `Data/Readme.md`.

## 🤖 Models Used

The following regression models are applied:

* **Lasso Regression**: To perform feature selection by penalizing less important features.
* **Ridge Regression**: To handle multicollinearity by adding L2 penalty.
* **Elastic Net**: Combines L1 and L2 regularization for robust modeling.
* **Logistic Regression**: Used where binary classification of weather conditions is relevant (e.g., rain vs. no rain).

Each model was trained and tested using appropriate preprocessing and evaluated with metrics like:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## 🛠 Technologies

* Python
* pandas, numpy
* scikit-learn
* matplotlib, seaborn
* Jupyter Notebook / Colab

## ✅ How to Run

1. Clone the repository.
2. Open any notebook from the `Model/` folder.
3. Ensure data files from `Data/` are available in the correct path.
4. Run the notebook cells to reproduce results and forecasts.

## 🚀 Future Work

* Add deep learning models (e.g., LSTM for time series).
* Incorporate real-time API data for live predictions.
* Deploy a simple forecasting web app.

## 👤 Author

Safna Fayas
[GitHub Profile](https://github.com/safnafayas)


