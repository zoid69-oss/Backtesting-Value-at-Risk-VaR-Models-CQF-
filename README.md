# Backtesting-Value-at-Risk-VaR-Models-CQF-
## Overview

The project examines the performance of Analytical VaR models using both traditional and EWMA-based volatility estimation techniques. Key objectives include identifying model limitations and refining frameworks to better capture market risks.

### Key Achievements
- Conducted backtesting of **10-day Analytical VaR** at a **99% confidence level** for NASDAQ-100 and S&P 500 indices.
- Evaluated model performance during high-volatility periods, including the **COVID-19 pandemic** and **2021-2022 market corrections**.
- Implemented **EWMA-based volatility estimation** for improved responsiveness to market changes.

## Features

### 1. **VaR Backtesting**
- Implemented Analytical VaR to evaluate potential losses over a 10-day horizon.
- Backtested VaR predictions against realized returns to calculate breach rates.

### 2. **EWMA-Based Volatility Estimation**
- Adopted the Exponentially Weighted Moving Average (EWMA) method to estimate dynamic volatility.
- Tuned the smoothing parameter (\u03bb) for optimal performance, balancing responsiveness and stability.

### 3. **Market Insights**
- Highlighted periods of model underperformance during extreme volatility.
- Provided actionable recommendations to improve VaR frameworks for future crises.


## Results

### VaR Model Performance
- Analytical VaR exhibited high breach rates during volatile periods (e.g., COVID-19).
- EWMA-based VaR showed improved adaptability but still faced challenges in extreme conditions.

### Key Insights
- Traditional VaR models tend to underestimate risk during market crises.
- EWMA methods provide a smoother volatility estimate but may require tuning for high-stress periods.
- Incorporating stress testing and alternative models can enhance risk management frameworks.

## Future Work

- Explore hybrid approaches combining VaR with other risk measures like CVaR.
- Test alternative smoothing parameters (\u03bb) for EWMA in various market scenarios.
- Integrate machine learning techniques to forecast volatility and improve model accuracy.

