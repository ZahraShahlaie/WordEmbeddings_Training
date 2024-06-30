# WordEmbeddings_Training

This project demonstrates how to manually derive word embeddings from raw textual data, enabling a deeper semantic understanding of words and their relationships. The project avoids using popular libraries like Gensim or Word2Vec, instead implementing the process of creating word embeddings manually.

## Project Overview
step 1: Load Data

step 2: Create Bigrams

step 3: Perform one-hot Encoding 

step 4: Create model and train 

step 5: Visulaize results

Word embeddings are dense vector representations of words that capture their meanings, semantic relationships, and syntactic similarities. Training word embeddings involves learning these vector representations from a corpus of text. This project includes:


1. Data preprocessing (removing newline characters, converting to lowercase, and removing stop words)
2. Creating bigrams from the preprocessed data
3. Generating a list of unique words
4. Creating a dictionary of words and performing one-hot encoding
5. Training a neural network model to learn the word embeddings
6. Visualizing the learned word embeddings using matplotlib

## Requirements

To run the code in this project, you need the following libraries:
- Python 
- TensorFlow
- Keras
- Matplotlib
- NumPy


