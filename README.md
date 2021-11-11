# Charity-Funding-Predictor
Deep Learning Homework



Results:
Data Processing

	My target variable for my model: IS_SUCCESSFUL
	All the variables from the datasets are features except for IS_SUCCESSFUL for my model
	Variable that were neither targets or features for the dataset is EIN and NAME which I eneded up drooping it. It will not impact the outcome.

Compiling, Training, and Evaluating the Model
	
		
	For my model I had 2 hidden layers. My first layer had 80 neurons, the second has 30 neurons.
	I used "relu" and "sigmoid" activation function for my model. I used "relu" because this function does not activate all
	all the neurons at the same time. I also used "sigmoid" function because it has the property that it maps the entire number line
	into a small range and also convert a real value into one that can be interpreted as a probability

Model Performance

	The model did not performed well and did not even reach 75% target. I used three different methods including changing Hidden Layers and Activation function,
	accuracy score was about same as none of the methods produced more tahn 75% acuracy score.

Summary,

	All of the three methods for my model produced less than 75% accuracy score. My recommendation for a different model could be Feature Selection.
	I recommend the feature selection model because you could possible run that before you run your neural network model to determine whcih features
	are import. Eliminating to unnecessary features could give us better accuracy rate. 
Thank you,
Veronika Patel
