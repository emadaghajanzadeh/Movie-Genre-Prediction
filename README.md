# Movie-Genre-Prediction

## Description
This project was part of assigments during the "Computational Intelligence" course and it focused on natural language processing using machine learning models. The given dataset is consisted of movies' overview and their genres and the task is to process the overview textes and predict the movie genres. Each film can have multiple genre and below you can see the distribution of genres in the both train and test dataset.

<img src="Trainlabels.png" width="80%">

<img src="Testlabels.png" width="80%">

## Implementation
Similar to other machine learning problems, the task is devided into some sub-tasks of preparing data and training machine learning models, which are described below.

### Pre-processing
Dataset was given in the form of excel files, so loading data is nothing but importing excell files. Later, as basic pre-processing steps, punctuations, numbers, single charactars, and multiple space are removed from the text. The result of these steps is illustrated below which shows the importance of them in keeping more important words and removing meaningless words.

You can see below the frequency of words in tranining data before the pre-processing steps and after it.

<img src="WordFreq_Train_Before.png" width="60%">

<img src="WordFreq_Train_Aftery.png" width="60%">



