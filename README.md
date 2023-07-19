# Sarcasm-Detection

This project is a deep learning model that can be used to detect sarcasm in news headlines. The model is trained on a dataset of news headlines that have been labeled as sarcastic or non-sarcastic. The model can then be used to predict whether a new headline is sarcastic or not.

Electronic journalism powered with Social media has become one of the major sources of information consumption lately. Many media houses are using creative ways in order to tap into increasing views on posts. One of the ways is using sarcastic headlines as click baits. A model that is able to predict whether a piece of headline is sarcastic or not can be useful for media houses in order to analyse their quarterly earnings by strategy. Also, from a reader's perspective, search engines can utilise this information of sarcasm and depending on the reader’s preference, recommend similar articles to them.
The goal is to build a model to detect whether a sentence is sarcastic or not, using Bidirectional LSTMs.

## Dataset 

News Headlines dataset for Sarcasm Detection The dataset is collected from two news websites, theonion.com and huffingtonpost.com . Past studies in Sarcasm Detection mostly make use of Twitter datasets collected using hashtag based supervision but such datasets are noisy in terms of labels and language. Furthermore, many tweets are replies to other tweets and detecting sarcasm in these requires the availability of contextual tweets. This new dataset has the following advantages over the existing Twitter datasets:
Since news headlines are written by professionals in a formal manner, there are no spelling mistakes and informal usage. This reduces the sparsity and also increases the chance of finding pre-trained embeddings.

Furthermore, since the sole purpose of TheOnion is to publish sarcastic news, we get high-quality labels with much less noise as compared to Twitter datasets. Unlike tweets that reply to other tweets, the news headlines obtained are self-contained. This would help us in teasing apart the real sarcastic elements

Content Each record consists of three attributes:

is_sarcastic: 1 if the record is sarcastic otherwise 0
headline: the headline of the news article
article_link: link to the original news article. Useful in collecting supplementary data

The project is written in Python and uses the following libraries:

TensorFlow
Keras
NumPy
Pandas
To install the requirements, you can run the following command:

Code snippet
pip install -r requirements.txt
Use code with caution. Learn more



Here are some additional details about the project:

The model is a simple convolutional neural network with two hidden layers.
The model was trained for 30 epochs.
The accuracy of the model on the test set is 81%.
