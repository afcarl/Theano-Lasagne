mlp

This was my first attempt of getting to grips with Theano and Lasagne. 
My goal was to perform a classification task with a dataset large enough to necessitate a mini batch approach. 
Tutorials for Theano and Lasagne tend to use the MNIST dataset and focus on image recognition. 
The issue of loading data, splitting data into train, test and validation sets and evaluating model performance is not covered by 
these tutorials. I was interested in how to use these tools with more prosaic regression and classification problems and also how to feed 
data into functions without relying on ready made functions as found in such tutorials.

I read some tutorials and Theano and Lasagne's documentation to understand the mechanics of the problem. 
The solution I found was to use a while loop to create the mini batches and then feed these batches into the function. 
In the future I plan to look at a regression problem and then experiment with more layers, different activation functions and 
regularization techniques.
