# Disaster Response Pipeline Project

### Table of Contents

1. [Project Motivation](#motivation)
2. [Project Description](#description)
3. [Requirements](#requirements)
4. [Files Descriptions](#files)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Motivation<a name="motivation"></a>

This project is part of the Data Science Nanodegree Program by Udacity in collaboration with IBM. The dataset contains users interactions with articles on the IBM Watson Studio platform, the aim of this project is to make recommendations that users may like.

## Project Description <a name="description"></a>

This project focus in analyze the users interactions in the IBM Watson Studio and make recommendations based there interactions in the platform and it's divided into 4 parts:

### I. Exploratory Data Analysis

Before making any recommendations, it's necessary to explore the data first. There are few basic questions that need to be answered about the data presented in this project. In the notebook, you can find some basic statistics that will help further in the later sections.

### II. Rank Based Recommendations

To iniciate the recommendations, it's showed the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users.

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

### IV. Matrix Factorization

Finally, we have complete machine learning approach to building recommendations. Using the user-item interactions, we have a matrix decomposition. Using that decomposition, we get an idea of how well it's predicting new articles that individuals might interact with (spoiler alert - it isn't great).

## Requirements <a name="requirements"></a>

The code should run with no issues using Python versions 3 with the following libraries: 
  - Machine Learning: NumPY, Pandas
  - Model Loading and Saving: Pickle
  - Data Visualization: Plotly

## File Descriptions <a name="files"></a>

- **Data**
  - articles_community.csv + user-item-interactions.csv - *Datasets with all the necessary informations*
  - Recommendations_with_IBM.ipynb - *File with recommendations codes*
  - Recommendations_with_IBM.html - *Copy of the ipynb file in html*
  - top_10.p, top_20.p, top_5.p, user_item_matrix.p - *lists and matrix for checking the recommendation code*

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to IBM Watson Studio for the data. Also, thank you Udacity for the training! Otherwise, feel free to use the code here as you would like! 
