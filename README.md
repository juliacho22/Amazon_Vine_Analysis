# School_District_Analysis
## Overview 
This project analyzes the Amazon reviews written by members of the paid Amazon Vine program using a subset of data that pertained to the video game subcategory. An ETL analysis was completed using AWS, Google Colaboratory, PostgreSQL, and PySpark. 

## Results 
- How many Vine reviews and non-Vine reviews were there? \
There are 94 vine reviews and 40,471 non-vine reviews for a total of 40,565 reviews. \
![vinereviews](https://github.com/juliacho22/Amazon_Vine_Analysis/blob/main/images/vinereviews.PNG) 

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?\
![5starreviews](https://github.com/juliacho22/Amazon_Vine_Analysis/blob/main/images/5starreviews.PNG) 

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? \
51.06% of paid reviews are 5-stars and 38.7% of unpaid reveiws are 5-stars. \
![paidreviews](https://github.com/juliacho22/Amazon_Vine_Analysis/blob/main/images/paidreviews.PNG) 

## Summary
Based on the analyusis, one can see that there is a positivity bias for reviews in the Vine program. The non-vine sample size was very large, and the vine sample size was less than 100 entries leading to a less signifcant result. To further the analysis, one could look into the percentage of those who bought the product by filtering the "verified_purchase" column to further confirm the positivity biase for reviews in the Vine program. 


