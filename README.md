
# Toxic-comment-classification
Text classification on the toxic comment dataset from Kaggle

In this project we build a multi-headed model that’s capable of detecting different types of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models.

## Table of Contents
<!-- ⛔️ MD-MAGIC-EXAMPLE:START (TOC:collapse=true&collapseText=Click to expand) -->
<details>
<summary>Click to expand</summary>

- [Dataset - Kaggle](#dataset-kaggle)
- [Project Structure](#project-structure)
- [Performance graphs](#performance-graphs)

</details>
<!-- ⛔️ MD-MAGIC-EXAMPLE:END -->

### Dataset-kaggle

- https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data
- ```kaggle competitions download -c jigsaw-toxic-comment-classification-challenge```

The dataset consists of a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate


### Project Structure

- ***static:*** This folder contains the static content such as images (accuracy and validation graphs) etc.
- ***toxic-classification-cnn.ipynb:*** Ipython notebook to classify toxic text using CNN and pre-trained embeddings.
- ***toxic-classification-lstm.ipynb:*** Ipython notebook to classify toxic text using an LSTM layer and pre-trained embeddings.


### Performance graphs

1. Performance graph for training a model with CNN layers and pre-trained embeddings of 100 dimenstions. 
   - toxic-classification-cnn.ipynb
   - The performance of toxic classification dataset on CNN model is decent.
   - This CNN model performed better on a GPU vs CPU.

![Accuracy](https://github.com/agoel41/toxic-comment-classification/blob/master/static/acc_toxic_cnn.png) ![Loss](https://github.com/agoel41/toxic-comment-classification/blob/master/static/loss_toxic_cnn.png)

2. Performance graph for training a model with an LSTM layer and pre-trained embeddings of 100 dimenstions.
   - toxic-classification-lstm.ipynb
   - The performance of LSTM model is better than a CNN model
   - This LSTML model performed better on a GPU vs CPU.
   
![Accuracy](https://github.com/agoel41/toxic-comment-classification/blob/master/static/acc_toxic_lstm.png) ![Loss](https://github.com/agoel41/toxic-comment-classification/blob/master/static/loss_toxic_lstm.png)

