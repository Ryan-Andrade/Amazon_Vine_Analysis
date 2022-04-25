# Big Data

## Overview of the analysis:
The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. I chose to analyze a Digital Music Purchases dataset to determine if there was any bias towards favorable reviews by Vine members.

## Results
https://postimg.cc/ThXJvrbG
1. Based on our filtering criteria there are no paid Vine reviews remaining at the end of the transformation.However for unpaid reviews, the total number of reviews that remained was 4532.
2. The number of five star vine reviews was zero. The number of non-vine reviews that were five stars is 2507.
3. The percentage of vine reviews that are five stars is 0%. The percentage of non-vine reviews that are five stars is 55%.

## Summary
Based upon our analysis we are unable to tell if there is any positivity bias in reviews written by members of the vine program. We filtered 1.6 million reviews to find those that had a minimum of 20 votes and of those votes half of them or greater had to consider the review to be helpful. From this filtering, no vine reviews were output and thus we are unable to draw a conclusion. I would recommend a further analysis be done starting with the vine reviews themselves and filtering based on that data slice.