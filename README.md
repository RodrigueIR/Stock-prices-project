# Brownian Motion
Brownian motion is a mathematical model used to describe random movement, often applied in finance to model stock prices. 
It represents the erratic and unpredictable nature of price changes over time, capturing the essence of how stock prices fluctuate due to numerous unforeseen factors. 
In finance, stock prices are often assumed to follow a geometric Brownian motion, which is characterized by:
- Continuous paths: Stock prices are modeled as continuous functions of time.
- Independent increments: The price changes over non-overlapping intervals are independent.
- Normally distributed returns: The logarithmic returns of stock prices are normally distributed.

This model forms the foundation for various financial theories, including the Black-Scholes option pricing model.
## Stochastic Processes
A stochastic process is a collection of random variables representing a process that evolves over time. 
In finance, stock prices can be viewed as a stochastic process where future prices depend on both current information and random influences. 
This framework allows for the incorporation of uncertainty and variability inherent in financial markets.

Key types of stochastic processes used in modeling stock prices include:
- Geometric Brownian Motion: As mentioned, this is commonly used for modeling stock price dynamics.
- Markov Processes: These processes rely on the principle that future states depend only on the current state, not on the sequence of events that preceded it.
- Mean-Reverting Processes: These assume that prices will tend to return to a long-term mean over time, which is useful for certain asset classes.
## Stock Price Prediction
Predicting stock prices involves using historical data and various mathematical models to estimate future movements. 
Machine learning techniques, particularly those based on time series analysis like Long Short-Term Memory (LSTM) networks, have gained traction for this purpose. 
These models leverage past price data and other relevant features to forecast future prices.
Key considerations in stock price prediction include:
- Data Sources: Historical price data can be sourced from platforms like Yahoo Finance.
- Model Selection: Different models (e.g., ARIMA, LSTM) are evaluated for their predictive performance.
- Evaluation Metrics: Performance is typically assessed using metrics such as Root Mean Square Error (RMSE) to determine accuracy.

Brownian motion and stochastic processes provide a robust theoretical framework for understanding and predicting stock price movements, while modern machine learning techniques enhance the ability to make accurate forecasts amidst market volatility.

## Stock-prices-project
- Sigma^2 = 0.01: This indicates a very low volatility. 
The stock prices increase steadily over time, with relatively small fluctuations.
- Sigma^2 = 0.05: This represents moderate volatility. 
The stock prices show more variation compared to the previous case, with larger fluctuations.
- Sigma^2 = 0.1: This represents higher volatility. 
The stock prices exhibit even larger fluctuations, indicating a more volatile market.
- Sigma^2 = 0.2: This indicates very high volatility. 
The stock prices show significant swings over time, reflecting a highly volatile market.
### Graph
![graph](https://github.com/user-attachments/assets/15899ccc-36e8-48e3-97c3-c938e3dcd655)
## Poisson process
Suppose ${X(t),t ≥ 0}$ is a Poisson process with rate $\lambda$. Obtain a realization of the process for a fixed time interval [0,T]. 
Take four values of $\lambda$ and compare the performance of the process. Draw the plot of realization in all the cases. 
Find X(T) in all the cases. Comment on your findings.
- Lambda = 1: With a low value of $\lambda$, the Poisson process tends to have fewer events occurring in the given time interval.
This leads to lower values of X(T), indicating lower process values at the end of the interval.
- Lambda = 5: A moderate value of $\lambda$ results in a higher number of events occurring in the process compared to the previous case.
This leads to higher values of X(T) compared to $\lambda$=1.
- Lambda = 10: A higher value of  results in even more events occurring in the process, leading to higher values of X(T) compared to $\lambda$=5.
The process exhibits more variability and tends to reach higher values.
- Lambda = 20: With a very high value of $\lambda$, the Poisson process has a large number of events occurring in the given time interval.
This results in even higher values of X(T) compared to the previous cases, indicating a more volatile and higher-performing process.
### Graph
![poisson](https://github.com/user-attachments/assets/9b9003a9-e2e6-481f-b600-5c63b8b5b40a)
