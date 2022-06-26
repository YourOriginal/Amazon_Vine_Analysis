# Amazon_Vine_Analysis

Customer reviews, ratings and content creators are all intertwined in a tightly connected network that all feeds off each other, often deciding important factors such as further funding, investment and overall success of the product. In this analysis, we will use amazons data on product reviews along with ratings of VINE to determine how the reviews fair and if they appear to be legitimate helpful reviews or fraud reviews that are for the better or worse for the product. 

## Analysis 

Initial import of the Video Game reviews required some filtering to find the correct matches. To do so, we wanted to only count ones with a sufficient sample size to minimize errors but stayed relatively general with a total vote count of > or = to 20 and also filtered through those with a 50% or greater overall positive "helpful votes". 

To filter for reviews and find which are part or not part of the vine program, all we had to do was filter for column "Vine" for Y or N and yielded the following table for Y (N is the same, just different code in filter)  with an overall count of 40471 NOT and 94 that ARE apart of the program.


![vine_y](https://user-images.githubusercontent.com/100324759/175795258-73ef456f-db7e-4062-92dd-14a1a1659669.PNG)


![count](https://user-images.githubusercontent.com/100324759/175795297-530358a8-cefa-4330-ba99-81893b2b7ab9.PNG)


Of these reviews, the Vine program had a 48/94 (51%) overall 5 star rating while the non-vine program yielded a count of 15663 5 stars and an overall percent of 39 showing that there is a noticeable trend in higher 5 stars in the paid vine program.


![code -](https://user-images.githubusercontent.com/100324759/175796053-343d1570-6d0f-4a09-bfd7-a2751153d6a3.PNG)


## Summary

Overall, the stats lean towards a positivity bias for those hired by the vine program. This is expected as companies are paying people generally, not to be honest to about their product but to advertise it to the widest range of audience. There are several things to consider: the number of people apart of the vine program is relatively small in sample size while those that weren't has a much larger sample. While the evidence leans towards one, statistical significance should be tested to determine the p-value of the outcome.
