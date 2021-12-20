# Amazon_Vine_Analysis

## Overview

To analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Resources
- PySpark to extract the dataset, transform the data, connect to AWS RDS instance and load the transformed data into pgAdmin.
- Google Colaboratory to import PySpark libraries and connect to Postgres in order to create SQL tables and export the results.

## Results

1. How many Vine reviews and non-Vine reviews were there?


![review](https://github.com/11nithin/Amazon_Vine_Analysis/blob/main/Images/Vine%20reviews%20and%20non-Vine%20reviews.JPG)

- 2.1% (1080) reviews were made by vine members and 97.9% reviews were non vine members

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Vine members gave 454 out of 1080 reviews a 5 star rating.
- Non Vine members gave 23,034 out of 49,659 reviews a 5 star rating

3.  What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 42% of the reviews for Vine members were rated 5 stars.
- 46.4% of the reviews for Non-Vine members were rated 5 stars.


## Summmary 

5 star rating for vine members was about 10 % less than Non vine members. It tells Vine members did not show bias when rating thier products. Vine customers seems more accurate when submitting there reviews.  To get a better idea we should include all of the data rather than filtering it to a percentage of helpful vs total votes as we did for this analysis.


![summary](https://github.com/11nithin/Amazon_Vine_Analysis/blob/main/Images/additional%20summary.JPG)
