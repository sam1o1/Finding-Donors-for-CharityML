# Finding Donors for CharityML
## Table of Content:

 - [Project Overview](#overview)
 -  [Installation](#installation)
 - [File Descriptions](#files)
 - [Get Started](#get_start)
 - [Findings](#finding)
 - [Licensing  and Authors](#L&A)
  
<a name="overview"></a>
## Project Overview 
CharityML is a fictitious charity organization located in the heart of Silicon Valley that was established to provide financial support for people eager to learn machine learning. After nearly 32,000 letters were sent to people in the community, CharityML determined that every donation they received came from someone that was making more than $50,000 annually. To expand their potential donor base, CharityML has decided to send letters to residents of California, but to only those most likely to donate to the charity. With nearly _15 million_ working Californians, CharityML has brought you on board to help build an algorithm to best identify potential donors and reduce overhead cost of sending mail. Your goal will be evaluate and optimize several different supervised learners to determine which algorithm will provide the highest donation yield while also reducing the total number of letters being sent. 
<a name="installation"></a>
## Installation
In order to run this project you need to install:
This project uses the following software and Python libraries:

-   [Python](https://www.python.org/downloads/release/python-364/)
-   [NumPy](http://www.numpy.org/)
-   [pandas](http://pandas.pydata.org/)
-   [scikit-learn](http://scikit-learn.org/0.17/install.html)  (v0.17)
-   [Matplotlib](http://matplotlib.org/)

You will also need to have software installed to run and execute a  [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the  [Anaconda](http://continuum.io/downloads)  distribution of Python, which already has the above packages and more included.

<a name="files"></a>
## File Descriptions
* `finding_donors.ipynb`: This is the main file where you can find  the project.
* `census.csv`: The project dataset. You'll load this data in the notebook.
* `visuals.py`: This Python script provides supplementary visualizations for the project. Do not modify.
 ## Get Started
 <a name="get_start"></a>
Use the following command to download the files : 

    gut https://github.com/sam1o1/Finding-Donors-for-CharityML

<a name="finding"></a>
## Implementation 
After exploring and transforming the data to make it ready for being used to be fed into ML algorithms. Three ML classifiers were:

 1. Logistic Regression 
 2. Decision Tree
 3. Naive Bayes 

![image](https://github.com/sam1o1/Finding-Donors-for-CharityML/blob/main/Finding%20Donors%20For%20CharityML/Visuals/results.jpg?raw=true)

it can be observed from the above results that in terms of the accuracy on the three different sizes of the training set, the decision tree classifier did very well. It too performed well in terms of the F-score. However, the results were on the training data which is something that the algorithm already has heard of before in the training process. Moreover, the computational cost for each classifier implied that the Naive Bayes is the greatest among the three classifiers.

For the test set, the computational cost of the Naive Has significantly increased. The accuracy score for the logistic regression in terms of both the accuracy score and the F_score has outperformed the other two.

In conclusion, the Logistic regression is the best model so far.

<a name="L&A"></a>
## Licensing  and Authors
Author : Eslam Abdelghany

Email: eslam322_1@hotmail.com
