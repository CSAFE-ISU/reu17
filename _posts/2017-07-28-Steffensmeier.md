---
title: "Statistical Approaches to Matching Bullets"
subtitle: "Anna Steffensmeier"
date: "2017-07-28 17:00:00 CDT"
topic: "week7"
layout: post
root: ../../../
tags: [forensics, statistics, assignment, week7]
---
 

1. What data do Hare *et al* use? 

Hare *et al* used the x3p file, bullet R-package, and the random forest package. The 3-D scanned images of the bullets from the Hamby study were used as the foundation of their data, which they then analyzed later.

2. In what ways do the methods used by Hare *et al* differ from the "traditional" methods of bullet matching? 

The traditional methods that have been used in the past involve firearm examiners using a comparison microscope to establish whether or not two bullets are a match or not a match. Their decision is not statistically based, however. Instead, they base their decision off of how many successively matching striae are on the two bullets in question (it is typically about six matching striae). Hare *et al* take several components into consideration when comparing two bullets to each other. One thing that separates the methods Hare *et al* use  is their creation of digital images to assist with their comparisons.

3. How do Hare *et al* use **clustering** to help perform bullet matching tasks? 

Clustering is not explicitly mentioned as a method they use to match two bullets. However, they use some similar methods to separate bullets as matches or nonmatches based on certain elements with the help of the Random Forest package. The bullets that have similar characteristics would be separted into the "matches" category while the bullets who have different characteristics would be categorized as "nonmatches".

4. Identify one statistics and/or probability concept in the presentation that you have not heard of before. Do a little bit of research (Googling/Wikipedia is ok) and try to describe it to someone who doesn't know about it. You should also consult [this paper](bulletmatchingpaper.pdf) to see if there is more detail on your chosen topic than is presented in the webinar. (Hint: Control + F is useful...) You **don't need** to read the whole paper.

The concept of Euclidean distance with bullet matching is an idea I have never thought of before. While I use the idea of Euclidean distance in math (more often than I'd like to), I have never heard of it applied to a real life situation. Forensic scientists use a specific equation to calculate the average diffeerence between two aligned signatures on a bullet (called Euclidean distance). A numerical value is assigned to test the probability that these lands came from bullets fired from the same gun. 
