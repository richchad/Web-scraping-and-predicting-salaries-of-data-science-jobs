# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 4: Web Scraping Job Postings

## Brief

You're working as a data scientist for a contracting firm that's rapidly expanding. Now that they have their most valuable employee (you!), they need to leverage data to win more contracts. Your firm offers technology and scientific solutions and wants to be competitive in the hiring market. Your principal has two main objectives:

   1. Determine the industry factors that are most important in predicting the salary amounts for these data.
   2. Determine the factors that distinguish job categories and titles from each other. For example, can required skills accurately predict job title?

To limit the scope, your principal has suggested that you *focus on data-related job postings*, e.g. data scientist, data analyst, research scientist, business intelligence, and any others you might think of. You may also want to decrease the scope by *limiting your search to a single region.*

---

## Summary

This project was an opportunity to put into practise data acquisition (via web scraping), exploratory data analysis and machine learning multinomial classification models and evaluation techniques.

Data science jobs were scraped from indeed.com (using requests and beautiful soup). NLTK was used to convert job descriptions into a data format suitable for modelling.

Experimented with logistic regression, decision trees, knn (with and without bagging).

Evaluated models feature importances, coefficient values, classification reports, confusion matrices and roc curves.

