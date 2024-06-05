**Combined Cycle Power Plant**

A combined-cycle power plant is an electrical power plant in which a Gas Turbine (GT) and a Steam Turbine (ST) are used in combination to produce more electrical energy from the same fuel than that would be possible from a single cycle power plant.
The gas turbine compresses air and mixes it with a fuel heated to a very high temperature. The hot air-fuel mixture moves through the blades, making them spin. 

The fast-spinning gas turbine drives a generator to generate electricity. The exhaust (waste) heat escaped through the exhaust stack of the gas turbine is utilized by a Heat Recovery Steam Generator (HSRG) system to produce steam that spins a steam turbine. This steam turbine drives a generator to produce additional electricity. CCCP is assumed to produce 50% more energy than a single power plant.

**Electrical Energy Output Prediction**

In this project, we'll see how to use an ANN Regression model to predict the electrical energy output of a Combined Cycle Power Plant. The objective is to create a data model that predicts the net hourly electrical energy output (EP) of the plant using available hourly average ambient variables.

**Library used** - Tensorflow, Scikit-learn, Keras, Numpy, Pandas

**Steps involved**

- Importing the dataset

- Splitting the dataset into the training set and test set

- Initializing the ANN

- Adding the input layer and the first hidden layer

- Adding the output layer

- Compiling the ANN

- Training the ANN model on the training set

- Predicting the results of the test set
