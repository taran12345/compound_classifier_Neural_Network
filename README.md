### Compound_classifier (Multi-Layer perceptron)

This code helps you classify compounds either'Musk' or 'Non-Musk' using Multi-Layer perceptron.

### Multi-Layer perceptron
A multilayer perceptron (MLP) is a feedforward artificial neural network that generates a set of outputs from a set of inputs.
An MLP is characterized by several layers of input nodes connected as a directed graph between the input and output layers.
MLP uses backpropogation for training the network. MLP is a deep learning method.


### DATA
1. 166 features
2. Class 1 = Musk and 0 = NON-MUSK
<img src = "https://github.com/taran12345/compound_classifier_Neural_Network/blob/master/Dataset.png">

### Model trainning
 1. Initialize parameters / Define hyperparameters
 2. Loop for num_iterations:
     
     a. Forward propagation
     b. Compute cost function
     c. Backward propagation
     d. Update parameters (using parameters, and grads from backprop) 
 4. Use trained parameters to predict labels

### Result
<img src = "https://github.com/taran12345/compound_classifier_Neural_Network/blob/master/graphical_representation.png">

### Classification_Report
<img src = "https://github.com/taran12345/compound_classifier_Neural_Network/blob/master/Classification_report.png">

### ACCURACY : 97%
