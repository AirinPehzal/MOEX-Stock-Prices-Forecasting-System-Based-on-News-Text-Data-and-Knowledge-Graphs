# MOEX Stock Prices Forecasting System Based on News Text Data and Knowledge Graphs
This repository provides source codes on all testing done on different ontology generation algorithms in MOEX-Stock-Prices-Forecasting-System-Based-on-News-Text-Data-and-Knowledge-Graphs thesis.

# Basic Preprocessing and Entity Extraction
Source code for preprocessing Lenta.ru news dataset (available at https://www.kaggle.com/datasets/yutkin/corpus-of-russian-news-articles-from-lenta) via spacy. Entity extraction is also conducted in the same file.

# Additional Preprocessing and DBpedia
Source code for some additional preprocessing of the dataset (limiting the data to a ten year period and putting extracted entities into a better format), cleaning of the extracted entities via a similarity function, attaining a list of all entities, their types and number of occurences in the dataset for creation of file with all terms that have a certain threshold occurence.
Also provides source code for interaction with DBpedia and extraction of links to entities there corresponding to the extracted entities in the dataset.

# Klink and Neo4j
Source code for preprocessing of the entire relevant news data, ontology creation via an adapted version of Klink algorithm and uploading of the ontology onto a Neo4j server
Also includes illustration of the graph from Neo4j

# HiExpan Testing and FinRED
Source code on testing conducted on HiExpan (https://github.com/mickeysjm/HiExpan/tree/master) and FinRED (https://paperswithcode.com/dataset/finred) dataset.
