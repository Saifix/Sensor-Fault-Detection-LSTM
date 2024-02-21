# LSTM Model for Fault Detection in Tennessee Eastman Process Simulation Dataset

## Introduction
This project focuses on developing an LSTM-based model for fault detection using the Tennessee Eastman Process Simulation dataset. The dataset consists of fault-free and faulty instances, which are utilized for training and evaluating the model.

### Steps Taken 🚀
1. **Importing Libraries**: Essential libraries including PyReadr for reading RData files, Matplotlib for visualization, Seaborn for statistical graphics, NumPy, Pandas for data manipulation, and Keras for building deep learning models were imported.
2. **Importing Dataset**: Fault-free and faulty training datasets were located and imported. PyReadr was used to read RData files, and Pandas for data manipulation.
3. **Preprocessing Dataset**: Data preprocessing involved filtering, scaling, and encoding categorical variables using StandardScaler and OneHotEncoder from scikit-learn. Sliding window technique was applied for sequence data preparation.
4. **Preparing LSTM Model**: An LSTM-based neural network model was constructed using Keras, with bidirectional LSTM layers and dropout regularization.
5. **Training Model**: The model was trained on the preprocessed data with early stopping to prevent overfitting.
6. **Evaluating the Model**: The model's performance was evaluated using confusion matrices and accuracy scores.

## Results
- **Training Performance**: The training history depicted decreasing loss and increasing accuracy over epochs, with some fluctuations indicating effective learning.
- **Evaluation Metrics**: The confusion matrix revealed the model's ability to accurately predict fault classes, with an overall accuracy score computed.
- **Real-time Fault Prediction**: Visualization of the model's predictions for real-time fault detection demonstrated its capability to identify fault classes over time.
- **t-SNE Visualization**: t-SNE visualization was used to analyze the clustering performance of the model, providing insights into its ability to distinguish between fault classes.

## Conclusion
This project illustrates the effectiveness of LSTM models for fault detection in industrial processes using the Tennessee Eastman Process Simulation dataset. Through rigorous preprocessing and model construction, a reliable fault detection system with promising performance metrics was achieved.
