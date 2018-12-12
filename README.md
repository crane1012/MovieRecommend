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

![picture2](https://user-images.githubusercontent.com/45834302/49903692-06c40980-fe36-11e8-98c1-c60a935336c0.png)

## Result

**The movies' rating that a specific user gave**  

![picture3](https://user-images.githubusercontent.com/45834302/49903780-47bc1e00-fe36-11e8-83d1-d8f338d4fbab.png)

**The movies' rating based on User-User Collaborative Filtering**  

![picture4](https://user-images.githubusercontent.com/45834302/49903784-4985e180-fe36-11e8-8753-5ab31727ff98.png)

**The movies' rating based on Item-item collaborative filtering**  

![picture5](https://user-images.githubusercontent.com/45834302/49903786-4b4fa500-fe36-11e8-81ae-0139009dafe8.png)

**The Predicted Rating vs Users Rating based on Item-based Recommendation System**  

![picture6](https://user-images.githubusercontent.com/45834302/49904013-e8aad900-fe36-11e8-91c3-f69052248c66.png)

## Future Works

* Cold-Start Problem, if we do not have enough data, there is no way for us to calculate the correlations
* We could using Bayesian approach by putting a prior to the average
* Optimize the time complexity of the algorithm
