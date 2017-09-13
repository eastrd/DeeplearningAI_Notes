# What is a neural network?
#### Housing Price Prediction (Linear Regression):
- can be a really simple neural network: <br> <b> Size -> O -> Price </b>
- A large neural network is formed by stacking these neurons.
- It can also be: <br>
<b> X -> [O , O , ...] -> O -> Y  </b>
, where X is <i> [size, #bedrooms, zipcode, wealth] </i> and Y is the <i> price. </i>

# Supervised Learning with Neural Networks
- Have an input X, and want to learn some function that maps to some output Y.
- E.g. <br> <b> Home Features -> Price : (Real Estate) : Vanilla NN
<br> <br>
Ad, user info -> Click on ad? (0/1) : (Online Advertising) : Vanilla NN
<br> <br>
Image -> Object (1..10000) : (Photo tagging) : CNN
<br> <br>
Audio -> Text transcript : (Speech Recognition) : RNN
<br> <br>
English -> Chinese : (Machine translation) : RNN
<br> <br>
Image, Radar info -> Position of other cars : (Autonomous Driving) : Custom Hybrid <br> <br> </b>
- Different Neural Network models are used in different applications.

#### Structured Data:
- Databases of Data, each of the features has a very well defined meaning

#### Unstructured Data:
- E.g. (sound waves in) Audio / (pixels in) Image / Text
- People are good at interpreting unstructured data.

# Why is Deep Learning taking off?
#### Comparison:
- Traditional learning algorithm has a performance v. Data Amount(m) graph of the shape of Logarithm. (Rapidly approaches to a flat gradient)
- We are having more and more data everyday.
- Neural network has a performance v. Data Amount(m) graph of a much steeper gradient.
- However, small amount of data doesn't perform well in Neural Network. This will depend more on skills and experience.

#### Main Drivers:
- Data
- Computation: Better CPU and GPU
- Algorithms: Make NN run much faster, e.g. <b> Switching from sigmoid function to a relu function, which avoid the slow learning problem in sigmoid function when the gradient approaches zero </b> .
- Training a neural network is <b> iterative </b> :
<br> <i> Idea -> Code -> Experiment -> Idea -> ... </i>
