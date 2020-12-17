# nasa-turbofan-RUL
Remaining usability lifetime of nasa turbofan dataset
The goal of this challenge is to predict the RUL (Remaining Useful Life) of turbofan engines.

The dataset consists of different multivariate time-series. These different time-series refer to different engines ( engineno in the dataset). The sampling of the time series is 1 point per engine cycle ( timein_cycles in the dataset).

The dataset is split into train data and test data to evaluate your model.

In the train dataset: the engine runs until failure. It means that for each data point we can associate the RUL (Remaining Useful Life in cycles). This column is present in the train dataset (RUL).

In the test dataset: The engine runs until a certain point. What you need to predict is the RUL at the last point of the dataset.
