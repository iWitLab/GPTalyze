# Using ChatGPT to analyze Twitter data

This repository contains an example to an interaction with ChatGPT to analyze Twitter posts (based on the ```gpt-3.5-turbo``` language model).
The example Jupyter notebook analyzes the publicly available Twitter dataset containing tweets about the COVID-19 pandemic (More information on the dataset's page at [Kaggle](https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification/)).

## Usage
- Install ```Python```  (Python 3.8) with Jupyter (or Jupyter-lab interface).
- Create a virtual environment (or alternatively Anaconda environment) and install the following packages (using ```pip install <package_name>```): ```numpy```, ```pandas```, ```seaborn```, ```jupyter```, ```nltk```, ```tweepy```, ```spacy```, ```gensim```, ```pysentimiento```, ```twarc```, ```openai```, ```sklearn```.
- Download the dataset from [Kaggle](https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification/)) and save it locally (filename is "Corona_NLP_train.csv").
- Run the jupyter notebook ```interact_with_chatgpt_general.ipynb```.

## Description and demonstration
[ChatGPT](https://chat.openai.com/) has recently emerged as a powerful Large Language Model (LLM), enabling unprecedented and innovative public interaction with generative language AI.
> "As of April 2023, ChatGPT boasts about 173 million active users and 1.8 billion monthly website visits" (reported by [Nerdynav](https://nerdynav.com/chatgpt-statistics/)).

These capabilities were not overlooked by the research community, who started leveraging ChatGPT for data analysis of various data sources, including textual unstructured data from social networks, such as Twitter.
In this repository, we utilize ChatGPT's API for analysis of Twitter data, employing ChatGPT's zero-shot-like abilities to summarize the discussed topics in a subset of tweets and perform other NLP tasks, such as sentiment analyis and emotion detection.
Specifically, we evaluate the interaction with ChatGPT on a publicly available Twitter dataset containing tweets about the COVID-19 pandemic (More information on the dataset's page at [Kaggle](https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification/)).
Since ChatGPT is a generic tool, (almost) any textual data from other sources can also be used for evaluation.

Thanks to the chat interaction of ChatGPT, the usage of this repository is quite simple.
- First, we download the textual corpus and pre-process it to be more natural for human interaction. This includes extracting the tweet posted text, removing unnecessary URLs, removing special characters that may not be recognized by the chat etc.
- Once the dataset is clean, we can call ChatGPT's API with the desired task and ask it to perform it (call limits may apply, depending on the account's pricing plan).
  Here, we demonstrate a very usufll use case of text summarization, in the form of extraction of discourse topics:


