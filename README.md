# Amazon_Vine_Analysis
# Overview
We pick up one of the datasets from "Amazon Review Datasets" and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We  use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset. 
# Results
### How many Vine reviews and non-Vine reviews were there?


### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
# Summary
### If there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement?
There is no positivity bias for reviews, as we can see that vine users gave only 36% five start' reviews. While non-vine users gave 47% of five star'reviews. This clearly shows that vine users havn't given any biased reviews. 

### Provide one additional analysis that you could do with the dataset to support your statement.
We can use the NLP and perform sentiment analysis on the dataset. We can find the biases in the reviews by analyzing the dataset.
