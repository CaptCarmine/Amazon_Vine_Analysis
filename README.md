# Amazon_Vine_Analysis

## Overview

Use Pyspark in google colabs to pull data from an amazon reivew dataset.(see following https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt). Use the ETL process to clean the data and find the difference in reviews, when users pay or don't for a reviewing service.

## Results

Looking at the results. we can see that a total of 40,565 products have at least 20 twenty reviews, with at least half of them being helpful.

![Total_Vines](https://github.com/CaptCarmine/Amazon_Vine_Analysis/blob/main/Images/Total_vines.png?raw=true)

of those only a small percentage, have used this paid service for the video game industry. Of the 94 games which paid for this service, more than 50 % of those games got a 5 star review.

![Paid vines](https://github.com/CaptCarmine/Amazon_Vine_Analysis/blob/main/Images/paid_vines.png?raw=true)

A much larger number of games did not pay for this service. and Of those only 38% got a 5 star reivew. 

![unpaid vines](https://github.com/CaptCarmine/Amazon_Vine_Analysis/blob/main/Images/unpaid_vines.png?raw=true)

## Summary

Looking at the data, We can notice that they have a higher rate of 5 star reviews, but I would state since there are only 94 points of data for the vine service It would be hard to say there is a statistical proof that the service has a positive bias on the product review. 

If we were to go deeper we can do a AI analysis of the words in the reviews for the 5-star products versus the products with a lower rating.
