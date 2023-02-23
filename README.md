# Amazon Vine Analysis

## Overview of Analysis

The purpose of this project is to analyze the reviews of cameras on Amazon. Our dataset contains reviews written by standard customers as well as reviews by members of the paid Amazon Vine program. We will perform several analyses on the data to determine whether there is any positivity bias among the Vine reviews compared to the non-Vine reviews.

## Results

Within our data set there was:

* a total of 607 Vine reviews that were considered to be helpful 
* a total of 50,522 non-vine reviews that were cosidered to be helpful

Of the totals listed above:

* 257 Vine reviews were 5 stars
* 25,220 non-vine reviews were 5 stars

This means that:

* 42% of the Vine reviews were 5 stars
* 50% of the non-Vine reviews were 5 stars

*We chose to cateogorize reviews as 'helpful' with over 50% of the votes on the review determined the review was helpful

## Summary

The percentages calculated above suggest that there is not positivity bias among the reviews in the Vine program, as the vine reviews actually had a lower percentage of 5 star reviews than the regular reviews.

It may be interesting to perform this test on the entire dataset rather than simply the reviews that were considered helpful. Perhaps there is positivity bias among Vine reviews, but those reviews simply do not get voted up. 

It may also be interesting to see the distribution of the other rating levels (4 stars, 3 stars, etc.) to see whether there are significant differences between the Vine and non-Vine reviews there.
