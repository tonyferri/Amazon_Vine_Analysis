# Amazon_Vine_Analysis
Module 16 Challenge

## Overview of the Analysis:
The purpose of this exercise was to analyze Amazon reviews written by Amazon Vine program members and determine if there is any bias included in their reviews.

## Results:
* How many Vine reviews and non-Vine reviews were there?
  * 60 Vine reviews
  * 14,477 non-Vine reviews
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  * 34 5-Star Vine reviews
  * 8,212 5-Star non-Vine reviews
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  * 56.67% of Vine reviews were 5-star
  * 56.72% of non-Vine reviews were 5-star
* Was there positivity bias for reviews in the Vine program?
  * Considering the percentages were almost identical, there was no bias in regards to the Vine program with 5-star reviews
* Further analysis:
  * It would be benefecial to try and increase the sample size.  One way to do this would be to include 4-star reviews as well.  I created one more step filtering by both 4-star and 5-star reviews and the results were the following:
    * 83.33% of Vine reviews were 5-star
    * 75.28% of non-Vine reviews were 5-star
  * As we increase the sample size, the potential for bias seems to increase as well.

## Pics:

[vine data df](https://github.com/tonyferri/Amazon_Vine_Analysis/blob/main/resources/vine%20data%20df.png);

[twenty total votes df](https://github.com/tonyferri/Amazon_Vine_Analysis/blob/main/resources/twenty%20total%20votes%20df.png);

[fifty percent helpful df](https://github.com/tonyferri/Amazon_Vine_Analysis/blob/main/resources/fifty%20percent%20helpful%20df.png);

[vine paid df](https://github.com/tonyferri/Amazon_Vine_Analysis/blob/main/resources/vine%20paid%20df.png);

[vine unpaid df](https://github.com/tonyferri/Amazon_Vine_Analysis/blob/main/resources/vine%20unpaid%20df.png);

[five star counts](https://github.com/tonyferri/Amazon_Vine_Analysis/blob/main/resources/five%20star%20counts.png);

[four to five star counts](https://github.com/tonyferri/Amazon_Vine_Analysis/blob/main/resources/four%20to%20five%20star%20counts.png);
