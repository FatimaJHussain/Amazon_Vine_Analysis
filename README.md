# Amazon_Vine_Analysis
# Overview
We pick up one of the datasets from "Amazon Review Datasets" and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We  use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset. 
# Results
### How many Vine reviews and non-Vine reviews were there?

Number of paid reviews are 613 and unpaid reviews is 64968, as shown in Figure-1.

Figure-1: Vine Reviews![Vine Reviews](https://github.com/FatimaJHussain/Amazon_Vine_Analysis/blob/main/reviews.png)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Figure-2: Vine 5 Stars Reviews![Vine 5 Stars Reviews](https://github.com/FatimaJHussain/Amazon_Vine_Analysis/blob/main/5star.png)

Number of vine reviews with 5 star ratings are 222 and non-vine reviews with 5 star ratings are 30543, as shown in Figure-2.


Figure-2: Vine 5 Stars Reviews![Vine 5 Stars Reviews](https://github.com/FatimaJHussain/Amazon_Vine_Analysis/blob/main/5star.png)
### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

Figure-3: Percetage of 5 Stars Reviews![Percetage of 5 Stars Reviews](https://github.com/FatimaJHussain/Amazon_Vine_Analysis/blob/main/percentage.png)

# Summary
### If there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement?
There is no positivity bias for reviews, as we can see that vine users gave only 36.2% five start' reviews. While non-vine users gave 47% of five star'reviews. This clearly shows that vine users havn't given any biased reviews. 

### Provide one additional analysis that you could do with the dataset to support your statement.
We can use the NLP and perform sentiment analysis on the dataset. We can find the biases in the reviews by analyzing the dataset.
