# Keras-MNIST
Keras Fashion MNIST dataset
 
**Neural Network Fashion MNIST prediction with Tensorflow and Keras**
 
 This is a multi class classification problem
 
 *Data source:* kaggle.com
 
 \
 Number of Classes: 10\
 Classes: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot.

\
Train set shape: (60000, 28, 28)\
Test set shape: (10000, 28, 28)

\
Model: sequential\
Activation Function (hidden layers): ReLU\
Activation Function (output layer): Softmax\
Optimizer= Adam optimizer\
Metrics= Accuracy\
Loss= Sparse Categorical Crossentropy\
Number of Epochs: 30

\
**Result:**

Validation set:\
Loss: 0.4509\
Accuracy: 0.8976

Test set:\
Loss: 0.4766\
Accuracy: 0.8899
