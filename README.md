# Amazon_Vine_Analysis
week 17 challenge


## Overview of the analysis

The Amazon Vine program is a service we off to manufacturers and publishers to get reviews for their products by analyzing Amazon reviews written by members of the paid Amazon Vine program.

We will use the AWS RDS service to host our database which is instanced using PostgreSQL using PGAdmin4 as the interface. PySpark will be used to extract, transform, then load the data on to our RDS.

From the data uploaded to our RDS, we will extract the vine_table data to answer analytical questions.

## Results


* How many Vine reviews and non-Vine reviews were there?
    There were a total of 1,785,997 reviews in total. Of the total amount of reviews, 4,291 of them were Vine users.

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    48 Vine reviews scored the products with 5 stars. 
    15,663 non-Vine reviews scored the products 5 stars.

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    1.12% of Vine reviews were 5 star.
    0.88% of non-Vine reviews were 5 star. 

## Summary

There is a very small amount of bias from Vine members given the data provided; there is only a .24% difference between Vine and non-Vine 5 star reviews. It is also notable that both Vine and non-Vine reviews are very close to 1%, which may infer that Vine members and non-Vine react almost identically to the product.

In the future, it may be beneficial to do a few one-tailed T-tests on the Vine members 5 star ratings to see if the probability is actually around 1.12%. 


