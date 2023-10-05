# GoogleStockPrediction

Overview
This project utilizes a Recurrent Neural Network (RNN) model to predict Google's stock price trends for January 2017. The model is trained on five years of historical Google stock prices to make future trend predictions.

Objective
The primary goal of this project is to forecast whether the Google stock price will trend upwards or downwards in January 2017. The model does not aim to predict the exact stock price but focuses on capturing the general trends.

Dataset
The dataset used for this project consists of historical Google stock prices for the past five years. This data is crucial for training the RNN model to understand patterns and trends in the stock price movement.

Model Training
The RNN model is trained solely on the historical stock prices from the past five years, excluding the January prices. This separation between training and testing data ensures that the model does not learn from the specific data it aims to predict.

Evaluation
To evaluate the model's performance, actual Google stock prices for January 2017 are used for comparison. The model's predictions are compared against the real January 2017 prices to assess its ability to capture the stock price trends.

Results
The final output of this project is a comparison between the predicted stock price trends and the actual trends for January 2017. A graphical plot at the end of the notebook visually demonstrates the model's success in capturing these trends.

Conclusion
The success of this project lies in its ability to predict the direction of Google stock price trends for January 2017, aiding investors and analysts in making informed decisions. While it does not provide exact prices, it serves as a valuable tool for understanding market trends and potential investment opportunities.
