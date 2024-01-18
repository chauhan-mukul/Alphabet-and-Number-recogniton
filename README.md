
# Number and Alphabet Recognition in Real Time(handwritten)

It is computer vision based model that is able to reconize between
different numbers and Alphabets in real time.

This model uses CNN based architecture to learn through past experiences to predict the correct output.



## What is CNN
CNN stands for Convolution Neural Networks.

CNN is much different from normal ANN's. In CNN we use different filters and convolute it over the image for feature extraciton from the image. The extracted features are stored in the form of a
vector R(n,m) space. The vector R(n,m) space is flattened to R(n*m,1) and passed to our ANN.


## Why use CNN
1.CNN decreases the number of trainable parmaters.

2.CNN allows translational invariance.

3.CNN has parameter sharing and because of sparsity of conneciton.


## Why use CNN
1.CNN decreases the number of trainable parmaters.

2.CNN allows translational invariance.

3.CNN has parameter sharing and because of sparsity of conneciton.

# How to create a realtime based Writing pad

We use open cv library with its features of eventlistners for this purpose. This is what it looks like

![write pad](https://github.com/chauhan-mukul/Alphabet-and-Number-recogniton/assets/143337342/3ad99f28-5d58-40a5-9084-73dcce5387d6)

The code for this is provided itself at the last of the ipynb file

