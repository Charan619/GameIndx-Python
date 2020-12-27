# GamerHood-Python-backend

  - This repo contains backend scripts used for game analysis and recommendation for the project GamerHood
  - This repo also contains scripts used for scraping and cleaning all game related information from [Steam Official Website](https://store.steampowered.com/)
  - Compiled Dataset can be found here: [80000 Steam Games DataSet](https://www.kaggle.com/deepann/80000-steam-games-dataset)
  - Machine Learning Part has been implemented using **PySpark** and Database Handling part has been implemented using **MongoDB Atlas**
  - Recommendation using **Alternating Least Squares (ALS)** has been implemented on Game Data and Game User Data using PySpark
  - Dynamic Determination of Appropriate number of Clusters for K-Means Clustering using **Elbow Method** has been implemented
  
# Sample Plots Information
  
  - Linear and Decision Tree Regression has been implemented for review data of [**Among Us**](https://store.steampowered.com/app/945360/Among_Us/) Game
  - KMeans Clustering has been Implemented for games related to [**GTA V**](https://store.steampowered.com/app/271590/Grand_Theft_Auto_V/) with respect to similar popular tags.
    - Clustering Parameters Used
      - Number of Positive Reviews
      - Number of Negative Reviews
      - Price
  - WordCloud has been implemented for [**Fall Guys: Ultimate Knockout**](https://store.steampowered.com/app/1097150/Fall_Guys_Ultimate_Knockout/) Game

## These data can be obtained for any game by changing the game id inside the notebooks
 
