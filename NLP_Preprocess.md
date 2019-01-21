# Natural Language Processing 

- Preprocessing
    - Cleaning, Stemming, Contraction removal, Special char removal
- EDA
    - Word2vec, Misspell Removal, Feature Creation
- Representation
    - Tokenisation, Text 2 sequence, Padding sequences
- Modelling
    - Bi-LSTM/GRU, Attention
- Deployment
    - Prediction and model evaluation
    
  

- Often iterate between preprocessing and EDA
- Representing words in a vocabulary
    - Could use one hot encoding of word vectors but doesn't enable word similarity such as cosine similarity. 
    - Also,one hot encoding gets very large and sparse very quickly.
    - Word2Vec provides fixed length vector represtnation of words. It also captures similarity and analogy relationships between words. 
    - For example: What is king - man + woman? It's Queen.
    - word2vec creates vectors for words. Thus we have a d dimensional vector for every word(common bigrams too) in a dictionary. We normally use pretrained word vectors which are provided to us by others after training on large corpora of texts like Wikipedia, twitter etc. The most commonly used pretrained word vectors are Glove and Fasttext with 300-dimensional word vectors. 
    - Don't forget to clean numbers, special characters and misspells. 
    - Expand contractions (words with apostrophes).
    
    
