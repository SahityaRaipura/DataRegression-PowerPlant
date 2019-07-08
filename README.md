# DataRegression-PowerPlant
Predicts energy output of powerplant using linear regression.
data is taken from https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant
The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant.
Outliers were removed using box plots.
Data was split into training and test data. 
Linear Regression model was used on the training data.
The model was 93.3 percent accurate (the mean absolute error is 3.6 energy units).
