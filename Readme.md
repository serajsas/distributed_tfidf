# Distributed TF-IDF algorithm

## Introduction:
This project aims to provide an efficient and scalable implementation of the Term Frequency-Inverse Document Frequency (TF-IDF) algorithm using a distributed computing approach. TF-IDF is a fundamental technique in natural language processing and information retrieval, commonly used for text analysis, search engines, and content recommendation systems.

## Architecture
The Distributed TF-IDF Algorithm is designed to follow a map-reduce-like architecture. It involves the following key steps:

1. Document Term Frequency Calculation: Calculate the term frequency (TF) of terms in each document.

2. Document Inverse Document Frequency Calculation: Calculate the inverse document frequency (IDF) of terms across the entire corpus.

3. TF-IDF Score Calculation: Combine the TF and IDF values to compute the final TF-IDF scores for each term in each document.

4. Aggregation: Aggregate the TF-IDF scores from all documents to generate the overall TF-IDF matrix.

## Dependencies:
1. Zookeeper
2. Java 11
3. Protobuf
