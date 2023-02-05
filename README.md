# video game sales analysis
 project
# Video Games Sales Analysis

## Introduction
You work at the online store "Ice" which sells video games from around the world. Data regarding user and expert reviews of games, genres, platforms (e.g. Xbox or PlayStation), and historical game sales data is available from open sources. You need to identify the patterns that determine whether a game is successful or not. That way, you can find the games with the most potential and plan their ad campaigns.

In front of you is data from 2016. Let's imagine that it is December 2016 and you are planning a campaign for 2017.
(Right now, the most important thing for you is to gain experience working with data. It doesn't matter whether you forecast 2017 sales based on data from 2016 or forecast 2027 sales based on data from 2026.).

This dataset contains abbreviations. ESRB stands for Entertainment Software Rating Board, which is an independent regulatory organization that evaluates game content and gives an age rating such as Teen or Mature.

## Objective
1. Top 5 platforms. Explain the variations in market share from one region to another.
2. Top 5 genres. Explain the difference.
3. Does the ESRB rating affect sales in each region?
4. Test the hypothesis whether the average user rating of the Xbox One and PC platforms is the same.
5. Test the hypothesis whether the average user rating for the Action and Sports genres is different.

## Stage
1. Open a file
2. Pre-processing
3. Data analysis
4. User profiling
5. Test the hypothesis

## Data Description
— Name (name)

— Platforms

— Year_of_Release (release year)

— Genres

— NA_sales (North American sales in millions of USD)

— EU_sales (European sales in million USD)

— JP_sales (sales in Japan in million USD)

— Other_sales (sales in other countries in millions of USD)

— Critic_Score (review score from critics, max. 100)

— User_Score (review score from users, up to 10)

— Ratings (ESRB)

Data for 2016 may be incomplete.

## Conclusions
Data preparation:
the data is opened and studied, then fixes the column, fixes the data type, resolves missing values, checks for duplicates, and finally creates a total sales column.

From the data analysis, it can be concluded that:
1. the most games released in 2009, and the range from 2007 to 2011 is the highest number
2. DS, PS, and PS2 used to be popular, but have since fallen to the point where they don't have any sales
3. Platform life span ranges from 10-12 years
4. generally from the time of emergence, it takes 3-5 years to reach the peak of popularity of a platform, and then decline
5. For the 2017 projection, data for the last 5 years is used, namely since 2012
6. since 2012, the top 5 most sales of PS4, PS3, X360, 3DS, XOne
7. The platforms that grew until 2015 were PS4 and XOne, while those that shrank were X360, PS3 and other platforms. platforms that still have the potential to generate profits are PS4, XOne, and 3DS

From user profiling, conclusions are obtained:
1. The NA and EU markets have many similarities in terms of platforms used, preferred genres and esrb ratings, while the JP markets have their own uniqueness in terms of platforms, genres and ratings

From the hypothesis test, it can be concluded that:
1. The average user rating for the Xbox One and PC platforms is the same
2. The average user rating for the Action and Sports genres is different