# Deep Learning with TensorFlow, Keras, and PyTorch

This repository is home to the code that accompanies [Jon Krohn's](www.jonkrohn.com) *Deep Learning with TensorFlow, Keras, and PyTorch* series of video tutorials. 

There are three sets of video tutorials in the series: 

1. The eponymous [Deep Learning with TensorFlow, Keras, and PyTorch](https://learning.oreilly.com/videos/deep-learning-with/9780136617617) (released in Feb 2020)
2. [Deep Learning for Natural Language Processing, 2nd Ed.](https://learning.oreilly.com/videos/deep-learning-for/9780136620013) (Feb 2020)
3. [Machine Vision, GANs, and Deep Reinforcement Learning](https://learning.oreilly.com/videos/machine-vision-gans/9780136620181) (Mar 2020)

The above order is the recommended sequence in which to undertake these tutorials. That said, the first in the series provides a strong foundation for either of the other two. 

Taken all together, the series -- over 18 total hours of instruction and hands-on demos -- parallels the entirety of the content in the book [Deep Learning Illustrated](https://www.deeplearningillustrated.com/), plus it includes some extra content such as: 

* Detailed interactive examples involving training and testing deep learning models in PyTorch
* How to generate novel sequences of natural language in the style of your training data
* High-level discussion of transformer-based natural-language-processing models like BERT, ELMo, and GPT-2 
* Detailed interactive examples of training advanced machine vision models (image segmentation, object detection)

## Installation

Installation instructions for running the code in this repository can be found in the [installation directory](https://github.com/jonkrohn/DLTFpT/tree/master/installation).

## Notebooks

There are dozens of meticulously crafted Jupyter notebooks of code associated with these videos. All of them can be found in [this directory](https://github.com/jonkrohn/DLTFpT/tree/master/notebooks). 

Below is a breakdown of the lessons covered across the videos, including their duration and associated notebooks.

#### Deep Learning with TensorFlow, Keras, and PyTorch 

* Seven hours and 13 minutes total runtime
* Lesson 1: Introduction to Deep Learning and Artificial Intelligence (1 hour, 47 min)
	* [Shallow Net in TensorFlow](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/shallow_net_in_tensorflow.ipynb)
* Lesson 2: How Deep Learning Works (2 hours, 16 min)
	* [Sigmoid Function](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/sigmoid_function.ipynb)
	* [Softmax Demo](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/softmax_demo.ipynb)
	* [Quadratic Cost](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/quadratic_cost.ipynb)
	* [Cross-Entropy Cost](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/cross_entropy_cost.ipynb)
	* [Intermediate Net in TensorFlow](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/intermediate_net_in_tensorflow.ipynb)
* Lesson 3: High-Performance Deep Learning Networks (1 hour, 16 min)
	* [Weight Initialization](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/weight_initialization.ipynb)
	* [Deep Net in TensorFlow](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/deep_net_in_tensorflow.ipynb)
* Lesson 4: Convolutional Neural Networks (47 min)
	* [LeNet in TensorFlow](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/lenet_in_tensorflow.ipynb)
* Lesson 5: Moving Forward with Your Own Deep Learning Projects (1 hour, 4 min)
	* [Shallow Net in PyTorch](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/shallow_net_in_pytorch.ipynb)
	* [Deep Net in PyTorch](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/deep_net_in_pytorch.ipynb)
	* [LeNet in TensorFlow for Fashion MNIST](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/lenet_in_tensorflow_for_fashion_MNIST.ipynb)

#### Deep Learning for Natural Language Processing

* Five hours total runtime
* Lesson 1: The Power and Elegance of Deep Learning for NLP (46 min)
* Lesson 2: Word Vectors (1 hour, 7 min)
	* [Creating Word Vectors with word2vec](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/creating_word_vectors_with_word2vec.ipynb)
* Lesson 3: Modeling Natural Language Data (1 hour, 43 min)
	* [Natural Language Preprocessing](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/natural_language_preprocessing.ipynb)
	* [Document Classification with a Dense Neural Net](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/dense_sentiment_classifier.ipynb)
	* [Classification with a Convolutional Neural Net](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/convolutional_sentiment_classifier.ipynb)
* Lesson 4: Recurrent Neural Networks (25 min)
	* [RNN](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/rnn_sentiment_classifier.ipynb)
	* [LSTM](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/lstm_sentiment_classifier.ipynb)
	* [GRU](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/gru_sentiment_classifier.ipynb)
* Lesson 5: Advanced Models (54 min)
	* [Bidirectional LSTM](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/bidirectional_lstm_sentiment_classifier.ipynb)
	* [Stacked Bi-LSTM](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/stacked_bi_lstm_sentiment_classifier.ipynb)
	* [Convolutional-LSTM Stack](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/conv_lstm_stack_sentiment_classifier.ipynb)
	* [Sequence Generation](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/sequence_generation.ipynb)
	* [Keras Functional API](https://github.com/jonkrohn/DLTFpT/blob/master/notebooks/multi_convnet_sentiment_classifier.ipynb)
