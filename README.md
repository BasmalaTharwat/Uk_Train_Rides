# UK Train Rides Analysis & Prediction

A Data Analytics and Machine Learning project that analyzes UK railway journey data to uncover insights about train punctuality, passenger behavior, ticket pricing, delays, and revenue trends.

## Project Goals

- Analyze UK train ride data
- Explore passenger and ticket trends
- Identify causes of train delays
- Forecast future revenue
- Predict ticket prices using Machine Learning

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI

---

## Dataset Features

The dataset includes:

- Purchase details
- Payment methods
- Ticket class & type
- Departure and arrival stations
- Journey status
- Delay reasons
- Ticket prices

---

## Data Preprocessing

- Handled missing values
- Standardized delay categories
- Converted date/time columns
- Created:
  - Trip Duration
  - Delay Time features

---

## Exploratory Data Analysis

The analysis includes:

- Train punctuality analysis
- Payment method distribution
- Ticket class comparison
- Delay reason analysis
- Station traffic trends
- Revenue analysis
- Monthly travel trends

---

## Machine Learning Models

### Revenue Forecasting
Model: `RandomForestRegressor`

- RMSE: 22.60
- R² Score: 0.81

Forecasted revenue from May–October 2024.

### Ticket Price Prediction
Model: `RandomForestRegressor`

- Testing MAE: 0.11
- Testing MSE: 0.04
- Accuracy (R): 0.98

---

## Key Insights

- 87% of journeys arrive on time
- Credit cards are the most used payment method
- Weather is the leading cause of delays
- Ticket prices are strongly affected by:
  - Ticket class
  - Ticket type
  - Destination
  - Trip duration

---

## Project Structure

```bash
UK_Train_Rides/
│── data/
│   ├── railway.csv
│   └── outcome.csv
|
├── UK_Train_Rides.ipynb
├── README.md
```
---
