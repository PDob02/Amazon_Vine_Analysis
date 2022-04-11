# Amazon_Vine_Analysis
## Module 16 Big Data ## 
### Overview of the analysis: Explain the purpose of this analysis. ###

In this week's task we were asked to work with PySpark, PostgreSQL, Google Colab, & AWS to Extract, Transform & Load data. The dataset that I chose from AWS was video game reviews from a few years ago. We analyzed a paid service called Vine versus unpaid video game reviews. This work was primarily done in PySpark. This can be applied to many instances of Big Data. 

![](https://github.com/PDob02/Amazon_Vine_Analysis/blob/main/Images/Product_Table.png)

* How many Vine reviews did you analyze? There were 90 vine reviews that we determined were useful based on the frequency of reviews

* How many Vine reviews were 5 stars? There were 44 5 Star reviews from the Vine (paid) users. 

* How many non-Vine reviews were 5 stars? Since this sample size was larger there were 14704 unpaid reviews that rated 5 stars.

* What percentage of Vine reviews were 5 stars? The vine (paid) review percentage came in at around 48.8%. 

* What percentage of non-Vine reviews were 5 stars? The unpaid reviews came in at 38.8%. 

![](https://github.com/PDob02/Amazon_Vine_Analysis/blob/main/Images/Star_Rating.png)

![](https://github.com/PDob02/Amazon_Vine_Analysis/blob/main/Images/Greater_than_20_reviews.png)

Summary: There could possibly be a statistical significance to the vine reviews. Further analysis might require a stastical "p-value" test or greater amounts of data from the vine reviewers since there were only 90 samples in that bucket. Additionally, the Vine group may not be a controlled group since they were being compensated monetarily and may give a favorable review to be invited to review again. Overall, we were able to  sample large swaths of big data and produce usable dataframes to back up our assumptions. 

![](https://github.com/PDob02/Amazon_Vine_Analysis/blob/main/Images/Vine_Reviews.png)