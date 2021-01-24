# Amazon_Vine_Analysis
---

## Overview of the analysis of the Vine program:
---
The purpose of this analysis was to create an Amazon RDS and create a connectoin to our local PGadmin. Using these two as well as using PySpark and SQL, I downloaded a dataset of my liking. I chose to work with the video game dataset. Using this dataset, we created 4 dataframes, the review_id, customers, products and vines dataframe. These dataframes were modified to match SQL tables created within PGadmin on our AWS server.

The second part of the analysis was to distinguish the number of paid and unpaid reviews, and from each subset, how many reviews were 5-stars.

## Results:
---
The results of this analysis answer the following questions:

- How many Vine reviews and non-Vine reviews were there?

There were 40,471 unpaid reviews and 94 paid vine reviews.

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

The number of paid 5-star reviews is 48, a little over 50% of total number of paid reviews.

The number of unpaid 5-stars is 15,663 nearly 39% of of the total number of unpaid reviews.

See the following [images](https://github.com/evflores001/Amazon_Vine_Analysis/tree/main/images) for reference.

## Summary:

These findings indicate that theres is a minor bias in reviews for paid vs unpaid reviews. Paid reviews tend to fair better than unpaid reviews.

However, these findings can, and should be invistigated further as the this was just from one of the several datasets. An additional analysis would be to replicate the same steps in different datasets to see if perhaps the category of the review might affect the number of reviews.
