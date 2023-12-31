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
 
- [MLOPS](#MLOPS)
-   [Distributed Training](#Distributed-Training)
  - [Gradient accumulation](#Gradient-accumulation)
  - [Data Parallelism](#Data-Parallelism)
  - [Model Parallelism](#Model-Parallelism)

  
### Neural Networks
- #### Introduction
- #### Architecture
- #### Activation Functions
- #### Forward Propagation
- #### Loss Function
- #### Gradient Descent
- #### Back Propagation

### Improving Neural Networks
- #### Train/Dev/Test Sets
- #### Bias/Variance
- #### Basic Recipe for Machine Learning
- #### Regularization
  - #### Why Regularization Reduces Overfitting?
  - #### Dropout Regularization
  - #### Understanding Dropout
  - #### Other Regularization Methods
- #### Normalizing Inputs
- #### Vanishing/Exploding Gradients
- #### Weight Initialization in Deep Network
- #### Numerical Approximation of Gradients
  - #### Gradient Checking
  - #### Mini Batch Gradient Descent
  - #### Exponentially Weighted Averages
  - #### Gradient Descent with Momentum
  - #### RMS Prop
  - #### Adam Optimization Algorithm
  - #### Learning Rate Decay
- #### Tuning Process
- #### Using an Appropriate Scale

### Convolutional Neural Networks (CNNs)
- #### Introduction to CNNs
  - #### What are Convolutional Neural Networks
  - #### Why CNNs are Important
  - #### Basic CNN Architecture
- #### Convolutional Layers
  - #### Convolution Operation
  - #### Padding and Stride
  - #### Filters and Feature Maps
- #### Pooling Layers
  - #### Max Pooling
  - #### Average Pooling
- #### CNN Architectures
  - #### LeNet
  - #### AlexNet
  - #### VGGNet
  - #### ResNet
- #### Transfer Learning with CNNs
  - #### Using Pretrained Models
  - #### Fine-tuning
- #### Applications of CNNs
  - #### Image Classification
  - #### Object Detection
  - #### Semantic Segmentation
- #### Challenges and Future Directions
  - #### Overfitting
  - #### Data Augmentation
  - #### Adversarial Attacks

### Recurrent Neural Networks (RNNs)
- #### Introduction to RNNs
  - #### What are Recurrent Neural Networks
  - #### Why RNNs are Useful
  - #### Basic RNN Architecture
- #### Vanishing and Exploding Gradients
  - #### Gradient Problems in RNNs
  - #### LSTM and GRU
- #### Applications of RNNs
  - #### Sequence to Sequence Tasks
  - #### Language Modeling
  - #### Machine Translation
  - #### Image Captioning
- #### Bidirectional RNNs
  - #### Forward and Backward RNNs
- #### Challenges and Future Directions
  - #### Long-Term Dependencies
  - #### Attention Mechanisms
  - #### Transformers
 
- ### MLOPS
- #### Distributed Training
  - #### Gradient accumulation
  - 
- #### Data Parallelism
  - ##### Communication primitives
    - #### Broadcast operator
      First we send from one node/gpu to other. Then both the first and second gpu sends to others and continue same   
      Initials 8 gpus 1-2-3-4-5-6-7-8
      step 1: 1-2 share parameter  5 seconds  
      step 2: 1-3 and 2-4 share parameter 5 seconds  
      step 3: 1-5, 2-6, 3-7, 4-8  5 seconds
      Without collective communication if we assume 5 seconds to send data, it takes total 40 secs 
      Now it is 5+5+5 = 15 secs  
      
      
      
      
    - #### Reduce operator
    - #### All-Reduce operator
- #### Model Parallelism
- #### Pytorch Data parallelism
  - #### Bucketing
  - #### Computaion-communication overlap during backpropagation
