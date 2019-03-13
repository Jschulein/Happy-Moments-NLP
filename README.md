# Happy-Moments-NLP

## What Makes People Happy? Analysis using Natural Language Processing (NLP)

> Jonathan Schulein's Capstone Project for General Assembly's Data Science Fundamentals course

---

## Introduction

HappyDB is a corpus of over 100,000 crowd-sourced, self-described 'happy moments' collected from Amazon Mechanical Turk workers over a period of 3 months. The corpus of happy moments are workers real-life explinations of what made them feel happy over the past 24 hours, and over the past 3 months. The happy moments were collected by a group a researchers who analyzed the data set, and published a paper on the topic (cited below).

> @inproceedings{asai2018happydb, 
  title = {HappyDB: A Corpus of 100,000 Crowdsourced Happy Moments}, 
  author = {Asai, Akari and Evensen, Sara and Golshan, Behzad and Halevy, Alon
  and Li, Vivian and Lopatenko, Andrei and Stepanov, Daniela and Suhara, Yoshihiko
  and Tan, Wang-Chiew and Xu, Yinzhan}, 
  booktitle = {Proceedings of LREC 2018},  
  month = {May},   year={2018}, 
  address = {Miyazaki, Japan}, 
  publisher = {European Language Resources Association (ELRA)}
}

### Data Source:
__[HappyDB GitHub](https://github.com/rit-public/HappyDB )__

---

### The overall goal for this project was to gain a better understanding of what makes people feel happy, by adding on to the work previously done by the researchers. 

---

## Project Objective(s)

### Part 1: Exploratory Data Analysis and Cleaning

### Part 2: NLP Modeling and Results

#### Modeling Goals:

###### 1. Select Model
The goal for this portion of the project was to determine which model was able to most accurately predict which category each Happy Moment was assigned to. Each Happy Moment was pre-assigned to a category by the research team that initially studied the subject. 
###### 2. Identify Most Informative Features
After selecting the most accurate model, apply the model to each of the categories to determine which features were most significant to it's prediction

#### NLP Tools Used:
* SpaCy used for tokenization and lemmatization
* Scikit-learn used for feature extraction/vectorization
