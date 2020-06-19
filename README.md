I have implement one-vs-all logistic regression and neural
networks to recognize hand-written digits.

I have  use logistic regression and neural networks to
recognize handwritten digits (from 0 to 9).

Automated handwritten digit recognition is widely used today - from recognizing zip codes (postal codes)
on mail envelopes to recognizing amounts written on bank checks.

Here are given a data set in ex3data1.mat that contains 5000 training exam-
ples of handwritten digits.

There are 5000 training examples in ex3data1.mat, where each training
example is a 20 pixel by 20 pixel grayscale image of the digit.

Each pixel is represented by a floating point number indicating the grayscale intensity at
that location. The 20 by 20 grid of pixels is \unrolled" into a 400-dimensional
vector.

Each of these training examples becomes a single row in our data
matrix X. This gives us a 5000 by 400 matrix X where every row is a training
example for a handwritten digit image.

I have used multiple one-vs-all logistic regression models to build a
multi-class classifiers. Since there are 10 classes, you will need to train 10
separate logistic regression classifiers.

To make this training efficient, it is important to ensure that your code is well vectorized. In this section, you
will implement a vectorized version of logistic regression that does not employ
any for loops.

Debugging Tip: Vectorizing code can sometimes be tricky. One com-
mon strategy for debugging is to print out the sizes of the matrices you
are working with using the size function. For example, given a data ma-
trix X of size 100X20 (100 examples, 20 features) and theta, a vector with
dimensions 20X1, you can observe that X*theta is a valid multiplication oper-
ation, while theta*X is not. 

Furthermore, if you have a non-vectorized version of your code, you can compare the output of your vectorized code and
non-vectorized code to make sure that they produce the same outputs.

Our neural network  has 3 layers { an input layer, a
hidden layer and an output layer}. Recall that our inputs are pixel values of
digit images.  

Since the images are of size 20X20, this gives us 400 input layer
units (excluding the extra bias unit which always outputs +1). As before,
the training data will be loaded into the variables X and y.
 
