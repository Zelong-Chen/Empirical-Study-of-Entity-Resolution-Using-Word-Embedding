# Empirical Study of Entity Resolution Using Word Embedding

### Abstract

### Archive Link

### Library and Pre-Trained Embedding
FastText Python Installation:  
https://fasttext.cc/docs/en/support.html#building-fasttext-python-module

FastText Pre-Trained Word Vectors:  
CBOW: https://fasttext.cc/docs/en/crawl-vectors.html  
SkipGram: https://fasttext.cc/docs/en/pretrained-vectors.html  

### Code + Experimental Results
#### Unsupervised Approaches
1. TF-IDF
    1. TF-IDF.ipynb
2. Random Indexing
    1. Random Indexing.ipynb
3. FastText Unsupervised (CBOW/SkipGram)
    1. FastText(Unsupervised).ipynb

#### Pre-Trained Approaches
4. FastText Wikipedia (CBOW)
    1. FastText (Wiki CBOW).ipynb
5. FastText Wikipedia (SkipGram):
    1. FastText (Wiki SkipGram).ipynb
6. FastText Wikipedia (CBOW/SkipGram) + Random Indexing
    1. Random Indexing (Pre-Trained CBOW).ipynb
    2. Random Indexing (Pre-Trained SkipGram).ipynb
    
#### Further Experiments
7. Combination of Ranked List (Average Cosine Similarity)
    1. TF-IDF + Pre-Trained (SkipGram) Cosine Similarity.ipynb
    2. Pre-Trained + Unsupervised (SkipGram) Cosine Similarity.ipynb
8. Word Embedding Concatenation
    1. TF-IDF + Pre-Trained (SkipGram) Vector Concat.ipynb
    2. Pre-Trained + Unsupervised (SkipGram) Vector Concat.ipynb
9. Blocking using Manufacturing and Price Fields
    1. FastText (Wiki SkipGram) + Blocking (-0.25).ipynb
    2. FastText (Wiki SkipGram) + Blocking (-3).ipynb
    3. TF-IDF + Pre-Trained (SkipGram) Vector Concat + Blocking (-0.25).ipynb	
    4. TF-IDF + Pre-Trained (SkipGram) Vector Concat + Blocking (-3).ipynb	
