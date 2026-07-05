# Customer Support Ticket Classification using DistilBERT

## Overview

This project implements an NLP-based customer support ticket classification system using the DistilBERT transformer model. It automatically predicts the category of a customer support ticket based on its text, helping organizations route tickets more efficiently and reduce manual effort.

## Features

* Automatic ticket classification using DistilBERT
* Text preprocessing and tokenization
* Fine-tuned transformer model for sequence classification
* Predicts ticket category with confidence score
* Performance evaluation using Accuracy, Precision, Recall, and F1-Score

## Dataset

The model is trained on a customer support ticket dataset containing ticket descriptions and their corresponding categories. The text is preprocessed, tokenized using the DistilBERT tokenizer, and encoded into numerical labels for training.

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Datasets
* Scikit-learn
* Pandas
* NumPy

## Project Workflow

1. Load and preprocess the dataset.
2. Encode ticket categories into numerical labels.
3. Split the dataset into training and testing sets.
4. Tokenize text using the DistilBERT tokenizer.
5. Fine-tune the DistilBERT model.
6. Evaluate the model using standard classification metrics.
7. Predict ticket categories for new customer queries.

## Project Structure

```
├── dataset/
├── notebooks/
└── README.md
```

## Results

The trained model classifies customer support tickets into predefined categories and returns the predicted category along with its confidence score.

## Future Improvements

* Improve classification accuracy using larger datasets.
* Add more ticket categories.
* Deploy the model as a web application using Flask or Streamlit.
* Integrate the system with real-time customer support platforms.

