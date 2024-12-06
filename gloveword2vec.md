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
Word embedding analyses give distant reading a semantic and syntactic basis for text interpretation. Beyond dictionary definitions, word embeddings like [GloVe](https://nlp.stanford.edu/projects/glove/)(Global Vectors for Word Representation, Stanford University) and [Word2Vec] (https://code.google.com/archive/p/word2vec/)(Google) give numerical representations of the similarities between words according to their presence in similar contexts. Based on trained vectors available for downloading, both tools measure the closeness between any given words in an English language corpus, although GloVe is a multilingual model and supported the Spanish corpus in our project as well.  

I decided to focus my analysis on word embeddings for two reasons. Firstly, because I could measure co-occurrences within our project’s corpora while simultaneously comparing it with other existing corpora, which could showcase to what extent these testimonies are different to the common knowledge about the Bracero Program. Secondly, because it sheds light on the substructures of each testimony, which might not be as easily perceived in a close reading. 

---

### Methods

GloVe
1. Selected the word vectors dataset that best matched our corpora: Wikipedia+Gigawork (printed press) 6 billion (400k words) tokens for BHA and Gov. 
2. Ran GloVe in Colab for the word vectors of the 30 most repeated words in each corpora.
3. Obtained a visualization in Colab of the word vectors to determine which words are relevant either in themselves or in relationship with others for the next step (figures 1, 2 and 3). 

Word2Vec
1. Selected 'father', 'Mexico', 'worker', and 'money' for BHA. Ran Word2Vec in Colab each. 
2. Selected 'government' and 'agricultural' for Gov. Ran Word2Vec in Colab each. Ran 'Mexico' and 'worker' too to compare with prior.

---

### Analysis Visualizations

#### GloVe 

Figure 1: GloVe visualization of corpus BHA <img width="732" alt="Visualization GloVe BHA" src="https://github.com/user-attachments/assets/4f232e68-8ba4-4aa0-9a8e-e282ee2de335">

Figure 2: GloVe visualization of corpus Gov <img width="766" alt="Visualization Glove Gov" src="https://github.com/user-attachments/assets/62ce0c9f-f960-4df4-a6be-c7e4585ce162">

Figure 3: GloVe visualization of corpus SW ![Visualization GloVe SW](https://github.com/user-attachments/assets/b0982446-7aa1-4b56-93b9-fa3f8cac0947)


#### Word2Vec 

Figure 4: Word2Vec visualization of 'father' in corpus BHA.<img width="1015" alt="Visualization Word2Vec BHA father" src="https://github.com/user-attachments/assets/d3cf77e4-4214-4b35-8c24-2d3e7efdedcd">

Figure 5: Word2Vec visualization of 'Mexico' in corpus BHA.<img width="1017" alt="Visualization Word2Vec BHA mexico" src="https://github.com/user-attachments/assets/7423398e-ca3c-400b-9b26-eb3efd73e9a4">

Figure 6: Word2Vec visualization of 'worker' in corpus BHA.<img width="1028" alt="Visualization Word2Vec BHA worker" src="https://github.com/user-attachments/assets/3dd5532c-4b2f-4d6f-9755-55bbdc6d47ad">

Figure 7: Word2Vec visualization of 'money' in corpus BHA.<img width="1011" alt="Visualization Word2Vec BHA money" src="https://github.com/user-attachments/assets/bdf40205-74e0-473c-b9d2-e89409bb2cdf">

Figure 8: Word2Vec visualization of 'government' in corpus Gov.<img width="1018" alt="Visualization Word2Vec Gov government" src="https://github.com/user-attachments/assets/a24a7cc5-3c39-4056-9f79-f7b8f555eb5c">

Figure 9: Word2Vec visualization of 'Mexico' in corpus Gov.<img width="1023" alt="Word2Vec Gov mexico" src="https://github.com/user-attachments/assets/d7230cfa-cfb4-4a8f-a0e4-06f8b7954c28">

Figure 10: Word2Vec visualization of 'agricultural' in corpus Gov.<img width="1023" alt="Visualization Word2Vec Gov agricultural" src="https://github.com/user-attachments/assets/966872f4-13e5-464e-b6e7-95baedcd9fc5">

Figure 11: Word2Vec visualization of 'worker' in corpus Gov.![Visualization Word2Vec worker Gov](https://github.com/user-attachments/assets/0229ae47-bf0f-4d02-b761-1781eedf0eb7)

---

### Interpretation

---

### References



