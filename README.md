# Sentiment-Analysis

## Problem Statement
"Develop a machine learning model to classify app reviews into five categories. The goal is to accurately identify user sentiment and help app developers and businesses understand customer feedback. The dataset includes reviews from various categories and sources, and participants will be evaluated based on their model's accuracy and performance on a held-out test set."

## Analysis

The dataset I’m using for the task of product reviews sentiment analysis was downloaded from Kaggle. This dataset contains the product reviews of over 21,000 customers who have purchased products. So let’s see what the data looks like:

![train](https://user-images.githubusercontent.com/63037914/232194121-e2e6af20-86e7-413a-aa56-8de036193611.jpg)

Now, let’s take a look at the rating breakdown to see how most customers rate the products:

![distri](https://user-images.githubusercontent.com/63037914/232194119-f10fdfb5-e3b9-405f-ba8e-ec229cb51d23.jpg)

## Text Preprocessing

In order to correcttly analyse the sentiments, we have to do some text preprocessing in order to convert the text into normalize format.

![pre](https://user-images.githubusercontent.com/63037914/232194382-a3a56fa5-7573-45fc-8e38-5a5fe4408339.jpg)

## Model and Accuracy

I have made use of SVM in my text analysis and have obtain an accuracy of <b> 92.9% </b> which shows that my model is able to correctly predict the rating given by the user based on its review approx 93% of time.
