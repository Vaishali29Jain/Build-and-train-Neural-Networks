# Build-and-train-Neural-Networks

# Data preprocessing 
1-Preprocessing is done by first removing the wrong values from the dataset. For example, if 
there was string in any column then that row was removed as values in the features should be 
numerical. 
2-For the numerical variables to have zero mean and unit variance, StandardScaler from 
sklearn was used. 
3-Extracting the features and target variable. The target variable is column with binary values, 
that tells about result is Positive or Negative. 
4- Data was split into test and train using train test split from sklearn.

# Build Neural network 
 The architecture structure of this neural network can be summarized as follows:
• Neural network has three layers: an input layer with 7 input neurons, a hidden layer 
with 64 neurons, and an output layer with a single neuron.
• Input layer with 7 neurons
• Fully connected linear layer to hidden layer with 64 neurons
• ReLU activation function
• Fully connected linear layer to output layer with a single neuron.
• Sigmoid activation function
• Dropout layer with specified dropout value.

# Optimized the neural network

Ran model for various Dropout values, Optimizer, Activation Function and Initializer to optimise the model.
The accuracy of model increased from 75% to 76.3% and training time decreased from 3.422 sec to 2.501 sec.
Earlystopping method used to increase accuracy to 77% from 76.3% and k-fold method increased accuracy to 78.9% from 76.3%.


