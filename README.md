# GameIndx-Python-backend 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ce4CBL9h_X7-pQrt2Y1EPHku65Qe1qyt?usp=sharing)


  - This repo contains backend machine learning based scripts used for game analysis and recommendation for the project 
  - **GamerHood**, a web application built with **PySpark(Python)** (WIP) for game analysis and recommendations. This enables users to access game information and related content and, based on their behaviour, get suggested games. This utilizes the help of **MongoDB Atlas** for managing databases and algorithms like clustering, regression, recommendation engine for analysis. 
  - This repo also contains scripts used for scraping and cleaning all game related information from [Steam Official Website](https://store.steampowered.com/)
  - Compiled Dataset can be found here: [80000 Steam Games DataSet](https://www.kaggle.com/deepann/80000-steam-games-dataset)
  - Machine Learning Part has been implemented using **PySpark** and Database Handling part has been implemented using **MongoDB Atlas**
  - Recommendation using **Alternating Least Squares (ALS)** has been implemented on Game Data and Game User Data using PySpark
  - Dynamic Determination of Appropriate number of Clusters for K-Means Clustering using **Elbow Method** has been implemented
  
# Sample Plots Information
  
  - Linear and Decision Tree Regression has been implemented for review data of [**Among Us**](https://store.steampowered.com/app/945360/Among_Us/) Game. [View Plot](https://htmlpreview.github.io/?https://github.com/DeepanNarayanaMoorthy/GamerHood-Python-backend/blob/main/samples%20of%20generated%20plots/kmeans_plot.html)
  - KMeans Clustering has been Implemented for games related to [**GTA V**](https://store.steampowered.com/app/271590/Grand_Theft_Auto_V/) with respect to similar popular tags. [View Plot](https://htmlpreview.github.io/?https://github.com/DeepanNarayanaMoorthy/GamerHood-Python-backend/blob/main/samples%20of%20generated%20plots/final_regression.html)
    - Clustering Parameters Used
      - Number of Positive Reviews
      - Number of Negative Reviews
      - Price
  - WordCloud has been implemented for [**Fall Guys: Ultimate Knockout**](https://store.steampowered.com/app/1097150/Fall_Guys_Ultimate_Knockout/) Game

## These data can be obtained for any game by changing the game id inside the notebooks
 
