# **Windows Version Market Share Time Series Forecasting**

## **Project Overview**

This project focuses on analyzing and forecasting the market share of various Windows versions in Turkey from September 2013 to September 2024. Using historical market share data, we employ time series analysis techniques to predict future trends for Windows 10. The project involves data cleaning, visualization, decomposition of time series components, and implementing a Seasonal AutoRegressive Integrated Moving Average (SARIMA) model for forecasting.

## **Data Source**

The data was obtained from the [StatCounter Global Stats](https://gs.statcounter.com/windows-version-market-share/desktop/turkey/#monthly-201309-202409) website, which provides the monthly market share percentages for different Windows versions.

## **Project Goals**

- Analyze the historical market share trends of different Windows versions in Turkey.
- Clean and preprocess the data to handle any missing values or anomalies.
- Visualize the trends to gain insights into the market dynamics.
- Apply a SARIMA model to forecast the market share of Windows 10 for the next 12 months.
- Evaluate the model performance and visualize the forecasted results.

## **Requirements**

To run the project, you need to have the following Python libraries installed:

- `pandas`: For data manipulation and analysis
- `matplotlib`: For data visualization
- `seaborn`: For enhanced data visualization
- `statsmodels`: For time series modeling and analysis

You can install these packages using the following commands:

```bash
pip install pandas matplotlib seaborn statsmodels
```

## **Data Preparation**

1. **Load the Data:**
   - Load the data from the CSV file and inspect the first few rows.

2. **Handle Missing Values:**
   - Check for missing values and handle them using forward fill (filling missing values with the last observed value).

3. **Check for Anomalies:**
   - Compute the total market share per month and ensure it adds up to approximately 100%. If any anomalies are found, inspect and address them.

## **Data Visualization**

- Visualize the market share trends of different Windows versions over time using line plots to observe historical patterns and trends.

## **Time Series Decomposition**

- Decompose the Windows 10 time series data into its components (trend, seasonality, and residuals) to better understand the underlying patterns.

## **SARIMA Model Implementation**

- Implement a SARIMA model to forecast the market share of Windows 10 for the next 12 months, taking into account the seasonality and trend components.

## **Forecast Visualization**

- Visualize the forecasted results along with the confidence intervals to understand the predicted trends and their reliability.

## **Usage**

To use this project, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/bkurtulmus/Time-Series-Forecasting-for-Windows-Version-Market-Share.git
   cd Time-Series-Forecasting-for-Windows-Version-Market-Share
   ```

2. Make sure you have all the required Python packages installed.

3. Run the notebook or script to execute the analysis and generate forecasts.

## **Results**

- The project provides a detailed analysis of Windows version trends in Turkey, along with predictions for the next 12 months for Windows 10.
- The SARIMA model forecast results are displayed with confidence intervals to show the expected range of future market share values.

## **Conclusion**

This project showcases the use of time series forecasting techniques for market share analysis, demonstrating the effectiveness of SARIMA models in predicting future trends based on historical data.

## **Future Improvements**

- Extend the analysis to other Windows versions or geographical regions.
- Explore alternative models like Prophet or LSTM for improved accuracy.
- Integrate real-time data updates for continuous forecasting.

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## **Acknowledgements**

- Data source: [StatCounter Global Stats](https://gs.statcounter.com/windows-version-market-share/desktop/turkey/#monthly-201309-202409)
