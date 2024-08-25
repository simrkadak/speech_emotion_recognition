TensorFlow implementation of Convolutional Recurrent Neural Networks for speech emotion recognition (SER) on the IEMOCAP database.In order to address the problem of the uncertainty of frame emotional labels, we perform three pooling strategies(max-pooling, mean-pooling and attention-based weighted-pooling) to produce utterance-level features for SER. These codes have only been tested on ubuntu 16.04(x64), python2.7, cuda-8.0, cudnn-6.0 with a GTX-1080 GPU.To run these codes on your computer, you need install the following dependency:
tensorflow 1.3.0
python_speech_features
wave
cPickle
numpy
sklearn
os