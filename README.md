### Table of Contents

1. [Introduction](#introduction)
2. [File Descriptions](#descriptions)
3. [Dependencies](#installation)
4. [Conclusion](#conclusion)
5. [Licensing, Authors, and Acknowledgments](#licensing)

## Introduction<a name="introduction"></a>
# Recommendation_Systems_IBM_Project_3
This is the third project of my Udacity Data Science Nano Degree. In this project, I will be creating a recommendation systems for IBM Watson platform. The idea that I will be investigate the the interactions between users and the articles on this platform and then based on this I would recommend new articles to the user that he/she might like. 

To be able to create such a recommendation system, i will be exploring the most popular techniques like, Rank Based, User-user based Collaborative recommendations and I will also be investigating the Matrix Factorization techniques. 


## File Descriptions<a name="descriptions"></a>

Below is the file structure of this project.

```bash
├── README.md
|
├── data
│   ├── articles_community.csv # database representing the details about articles.
│   ├── user-item-interactions.csv # dataset representing the interactions between users and articles
│   
│── Recommendations_with_IBM.ipynb # Recommendation system notebook
│   
|── project_tests.py #test file 
|
|── top_5.p
│   
|── top_10.p
│   
|── top_20.p
│   
└── user_item_matrix.p
```   

- The **data** folder contains the  **articles_community.csv** and **user-item-interactions.csv** files which represents the dataset used in this project.

- The **Recommendations_with_IBM.ipynb** file contains the code for the recommendation system. 

- The **project_tests.py** is a test file which is used to run tests through out the notebook.

- The **top_5**, **top_10**, **top_20**, **user_item_matrix** are teh files used to run tests on the code.


#### Dependencies

Following packages and python libraries were used in this project:
- pandas
- numpy
- sklearn.metrics
- pickle
- scikit-learn
- matplotlib.pyplot


## Conclusion<a name="conclusion"></a>
In the end i would like to say that recommedations engines are in every technology that we use nowadays, let it be, Facebook, Google, Amazon, Netflix and the list goes on. There are many different approaches to creat a recommendation system e.g. rank based, user-user collaboration based, item-item collaborations based, content based and the so many more.So, is no single best approach to have when you are creating a recommendation engine because depending on the use case you might need to use combinaition of approaches or may be you would need only one particular appraoch only. 
As a data scientist, it is a great skill to know how to create a recommendation system


## Licensing, Authors, and Acknowledgments<a name="licensing"></a>

This project was made possible by IBM. for providing the dataset and Udacity, for providing us such a great platform for learning.
Feel free to use my code in any of your projects

Enjoyyy.
