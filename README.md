
# Sales Trends Analysis Project

## Overview

This project aims to analyze sales trends and identify key patterns in the sales data of a retail store chain. The primary goals are to determine the peak and low sales dates for each year, examine the impact of promotions on sales, and understand the sales dynamics across different product families and store clusters. The analysis leverages Python's Polars library for efficient data manipulation and Seaborn for data visualization.

## Steps and Methods

### Data Analysis
- **Descriptive Statistics**: Calculated highest and lowest sales for each year, identifying significant sales trends.
- **Impact of Wage Payments**: Analyzed sales data on wage payment days, finding a slight increase in sales.

### Hypothesis Testing
- **Effect of Holidays on Sales**: Conducted a Mann-Whitney U test to determine the impact of holidays on sales, leading to the rejection of the null hypothesis, indicating a significant effect.

### Time Series Analysis
- **Data Preparation**: Applied differencing to remove trends and seasonality, confirmed data stationarity using the Augmented Dickey-Fuller test.
- **Modeling**: Compared SARIMA, ARIMA, and Prophet models, with SARIMA showing the best performance based on error metrics.

### Machine Learning Models
- **Feature Engineering**: Created date-related features and preprocessed the data using pipelines for numerical and categorical features.
- **Model Training**: Trained Linear Regression and XGBRegressor models, with XGBRegressor performing better.

### Forecast Visualization
- **Comparison Plots**: Visualized observed sales vs. forecasts from different models to compare accuracy.

## Conclusion and Recommendations

- **Conclusion**: SARIMA was the best performing statistical model, while XGBRegressor was the best machine learning model.
- **Recommendations**:
  - Enhance feature engineering with additional relevant features.
  - Use ensemble methods to combine forecasts.
  - Regularly update models with new data for improved accuracy.

## Article

| Topic                    | Link                                      |
|--------------------------|-------------------------------------------|
| Detailed Project Article | [Read the full article here](https://medium.com/@nheldana8/time-series-store-sales-forecasting-f4a2e184b5a6) |

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Python


### Setup

Clone this repository to your desired folder:


```sh
  cd your-folder
  git clone https://github.com/heldana30/Time_Series_Regression_Analysis.git
```
Change into the cloned repository

```sh
  cd Time_Series_Regression_Analysis
```

Create a virtual environment

```sh

python -m venv env

```

Activate the virtual environment

```sh
    env/Scripts/activate
```
### Install

Here, you need to recursively install the packages in the `requirements.txt` file using the command below 

```sh
   pip install -r requirements.txt
```

## 👥 Authors <a name="authors"></a>

👩‍💻 **Heldana Natnael Ambaw**

- GitHub: [GitHub Profile](https://github.com/heldana30)

- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/heldana-n/)

## 🙏 Acknowledgments <a name="acknowledgements"></a>

A big shoutout to my awesome team, Team Curium! ♥
Your support, guidance, and collaboration have been invaluable. Thanks for all the help and camaraderie throughout this journey!

# Sales Forecasting Analysis

This project involves analyzing and forecasting sales data using statistical and machine learning models. The analysis includes data preparation, hypothesis testing, time series modeling, and machine learning techniques.

