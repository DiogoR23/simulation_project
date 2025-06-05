# 📈 Demand Forecasting Simulation for Supermarket Products

This academic project was developed as part of the **Data-Oriented Simulation** course in the Bachelor's Degree in Applied Data Science – Universidade Católica Portuguesa (2025/2026).

## Objective

This project simulates the weekly demand of 50 supermarket products over 260 weeks, aiming to explore forecasting methods and assess their robustness in the presence of seasonality and random shocks. The simulation reflects real-world challenges faced by large retailers in inventory management and supply chain planning.

## Project Components

1. **Demand Simulation using the Bass Diffusion Model**  
   Synthetic time series are generated to represent the adoption and lifecycle of each product using the Bass model.

2. **Incorporating Seasonality**  
   The simulated demand curves are adapted to include realistic seasonal patterns.

3. **Forecasting Models**  
   Classical time series models (e.g., ARIMA, Exponential Smoothing) and machine learning methods (e.g., Random Forest, XGBoost) are used to forecast 10 future periods.

4. **Monte Carlo Simulation for Robustness Testing**  
   Robustness of the models is evaluated under increasing levels of random demand shocks (10%, 20%, ..., 60%).

## References

- Kang, Y., Hyndman, R. J., & Li, F. (2020). *GRATIS: Generating Time Series with Diverse and Controllable Characteristics*.
- Talagala, T. S., Hyndman, R. J., & Athanasopoulos, G. (2023). *Meta-learning how to forecast time series*.
- Das, S. R. (2021). *Product Forecasting using Bass Diffusion Model*.  
- [Bass Model](https://srdas.github.io/MLBook/productForecastingBassModel.html)

> **Note**: This project uses fully synthetic data generated through simulation and does not contain real or sensitive information.
