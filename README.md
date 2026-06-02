# weather_ai_project


## Project Overview

This project analyzes historical weather data and predicts temperature using Machine Learning techniques.

The system processes weather information such as humidity, precipitation, wind speed, location, and date information to estimate future temperature trends.

The project demonstrates the complete Machine Learning workflow including data cleaning, feature engineering, model training, evaluation, and visualization.

---

## Features

- Weather data analysis
- Data cleaning and preprocessing
- Feature engineering
- Temperature prediction
- Random Forest Machine Learning model
- Model evaluation
- Historical weather visualization
- Actual vs Predicted comparison
- Feature importance analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook
- Anaconda

---

## Dataset Description

The dataset contains weather information collected from multiple locations.

### Attributes

| Column Name | Description |
|------------|-------------|
| Location | City Name |
| Date_Time | Date and Time |
| Temperature_C | Temperature in Celsius |
| Humidity_pct | Humidity Percentage |
| Precipitation_mm | Rainfall in Millimeters |
| Wind_Speed_kmh | Wind Speed in km/h |

---

## Machine Learning Workflow

### 1. Data Collection

Weather data is loaded from a CSV file.

```python
df = pd.read_csv("weather_data.csv")
```

---

### 2. Data Cleaning

Performed operations:

- Remove missing values
- Remove duplicate records
- Convert Date_Time into datetime format
- Sort records by date

---

### 3. Feature Engineering

Additional features created:

- Location Encoding
- Year
- Month
- Day

Example:

| Location | Location_Code |
|----------|--------------|
| San Diego | 0 |
| Philadelphia | 1 |
| San Antonio | 2 |

---

### 4. Train-Test Split

Dataset is divided into:

- 80% Training Data
- 20% Testing Data

---

### 5. Model Training

Machine Learning Algorithm:

### Random Forest Regressor

Advantages:

- Handles large datasets
- Reduces overfitting
- Captures nonlinear relationships
- Provides feature importance

---

### 6. Temperature Prediction

The trained model predicts temperature based on:

- Location
- Date
- Humidity
- Rainfall
- Wind Speed

---

### 7. Model Evaluation

Metrics Used:

#### R² Score

Measures prediction performance.

- 1.0 = Perfect
- 0 = Average Prediction
- Less than 0 = Poor Prediction

#### Mean Absolute Error (MAE)

Measures average prediction error.

---

### 8. Data Visualization

Graphs Generated:

#### Historical Temperature Trend

Shows temperature changes over time.

#### Actual vs Predicted Temperature

Compares model predictions with actual values.

#### Feature Importance Graph

Displays which features contribute most to prediction.

---

## Project Structure

WeatherPredictionProject/

├── weather_data.csv

├── weather_prediction.ipynb

├── weather_model.pkl

├── README.md

└── requirements.txt



## Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
weather_prediction.ipynb
```

Execute all cells.

---

## Results

The model analyzes weather conditions and predicts temperature values.

Outputs include:

- Temperature prediction
- Model accuracy metrics
- Historical weather trends
- Feature importance analysis

---

## Future Enhancements

- Deep Learning (LSTM)
- Real-Time Weather API Integration
- Weather Forecast Dashboard
- Streamlit Web Application
- Seasonal Prediction Models
- Multi-City Forecasting

---

## Learning Outcomes

This project demonstrates:

- Data Preprocessing
- Feature Engineering
- Machine Learning
- Regression Analysis
- Model Evaluation
- Data Visualization
- Weather Analytics

---

## Conclusion

This project successfully applies Machine Learning techniques to weather data analysis and temperature prediction. The system demonstrates how environmental factors such as humidity, precipitation, wind speed, and location can be used to estimate temperature trends.

---

## Author

Mayank Raj kushwaha

BCA Student

A.I. Project
