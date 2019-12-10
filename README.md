Abhinav Sagar who is Machine Learning Researcher at VIT. I took reference from his article on Medium.
Link:-"https://towardsdatascience.com/cryptocurrency-price-prediction-using-deep-learning-70cfca50dd3a"
Digital currencies that use complex computer algorithms and encryption to generate more currency and to protect transactions .
Crypto currencies is that they utilize a network of thousands of computers that forward people’s transactions to what’s known as a block chain (essentially a big record of transactions kept secure by the network of computers). Once a transaction is in the block chain, it’s never coming out again; this protects crypto currencies from double-spends.
1.	We are building a three-layer recurrent network with 20% dropout at each layer to reduce over fitting in the training. The type of RNN we’re going to build is called a bidirectional LSTM network.
2.	Bi-directional LSTM RNN is a relatively complex model to make in TensorFlow but with Keras we can do this in just about 1 lines. The Dense fully connected layer comes at the end then our activation function and then our loss function at the very end which is going to be Adam.
 
3.	The loss function is going to be mean squared error. The linear activation function in this model is going to determine the output of each neuron in the model.
4.	Training the Model:
We’re gonna train it with a batch size of 64 for 100 epochs. we are going to minimize the loss of its training data using the mean squared error. For fitting The model use model.fit and we give it all of those variables that we computed At the very beginning the training data.


