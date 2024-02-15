# Sentiment-classification-with-transformers

## Objective:
Fine tuning BERT to classify sentiment of given text into POSITIVE or NEGATIVE.

## Dataset used:
Link to the [dataset](https://www.kaggle.com/amitkumardas/sentiment-train).

## Framework used:
Pytorch

## Method of fine-tuning
- Froze the pre-trained BERT model's architecture. 
- Added new layers to the BERT model
- Considered the class weights while deifing the loss function, stratified data while splitting into train, test and validation to handle the imbalance in the dataset.
- Used BERT tokenizer to process texts before fine-tuning.
