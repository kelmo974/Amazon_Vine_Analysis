# Amazon_Vine_Analysis
Using AWS S3 bins and RDS instances connected to PostgreSQL.


## Purpose
This analysis was conducted to explore the validity of reviews. Are those that come from a required review through a paid service skewed in any manner with respect to "general population" reviews. The vast majority of Amazon come from outside of the Vine program, so there is never any monetary incentive to leave a review for the average shopper. 

Employing Pyspark and AWS isntances coupled with a familiar RDS - PostgreSQL, a dataset stemming from sporting goods sold on Amazon was analyzed with a mind to highlight differences among reviews as previously mentioned. Some familiar concepts, such as assignming arrays to lists and creating tables was required, but the Pyspark environment calls for a slightly different nomenclature than prior Pandas experience, so there was a stagnation and self-teaching inolved here.

## Results
There were a total of 61948 revies in the dataset.

There were a total of 32,804 5-star reviews. 99.6% of those were unpai - or 32,665 reviews were outside of Vine. The remaining 0.4% was through a Vine program account. 139 other 5-star votes came paid through Vine.

## Summary
Such a small number of vine reviews being 5-star allows for the analyst to draw a conclusion that the Vine program introduces little, if any bias, to reviews. Otherwise, there would be a substantial increase in the % of 5-star reviews.
