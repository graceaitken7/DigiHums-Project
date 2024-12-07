---
layout: page
title: GloVe and Word2Vec
author: Nuria Sánchez
---

## GloVe and Word2Vec
Made with Google Colab, by Nuria Sánchez

{:.no_toc}

* ToC
{:toc}

---

### Rationale
Word embedding analyses give distant reading a semantic and syntactic basis for text interpretation. Beyond dictionary definitions, word embeddings like [GloVe](https://nlp.stanford.edu/projects/glove/) (Global Vectors for Word Representation, Stanford University) and [Word2Vec](https://code.google.com/archive/p/word2vec/) (Google) give numerical representations of the similarities between words according to their presence in similar contexts. Based on trained vectors available for downloading, both tools measure the closeness between any given words in an English language corpus, although GloVe is a multilingual model and supported the Spanish corpus in our project as well.  

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

GloVe allowed me to pinpoint the main nodes of conversation in each corpus, called clusters in the field of word embeddings. In one hand, BHA orbits around the topic of family (‘father’, ‘mother’, ‘dad’, ‘family’), geography (‘Mexico’, ‘California’, ‘Texas’, ‘camps’), labor (‘work’, ‘years’, ‘time’), and sustenance (‘money’, ‘food’). The topics reappear in the SW corpus, but not arranged in the same way; for instance, ‘time’, ‘work’ and ‘money’ belong to the same category, and ‘field’ is closer to ‘ranch’, ‘town’, and ‘family’, and ‘food’ no longer appears similar to ‘money’. In the other hand, the Gov corpus yielded the topics of political figures (‘ambassador’, ‘president’, ‘embassy’, ‘secretary’), international politics (‘agreement’, ‘relationships’, ‘matter’, ‘United States’, ‘Mexico’, ‘war’), government (‘commision’, ‘government’, ‘department’, ‘state’), and work (‘manpower’, ‘agricultural’, ‘workers’). 
When ran on its own, that is, without a biased input, Word2Vec yielded interesting constellations that showcased differences, for example, between ‘joy’ and ‘sad’, which is a cluster not relevant enough for the GloVe model; however, after doing research about Word2Vec’s accuracy, I decided to only interpret the analysis I made with the words obtained after the GloVe analysis and interpretation, since it would also give me the opportunity to compare the 3 corpora amongst each other. For example, ‘Mexico’ is similar to ‘work’ in the Gov corpus, whereas it is closer to ‘oranges’, ‘family’ and ‘lives’ in BHA. While this might sound as something evident, other discoveries were found out through the process: when I analysed ‘agricultural’ in Gov, a word adjacent to ‘work’, the word ‘immigration’ appeared, although the program was not conceived as such. As a matter of fact, for the Gov corpus, ‘work’ equals ‘documented’ and ‘solution’, yet upon close reading of the BHA testimonies, many of the bracero relatives mention all the hardships they overcame to either become legal residents or to prove they gained such right. Symptomatically, the BHA second party testimonies consider the workers as ‘able’ people to carry out the job with machines like ‘tractors’, since many former employers and their families mostly remember that from the braceros they hired, but did not socialize further with them. 
All these paths remain open to further analysis and research, particularly the Spanish language analysis of the SW corpus, and to complement the Word2Vec analysis since it does not measure re-occurence nor frequency.

---

### References

Pennington, Jeffrey, “[Glove: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/)”. NLP Stanford, August 2014. 
Rieping, Holly Anne, *[Audio Segmenting and Natural Language Processing in Oral History Archiving]*(https://dspace.mit.edu/handle/1721.1/143185). MIT, graduate thesis, February 2022. 
Smetanin, Sergey, “[Google News and Leo Tolstoy: Visualizing Word2Vec Word Embeddings using t-SNE](https://towardsdatascience.com/google-news-and-leo-tolstoy-visualizing-word2vec-word-embeddings-with-t-sne-11558d8bd4d)”. Medium, November 16th, 2018. 
Suri, Manan, “[A Dummy’s Guide to Word2Vec](https://medium.com/@manansuri/a-dummys-guide-to-word2vec-456444f3c673)”. Medium, January 21st, 2022. 
