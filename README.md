# My_Neural_Network
In this project, I have build a <strong>Deep Neural Network</strong>, with as many layers as we want!

- In this project, I have implemented all the functions required to build a deep neural network.
- I have used these functions to build a deep neural network for image classification (cat/non-cat)

**Note:**
- I have implemented an easy-to-use neural network class.
- I have used non-linear units like ReLU for the hidden layers to improve the model and Sigmoid function for outer layer.
- I have build a deeper neural network (with more than 1 hidden layer). We can mention the number of hidden layers and their corresponding number of nodes we want in our neural network.


## Performance
I have compared the performance of a 2 Layer neural network vs L-layer neural network (4 Layer) to classify a cat and non-cat image on the test data

- 2 Layer had accuracy of 72%
- 4 Layer with L2 Regularization had accuracy of 80%
- 4 Layer with Dropout had accuracy of 82%

So, neural network with more than 2 layers performed better

## Notebook
- Click to access the detailed [Jupyter Notebook](https://github.com/aprasad13/My_Neural_Network/blob/master/My_Neural_Network_V6.ipynb) for code and visualizations.
- Click to access the [Training Dataset](https://github.com/aprasad13/My_Neural_Network/blob/master/train_catvnoncat.h5) and [Testing Dataset](https://github.com/aprasad13/My_Neural_Network/blob/master/test_catvnoncat.h5)

## Functionality for Performance Improvement 
- Implemented <strong>He Initialization</strong> (recommended for Relu activation) for parameter initialization so that the gradiant descents do not explode or vanish
- Implemented <strong>L2 Regularization</strong> functionality. User can mention the value of lambda (regularization parameter).
- Implemented <strong>Dropout</strong> functionality. User can mention the layer_number to implement dropout upon and the probability to nock-out.
- User can also implement both L2 Regularization and Dropout simultaneously 
