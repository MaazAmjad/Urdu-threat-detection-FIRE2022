# Urdu-threat-detection-FIRE2022


                                Urdu Threatening Tweet Dataset
                              ===========================

                                
---
## CONTENTS
 1. Introduction
 2. Data Annotation
 3. Dataset structure
 4. Task Description
 5. Feedback
 6. Citation Info
---

## 1. Introduction

This README demonstrates Urdu Threatening Tweet dataset that contain "Threatening" and "non-threatening" tweets.

---

## 2. Data collection

**"Urdu Threatening Tweet Dataset"** dataset contains "Threatening" and "non-threatening" tweets in Urdu language. More details on the data collection are provided in the paper. 

---

## 3. Dataset structure 

This dataset has two folders. Each folder contains real and fake news. There are 5 types of news in this dataset such as technology, business, sports, health, and entertainment. The file names show the category of news. For example, the news categories are sports (sp), technology (tech), etc.

The class distribution for the fake and real news for each dataset is shown below:

| Dataset             | Class      | Entries |
|:--------------------|:----------:|--------:|
|                     | Threatening|  1,782     |
| Urdu Threatening    |------------|---------|
| Tweet Dataset       | Non-Threatening| 1,782 |
| Total Tweets       | -----| 3,564 |


| Dataset             | Class      | Entries |
|:--------------------|:----------:|--------:|
|                     |  Group |  1,341     |
| Group Threat    |------------|---------|
| Individual Threat      | Individual| 441 |
| Total Tweets       | -----| 1,782 |



## 4. Task Description

This is a binary classiifcation task. There tare two primary tasks in this shared task. 

1. The first task is to classifiy the given tweet as "Threatening" and "non0threatening". 
2. The second tasks is if the tweet is classified as "threatening" tweet, then it should be further classified as threat is given to an "individial" or a "group". 

The format of the Training Dataset.xlsx file is as follows:

The first column corresponds to the Tweet text to be classified as "Threatening" and "non-threatening". If the tweet is classified as "threatening" tweet, then it should be further classified as threat is given to an "individial" or a "group". 

The second column contains the truth label "1" or "0". 
  a. The truth label "1" corresponds to the threatening tweet. 
  b. The truth label "0" corresponds to the non-threatening tweet. 
  

The third column contains the truth label "1", "0", "2". 
  a. The truth label "1" corresponds to the threat is given to an "individual". 
  b. The truth label "0" corresponds to the threat is given to an "group". 
  c. The truth label "2" corresponds to the non-threatening tweet.
  
---

## 5. Feedback
If you want to know how this dataset was build (include the explanation of crawling and annotation technique) and how we did our experiments for Fake News detection in Urdu language using this dataset, you can read our paper DOI: 10.1109/ACCESS.2021.3112500

*For further questions or inquiries about this dataset, you can contact Maaz Amjad (maazamjad@phystech.edu)* 

---

## 6. Citation Info
This dataset and the other resource can be used for free, but if you want to publish a paper/publication using this dataset, please cite this publication:
```
@ARTICLE{maaz9536729,
  author={Amjad, Maaz and Ashraf, Noman and Zhila, Alisa and Sidorov, Grigori and Zubiaga, Arkaitz and Gelbukh, Alexander},
  journal={IEEE Access}, 
  title={Threatening Language Detection and Target Identification in Urdu Tweets}, 
  year={2021},
  volume={9},
  number={},
  pages={128302-128313},
  doi={10.1109/ACCESS.2021.3112500}}
```
---
