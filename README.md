# Text Analyzer GUI
## A beginner's guide for NLP
Text analytics can be a bit overwhelming and frustrating at times
with the unstructured and noisy nature of textual data and the 
vast amount of information available. To read through all the texts and 
further draw conclusions from it is the most cumbersome task.

Natural Language Processing (NLP) which is broadly defined as the automatic manipulation of
Natural Language provides many inbuilt features that can be of great advantage for many.

## What does it offer?
The two main features offered by NLP are being used in this platform:
- Sentimental Analysis - It classifies the specific text into three main sentiments using "SentimentIntensityAnalyzer" from "vaderSentiment". The three categories of sentiments are namely positive, neutral and negative.

![image](https://user-images.githubusercontent.com/97681112/202786807-2505adc1-7240-4bc3-8069-19830cd17ed7.png)

- Word Cloud Generator - Generates a word cloud which shows us the relevance of specific words on the basis of the number of times it occurs in the text file. Since there are more chances of occuring of stopwords like "a", "and" and "the", a function is defined to not consider such words.

<img width="572" alt="image" src="https://user-images.githubusercontent.com/97681112/202787652-d6d9ba79-c44d-422e-8d6f-eaf68f389602.png">

## Prerequesites:
This projct requires the setup of Python on your system.

## Dependencies:
It also requires the following dependencies to be installed.
- "pip install tkinter"
- "pip install wordcloud"
- "pip install vaderSentiment"
- "pip install PIL"
