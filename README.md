# Tiktok

## Project Title

Use ML, Statistical analysis and hypothesis testing to help **TikTok** predict if a video is a claim or an opinion

## Project Overview

TikTok users can report videos that they believe violate the platform's terms of service. Because there are millions of TikTok videos created and viewed every day, this means that many videos get reported—too many to be individually reviewed by a human moderator. Analysis indicates that when authors do violate the terms of service, they're much more likely to be presenting a claim than an opinion. Therefore, it is useful to be able to determine which videos make claims and which videos are opinions.

TikTok wants to build a machine learning model to help identify claims and opinions. Videos that are labeled opinions will be less likely to go on to be reviewed by a human moderator. Videos that are labeled as claims will be further sorted by a downstream process to determine whether they should get prioritized for review. For example, perhaps videos that are classified as claims would then be ranked by how many times they were reported, then the top x% would be reviewed by a human each day.


## Conclusion
1. Using Random Forests or XG Boost we find that most predictive features were all related to the user engagement levels associated with each video. It was classifying videos based on how many views, likes, shares, and downloads they received.
2. Logistic Regression does quite poorly on the data set and would not be a recommended method 
3. Additional helpful features are  the number of times the video was reported. It would also be useful to have the total number of user reports for all videos posted by each author.
