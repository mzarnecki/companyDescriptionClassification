# Text classification into industry categories

The goal of this projest is to present 2 different approaches for text classification. 
Company descriptions are classified into 1835 industry codes from official german classification WZ 2008. 
Complete description of the task and used approaches can be found in [this article](https://medium.com/p/3bff25ce6616).

## Approach with LLM (Large Language Model) + RAG (Retrieval Augmented Generation)

Project shows classification of text with OpenAI GPT-4 model accessed via API.
To improve classification results prompt is enriched by additional guidelines text accessed with RAG (Retrieval Augmented Generation) is used. 


[classify-industry-with-LLM-and-RAG.ipynb](classify-industry-with-LLM-and-RAG.ipynb)


## Approach with self trained model - RandomForestClassifier
Project contains text normalization, tokenization, model training and evaluation as well as model export and import. 
Presented approaches were used to classify company descriptions from [data/data.csv](data/data.csv) into 2 industry categories. 

[classify-industry-with-self-train-model.ipynb](classify-industry-with-self-train-model.ipynb)

In order to use these examples in your classification problems just replace datasets.
