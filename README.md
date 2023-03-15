---
title: Topic Modelling LinkedIn Job Descriptions and Reddit Posts
---

# **Project Title**
My project analyzes topics in Reddit posts and job descriptions to identify areas of overlap.

## **Technology Used**
- Python 3
- PRAW, Beautiful Soup
- NLTK, gensim
- PCA, kMeans
- MySQL
- Google Cloud
- pandas, numpy

## **Methods Used**
- Machine Learning
- Data Visualization 
- Data Preprocessing
- Data Scraping
- Data Storage

## **Projecy Description**
### **Part 1: Scraping Reddit Posts**
I used the PRAW library in Python to scrape Reddit posts and store them in a MySQL database. In addition to the post title and body, I also scraped the top 3 comments on each post, post score, and post date.

### **Part 2: Analyzing Reddit Post Bodies**
In a separate Python script, I analyzed the scraped post bodies using the NLTK library to identify word frequencies. I then used an LDA model to identify topics within the posts.

### **Part 3: Scraping Job Descriptions**
I used the Beautiful Soup library in Python to scrape job descriptions from linked job postings in the USA. I then used an LDA model to identify topics within the job descriptions.

### **Conclusion**
By comparing the topics identified in the Reddit posts and job descriptions, I was able to identify areas of overlap and potential areas for further exploration.