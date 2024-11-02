# IMDB Movie Review Sentiment Analysis with TensorFlow and TensorFlow Hub
This repository includes a Jupyter Notebook for classifying IMDB movie reviews as either positive or negative using TensorFlow, TensorFlow Hub, and a pretrained text embedding model. The project demonstrates a straightforward text classification model that leverages pretrained embeddings to enhance performance and reduce training time.

**Project Description**

The notebook applies a binary classification model to the IMDB dataset to predict the sentiment (positive or negative) of movie reviews. Using TensorFlow Hub’s nnlm-en-dim50 pretrained embedding, the model converts text reviews into embeddings and trains a dense neural network classifier.

**Dataset Information**

The IMDB dataset contains 50,000 labeled movie reviews split as follows:

1.Training Set: 25,000 reviews

2.Testing Set: 25,000 reviews

**Model Overview**

1.Pretrained Embedding Layer: Utilizes nnlm-en-dim50 embedding from TensorFlow Hub.

2.Dense Layer: A dense layer with 16 units using ReLU activation.

3.Output Layer: A dense layer with 1 unit and sigmoid activation, suited for binary classification.
