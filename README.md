# powerball

An attempt to use an LSTM model to predict individual numbers for Powerball drawings. All historical numbers were taken from data.gov and formatted into a long series. The series was trained on a model with an R2 score of .80 and then the model was used to predict the subsequent 5 numbers.

This was attempted with 7 and 30 day lookback windows. 

Currently not sure how to handle duplicate predicted numbers and first 5 numbers and powerball are handled via 2 separate scripts, which is pretty redudant. 
