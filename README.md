# Amazon_Vine_Analysis
## Overview

In this challenge, I used the US apparel product review from Amazon, with the goal to see if it be worth to subscribe to a Vine program if I were to sell similar apparel through this platform. I was able to use Pyspark to extract, transform and load the ETL data to my AWS RDS account in which I created.Using PPostgreSQL, I was able to query the data, create tables and create a CSV file.  From there, I used Pandas to extract the CSV file data, and then analized the the data.

## Resources
* Datasets - US Apparel Dataset from Amazon
* Software / Apps / Servers
  - Google Colab (to run PySpark)
  - Jupyter Notebook
  - Postgres
  - AWS S3
  - AWS RDS

Using AWS and Colab
Once I set up the RDS and S3 accounts on the Amazon platform, I used Pyspark to extract the dataset from an s3 in AWS. The dataset was then seperated into 4 different dataframes.  Once that was completed, I used Pandas to extract data to analize.

## PySpark Data

![image](https://user-images.githubusercontent.com/94253815/159140639-50e9de99-cef1-4fb1-859d-bd5ae8e66f42.png)


![image](https://user-images.githubusercontent.com/94253815/159140663-758dc643-5bd6-4721-97de-00b3398e1f9a.png)


![image](https://user-images.githubusercontent.com/94253815/159140770-828190e0-b6e5-4bc4-89e8-0061cb1efdf0.png)


![image](https://user-images.githubusercontent.com/94253815/159140812-c6b97874-0966-4dfa-ac0a-75391753ba77.png)


## Results

* Paid Vine Program
  * 33 Total Views
  * 15 5 Star reviews
  * 45.5% of Vine reviews were 5 Star

* Unpaid Reviews
  * 45,388 total reviews
  * 23,733 5 star reviews
  * 52.3% of unpaid reviews were 5 star

## Summary
  It doesn't appear the Vine program is is worth in the apparel category. There were only 33 total helpful reviews and half of them were 5 star rated (45%).Unpaid reviews that were 5 star rated came in at 52%Looking at the data, all indications point that the vine program is not a very popular category. It s not in the best interest financially to incentivizing people to write better reviews.
  We can look a bit further into this further and conclude that customers don't feel positively bias for leaving good or positive reviews in the paid program as there are so few and not so many well rated reviews. We analized the dat even further to calculate the mean of the each programs star rating to see if there is incentive.
  
  
  ## Further Analysis - Mean
  
  
  
  




