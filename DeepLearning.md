# Deep Learning

# Table of Contents
- [Neural Networks](#data-structures)
  - [architecture](#Architecture)
  - [activation functions](#linked-list)
  - [forward propagation](#forward-propagation)
  - [loss function](#loss-function)
  - [gradient descent](#gradient-descent)
  - [back propagation](#back-propagation)

- [Improving Neural Networks](#improving-neural-networks)
  - [Train/Dev/Test Sets](#train-dev-test-sets)
  - [Bias/Variance](#bias-variance)
  - [Basic Recipe for Machine Learning](#basic-recipe-for-machine-learning)
  - [Regularization](#regularization)
    - [Why Regularization Reduces Overfitting?](#why-regularization-reduces-overfitting)
    - [Dropout Regularization](#dropout-regularization)
    - [Understanding Dropout](#understanding-dropout)
    - [Other Regularization Methods](#other-regularization-methods)
  - [Normalizing Inputs](#normalizing-inputs)
  - [Vanishing/Exploding Gradients](#vanishing-exploding-gradients)
  - [Weight Initialization in Deep Network](#weight-initialization-in-deep-network)
  - [Numerical Approximation of Gradients](#numerical-approximation-of-gradients)
    - [Gradient Checking](#gradient-checking)
    - [Mini Batch Gradient Descent](#mini-batch-gradient-descent)
    - [Exponentially Weighted Averages](#exponentially-weighted-averages)
    - [Gradient Descent with Momentum](#gradient-descent-with-momentum)
    - [RMS Prop](#rms-prop)
    - [Adam Optimization Algorithm](#adam-optimization-algorithm)
    - [Learning Rate Decay](#learning-rate-decay)
  - [Tuning Process](#tuning-process)
  - [Using an Appropriate Scale](#using-an-appropriate-scale)
 
- [Introduction to CNNs](#introduction-to-cnns)
  - [What are Convolutional Neural Networks](#what-are-convolutional-neural-networks)
  - [Why CNNs are Important](#why-cnns-are-important)
  - [Basic CNN Architecture](#basic-cnn-architecture)
  - [Convolutional Layers](#convolutional-layers)
  - [Convolution Operation](#convolution-operation)
  - [Padding and Stride](#padding-and-stride)
  - [Filters and Feature Maps](#filters-and-feature-maps)
  - [Pooling Layers](#pooling-layers)
  - [Max Pooling](#max-pooling)
  - [Average Pooling](#average-pooling)
  - [CNN Architectures](#cnn-architectures)
    - [LeNet](#lenet)
    - [AlexNet](#alexnet)
    - [VGGNet](#vggnet)
    - [ResNet](#resnet)
  - [Transfer Learning with CNNs](#transfer-learning-with-cnns)
  - [Using Pretrained Models](#using-pretrained-models)
  - [Fine-tuning](#fine-tuning)
  - [Applications of CNNs](#applications-of-cnns)
  - [Image Classification](#image-classification)
  - [Object Detection](#object-detection)
  - [Semantic Segmentation](#semantic-segmentation)
  - [Challenges and Future Directions](#challenges-and-future-directions)
    - [Overfitting](#overfitting)
    - [Data Augmentation](#data-augmentation)
    - [Adversarial Attacks](#adversarial-attacks)

- [Introduction to RNNs](#introduction-to-rnns)
  - [What are Recurrent Neural Networks](#what-are-recurrent-neural-networks)
  - [Why RNNs are Useful](#why-rnns-are-useful)
  - [Basic RNN Architecture](#basic-rnn-architecture)
  - [Vanishing and Exploding Gradients](#vanishing-and-exploding-gradients)
  - [Gradient Problems in RNNs](#gradient-problems-in-rnns)
  - [LSTM and GRU](#lstm-and-gru)
  - [Applications of RNNs](#applications-of-rnns)
    - [Sequence to Sequence Tasks](#sequence-to-sequence-tasks)
    - [Language Modeling](#language-modeling)
    - [Machine Translation](#machine-translation)
    - [Image Captioning](#image-captioning)
  - [Bidirectional RNNs](#bidirectional-rnns)
  - [Forward and Backward RNNs](#forward-and-backward-rnns)
  - [Challenges and Future Directions](#challenges-and-future-directions)
  - [Long-Term Dependencies](#long-term-dependencies)
  - [Attention Mechanisms](#attention-mechanisms)
  - [Transformers](#Transformers)

  
### Neural Networks
Introduction to Neural Networks
What are Neural Networks?
Why Neural Networks are Important
Basic Neural Network Architecture
Activation Functions
Forward Propagation
Loss Function
Gradient Descent
Back Propagation
Improving Neural Networks
Train/Dev/Test Sets
Bias/Variance
Basic Recipe for Machine Learning
Regularization
