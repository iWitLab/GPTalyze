# twitter-analysis-using-chatgpt

[ChatGPT](https://chat.openai.com/) has recently emerged as a powerful Large Language Model (LLM), with many chatbot capabilies and innovative interaction.
This repository contains an example to an interaction with ChatGPT to analyze Twitter posts (based on the ```gpt-3.5-turbo``` language model).
The example Jupyter notebook analyzes the publicly available Twitter dataset containing tweets about the COVID-19 pandemic (More information on the dataset's page at [Kaggle](https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification/)).

## Usage
- Install ```Python```  (Python 3.8) with Jupyter (or Jupyter-lab interface).
- Create a virtual environment (or alternatively Anaconda environment) and install the following packages (using ```pip install <package_name>```): ```numpy```, ```pandas```, ```seaborn```, ```jupyter```, ```nltk```, ```tweepy```, ```spacy```, ```gensim```, ```pysentimiento```, ```twarc```, ```openai```, ```sklearn```.
- Download the dataset from [Kaggle](https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification/)) and save it locally (filename is "Corona_NLP_train.csv").
- Run the jupyter notebook ```interact_with_chatgpt_general.ipynb```.
