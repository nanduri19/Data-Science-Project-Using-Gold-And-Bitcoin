# Data-Science-Project-Using-Gold-And-Bitcoin
**Gold price dataset link:**
https://uk.investing.com/commodities/gold-historical-data

**Bitcoin Price dataset link:**
https://www.kaggle.com/datasets/adilbhatti/bitcoin-and-fear-and-greed
**Neural Network Approaches for Gold and Bitcoin Price Prediction**

**Overview**

This project explores neural network approaches for predicting the
prices of Gold and Bitcoin. By leveraging various deep learning models,
the aim is to assess and compare their performance in forecasting
financial time series data. The research employs advanced neural network
architectures to provide insights into their effectiveness for
predicting the future prices of these valuable assets.

**Objectives**

-   To implement and evaluate various neural network architectures for
    predicting Gold and Bitcoin prices.

-   To compare the performance of different models based on accuracy,
    training time, and prediction quality.

-   To provide a comprehensive analysis of model effectiveness in
    financial forecasting.

**Features**

-   **Multiple Neural Network Models:** Implementation of various
    architectures including LSTM (Long Short-Term Memory), GRU (Gated
    Recurrent Unit), CNN (Convolutional Neural Network), and hybrid
    models.

-   **Data Preprocessing:** Techniques for data normalization, feature
    extraction, and time series analysis.

-   **Performance Evaluation:** Metrics including Mean Squared Error
    (MSE), Mean Absolute Error (MAE), and R-squared values to assess
    model performance.

-   **Visualization:** Graphs and plots to illustrate predictions versus
    actual values.

**Installation**

To set up the project environment, follow these steps:

1.  **Clone the Repository:**

> bash
>
> Copy code
>
> git clone https://github.com/yourusername/price-prediction.git
>
> cd price-prediction

2.  **Install Dependencies:** Create a virtual environment (optional but
    recommended):

> bash
>
> Copy code
>
> python -m venv venv
>
> source venv/bin/activate \# On Windows use \`venv\\Scripts\\activate\`
>
> Install required packages:
>
> bash
>
> Copy code
>
> pip install -r requirements.txt

**Usage**

1.  **Prepare the Data:** Download and place the Gold and Bitcoin price
    datasets into the data/ directory.

2.  **Run the Models:** Execute the scripts to train and evaluate the
    models. For example:

> bash
>
> Copy code
>
> python train_lstm.py
>
> python train_gru.py
>
> python train_cnn.py

3.  **View Results:** After training, results and visualizations will be
    saved in the results/ directory. You can view performance metrics
    and comparison plots.

**Data**

-   **Gold Price Data:** Historical gold price data (daily) used for
    training and testing.

-   **Bitcoin Price Data:** Historical Bitcoin price data (daily) used
    for training and testing.

You can obtain the datasets from the following sources:

-   Gold Price Data

-   Bitcoin Price Data

Make sure to place these files in the data/ directory.

**Contributing**

Contributions are welcome! If you have suggestions, improvements, or bug
fixes, please follow these steps:

1.  Fork the repository.

2.  Create a new branch for your changes.

3.  Commit your changes with descriptive messages.

4.  Push your changes to your forked repository.

5.  Open a pull request detailing your changes and improvements.
