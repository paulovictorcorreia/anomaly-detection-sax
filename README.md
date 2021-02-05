# Anomaly Detection in Compressed Time Series with SAX

This repository consists in results obtained in my research of anomaly detection in industrial context. It contains the notebooks and data used to perform what is proposed.

The purpose of this work is to detect anomalies in time series obtained in sensors and actuators from industries. The first step is to compress the data, transform the target data to the compressed domain, apply the result in a LSTM network powered by PyTorch, and apply the final binary output to a Moving Average Filter.

The data used is the Tenessee Eastman Process, which we ran simulations in MATLAB and obtained the resulting dataset to use as benchmark to detect anomalies.

## Notebooks

It contains the following notebooks:

*   *GridSearch Compression Parameters for Anomaly Detection.ipynb* - Notebook used to search for optimal compression parameters to detect anomalies in compressed data.
*   *Plotting Results of the Detector.ipynb* - Notebook used to plot the results of anomaly detection with specified parameters.
*   *Gridsearch Optimization in Unknown Data.ipynb* - Applying the gridsearch and obtaining the classification metrics by training the detector with training data and validating with unknown data, which consists all of Tenessee Eastman Process simulations.

## Data
