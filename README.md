# Sentiment Analysis Project
 
Problem Statement:  

Using transformers for sentiment analysis using data such as comments or reviews.   We will use these databases to analyze whether a statement or sentence has a positive, negative, or neutral connotation. Our AI of choice will be Roberta.  

 

Planned Transformers and Datasets: 

The transformer we plan to use is called RoBERTa transformer. This transformer builds on BERT and modifies key hyperparameters, removing the next sentence pretraining objective and training with much larger rates. 

For our dataset, we will be using  

HuggingFaceGECLM/REDDIT_comments · Datasets at Hugging Face 

breadlicker45/youtube-comments-v2 · Datasets at Hugging Face 

amazon_us_reviews · Datasets at Hugging Face 

 

Proposed Process: 

Our process will be to fine tune a Roberta model for the sentiment analysis of YouTube, Facebook, and reddit post comments. We will start by importing Python libraries and preparing the environment which will either be on google co lab or Aarya’s laptop (his laptop has good GPU). After preparing the environment, we will import and pre-process the data from hugging face. After importing the data, we will prepare the dataset and data loader. Creating the Neural network for fine tuning is next and then finally we will fine tune the Model. After fine tuning, we test the model to see if it works and validate the model performance. 
