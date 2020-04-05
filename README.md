# Predicting E-commerce Customer Behavior using Recurrent Neural Networks & Data Augmentation Techniques
A recommender system for predicting online consumer behaviour based on RNN.

With this article, we seek to describe how we’re able to improve today’s recommendation engines by applying a novel model-based approach using recurrent neural networks, a sub-class of artificial neural networks. The research was conducted using consumer behavioral session data from two large e-commerce webstores located in Europe, RSC and AVM — Find description below.
We end up proving that recommendations can be improved in terms of accuracy, consequently improving competitive advantages significantly by capturing the interests of (new) customers. Results were compared to a baseline model built using the k-nearest neighbor algorithm, a common method for generating recommendations.

Data were modeled using deep learning techniques, in particular, recurrent neural networks specializing in sequential data; customer sessions. Recurrent neural networks currently demonstrate state-of-the-art results in natural language processing tasks, such as predicting words in sentences. We argue that sequences of words (sentences) share similar properties to sequences of customer clicks (sessions). By applying techniques known from natural language processing, this research treats customer sessions as human sentences, in order to predict the next customer move.

Two basic models were found, each with different combinations of hyperparameter values depending on the source of data. Finally, we found that recurrent neural networks outperform the baseline model by 41.3% (RSC) to 161.9% (AVM), increasing accuracies from 50.65% and 20.18% to 71.55% and 52.85%, respectively. The increase in accuracy of consumer behavioral predictions should consequently improve customer loyalty and thereby revenue, assuming increased quality in recommendations leads to better foundation for decision making while shopping 🤘

## Thesis
### Blog version

A shorter version of the thesis is available as [a blog](https://blog.nirida.ai/predicting-e-commerce-consumer-behavior-using-recurrent-neural-networks-36e37f1aed22) post.

### Full version
The [full version](https://github.com/nrishoj/recsys-on-rnn/blob/master/recsys-on-rnn.pdf) is found in this repository.

### Code
The main model can be found as [a notebook](https://github.com/nrishoj/recsys-on-rnn/blob/master/notebook-model.ipynb) in this repository.

Models were implemented using TensorFlow 1.7.

## Team
- [Mathias Smedemark Kristiansen](https://www.linkedin.com/in/mathias-smedemark/)
- [Nick Rishøj Danmand](https://www.linkedin.com/in/nick-danmand/)
