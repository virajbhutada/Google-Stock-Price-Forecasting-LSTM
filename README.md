## Google Stock Analysis 📊 & Prediction Using LSTM 📈

In this comprehensive project, we explore Google's stock market data, analyzing patterns and fluctuations, and utilizing LSTM (Long Short-Term Memory) networks to predict future stock prices. This analysis aims to provide insightful and informed decision-making tools.

### Table of Contents

1. [Introduction](#introduction)
2. [Data Exploration](#data-exploration)
3. [Data Preprocessing](#data-preprocessing)
4. [LSTM Dataset Creation](#lstm-dataset-creation)
5. [Model Building](#model-building)
6. [Model Training](#model-training)
7. [Evaluation and Visualization](#evaluation-and-visualization)
8. [Future Predictions](#future-predictions)
9. [Upcoming Price Visualization](#upcoming-price-visualization)
10. [Dataset](#dataset)
11. [Conclusion](#conclusion)


---

## Introduction

In this immersive journey, we delve into the intricate world of Google's stock market. With keen observation and meticulous analysis, we uncover the nuanced patterns and fluctuations within Google's stock data. Employing cutting-edge LSTM technology, we navigate the complexities, foreseeing future trajectories, and providing insights that empower informed decision-making.

---

## Data Exploration

### Initial Analysis

We begin by analyzing 14 insightful columns and 1257 rows of data, focusing on attributes like close, high, low, open, volume, and more. This thorough exploration sets the foundation for subsequent steps, involving statistical summaries, visual inspections of distributions, and the identification of potential patterns or anomalies.

---

## Data Preprocessing

### Data Cleaning and Preparation

- **Handling Missing Values**: Missing values are addressed using strategies like forward fill, backward fill, or interpolation to maintain data integrity.
- **Scaling Data**: We use MinMaxScaler to normalize the data, ensuring all features contribute equally to the model and preventing any single feature from dominating due to its scale.

---

## LSTM Dataset Creation

### Data Sequencing

Given the temporal nature of stock data, we create sequences of data tailored for LSTM. This involves careful consideration of sequence length and feature selection, generating input-output pairs suitable for LSTM training by sliding a window over the time series data.

---

## Model Building

### Constructing the Model

We construct a robust LSTM model using layers such as LSTM, Dropout, and Dense. Each layer is meticulously tuned to predict stock prices effectively, leveraging insights from both theory and empirical experimentation. The LSTM layer captures temporal dependencies, the Dropout layer prevents overfitting, and the Dense layer outputs the final predictions.

---

## Model Training

### Iterative Training

We train the LSTM model over 100 epochs, allowing it to learn from historical data and adapt its weights, enhancing its predictive capabilities. This involves optimizing the model parameters using backpropagation through time (BPTT) and gradient descent techniques.

---

## Evaluation and Visualization

### Assessing Accuracy

We evaluate the model's performance using metrics like Root Mean Squared Error (RMSE), providing a quantitative measure of its predictive prowess. Visualizations further aid in interpreting the model's predictions, offering insights into its strengths and limitations. Comparison plots between actual and predicted prices help in visually assessing the model's performance.

---

## Future Predictions

### Forecasting

The model predicts the next 20 days' open and close stock prices by iteratively feeding the most recent data and generating future values.

---

## Upcoming Price Visualization

### Visualizing Predictions

We showcase the upcoming stock price predictions using visualization tools such as line plots, candlestick charts, and confidence intervals to effectively present the forecasted prices.



### Visuals

| ![Screenshot 2024-06-05 225005](https://github.com/virajbhutada/Google-Stock-Price-Forecasting-LSTM/assets/143819712/f6e89b00-4690-4df9-a648-5bfd75ab79f0) | ![Screenshot 2024-06-05 224959](https://github.com/virajbhutada/Google-Stock-Price-Forecasting-LSTM/assets/143819712/f3ac6779-af6c-4dbf-afe6-35a76934c365) |
|:---:|:---:|
| ![Screenshot 2024-06-05 224946](https://github.com/virajbhutada/Google-Stock-Price-Forecasting-LSTM/assets/143819712/63dcc3b7-0dfe-49c9-b398-1ca01fc73cc2) | ![Screenshot 2024-06-05 224940](https://github.com/virajbhutada/Google-Stock-Price-Forecasting-LSTM/assets/143819712/6b621270-4186-4afa-8445-f68042359ab9) |
| ![Screenshot 2024-06-05 224934](https://github.com/virajbhutada/Google-Stock-Price-Forecasting-LSTM/assets/143819712/7499ef1c-4f3c-426f-81ec-b501274ea2f0) | ![Screenshot 2024-06-05 224925](https://github.com/virajbhutada/Google-Stock-Price-Forecasting-LSTM/assets/143819712/ac928000-2bd9-4d7a-a5f5-e84e99cfc1a5) |
| ![Screenshot 2024-06-05 224917](https://github.com/virajbhutada/Google-Stock-Price-Forecasting-LSTM/assets/143819712/390264d2-92e9-4155-b542-6494ba346a2a) | ![Screenshot 2024-06-05 224901](https://github.com/virajbhutada/Google-Stock-Price-Forecasting-LSTM/assets/143819712/d36c4c58-4655-4cfe-8eb4-740b20966945) |

---

## Dataset

The dataset used for this project is available on Kaggle:
- [Google Stock Prediction Dataset](https://www.kaggle.com/datasets/shreenidhihipparagi/google-stock-prediction)

---

## Conclusion

This project isn't just about predicting numbers; it's about understanding market dynamics, leveraging cutting-edge technology, and making informed decisions. Join us as we decode the language of stock prices and unlock the secrets hidden within the data. This project underscores the importance of advanced machine learning techniques in financial forecasting and provides a comprehensive approach to stock price prediction.
