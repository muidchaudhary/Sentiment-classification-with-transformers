# Sentiment-classification-with-transformers

## Objective:
Fine tuning BERT to classify sentiment of given text

## Dataset used:
Link to the [dataset](https://www.kaggle.com/amitkumardas/sentiment-train).

## Framework used:
Pytorch

## Method of fine-tuning
- Froze the pre-trained BERT model's architecture. 
- Added new layers to the BERT model
- Considered the class weights while deifing the loss function, stratified data while splitting into train, test and validation to handle the imbalance in the dataset.
- Used BERT tokenizer to process texts before fine-tuning.


## Result
-<img width="258" alt="Screenshot 2024-02-15 181320" src="https://github.com/muidchaudhary/Sentiment-classification-with-transformers/assets/149241132/ef5d50dd-279e-4dc2-a7db-f4117e25ed06">


## References:
- https://huggingface.co/docs/transformers/model_doc/bert
- https://huggingface.co/docs/transformers/index
- https://huggingface.co/docs/transformers/custom_datasets
