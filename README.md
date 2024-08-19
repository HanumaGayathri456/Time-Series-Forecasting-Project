
# Time Series Forecasting using RNN

## Project Description

This project implements a time series forecasting model using a Recurrent Neural Network (RNN). The model is trained on historical time series data to predict future values.

## Requirements

- Python 3.x
- TensorFlow 2.x
- Keras
- Pandas
- NumPy
- scikit-learn
- Matplotlib

## Installation

Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Place your time series data in a CSV file, and ensure it has a 'Date' column and a target column.
2. Run the `RNN_TimeSeries_Forecasting.ipynb` notebook.
3. The notebook will output predictions and visualizations of the forecasting results.

## Model Details

- The RNN is implemented using the Keras library.
- The model uses SimpleRNN layers with a dense output layer.
- Data is scaled using MinMaxScaler.
- The model is trained using Mean Squared Error (MSE) as the loss function.

## Example Results

The model achieves a Root Mean Squared Error (RMSE) of approximately X on the training set and Y on the testing set (replace X and Y with actual values).

## Future Work

- Experiment with more complex RNN architectures, such as LSTM or GRU.
- Include additional features in the model.
- Test with different time steps and hyperparameters.
