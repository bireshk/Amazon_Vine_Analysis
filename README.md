# Amazon Vine Analysis

## Analysis Overview
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members for different wireless products.

The analysis uses PySpark to perform the ETL process to extract the dataset by connecting to AWS RDS instance, then transform the data and finally load the transformed data into pgAdmin. Tha analysis also calculate different metrics.

## Results
### Total number of reviews
* Vine reviews
![total_paid_reviews](https://user-images.githubusercontent.com/62515666/135785336-130cc320-f539-4a1d-8a6d-652183eff0e7.png)


* Non-Vine reviews
![total_unpaid_reviews](https://user-images.githubusercontent.com/62515666/135785359-261aa458-67ef-4a1c-8565-072f8e4bca5b.png)


### Total number of 5-star reviews
* Vine reviews
![paid_five_star_reviews](https://user-images.githubusercontent.com/62515666/135785426-f3fb98c7-1ca8-4505-836b-3361683255eb.png)


* Non-Vine reviews
![unpaid_five_star_reviews](https://user-images.githubusercontent.com/62515666/135787070-34ce9e16-0cb5-4f79-aef0-3858722e6e60.png)


### Percentage of 5-star reviews
* Vine reviews
![percentage_five_star_reviews](https://user-images.githubusercontent.com/62515666/135787107-8cc978f8-ef19-4c1c-b6e2-5f0e491c72b6.png)


* Non-Vine reviews
![unpaid_percentage_five_star_reviews](https://user-images.githubusercontent.com/62515666/135787130-246a3dee-5b56-4061-920f-92ef844dd185.png)


## Summary
36% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is 47%. This describes no positivity bias for reviews in the Vine program.

Additionally, we could analyze the statistical distribution such as mean, median and mode of the star rating for the Vine and non-Vine reviews.

