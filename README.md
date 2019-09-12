# Toxic-comment-classification
Text classification on the toxic comment dataset from Kaggle


In this project we build a multi-headed model that’s capable of detecting different types of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models.

### Dataset - kaggle

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
- ***toxic-classification-cnn.ipynb:*** Ipython notebook to classify text using CNN and pretrained embeddings.


### Performance graphs

1. Performance graph for training a model with CNN layers and pre-trained embeddings of 100 dimenstions.
  
   * ![Accuracy](https://github.com/agoel41/toxic-comment-classification/blob/master/static/acc_toxic_cnn.png)
	   ![Loss](https://github.com/agoel41/toxic-comment-classification/blob/master/static/loss_toxic_cnn.png)
