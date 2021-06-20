# astp_mcd_2021
Project content description

It has 6 different notebooks:
1-Data_Cleaning.ipynb - Responsible to read the original data and build the CSV needed by the product;
2-Data_Prepare.ipynb - Reads the CSV and build different outputs with different perspectives, needed by the models;
3.1-Model_ARMA_ARIMA_SARIMA.ipynb - Handle the models ARMA,ARIMA and their variations;
3.2-Model_ARCH_GARCH.ipynb - Work over the "best" ARIMA model, and models the variance;
3.3-Model_LSTM.ipynb - Another approach using RNN;
3.4-Model_Prophet.ipynb - Using Prophet;

Ideally, the notebooks should be executed in the order described above.

The original data is in the following path:
./rawdata/online_retail_II.xlsx

And the other data perspectives needed for the models will be in the folder:
./data/