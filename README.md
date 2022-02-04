# 05
LSTM 



The work is done in the following steps:

step 01: Creating the corpus by removing punctuations and lower caseing the headlines.

step 02: We shuffle the dataset and test on the first 2000 lines, if all goes as planned, split the dataset and wait.

step 03: Tokenization, define a funtion that takes the corpus and return the token list and total words processed. (for generalizazions)

step 04: Padding (pre), define a function that takes the tojen list held in step 03 and return predictors, labels and an max sentence length. (for generalizazions)

step 05: Model creating, we will make a simple 3 layers model, the first one will be the ebmedding layer, second coes the LSTM layer (hidden) and finally a sofmax activation layer, the loss will be "crossentropy" (categorical since multiple, countable), the optimizer will be "adam" (most recommended)

step 06: Fit the model and wait, we will do 32 batches and work over 120 epochs.

step 07: Create a funtion that takes a seed and return a sequence of a fixed length using the model.
