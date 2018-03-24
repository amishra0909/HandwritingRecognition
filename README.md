HandwritingRecognition 
======================     

This project recognizes hand written Roman numerals using deep learning and neural networks.

Training data and input layer:
The training data for the network will consist of many 28x28 pixel of images of scanned handwritten digits, and so the the input layer contains 784 (28 x 28) neurons - one neuron for each pixel. The input pixels are greyscale, with a value of 0.0 representing white and value of 1.0 representing complete black, and in between values representing gradually darkening shades of grey.

Output layer:
The output layer will have 10 neurons. If the first neuron fires, i.e., has an out close to 1, then that will indicate the network thinks the digit is 0. If the second neuron fires then that will indicate that the network thinkgs the digit is a 1. And so on. A little more precisely, we number the output neurons from 0 to 9, and figure out which neuron has the highest activation value. If that neuron is, say, neuron number 6, then our network will guess the digit to be 6. And so on for other output neurons.

