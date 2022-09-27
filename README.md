# Analysis of Amazon Vine Program Reviews

## Overview:
This project's purpose is to perform an analysis of reviews written by members of Amazon's Vine program to help our client, Sellby, better weigh the pros and cons of joining the program. Sellby would need to pay a fee to Amazon to join the program and then provide products to Vine members for them to publish reviews. As such, Sellby wants to know if there is any bias towards favorable reviews from Vine members.

## Results:
These results were compiled Amazon dataset containing reviews of Office Products.

- **Number of Vine and non-Vine reviews:**
  - There were 969 Vine reviews and 43,745 non-Vine reviews for a total of 44,714 reviews in this dataset.
    ![vine_reviews](https://github.com/bfox87/Amazon_Vine_Analysis/blob/main/Screenshots/Vine_Reviews/vine_reviews.PNG)
    ![non_vine_reviews](https://github.com/bfox87/Amazon_Vine_Analysis/blob/main/Screenshots/Vine_Reviews/non_vine_reviews.PNG)

- **Number of Vine and non-Vine reviews that were 5 stars:**
  - There were 430 Vine reviews with 5 stars and 19,233 non-Vine reviews with 5 stars.
![vine_5star](https://github.com/bfox87/Amazon_Vine_Analysis/blob/main/Screenshots/Vine_Reviews/vine_5star.PNG)
![non_vine_5star](https://github.com/bfox87/Amazon_Vine_Analysis/blob/main/Screenshots/Vine_Reviews/non_vine_5star.PNG)

- **Percentage of Vine and non-Vine reviews that were 5 stars:**
  - 44.4% of all Vine reviews gave 5-star ratings, while roughly 44.0% of non-Vine reviews were 5-stars.
    ![vine_5star_percent](https://github.com/bfox87/Amazon_Vine_Analysis/blob/main/Screenshots/Vine_Reviews/vine_5star_percent.PNG)
    ![non_vine_5star_percent](https://github.com/bfox87/Amazon_Vine_Analysis/blob/main/Screenshots/Vine_Reviews/non_vine_5star_percent.PNG)

## Summary:
There does not appear to be any positivity bias for reviews in the Vine program. The breakdown of both Vine and non-Vine reviews shows roughly 44% of each had reviews of 5-stars. This appears to indicate that paid reviewers of office products were not influenced to more favorably rate a product than those not part of the Vine program.

#### Additional Recommended Analysis:
A comparison of the rating distributions between Vine and non-Vine reviews is recommended. Some summary statistics and a plot like a histogram could provide a more complete understanding of any potential bias. For example, paid reviews might be predominately 4 or 5 stars while non-Vine reviews might show a higher percentage of 1 or 2 star ratings. Just looking at the breakdown of 5-stars may not reveal the whole story.