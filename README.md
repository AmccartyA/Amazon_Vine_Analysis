# Amazon_Vine_Analysis
 
## Overview
For this Project I gathered amazon reviews for current Video Games using their review system on their website. After loading and running the large amount of data through Amazon RDS, I then converted that data to smaller Data Frames with Pandas and Jupyter Notebook. The goal was to see if there was a bias in ratings for certain reviews based on the Amazon Vine project which pays users to leave reviews on products gifted to them from the manufacturer .
 
## Results
We were able to gather over 1 million reviews, but of those reviews very few were Part of the Vine Program.
 ![filters](https://user-images.githubusercontent.com/103524591/194142909-6c7e49a1-916a-4691-a432-a929a4cd9d8b.png)

Based on all the 5-star reviews. A lot of them were actual from non-vine reviewers
 ![non-vine5star](https://user-images.githubusercontent.com/103524591/194142873-26c8e347-aeda-4d26-84ea-c7b44261423e.png)

Less than 1 Percent of all the reviews are part of the Vine Program
 ![Percentage5star](https://user-images.githubusercontent.com/103524591/194142820-a18b2e87-e82c-4ab9-89fa-61ce32fb8274.png)

 
 
## Summary
Though we can still gain insight into which Video games are more popular. A lot of the High Ratings are subject to personal critique as an overwhelming majority were made with no Vine account attached to it.
Although Vine accounts tend to Vote Favorable with the Majority of Votes being 4's and 5's
 ![Starratings](https://user-images.githubusercontent.com/103524591/194142690-0b1cdf0b-59af-4c60-bb25-3e3ef479a1c9.png)

A Majority of the Reviews for Non-Vine Accounts were also 5-star but, non-vine users had no problem giving products a 1-star review.
