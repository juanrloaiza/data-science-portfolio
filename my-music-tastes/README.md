# Understanding my music tastes

Here I use data from the Spotify Web API to analyze my tastes in music.

I take the songs of my most listened artists and contrast them with general features of popular music. I use this to get insights into what is unique about the music I like.

According to this analysis, we can see the following patterns:

* I like energetic, like music.
* I like sadder music relative to top hits.
* Top hits are more danceable than my favorite artists' songs.
* The most important features that characterize my music are danceability and instrumentalness.

To do this, I use two approaches. In the first notebook I show how to get information from the Spotify Web API and run some general analyses using ```pandas```, ```seaborn```, and ```scipy.stats```. In the second notebook I run some ML models to try and identify the most relevant features distinguishing my tastes from popular music. I use ```sklearn``` and run:

* Logistic Regression
* Gaussian Naive Bayes
* K Nearest Neighors
* Decision Tree
* Random Forest
* Support Vector Classifier.