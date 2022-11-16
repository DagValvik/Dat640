# Dat640

## Requirements
Have a Anaconda installed.

Dowloand/install requirements from "environemt.yml" using:
```
conda env create -f environment.yml
```

Also need to run an instance of ElasticSearch in the background.


### Download data 
From https://microsoft.github.io/msmarco/Datasets
* Collection - collection.tar.gz
* Queries - queries.tar.gz
 
Download "qrels" from https://trec.nist.gov/data/deep/2019qrels-pass.txt

Store collection as "collection.tsv" in "data/collection".

Store Queries as "queries.eval.tsv" in "data/queries".

Store qrels as "qrels.txt" in "data/qrels".

## Instruction

Run Elasticsearch_BM25.ipynb first,
then BERT.ipynb.

