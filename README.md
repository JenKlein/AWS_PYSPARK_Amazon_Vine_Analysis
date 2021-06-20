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


## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

### Bias of Vine Reviews

In total, there were 248 vine reviews, and 17,514 non-vine reviews. Of these reviews, those that had 5-star ratings there were 102 (1.94%) vine reviews, and 5,154 (98.06%) non-vine reviews. Of all the total rating scores, those with 5-star paid ratings made up 0.6%, and those with 5-star unpaid ratings made up 29%. 


## positivity bias
There is insufficient evidence to determine if there is bias towards reviews written as part of the Vine program. Having a paid Vine reivew makes a difference in the percentage of 5 star reviews. 
In order to determine if having a paid vine review makes a difference in the percentage of 5 star reviews, more investigation would be necessary to how heavily the vine ratings are weighted. 

## one additional analysis that could be done
