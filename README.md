# w-LSTM & w-GRU

### Combining Moving Average and Deep Learning Methods for Better Forecasting

Various time series forecasting methods have been introduced in the literature. The main goal is to predict future values from known historical data. In this study, we propose a new method of time series forecasting using two well-known Deep Learning methods, Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU), combine with Weighted Moving Average (WMA) method. We then prepare two scenarios, one for the original LSTM and GRU implementation and another for the proposed methods (w-LSTM and w-GRU) implementation. Based on experimental results on two types of real-world import values dataset, the proposed w-LSTM and w-GRU methods got lower average values of 1143.242, 999.028, and 0.155 for Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE) respectively than the ones from original LSTM and GRU implementation. Hence, the proposed methods have better prediction results than the original version of the Deep Learning methods applied in the dataset.

This repository contains all the project codes, revision history, and data samples used in the project.
We welcome any comments, suggestions, and questions which can be addressed to the email provided below.

*RELATED ARTICLE*

For more detailed information related to the proposed method and previous studies, please refers to following publications and articles:
1. Hansun, S., Young, J.C. Predicting LQ45 financial sector indices using RNN-LSTM. J Big Data 8, 104 (2021). https://doi.org/10.1186/s40537-021-00495-x
2. Hansun, S. (2013). A New Approach of Moving Average Method in Time Series Analysis. Proceedings of 2013 Conference on New Media Studies, Tangerang, Indonesia. doi:10.1109/CoNMedia.2013.6708545
3. http://colah.github.io/posts/2015-08-Understanding-LSTMs/
4. https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21

*DATA SOURCE*
* The main data source is taken from *Statistics Indonesia*. https://www.bps.go.id/indicator/8/1754/1/nilai-impor-migas-nonmigas.html
* For simplicity, the datasets being used can be found in the 'Dataset' folder

*CONTACT US*

*Email: seng.hansun@lecturer.umn.ac.id

*TERMS OF USE*

For publications that use codes and data provided in this repository, please cite:
* "Hansun, S. Combining Moving Average and Deep Learning Methods for Better Forecasting. https://github.com/senghansun/w-LSTM-w-GRU"
