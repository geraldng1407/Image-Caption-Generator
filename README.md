# Image Caption Generator

The objective of the project is to predict the captions for the input image. The dataset consists of 8k images and around 5 captions for each image. The features are extracted from both the image and the text captions for input. The features will be concatenated to predict the next word of the caption. CNN is used for image and LSTM is used for text. BLEU Score is used as a metric to evaluate the performance of the trained model.

## Libraries
- numpy
- matplotlib
- keras
- tensorflow
- nltk

## Neural Network
- VGG16 Network
- CNN-LSTM Network

The project uses CNN and LSTM models to extract image and text features, concatenate them, and generate captions for input images based on a dataset of 8k images with 5 captions each.

Key libraries used include Keras with a TensorFlow backend for building and training the deep learning models. NLTK is used for text data preprocessing. The CNN-LSTM model is trained end-to-end to maximize the BLEU score, a common metric for evaluating generated text. Overall, this project exemplifies deep multimodal learning for image captioning.

## Sample Output
