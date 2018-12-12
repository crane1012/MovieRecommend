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

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

