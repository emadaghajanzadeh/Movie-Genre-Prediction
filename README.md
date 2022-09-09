# Movie-Genre-Prediction

## Description
This project was part of assigments during the "Computational Intelligence" course and it focused on natural language processing using machine learning models. The given dataset is consisted of movies' overview and their genres and the task is to process the overview textes and predict the movie genres using a **combination of two TF-IDF and Word2Vec algorithms**. Each film can have multiple genre and below you can see the distribution of genres in the both train and test dataset.

<img src="Trainlabels.png" width="80%">

<img src="Testlabels.png" width="80%">

## Implementation
Similar to other machine learning problems, the task is devided into some sub-tasks of preparing data and training machine learning models, which are described below.

### Pre-processing
Dataset was given in the form of excel files, so loading data is nothing but importing excell files. Later, as basic pre-processing steps, punctuations, numbers, single charactars, and multiple space are removed from the text. The result of these steps is illustrated below which shows the importance of them in keeping more important words and removing meaningless words.

You can see below the frequency of words in tranining data before the pre-processing steps and after it.

<img src="WordFreq_Train_Before.png" width="60%">

<img src="WordFreq_Train_After.png" width="60%">


### Obtaining Word Representation
In order to process text we need to first transform it to the language of computers, i.e. digital numbers, so it is needed to derive some vector representations of text to work with them instead. In order to do this, two well-known algorithms [Word2Vec](https://arxiv.org/pdf/1301.3781.pdf%C3%AC%E2%80%94%20%C3%AC%E2%80%9E%C5%93) and [TF-IDF](https://towardsdatascience.com/tf-idf-in-a-nutshell-b0ff082fbbc) had been introduced. However, these algorithms have thier own pros and cons, and so in this project, after implementing both of them, an initiative method is used to combine these two methods as to alleviate their problems.

#### Word2Vec
This 

#### TF-IDF

#### Combination

### Classifiers

## Conclusion






