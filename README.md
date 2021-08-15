# School_District_Analysis
## Overview 
This project analyzes the Amazon reviews written by members of the paid Amazon Vine program using a subset of data that pertained to the video game subcategory. An ETL analysis was completed using AWS, Google Colaboratory, PostgreSQL, and PySpark. 

## Results 
- How many Vine reviews and non-Vine reviews were there?
There are 94 vine reviews and 40,471 non-vine reviews for a total of 40,565 reviews. \
* add image here

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were 48 5-star vine reviews and 15663 5-star non-vine reviews for a total of 15,711 5-star reviews. \
* add image here

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? 
51.06% of paid reviews are 5-stars and 38.7% of unpaid reveiws are 5-stars. \
* add image here

## Summary
Based on the analyusis, one can see that there is a positivity bias for reviews in the Vine program. The non-vine sample size was very large, and the vine sample size was less than 100 entries leading to a less signifcant result. To further the analysis, one could look into the percentage of those who bought the product by filtering the "verified_purchase" column to further confirm the positivity biase for reviews in the Vine program. 


