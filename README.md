# Online Article Success Predictor: A Binary Classification Project
## Project Overview
A machine learning project to predict whether an online article will be "popular" using the UCI Machine Learning Repository's Online News Popularity dataset. This project focuses on essential data science skills while maintaining practical business value.

Fernandes, K., Vinagre, P., Cortez, P., & Sernadela, P. (2015). Online News Popularity [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5NS3V.

## Business Problem
Content creators need a simple way to predict if their articles will achieve high engagement before publication.

* Binary prediction: Will the article be popular (high shares) or not?
    * If greater than 14,0000 shares and then considered popular. The Orignal paper finds Random Forest modelling the best performing relative to AdaBoost. SVM, KNN & NB
* Understand basic factors that influence article success
* Get clear yes/no guidance for content decisions

## Dataset
Source: UCI Machine Learning Repository (Mashable articles)
Size: 39,644 articles
Target: Binary (Popular/Unpopular) based on share count threshold
Key Features: Content metrics, timing, topic categories

## Project Steps
### Initial Data Processing
* Set  popularity threshold (using median shares)
* Select top 8-10 most relevant features
* Basic data cleaning

### Basic Model Development
* Use Random Forest Classifier (best performer from research paper)
* Simple train-test split
* Focus on accuracy and ROC-AUC metrics

### Simple Analysis
* Basic feature importance visualization
* Correlation matrix
* Top 3-5 recommendations for content creators

### Tools
* Python
* Pandas
* Scikit-learn
* Matplotlib/Seaborn

### Expected Timeline
* Week 1: Data preprocessing and model building
* Week 2: Analysis and documentation

### Deliverables
* Jupyter notebook with documented code
* Simple model predicting article success
* Basic visualizations of key findings
* Brief recommendations for content creators
