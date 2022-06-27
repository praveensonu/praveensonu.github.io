---
layout: post
title: Predicting Web Article Genre
subtitle: Summary
categories: NLP
tags: [NLP, Python, Classification]
---

- Problem Statement: Predict the Web article genre (news, entertainment, publication etc) based on the url and content.
- Data is collected from 53000 web articles. Each article is categorized into their respective genres (news, publication) in a total of 9 genres
- TFIDF to vectorize the data. The problem is a supervised prediction, applied Logistic regression, Decision trees, Random forest and Naive Bayes.
- Cross validation to not over-fit data. Evaluation metric F1-score to find the best performing model.
- Pickled the best performing model and developed the backend API with Flask for the deployment.
- Deployed on heroku. [Web-Page-Classifier](https://web-page-classification.herokuapp.com).
