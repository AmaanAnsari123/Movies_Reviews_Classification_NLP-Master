# Movies_Review_Classification_NLP

<h3>Dataset Link : https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews</h3>
<br>

<h3> Deployment Link : https://movies-reviews-classifier.herokuapp.com/ </h3>
<br>

This project involves building an end-to-end Sentiment Analysis application using Natural Language Processing (NLP) techniques. The primary goal is to classify movie reviews as positive or negative using TF-IDF vectorization and a Naïve Bayes classifier.

Key Steps in the Project:
Data Preprocessing: Applied stemming to process text and converted it into numerical features using TF-IDF.
Model Training & Selection: Trained a Naïve Bayes classifier and tested different models to find the best-performing one.
Model Serialization: Saved the trained model as a .pkl file for later use.
Flask-Based Web Application:
Built a Flask app to serve predictions via a simple web interface.
Created home.html for input submission and result.html to display predictions.
The app takes a user’s review as input, processes it, and returns the sentiment prediction.
REST API Integration:
The application exposes a POST endpoint (/predict) that takes text input and returns a sentiment prediction.
<br>
<h1> Working of Movies Reviews Classifier</h1>
<br>
<img class="gif" src="img/work.gif" alt="happy Image" , height="400" , width="400">
<br>
<h1> Thank You !!!!!!!!!!!</h1>
