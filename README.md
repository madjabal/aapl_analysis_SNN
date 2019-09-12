# aapl_analysis_SNN
In depth analysis of AAPL stock with a self-normalizing neural net (using SELU's)

Data was collected from Kaggle (link to follow soon).

Analysis was done using a 5 layer fully connected neural network taking advantage of the SELU activation function.
These functions (Self Exponential Linear Units) create a self-normalizing neural network that has faster convergence and
better training results vs other activation functions for regressions.

The results obtained were good, possibly not great depending on the actual ability of a model to approximate AAPL's stock 
price function. 

The model may seem overfit, but it does seem to follow the price closely in a time period where the function was not trained.
The 'attitude' or some internal function changes and the predicting power of the network becomes significantly diminished
(the model thinks the stock should be lower according to its historic price.
