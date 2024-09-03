## Project Description
This project presents a comprehensive study on predicting the adjusted closing prices of stocks using Machine Learning Algorithms. The primary objective is to build models such as Long Short-Term Memory (LSTM), Support Vector Regression (SVR), and a hybrid LSTM-SVR model to predict adjusted closing stock prices. The performance of these models was evaluated and compared to select the best-performing model. The models were trained and tested on historical stock market prices for Netflix and Tesla, ranging from 2004 to 2024.

## Dataset Details
the datasets used in this project were obtained directly using the Yahoo Finance Python library. They contain historical stock prices for Netflix and Tesla. The data underwent preprocessing steps, including normalization, data splitting, and removal of duplicates.


## Usage Instructions
1. *Preprocessing the Data:*
   - Load the datasets from Yahoo Finance.
   - Normalize the data to ensure that all features contribute equally to the models.
   - Split the data into training and testing sets.

2. *Training the Models:*
   - Run the notboook to train the LSTM, SVR, and hybrid LSTM-SVR models.
   - Evaluate the models using R² and RMSE metrics.

3. *Testing the Models:*
   - Test the trained models on the test dataset.
   - Compare the predicted prices with actual prices to determine model accuracy.

4. *Viewing Results:*
   - The notebook will generate plots and performance metrics for each model.

## Results Overview
Among the three models used in this study, the SVR had the overall best performance on the Netflix and Tesla dataset, with a R2  of 0.99  on both datasets,  it also had a high RMSE of 3.17 and 2.35 suggesting that it performed poorly at minimizing prediction errors. Further fine tuning of the datasets can be done to  improve the performance of the models. The LSTM model also performed well on both datasets having a R2 of 0.98 and 0.92 for Netflix and Tesla respectively, but had the highest RMSE of 4.27 and 2.88 when compared to other models, meaning that LSTM’s predictions were a bit far from the actual prices. As for the hybrid LSTM-SVR, it performed the least, with a R2 of 0.77 and 0.91 on the Netflix and Tesla Datasets respectively, though it still proved to be effective in minimizing prediction errors having a considerably low RMSE of 0.09 and 0.04 on both data sets. 


