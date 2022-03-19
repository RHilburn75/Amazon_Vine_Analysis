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

