# Sarcasm Detection in News Headlines using DistilBERT

This repository contains the mid-term work for the WIDS project on sarcasm detection using transformer-based models.

## Objective
The objective of this project is to understand and apply transformer-based models for detecting sarcasm in news headlines.

## Work Done Till Mid-Term
- Studied fundamentals of Natural Language Processing (NLP)
- Learned transformer architecture and self-attention mechanism
- Explored challenges involved in sarcasm detection
- Worked with the News Headlines Sarcasm Detection dataset from Kaggle
- Performed data loading and basic exploration
- Split the dataset into training and testing sets using stratified sampling
- Implemented tokenization using DistilBERT uncased tokenizer
- Applied padding and truncation for uniform input length
- Fine-tuned a pretrained DistilBERT model for binary classification
- Evaluated the model using standard classification metrics
## Work done after mid term
- Studied the importance of model interpretability for transformer-based models
- Implemented LIME (Local Interpretable Model-Agnostic Explanations) for model interpretability
- Applied LIME to a sample news headline to analyze word-level contributions to sarcasm prediction
- Interpreted how specific words influenced the model’s decision, improving transparency and understanding of model behaviour
## Model Used
- **DistilBERT (distilbert-base-uncased)**
- A single classification layer was added on top of the transformer encoder for sarcasm prediction

## Tools & Libraries
- Python
- HuggingFace Transformers
- PyTorch
- Pandas
- Scikit-learn
- LIME

## Dataset
News Headlines Dataset for Sarcasm Detection  
Source: Kaggle

## Notes
The code was developed and executed using a Kaggle notebook environment and then uploaded to this GitHub repository. 
Model interpretability experiments using LIME were added as part of the end-term work.
