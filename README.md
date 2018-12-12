# Movie Recommendation System using the MovieLens data set

**CSC 440 Final Project**  
**Instructor:** T. F. Pawlicki, PhD  
**Team Member:** Haoyu Li &Zenghe Huang  
**Date:** 12/12/2018  

## Objective

* The main objective of this project is to build the Movie Recommendation Systems using the MovieLens data set. 
* The recommendation system shall predict the ratings of a movie that the user haven’t seen yet.
* Using both user-user approach and item-item approach.

## Approach

The problem was divided into several steps:

1. **Data preprocessing:** Data was relabeled, shrinked, converted to HashMaps, and get rid of useless information.
2. **User-User Collaborative Filtering:** The algorithm uses that logic and recommends items by finding similar users to the active user to whom we are trying to recommend a movie.
3. **Item-item collaborative filtering:** The algorithm chooses items for a user, because this user has liked similar items in the past.
4. **WordCloud:** The font size is larger as the frequency of the keywords increase.

![picture1](https://user-images.githubusercontent.com/45834302/49903367-fc554000-fe34-11e8-925a-335c80380114.png)

### Similarity

**Using Pearson Correlation Coefficient**

