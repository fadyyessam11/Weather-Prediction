a machine learning workflow for predicting weather data using three different types of Recurrent Neural Networks (RNN): Simple RNN, LSTM (Long Short-Term Memory), and GRU (Gated Recurrent Units). It goes through data preprocessing, model definition, training, and evaluation

This code performs the following tasks:

Prepares and normalizes the weather prediction dataset.

Trains three different types of RNN models (SimpleRNN, LSTM, and GRU) using multiple time steps (7, 14, 30, 45).

Evaluates each model by tracking training and testing loss and stopping epoch.

Saves the models for later use.

Visualizes results using boxplots and applies styling to highlight minimum validation losses
