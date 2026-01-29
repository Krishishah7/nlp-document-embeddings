# Document Embeddings using Word2Vec (NLP)

This project demonstrates how to create **document (sentence) embeddings** by averaging Word2Vec word vectors to represent entire sentences numerically.

## Overview
Document embeddings convert a full sentence or document into a single dense vector.  
This allows semantic comparison between documents using vector similarity instead of simple word matching.

## Features
- Training a Word2Vec model on tokenized sentences
- Generating word embeddings
- Creating document embeddings using average word vectors
- Comparing documents using cosine similarity
- Demonstrating semantic similarity at document level

## Tools & Libraries
- Python
- gensim
- numpy
- scikit-learn
- Google Colab

## Method Used
The document vector is computed by:
1. Getting vectors for all words in a sentence
2. Averaging the word vectors
3. Using the mean vector as the document representation

## Important Note
Averaging word vectors is a simple baseline approach.  
It ignores word order and word importance but works well for small demonstrations and basic similarity tasks.

## Use Cases
- Document similarity
- Resume matching
- Semantic search
- Text clustering
- Recommendation systems
