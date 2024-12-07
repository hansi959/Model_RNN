# Model_RNN
This project demonstrates the use of Long Short-Term Memory (LSTM) networks for predicting Google stock prices based on historical market data. The model was designed to analyze temporal dependencies in stock market trends and provide future price predictions.
### Features
Data Preprocessing: Historical stock data (Open, High, Low, Close, and Volume) was scaled and transformed into sequences for efficient training.
Model Architecture: A stacked LSTM network with multiple layers and dropout regularization to prevent overfitting.
Training: The model was trained to minimize mean squared error (MSE), and its performance was evaluated using training, validation, and test datasets.
Visualization: Actual vs. predicted stock prices were visualized to assess the model's performance and trend-following capabilities.
### Technologies Used
Python (NumPy, Pandas)
TensorFlow/Keras for deep learning
Matplotlib for data visualization
Scikit-learn for preprocessing
