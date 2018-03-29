# Assesment-1

Given this dataset, predict y (an element of the return of a financial data series; it is a column in the dataset) from a number of features that are supplied.

Here is a brief description of the features:

* Index: A unique value that labels each row in the data set
* Day: Index from an initial reference day
* Market: A label that indicates which exchange the instrument is traded on
* Stock: A unique label for each instrument
* x0...x3E: Predictors that relate to the observed behaviour of the instrument on the day in question. The features labelled 'x3A', 'x3B', etc. are strongly related amongst themselves and might be expected to be highly correlated.
* x4...x6: Predictors that describe the ‘typical’ behaviour that we would expect of the instrument on that day.

Your final submission should be the test.csv file with an added column named 'y_pred' which are your predictions. Your submission will be evaluated using the standard RMSE number. Along with the test file, please also upload your jupyter notebook.

Please update your notebook and csv file in your self-named branch in this repository. 
