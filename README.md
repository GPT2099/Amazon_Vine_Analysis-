# Amazon_Vine_Analysis

## Overview 
- This challenge was to take an Amazon data set of both paid and unpaid video game reveiws and to analize and find any difference in paid/unpaid reviews. 

__Tools:__ 
  * PySpark 3.1.1
  * pgAdmin 4.29 and PostgreSQL 
  * Amazon RDS (AWS Console)

## Results 

1) How many Vine review and non-Vine reviews are there?
 - There are 94 paid vine reviews vs 40565 un-paid reviews.
2) How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
 - The total paid membership 5 start reviews are 48. The total 5 star reviews is 15711. 
3) What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
 - 0.3% of the Vine reviews are 5-stars, the 99.7% remaing percentage is for non-Vine people that were un-paid.
 
## Summary 
The data suggests there is no evidence for a positive bias and increased ratings due to membership. With only 0.3% of 5 star reviews being made my members, this is not sufficient informartion required to suggest a positive bias. Further analysis could start by repeating this process for the remaining rating levels (stars) to compare and contrast these percentages. 


