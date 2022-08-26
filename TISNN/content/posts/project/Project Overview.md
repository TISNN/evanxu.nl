---
title: "Project Overiew"
date: 2022-05-05T00:18:06+08:00
lastmod: 2022-05-05T00:18:06+08:00
author: ["Evan Xu"]
keywords: 
- 
categories: 
- 
tags: 
- Practical
description: ""
weight:
slug: ""
draft: false # 是否为草稿
comments: true
reward: false # 打赏
mermaid: true #是否开启mermaid
showToc: true # 显示目录
TocOpen: true # 自动展开目录
hidemeta: false # 是否隐藏文章的元信息，如发布日期、作者等
disableShare: true # 底部不显示分享栏
showbreadcrumbs: true #顶部显示路径
cover:
    image: "" #图片路径例如：posts/tech/123/123.png
    caption: "" #图片底部描述
    alt: ""
    relative: false
---

# 📕 Master Projects

### Personal Website

Github io + Hugo + PaperMod

| Link: 

---

### Robotic Process Automation (RPA)

Related Course: Entrepreneurship in Analytics and AI(EAAI) - 2022 - VU

*Jan. - Mar. 2022*


| Github: https://github.com/TISNN/EAAI_2022_RPA

#### Problems

<mark>Banking industries </mark>often have to process a huge amount of information or data statistics. In recent years, most enterprise systems do not have the function of intelligent batch processing, and it often takes a lot of manpower and time to extract the target information in the file. These are very tedious and boring repetitive tasks.

#### Solutions

Use <mark>RPA+chatbot</mark> technology to develop an intelligent document processing and intelligent data analysis results. Use this technology to recognize complex textual information and customer needs.

#### The value we create

For enterprises, reduce labor and time costs and improve work efficiency. For customers, increase customer satisfaction during the use of the system.


<!-- {{< ppt src="https://docs.google.com/presentation/d/1J-K0ivhOVnrEg-nW4Pus5X7L1n6wV61d/edit#slide=id.p1" >}}  -->


---


### Using machine learning to analyze the sensor data from people's activities

Grade: 9.0/10.0 

Related Course: Machine Learning for Quantified Self(ML4QS) - 2022 - VU

*Jun. - July. 2022*, Python

| Github: https://github.com/TISNN/2022_ML4QS


#### Work
The focus of our work is to predict the activity of each subject by using sensor data. We followed the machine learning workflow from the <a href="https://link.springer.com/book/10.1007/978-3-319-66308-1" target="_blank">book</a> and processed the large <a href="https://archive.ics.uci.edu/ml/datasets/pamap2+physical+activity+monitoring" target="_blank">PAMAP2</a> data set with good results.

#### Solution & Innovation
We labelled subject’s activity with different classification algorithms and conducted comparative experiments, the <mark>Optimized LSTM</mark> model had the best accuracy.

Our innovation is that we use LSTM to deal with multivariate time series, depending on the complexity of our data set. We have also improved the model by adding the <mark>dense layer and dropout</mark>, which greatly improves the accuracy of the training and test sets.


---
### Create a modular data processing pipeline using Brane framework

Related Course: Web Services and Cloud-Based Systems(WSCBS) - 2022 - UvA

*Apr. - Jun. 2022*, Pyhton 

| Github: https://github.com/TISNN/WSCBS_Assignment4b

#### Problem
It is about using the Brane framework to implement a data processing pipeline. The pipeline is built for the Kaggle challenges -- <a href="https://www.kaggle.com/c/titanic" target="_blank">Titanic – Machine Learning from Disaster</a>.

#### Brane framework
The <mark>Brane framework</mark> uses containerisation to encapsulate functionality into portable building blocks in the form of workflow applications that perform specified work on multiple nodes distributed across multiple domains.

It addresses the challenge of running distributed applications on geographically dispersed IT resources. Scientists can write applications to compose their own data processing pipelines through the framework without having to deal with the underlying technical details. 

#### Solution
Tiantic’s project has been divided into <mark>four packages</mark>:
* Initialization
* Get Features
* Train and Prediction
* Visualization
  
Then they are composed into a programmable Brane pipeline.


---

### Implement a verifier with Constrained Horn Clauses

Related Course: Verification of Security(VOS) - 2022 - VU

*Apr. - Jun. 2022*, Haskell

| Github: https://github.com/TISNN/vos_hw2

The project is divided into four parts:

#### Part 1: Horn Clause generation
 
  Provide an implementation for the generation of Horn Clauses from Nano statements. It should follow the method that use weakest preconditions and VCGen.

  Normalization: The translation to Horn clauses produces clauses that don't fit syntactic restrictions. So it queries may contain expressions rather than just variables. The task is to normalize the clauses, such that they fit the restrictions.

#### Part 2: Solving Horn Clauses via Predicate Abstraction

  The task is to implement the solving algorithm.

#### Part 3: Verification

  The task is to verify a small suite of NanoJS programs.


---
### Verifier based on the weakest-precondition/VCGen methodology

Grade: 10.0/10.0

Related Course: Verification of Security(VOS) - 2022 - VU

*Apr. - Jun. 2022*, Haskell

| Github: https://github.com/TISNN/2022_VOS_hw1

The verifier based on the <mark>weakest-precondition/VCGen methodology</mark>    was been completed by three parts:

#### Part A: Verification Condition Generation
#### Part B: Verifying A Small Suite of NanoJS Programs
#### Part C: Add New Test-cases
  
Programs that were written in a subset ECMAScript and translated them into the imperative language Nano.

---
### Recommender system: Personalize Expedia Hotel Searches

Grade: 9.4/10.0

Kaggle Ranking: 12/233

Related Course: Data Mining Technologies(DMT) - 2022 - VU

