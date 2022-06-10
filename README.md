# Optical-character-recognition
Using the keras library, i created a CNN with 2 hidden layers and width of 128 neurons. I used the 'Dropout' regularization  and used 'adam' as my optimizer. this model differentiated image samples into cats and dogs with an accuracy of 90 percent.

Convolutional Neural Network: 
The data gets into the CNN through the input layer and passes through various hidden layers before getting into the output layer.
  - the sequential model in keras lets you build a network by specifying what dimentions you want at each layer.
  
The output of the network is compared to the actual labels in terms of loss or error. 

the partial derivatives of this loss with respect to the trainable weights are calculated, and the weights are updated through one of the various using back propagation.

CNN TEMPLATE: 
1. layer function.
    a. Fully Connnected.
    b. Convolutional Layers.
    c. Tranposed Convolutional (DeConvolutional) Layer: 
2. Pooling: 
    a. Max/Average Pooling.
    b. UnPooling.
3. Normalization
    a. Loal Response Normalization LRN.
    b. Batch Normalization.

4. Activation: introduces nonlinearity to CNN can efficiently map non-linear complex mapping.
    a. non-parametric/STatic functions: Linear ReLU
    b. Parametric functions: ELU, tanh, sigmoid, Leaky, ReLU
    c. Bounded functions: tanh, sigmoid
    
5. Loss function: Quatifies how far off the CNN predition is from the actual labels.
    a. Regression Loss Functions: MAE, MSE, Huber loss
    b. Classification Loss Functions: Cross entropy, Hinge loss
