[//]: # (Image References)

[image1]: ./images/pipeline.png "ASR Pipeline"
[image2]: ./images/select_kernel.png "select aind-vui kernel"

## Introduction 

This project belongs to Udacity - [Natural Language Processing Nanodegree](https://www.udacity.com/course/natural-language-processing-nanodegree--nd892)
In this project, student have to implement various models in automatically recognizing speech.

## Project Overview

In this notebook, you will build a deep neural network that functions as part of an end-to-end automatic speech recognition (ASR) pipeline!  

![ASR Pipeline][image1]

We begin by investigating the [LibriSpeech dataset](http://www.openslr.org/12/) that will be used to train and evaluate your models. Your algorithm will first convert any raw audio to feature representations that are commonly used for ASR. You will then move on to building neural networks that can map these audio features to transcribed text. After learning about the basic types of layers that are often used for deep learning-based approaches to ASR, you will engage in your own investigations by creating and testing your own state-of-the-art models. Throughout the notebook, we provide recommended research papers for additional reading and links to GitHub repositories with interesting implementations.

## Todo
- [x] Prepare dataset (Acoustic Features for Speech Recognition)
  - [x] Spectrograms
  - [x] MFCCs
- [x] Model 0: Simple RNN (Keras)
- [x] Model 1: RNN + TimeDistributed Dense (Keras)
- [x] Model 2: Deeper RNN + TimeDistributed Dense (Keras)
- [x] Model 3: CNN + RNN + TimeDistributed Dense (Keras)
- [x] Model 4: BiRNN + TimeDistributed Dense (Keras)
## Extends
- [x] Pytorch Dataset, DataLoader
- [x] Model 5: Encoder-Decoder + CTC Loss
- [ ] CTC Decode
- [ ] Compare Models 