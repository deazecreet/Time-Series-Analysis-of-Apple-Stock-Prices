# Time-Series-Analysis-of-Apple-Stock-Prices

## Project Overview
This project involves time series analysis on Apple's stock price from 1980 to 2021, aiming to forecast future prices using Long Short-Term Memory (LSTM) networks. By leveraging TensorFlow and Keras, the model predicts closing prices based on historical data, showcasing the potential of LSTM in financial market analysis.

## Dataset
The dataset, sourced from HuggingFace (`apple_stock_price_from_1980-2021` by Ammok), includes daily stock prices with attributes such as Open, High, Low, Close, and Volume. This analysis focuses on the `Close` price, normalized to aid in the model's performance.

## Key Steps
- **Data Preprocessing:** Normalization of closing prices and splitting into training and validation sets.
- **Model Building:** An LSTM model is constructed, consisting of LSTM layers followed by Dense layers, to predict the normalized closing prices.
- **Model Training and Evaluation:** Utilizes callbacks like EarlyStopping and ReduceLROnPlateau to optimize training. The model's performance is evaluated using Mean Absolute Error (MAE) against the actual stock prices.

## Results
The LSTM model successfully predicts the stock prices with a satisfactory MAE, indicating the model's capability to capture the temporal dependencies in the stock market data. A comparison of the model's predictions with actual prices is visualized, providing insights into the model's accuracy and potential improvements.

## Technologies Used
- Python for programming.
- TensorFlow and Keras for building and training the LSTM model.
- Pandas for data manipulation.
- Matplotlib for data visualization.
- Scikit-learn for data preprocessing.

## Future Work
- Exploring the impact of different LSTM architectures and hyperparameters on model performance.
- Incorporating additional features such as volume and open prices to improve predictions.
- Applying the model to other financial time series data for broader applicability.

## Acknowledgments
- HuggingFace for providing the `apple_stock_price_from_1980-2021` dataset.
- The TensorFlow and Keras community for the deep learning framework.
