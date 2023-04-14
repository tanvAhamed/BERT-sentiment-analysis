# Sentiment Analysis using BERT

This project aims to demonstrate how to analyze a dataset for sentiment analysis using PyTorch BERT model. Additonally, we will learn how to fine-tune the model, adjust the architecture for multi-class classification, and design a train and evaluate loop to monitor model performance as it trains, including saving and loading models. By the end of this project, we will be able to finetune the BERT model in PyTorch on any sequence-based text problem, such as sentiment analysis.

## Objectives

There are three learning objectives:

1. Understand Sentiment Analysis and approach the problem from a neural network perspective.
2. Load in pretrained BERT with custom output layer.
3. Train and evaluate finetuned BERT architecture on Sentiment Analysis.


## Tasks

To better understand the project, here are the tasks that we will perform:

1. Understand some basic theory behind BERT and the sentiment analysis problem.
2. Explore dataset distribution and perform some basic preprocessing.
3. Split the dataset into training and validation using a stratified approach.
4. Load the pretrained tokenizer to encode the text data into numerical values (tensors).
5. Load the pretrained BERT with a custom final layer.
6. Create dataloaders to facilitate batch processing.
7. Choose an optimizer and a scheduler to control the training of the model.
8. Design performance metrics for the problem.
9. Create a training loop to control PyTorch finetuning of BERT using CPU or GPU acceleration.
10. Load in a pre-saved finetuned BERT model and evaluate its performance, and some final thoughts.

## Conclusion

The project enables use to know how we can fine-tune a BERT model in PyTorch for sentiment analysis. By the end of this project, we will learn how to preprocess the dataset, load pretrained models, create dataloaders, design performance metrics, and train and evaluate the model. Additionally, we will learn how to save and load the trained model.