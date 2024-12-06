---
layout: page
title: GloVe and Word2Vec
author: Nuria Sánchez
---

## GloVe and Word2Vec
Made with Google Colab
By Nuria Sánchez

---

### Rationale
Word embedding analyses give distant reading a semantic and syntactic basis for text interpretation. Beyond dictionary definitions, word embeddings like [GloVe](https://nlp.stanford.edu/projects/glove/)(Global Vectors for Word Representation, Stanford University) and [Word2Vec] (Google) (https://code.google.com/archive/p/word2vec/) give numerical representations of the similarities between words according to their presence in similar contexts. Based on trained vectors available for downloading, both tools measure the closeness between any given words in an English language corpus, although GloVe is a multilingual model and supported the Spanish corpus in our project as well.  

I decided to focus my analysis on word embeddings for two reasons. Firstly, because I could measure co-occurrences within our project’s corpora while simultaneously comparing it with other existing corpora, which could showcase to what extent these testimonies are different to the common knowledge about the Bracero Program. Secondly, because it sheds light on the substructures of each testimony, which might not be as easily perceived in a close reading. 

---

### Methods

GloVe
1. Selected the word vectors dataset that best matched our corpora: Wikipedia+Gigawork (printed press) 6 billion (400k words) tokens for BHA and Gov. 
2. Ran GloVe in Colab for the word vectors of the 30 most repeated words in each corpora.
3. Obtained a visualization in Colab of the word vectors to determine which words are relevant either in themselves or in relationship with others for the next step (figures 1, 2 and 3). 

Word2Vec
1. Selected 'family', 'worker', 'Mexico', and 'money' for BHA. Ran Word2Vec in Colab each. 
2. Selected 'government' and 'agricultural' for Gov. Ran Word2Vec in Colab each. Ran 'Mexico' and 'worker' too to compare with prior.

---

### Analysis Visualizations

#### GloVe 

Figure 1: GloVe visualization of corpus BHA <img width="732" alt="Visualization GloVe BHA" src="https://github.com/user-attachments/assets/4f232e68-8ba4-4aa0-9a8e-e282ee2de335">

Figure 2: GloVe visualization of corpus Gov <img width="766" alt="Visualization Glove Gov" src="https://github.com/user-attachments/assets/62ce0c9f-f960-4df4-a6be-c7e4585ce162">

Figure 3: GloVe visualization of corpus SW ![Visualization GloVe SW](https://github.com/user-attachments/assets/b0982446-7aa1-4b56-93b9-fa3f8cac0947)


#### Word2Vec 

Figure 1: GloVe visualization of corpus BHA

Figure 2: GloVe visualization of corpus Gov

Figure 3: GloVe visualization of corpus SW

---

### Interpretation

---

### References



