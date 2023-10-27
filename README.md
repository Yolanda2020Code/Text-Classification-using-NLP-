# Text Classification using NLP

This project demonstrates a simple text classification model that categorizes text as either positive or negative.

## Description:
- Utilizes Tokenization to convert text data into sequences.
- Uses Keras Embedding layer to represent words as dense vectors.
- A basic neural network is trained to classify the texts based on their sentiments.

## Requirements:
- tensorflow>=2.0
- keras>=2.4.0
- sklearn>=0.23.0

## Usage:
1. Update the `texts` and `labels` with your dataset.
2. Ensure required libraries are installed.
3. Run the code to train the model on your dataset.
4. The trained model can then be used to predict sentiments or categories of unseen texts.

**Note**: This is a basic demonstration for sentiment analysis. In a practical scenario, consider using a larger and balanced dataset, more complex architectures, and additional preprocessing for better accuracy.
