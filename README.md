### Vector Model Based Information Retrieval System with Word Embeddings

#### Overview
This project implements a vector space based Information Retrieval (IR) system using word embeddings.
The goal is to retrieve relevant documents for a given query by representing text as vectors and measuring similarity.

The work was presented at the IEEE ICETET-SIP 2022 conference.

#### Problem Statement
Traditional keyword-based information retrieval systems fail to capture semantic meaning.
This project explores vector-based models that use word embeddings to improve document relevance.

#### Dataset
The dataset is taken from the TREC 2019 Deep Learning Track.
It contains a large corpus of documents and user queries.
Due to the dataset size, experiments were conducted on Google Colab.

#### Preprocessing
Lowercasing text
Removing stop words
Stemming and lemmatization
Cleaning and normalization of text

#### Models Used
Word2Vec
GloVe
SBERT (Sentence-BERT)

#### Embedding Transformation
PCA (Principal Component Analysis)
Factor Analysis

These transformations are applied to improve embedding quality and document similarity results.

#### Approach
Convert documents and queries into vector embeddings
Apply dimensionality reduction techniques
Compute similarity using cosine similarity and Euclidean distance
Evaluate performance using Mean Average Precision (MAP)

#### Results
Factor Analysis improved retrieval performance compared to raw embeddings.
An average improvement of 2–3% in Mean Average Precision was observed.
SBERT produced more semantically meaningful results compared to Word2Vec and GloVe.

#### Tools and Technologies
Python
Google Colab
Word Embedding Models
Scikit-learn
NLP Libraries

#### Conclusion
The project demonstrates that vector-based information retrieval systems outperform traditional methods.
Embedding transformations such as Factor Analysis significantly enhance retrieval accuracy.

Publications: https://ieeexplore.ieee.org/document/9791503
