# Live-Stock-Prediction-using-Live-Dataset
This project involves time series analysis and forecasting of Oracle and Apple stock data. It examines stock trends, seasonality, and changes over time using statistical techniques like resampling, normalization, rolling statistics, and decomposition. Predictive models, including ARIMA, SARIMA, and Dynamic Factor Models, are applied to forecast stock prices and volumes. Among the models, the Dynamic Factor Model achieved the best accuracy for Oracle volume prediction with the lowest RMSE because of its ability to account for multivariate dependencies and shared patterns across multiple time series, effectively capturing latent factors influencing the data. This makes it particularly suitable for complex datasets with intertwined variables and structural relationships. SARIMA, on the other hand, is particularly well-suited for datasets with strong seasonal patterns, providing better results in handling such complexities. In contrast, ARIMA and ARMA struggled with seasonal and multivariate data, highlighting their limitations in addressing these patterns effectively. The project emphasizes visualization using Matplotlib and Plotly, providing actionable insights into stock performance.
