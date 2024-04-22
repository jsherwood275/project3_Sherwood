Project 3 - Sentiment Analysis

Purpose - The goal of this notebook is to use the Yelp Fusion API to download 30 business ID's and extract the reviews. The data will be cleaned using various techniques then exported into a clean data set file. Additionally, this will provide the command to explore the data set and to create plots to provide an analysis of the data.

Overall Question -  What is the sentiment analysis for NJ steakhouses with a rating of 3.0 or greater and over 100 reviews?

Problem Statement - Is there an inherent difference in the sentiment analysis when using 2 differnt analysis tools?

Summary - Download 30 business ID using the Yelp Fusion API (provided by the Professor) and extract the reviews.  Next, I will store the business and the reviews into a data frame so that the data can be reused without having to re-reqeust data from the API.  The data frame will be used to perform sentiment analysis using the default textblob and NaiveBayesAnalyzer.  The results will be diplayesd in a donut chart.  Finally, using the NLTK library to remove stop words I will display the top 20 words used in the reviews.

files
readme.md - this file
project3_sherwood.ipynb - notebook containing the ingestion, cleaning and analysis of Yelp reviews of NJ steakhouses.