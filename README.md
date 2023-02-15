## CSE 582: Natural Language Processing
## Homework 1

## Submission Details

This repo consists of the following files:

```
word2vec.c      # Find commented code here
hw1.sh          # Shell script for training
output_cat.txt  # Word embeddings for "cat" using CBOW
output_she.txt  # Word embeddings for "she" using CBOW
output_like.txt # Word embeddings for "like" using CBOW
```

## Training Details

- Uses Continuous Bag of Words (CBOW) to generate word embeddings
- Size of word vectors: 300
- Window Size: 10
- \# Negative Samples: 10
- Down Sampling Range: 1e-5
- \# Threads for training: 300
- \# Training iterations: 3
- \# Discard words that occur less than (min-count): 10 times

Questions for reference:

Q1. How does CBOW compose context embeddings?
- predicts the target word based on the context which means that it will take a certain number of words before the target word and the same number after and calculate the probability of the target word . The number of words for prediction is calculated based on the input parameter

Q2. How does it compute word probability given context?
- refer 

Q3. Any other parameters apart from the word embeddings and context embeddings?
- learning rate; gradient descent; neural network; 

Q4. What input format does Word2Vec require?
<!-- If input parameters: describe all inputs  -->