*Apr. - Jun. 2022*, Python

| Github: https://github.com/TISNN/Datamining2022

| Kaggle: https://www.kaggle.com/competitions/2nd-assignment-dmt2022

#### Problems
The objective of the project is to explore a dataset provided by Expedia - an online travel shopping company, which contains 5 million search hotel queries by real users.

It is expected to leverage data mining techniques to train a model that can be adapted by the search engine to predict users' choices and rank the hotels based on the user's history searching records and hotel information. Finally, to see the performance of our model.

#### Solutions
We used the scores of <mark>NDCG@5</mark> from both the training and test sets for evaluation. When compared Random Forest Classifie, DeepFM, XGBoost and LightGBM, we find that the <mark>lightGBM model worked  best</mark> with the training score 0.5244792 and test score 0.416901. And the score on Kaggle is 0.40851.

---

### Utilizing Multi-layer LSTM Model and Ensemble Learning Algorithm to Detect Fake News


Related Course: Web Data Processing Systems(WDPS) - 2021 - VU

*Nov. - Jan. 2021*, Python, Pyspark

#### Background
In the past many years, the development of information exchange
lead to the rapid spread of fake news on the internet. Fake news
may bring disastrous consequences and may plunge society into a
serious crisis. 

#### Task
In order to detect and eliminate fake news in the early stages to avoid social hazard and help people obtain the true information.

This project intended to use machine learning models (e.g., LSTM,
Bi-LSTM) to establish a fake news detection system. Simultaneously,
some optimizations (e.g., ensemble learning methods, trained
classifiers) were made as well. The result of our test showed that
our approach improved the performance of fake news detection on
specific dataset.

---

### CR2: Scientific Communities

Related Course: Large Scale Data Engineering(LSDE) - 2021 - VU

*Sep. - Nov. 2021*, Python, Pyspark

<!-- | Github:  -->

| Visualization: https://billysen.github.io/

#### Problem
Our project is to process and analyze the metadata of academic papers from <mark>CrossRef</mark> to create a directed graph that represents the mutual citation relationship between different academic papers or journals. Afterwards, a list of scientific communities will be established by using specific <mark>graph clustering algorithm</mark>. 

<mark>A scientific community</mark> means a group of researchers who work in a specific field and regularly publish at the same venues (e.g., the database research community publishes at VLDB, SIGMOD, ICDE, EDBT,
TODS, TKDE, and VLDBJ). 

#### Solution
It is worthy to analyze the characteristics of the directed graph of each scientific community to find the writing habits and other characters shared by researchers in a certain subject.

<!-- In general, we will analyze the 96GB json file to get the mutual citation of academic papers in CrossRef. After preliminary preprocessing, we found that only 44,672,628 records contained citation data of academic articles and can be utilize by this project (these valid records accounted for about 1/3 of all academic paper records). It is expected to use these metadata from CrossRef to complete the establishment of the relationship diagram, build scientific communities with graph cluster algorithm, analyze the characters of every single community, and evaluate the connections between several different communities. -->

#### Meaning
This project is quite useful and interesting. For scientific researchers, it is very necessary to understand the development and achievements of their research field.



---
# 📕 Undergraduate Projects

### Using Different Deep Learning Models to Detect COVID-19 

Thesis - Macau University of Science and Technology

Supervisor: Dr. Subrota Kumar Mondal

*Dec. 2020 - May. 2021* , Python 

| Github: https://github.com/TISNN/COVID

#### Purpose
The aim of this study is to build an early screening model using deep learning techniques to <mark>distinguish COVID-19 pneumonia</mark> from CT images of lungs in healthy cases, and to help doctors make rapid diagnoses and improve diagnostic eﬀiciency from an artificial intelligence perspective.

#### Methods
The publicly available <mark>COVID-19 CT image dataset</mark>. The data were collected mainly through CT images in photocopies and other public sources, and indirectly through hospitals and physicians. Various deep learning models were used to classify the CT images of new coronary pneumonia.

#### Results
Among several deep learning models for image classification, <mark>DResUnet</mark> had the best results with <mark>85.54% Accuracy and 87.02% AUC.

*Provide GUI

<!-- ![Healthy Lung](../../../static/img/Healthy%20lungs.png))![Infected Lung](img/../../../../static/img/COVID-Lung.png)![Grad-Cam](img/../../../../static/img/grad-cam4.jpeg) -->

<!-- <center class="half">
    <img src="../../../static/img/Healthy%20lungs.png" width="150"/><img src="img/../../../../static/img/COVID-Lung.png" width="150"/><img src="img/../../../../static/img/grad-cam4.jpeg" width="150"/>
</center>
<center>我是图片标题</center> -->

# 📕 Research

<!-- ![ss](/content/posts/project/School%20project/COVID-Lung.PNG) -->

### Stock Price Prediction Based on Artificial Neural Network

*Apr. 2020 - Feb. 2021* 

X. Kan, M. Miao, L. Cao, T. Xu, Y. Li and J. Jiang, "Stock Price Prediction Based on Artificial Neural Network," 2020 2nd International Conference on Machine Learning, Big Data and Business Intelligence (MLBDBI), 2020, pp. 182-185, doi: 10.1109/MLBDBI51377.2020.00040.

| Conferences: 2020 2nd International Conference on Machine Learning, Big Data and Business Intelligence (MLBDBI)

| Publisher: IEEE

| Link: https://ieeexplore.ieee.org/abstract/document/9360953

Researched on the <mark>judgment of stock price based on artificial neural network. 

The result of the experiment show that the model proposed in this paper can accurately judge the future price trend of stocks, and the model runs faster, which <mark>fundamentally solves the defects of the traditional forecasting methods of slow operation efficiency and low forecast accuracy.