# Image-Captioning
This repository contains the code implementation for Captioning an Image using CNN+LSTM and CNN+Transformer architectures. The goal of the project is to generate captions for images using both architectures and compare their results.
# Dataset
Both architectures are trained on Flickr8k Dataset and then also on the Flickr30k Dataset.
# CNN
The CNN architecture used was ResNet50. ResNet50 is a variant of ResNet model which has 48 Convolution layers along with 1 MaxPool and 1 Average Pool layer.
# Approach
The approach used was encoder-decoder approach in which the role of an encoder is to extract the semantic information from the image and is typically represented by Convolutional Neural Networks (CNN). The role of a decoder is to translate the encoded image features into natural language. We have performed sensitivity analysis of several hyperparameters for both LSTM-based decoder and Transformer-based decoders.
