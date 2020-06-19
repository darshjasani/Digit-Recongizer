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
