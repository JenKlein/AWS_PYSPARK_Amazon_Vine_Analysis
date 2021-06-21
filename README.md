# AWS_PYSPARK_Amazon_Vine_Analysis


## Overview
The purpose of this project was to analyze the Amazon reviews written by members of the paid Amazon Vine program on Software products. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products - in this project we're analyzing reviews on software products. The Software review data was extracted from AWS, transformed in Google Colab with PySpark and loaded in to pgAdmin.


### Resources
* PySpark
* Postgres SQL
* AWS
* Google Colab


## Results

### Customers Table
![Screen Shot 2021-06-19 at 1 35 56 PM](https://user-images.githubusercontent.com/69849998/122683363-9fd4f780-d1cc-11eb-82a5-1b47959aa2f1.png)

### Products Table
![Screen Shot 2021-06-19 at 1 35 46 PM](https://user-images.githubusercontent.com/69849998/122683369-a5cad880-d1cc-11eb-8cc6-1eddee6fa177.png)

### Review ID Table
![Screen Shot 2021-06-19 at 1 35 37 PM](https://user-images.githubusercontent.com/69849998/122683372-a8c5c900-d1cc-11eb-8e6b-90da2827cceb.png)

### Vine Review Table
![Screen Shot 2021-06-19 at 1 35 25 PM](https://user-images.githubusercontent.com/69849998/122683374-ae231380-d1cc-11eb-8124-7da3465d2dc5.png)


## Summary

### Paid Reviews with 5 star ratings
<img width="656" alt="Screen Shot 2021-06-20 at 9 18 17 PM" src="https://user-images.githubusercontent.com/69849998/122694956-0e39aa00-d20d-11eb-8a40-16c8908a5abe.png">

### Unpaid Reviews with 5 star ratings
<img width="655" alt="Screen Shot 2021-06-20 at 9 19 55 PM" src="https://user-images.githubusercontent.com/69849998/122695016-44772980-d20d-11eb-9a94-67767486820a.png">

#### Bias of Vine Reviews
In total, there were 248 vine (paid) reviews, and 17,514 non-vine (unpaid) reviews. Of these reviews, those that had 5-star ratings there were 102 (1.94%) vine reviews, and 5,154 (98.06%) non-vine reviews. Of all the total rating scores, those with 5-star paid ratings made up 0.6%, and those with 5-star unpaid ratings made up 29%. 

With 98.06% of 5 star reviews from unpaid customers, this shows that there was no positivity bias in the 5 stars review. In other words, the fact that people were paid did not bias the reviews. The fact that the overwhelming majority of reviews came from unpaid customers demonstrates that people were so satisfied with their software products that they did not require payment to leave a 5 star review. 

Since the 5star unpaid reviews made up 29% of all of the reviews, it would be interesting to perform the same percentage calculations for each star rating to see the distribution of the reviews. 


