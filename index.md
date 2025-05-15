# Financial Advisor
Jackson Eshbaugh, Gia Mazza &bull; Spring 2025 &bull; CS 424 &bull; Lafayette College
<br /><a href="https://colab.research.google.com/github/jacksoneshbaugh/CS-424-Final-Project/blob/master/Final_Project_Mazza_Eshbaugh.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Overview
For our final project in Intro to Machine Learning, we decided to implement a helpful finacial advisor tool. It predicts your future spending, flags unusual trasactions, and reports all this information through a chat interface, where you can engage in further conversation. This is done using an isolation forest model, Long Short-Term Memory (LSTM) neural network, and Google Gemma's 2 2B large language model (LLM). We utilized a Kaggle data set (linked below), which had personal financial transactions over time. Overall, our models performed well when detecting anamolous transactions and predicting future spending, and while the LLM did not do as well, it still generated personalized recommendations. Thus, our project was a success.  
<br />
For additional information, read the full executive report and video.

## Video

[![](https://markdown-videos-api.jorgenkh.no/youtube/QxdjZONUkJo)](https://youtu.be/QxdjZONUkJo)

> **Note**: The graphs shown in the video show solid performance (especially when you take into context how zoomed in the curves are). However, as the space between the curves increases, we see signs of _slight_ (and I do mean slight) overfitting, which is why the 6th trial won out.

## Executive Report
Read our executive report [here](https://github.com/jacksoneshbaugh/CS-424-Final-Project/blob/main/report/main.pdf).

### Thank you to Ismat Samadov for our Data Set
https://www.kaggle.com/datasets/ismetsemedov/personal-budget-transactions-dataset
