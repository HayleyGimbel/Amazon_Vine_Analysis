# Amazon_Vine_Analysis

# Overview of the analysis:
In this analysis I am using a dataset of music reviews to determine if there is any bias toward favorable reviews from Vine, an Amazon service that allows manufacturers and publishers to receive reviews for their products.  In order to perform this analysis I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in my dataset.

# Results:

VINE REVIEWS

NON-VINE REVIEWS

- How many Vine reviews and non-Vine reviews were there?
  - There were 7 Vine reviews and 96798 non-Vine reviews in the music reviews dataset. 

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There were 0 Vine reviews with 5 stars, and 61784 non-Vine reviews with 5 stars.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 0% of Vine reviews were 5 stars, and 63.83% of non-Vine reviews were 5 stars.

# Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
This analysis shows that there is not any positivity bias for reviews in the Vine program.  The number of music reviews that used the Vine program was very small, and there were 0 Vine reviews with 5 star reviews.  In comparison to non-Vine reviews, which contained 63.83% positive reviews, there is not a positivity bias for Vine reviews.  An additional analysis that I could do to support this statement would be to analyze the number of 4-star reviews included in each category to gauge if there are more positive reviews that aren't full 5-star reviews.  
