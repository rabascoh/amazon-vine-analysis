# Amazon Vine Analysis
The purpose of this analysis is to determine whether paying Amazon reviewers via the 'Amazon Vine' program biases reviews. For this analysis, we have focused on reviews in the Beauty vertical. 

## Results
Of the 74,760 Beauty product reviews, less than 1% were Vine reviews (*n*=647). The differences between Vine and non-Vine product reviews are outlined below. 

### Number of Reviews
There are 647 Vine reviews and 74,113 non-Vine reviews for beauty products. 

### Number of 5 Star Reviews
Of the 647 Vine reviews, 229 were 5 star reviews. 
Of the 74,113 non-Vine reviews, 43,217 were 5 star reviews. 

### Percentage of 5 Star Reviews
Thirty-five percent of Vine reviews were 5 stars compared to 58% of non-Vine reviews. 

Vine
![vine_findings]() 

Non-Vine
![nonvine_findings]() 

## Summary
Based on the initial analysis, we found that paying customers via the Vine program may actually cause a *negativity* bias for product reviews in the Beauty category. There are only 35% of 5-star reviews for Vine reviewers compared to 58% of 5-star reviews for non-Vine reviewers. 

### Additional Analysis
We recommend conducting an independent samples t-test to determine whether the differences in ratings between Vine reviews and non-Vine reviews are significant. 

Variables: 
Independent Variable: Vine review status (Levels: Vine Review, Non-Vine Review)
Dependent Variable: Star Rating

Hypotheses: 
H0: There is no difference in star ratings between Vine and non-Vine reviews. 
H1: Vine reviews have significantly lower star ratings compared to non-Vine reviews. 

