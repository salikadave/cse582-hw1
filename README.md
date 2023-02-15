## CSE 582: Natural Language Processing
## Homework 1

## Submission Details

My comments are in the following files:

`
word2vec.c
`

Questions to be answered:

Q1. How does CBOW compose context embeddings?
- predicts the target word based on the context which means that it will take a certain number of words before the target word and the same number after and calculate the probability of the target word . The number of words for prediction is calculated based on the input parameter

Q2. How does it compute word probability given context?

Q3. Any other parameters apart from the word embeddings and context embeddings?

Q4. What input format does Word2Vec require?
<!-- If input parameters: describe all inputs  -->