# AI_classification
<p>The purpose of this project was to take numerical pixel data from a 3x3 satellite image of neighbourhoods and classify the type of soil into one of seven classes. The input data is the 9 pixels (from the 3x3 square) under four different spectral bands of colour: green, red, and two types of infra-red, giving 36 input columns. 3,199 rows were used from an initial 10,000. The AI technique used to solve this problem a feed forward neural network (FNN) with a multilayer perceptron model (MLP). There was a total of 8 layers not including the input layer: layer with 512 neurons, 0.2 out of 1.0 chance of dropout, layer with 512 neurons, 0.2 dropout layer, neuron with 512 neurons, 0.2 dropout layer, layer with 100 neurons and finally, the output layer. 
	The major findings with this model were a 91.45% accuracy score and 91.65% F1 score. This demonstrates the high efficiency and excellent rate of correctly predicting the correct classes of soil for the pixel data. When four sample pieces of data were used for prediction, the model predicted 3 out of 4 of their classes correctly. 
	In conclusion, the MLP model used for this problem had high rates of accuracy, precision, recall, and F1 scores. This shows the model makes good and consistent predictions with the data provided. It is recommended that this model be used for this data set in the future.

</p>
<br>-----------------------------------------------<br>
The link to this notebook is: <a href="https://github.com/meganegross/AI_classification/blob/main/miniP3.ipynb">Classification Notebook</a>
