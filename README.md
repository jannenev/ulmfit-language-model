
# Applying ULMFit Language Model on Entity Level Sentiment analysis of Business news articles.
This repo contains code to train ULMFit* for 
(*Universal Language Model with Fine tuning)

Refer to paper Universal Language Model Fine-tuning for Text Classification by Jeremy Howard and Sebastian Ruder.
https://arxiv.org/abs/1801.06146

Info about ULMFit
http://nlp.fast.ai/classification/2018/05/15/introducting-ulmfit.html
Implementation is based on FastAI:s
https://github.com/fastai/fastai/blob/master/courses/dl2/imdb.ipynb

Business news dataset
Dataset: 16840 entries of business news in 5 categories by how negative/positive for given entity
Entity is a company name, with given location within text. Can be several entities in single article. 

Data is available at http://puls.cs.helsinki.fi/static/polarity/index.html 
Supporting paper "Benchmarks and models for entity-oriented polarity detection" http://aclweb.org/anthology/N18-3016
