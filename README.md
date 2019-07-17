# Machine Learning Engineer Nanodegree
## Capstone Project: Identifying Toxic Online Comments

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- keras
- gensim

It needs TensorFlow backend.

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

Download crawl-300d-2M.vec pre-trained embedding, which is trained from Common Crawl (a website that collects almost everything). It has 2 million words. Each word is represent by a vector of 300 dimensions. You can get it from https://fasttext.cc/docs/en/english-vectors.html

### Code

Template code is provided in the `Final project_NLP.ipynb` notebook file. You will also be required to use the `data.csv` dataset file to complete your work. Since the full dataset is 797KB containing 1,804,874 records, which can be downloaded from https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data . The `capstone_data_sample.csv` here only contains 10000 records, which gives you an idea of data structure. 

### Run

In a terminal or command window, navigate to the top-level project directory and run the following commands:

Model building
```bash
ipython notebook Final project_NLP.ipynb
```  
(data exploratory)
```bash
jupyter notebook explore data nlp.ipynb
```


### Data

The dataset consists of 1,804,874 data points, with each datapoint having 106 features. This dataset is the train dataset found on the https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data. This project splitted the train dataset online into training and testing datasets to build model without using the testing dataset online.

**Features**
1. `comment_-text`: raw sentences of online comments

**Target Variable**
Type
1. `target`: whether the comment is toxic or not

Sube Type
1. `severe_toxicity`
2. `obscene`
3. `identity_attack`
4. `insult`
5. `threaty`
6. `sexual_explici`


**Variable for Weight**
'male', 'female','homosexual_gay_or_lesbian', 'christian', 'jewish', 'muslim', 'black', 'white', 'psychiatric_or
mental_illness'
