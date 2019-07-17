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

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes
