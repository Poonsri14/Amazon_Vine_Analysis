# Amazon_Vine_Analysis
Big Data-AWS, PySpark,SQL

## Overview of the analysis
To analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

 
## Results: 

#### Vine Table
![1](https://github.com/Poonsri14/Amazon_Vine_Analysis/blob/main/Resources/vine_table.png)

### Analysis for Vine Reviews and Non-Vine Reviews

#### Vine Reviews
![1](https://github.com/Poonsri14/Amazon_Vine_Analysis/blob/main/Resources/Paid.png)

#### Non-Vine Reviews
![2](https://github.com/Poonsri14/Amazon_Vine_Analysis/blob/main/Resources/Unpaid.png)


How many Vine reviews and non-Vine reviews were there?

    There were 463 of Vine reviews and 25094 of non-Vine reviews.


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

    The 5 stars for Vine reviews were 202 and the 5 stars for non-Vine reviews were 12033.


What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

    The percentage of Vine reviews were 5 stars are 43.63% and for non-Vine reviews were 5 stars are 47.95%



## Summary: 

    Base on the results above, we can see that there are almsot 50% positive bias for reviews in the Vine program. 
    However, if we compare with the non-Vine reviews, there are 4.32 percentages are less than non-Vine review. 
    To get more detail and support our analysis, we can use the dataset to combine 4 and 5 stars reviews for positive reviews 
    before making the decision if the Vine program is worth to pay for fee or not. 
    
    

