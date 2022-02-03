# Amazon_Vine_Analysis

## Purpose
The purpose of this analysis was to gain better familiarity with ETL using big data. Using Amazon AWS RDS, pgAdmin, and PySpark, we were able to extract, transform and load thousands of Amazon reviews for watches to determine if there's a positivity bias for reviews that are in the Vine program vs. reviews from non-Vine members. Members of Vine are chosen by Amazon based on the helpfulness, thoroughness, and impact of their reviews. And for those reasons, they are given products by companies to use and review. And we chose reviews on watches for our ETL and positivity bias analysis. 

## Results
As we see in the screen shot below, there's 8343 total reviews from non-Vine reviewers, and 47 that are from Vine reviewers. 4318 of the 8343 non-Vine reviews gave a 5 star review, which is just over 51 percent of the total. Meanwhile, 15 of of the 47 Vine member reviews were 5 star, or around 32 percent. 


<img width="573" alt="Del  16 reviews" src="https://user-images.githubusercontent.com/90881705/152235629-ae117f78-b826-4bef-a3df-f372590ccb7e.png">


## Summary 
Given the data we have, we can safely determine there isn't a positivity bias when it comes to whether a review is from a Vine member or not. Just under a third of Vine reviews are 5 star, compared to just over half of the non-Vine reviews being 5 star. It would seem Vine reviewers are more critical and discerning. WIth that in mind, recommendeded additional analysis would be to perform similar ETL for 1 star reviews. The theory being Vine member reviews would be a larger percentage of their total reviews than non-Vine reviews. 
