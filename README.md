# Project Two: A Subreddit Analysis of the Republican and Democratic Parties Using Classification Models

## Problem Statement
-----

As a political analyst for Bring Back Democracy, I have been asked to analyze the subreddits for Republicans and Democrats of Reddit.com.

My analysis involved reviewing the most prevelent topics of interest for each group to identify similarities and differences and, most importantly, to be able to predict classify future topics by political party. In this way, we will be able to better understand the interests of each party on an ongoing basis.

>  Can an accurate model be created using the subreddits r/Republican and r/democrats to aid predict whether a new title would belong in the r/Republican subreddit over the r/democrat.


## Executive Summary
----

Tasked with evalauting patterns in the r/Republican and r/democrats subreddit, I created a model that predicted with about 70% accuracy on whether a particular set of words or phrases could determine whether someone posted in the democrat or Republican subreddits. Based on the performance of the model, I recommend that further analysis be taken to give weight to certain words based on whether they use those words in a positive or negative way. For example, is President Trump used in more positive phrases or negative ones.

## Next Steps
------

My recommendation from this point would be to find ways to apply weights to certain words so that they give a stronger probability of correctly predicting one subreddit over the other.

----


## Data Dictionary
|Feature|Type|Description|
|---|---|---|
|Title|object|Original posted title|
|Subreddit|object|r/Republican and r/democrats|