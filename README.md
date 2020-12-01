# BMDATA
Compilation of small projects during BMDATA courses:

## Multi-Classification-clothes
This work use multi-class classification to with a dataset of clothes. The objective is to predict the class of an image between 8 classes.

The approached subjects are :
* Image Processing 
* Creation and training of a classical Convolutionnal Neural Network
* Transfer Learning from pretrained VGG16 on ImageNet
* KNN to find similar images 
* PCA to visualize image clusters from their features

As a result, built models were able to predict with an accuracy of ~90%.

The dataset is available at this [link](https://drive.google.com/drive/folders/1JnsVK6Z-c_UPyqc-TSwjQcyptGW2iQ6v?usp=sharing).
The models weights and optimizer parameters are available at this [link](https://drive.google.com/file/d/1tkGm17lUiNxdpAJ7OLV_H3hPCbD8JcMw/view?usp=sharing)

## TPAutoencoder

I study autoencoders with the stl10 dataset. The objective is to predict the class of the images. The approached subjects are :
* Image Processing
* Basic Autoencoders
* Transfer Learning (from .npy files)
* Features Extraction
The autoencoder has already been trained.

## TPTimeSeries

This work was about time series. The idea was to compare the best netowrks between CNN2D, CNN1D and LSTM with an application on movement recognition. The approached subjects are :
* Time series Processing
* Application of Conv2D, Conv1D and LSTM, and comparison of their performances.
* LSTM with pad and masking sequences

## NLP_MLP_Movie classification

A Basic NN to predict the sentiment of a movie review. The subject approached are :
* Texts processing
* Creation of a dictionnary and one-hot encoding of texts
* Creation and Training of a MLP
* Visualisation of the predictions

## TPEmotion

Sentiment classification of a face. The subject approached are :
* Image processing
* Classification : MLP and CNN
* Video Capture on Colab
* Comparison between landmarks and face to predict sentiment
