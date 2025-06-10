![project](https://img.shields.io/badge/Project-Data%20Science-blueviolet)
![language](https://img.shields.io/badge/Language-Python-success)
![topics](https://img.shields.io/badge/Topics%20Covered-Data%20Manipulation%2C%20Data%20Visualization%2C%20Probability%20&%20Statistics%2C%20Importing%20&%20Cleaning%20Data-informational)

# The-Android-App-Market-on-Google-Play
**Loaded, cleaned, and visualized the scraped Google Play Store data to gain insights into the Android app market.**

### Project Description
---

Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this project, I have done a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. I have looked for insights in the data to devise strategies to drive growth and retention. The data for this project was scraped from the Google Play website. While there are many popular datasets for Apple App Store, there aren't many for Google Play apps, which is partially due to the increased difficulty in scraping the latter as compared to the former. The data files are as follows:

- **apps.csv:** contains all the details of the apps on Google Play. These are the features that describe an app.
- **user_reviews.csv:** contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed, passed through a sentiment analyzer engine and tagged with its sentiment score.

## Project Tasks
1. _**Google Play Store apps and reviews**_
2. **_Data cleaning_**
3. _**Correcting data types**_
4. **_Exploring app categories_**
5. _**Distribution of app ratings**_
6. **_Size and price of an app_**
7. _**Relation between app category and app price**_
8. _**Filter out "junk" apps**_
9. _**Popularity of paid apps vs free apps**_
10. _**Sentiment analysis of user reviews**_

📘 Project Description
In this project, I explored over 10,000 Android apps and their associated user reviews to understand factors that drive app popularity and user satisfaction. Using TextBlob, I extracted polarity and subjectivity scores from user reviews. I compared paid vs free apps, ratings, and categories to determine sentiment and retention strategies. The dataset was preprocessed and analyzed with the goal of producing actionable insights.

Data Files:

apps.csv: App metadata (category, size, rating, type, price)

user_reviews.csv: Pre-processed user reviews with sentiments

✅ Project Tasks
Load the app and the review data

Clean missing values and filter invalid entries

Engineer review length, polarity, and subjectivity

Normalize sentiment features

Analyze rating distribution by category and type

Plot review sentiment vs category using box/violin plots

Visualize sentiment with word clouds for positives and negatives

Train SVM model to classify sentiment (tuned via GridSearchCV)

Evaluate sentiment prediction with confusion matrix and reports

### The Jupyter notebook contains the answer (code) for all of the above tasks:

## Click [here](http://localhost:8891/notebooks/Resume%20Projects/Android%20App%20Market%20Analysis/Android%20App%20Market%20Analysis.ipynb) to check out
