# Text Classification of News Headlines using Naives Bayes Classification

![alt-text](https://cdn-images-1.medium.com/max/800/1*HgXA9v1EsqlrRDaC_iORhQ.png "Test Alt Text")

## Contents
+ [What is Naives Bayes?](https://github.com/bedangSen/Text-Classification-of-News-Headlines-using-Naives-Bayes-Classification/blob/master/README.md#what-is-naives-bayes)
+ [Naives Bayes and Machine Learning](https://github.com/bedangSen/Text-Classification-of-News-Headlines-using-Naives-Bayes-Classification/blob/master/README.md#naives-bayes-and-machine-learning)
+ [Text Classification of News Headlines into News Groups](https://github.com/bedangSen/Text-Classification-of-News-Headlines-using-Naives-Bayes-Classification/blob/master/README.md#text-classification-of-news-headlines-into-news-groups)

## What is Naives Bayes?

Naive basyes classifier works on the priniciple of condition probability as given by the Bayes theorem. The bayes theorem gives us the conditional probability of an event **A** given that an event **B** has occured. In the Bayes theorem, the probability of **A** occuring given that **B** has occured, is the probability of **B** occuring fiven that **A** has occured times the probability of **A** over the probability of **B**. 

![alt-text](https://cdn-images-1.medium.com/max/800/1*LB-G6WBuswEfpg20FMighA.png)

## Naives Bayes and Machine Learning

![alt-text](https://github.com/bedangSen/Text-Classification-of-News-Headlines-using-Naives-Bayes-Classification/blob/master/Naives%20Bayes%20in%20Machine%20Learning.png)

It is importnat to undertand where the Naives Bayes fits in the heirarchy of Machine Learning. So under machine learning there is **Supervised Learning** and **Unsupervised Learning**. Under the supervised learning there is the **Classification** and **Regression**. And under Classification we have the **Naives Bayes**. 

## Text Classification of News Headlines into News Groups

### Getting Started 

1. Sign up for an [IBM Cloud Account](https://console.bluemix.net/registration/)
1. Login to [Watson Studio](https://www.ibm.com/cloud/watson-studio)

### Running the Jupyter notebook

#### 1. Sign up for Watson Studio

Sign up for IBM's [Watson Studio](https://dataplatform.ibm.com/).

#### 1. Create a new Project

> Note: By creating a project in Watson Studio a free tier `Object Storage` service will be created in your IBM Cloud account. Take note of your service names as you will need to select them in the following steps.

* On Watson Studio's Welcome Page select `New Project`.

* Choose the `Data Science` option and click `Create Project`.

* Name your project, select the Cloud Object Storage service instance and click `Create`

### 1. Import notebook to Watson Studio

* Create a **New Notebook**.

* Import the notebook found in this repository

* Give a name to the notebook and select a `Python 3.5` runtime environment, then click `Create`.

#### 6. Follow the steps in the notebook

Thesteps in the notebook should allow you to understand how to download the dataset, create a model that uses Naives Bayes Classification and then visualize it using a Confusion Matrix and Heat map. 

Finally you should be able to test the model and check it's accuracy.

## References 

[Naive Bayes Classifier | Naive Bayes Algorithm | Naive Bayes Classifier With Example | Simplilearn](https://www.youtube.com/watch?v=l3dZ6ZNFjo0)

***
