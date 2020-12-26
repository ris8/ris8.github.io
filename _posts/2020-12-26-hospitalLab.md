---
layout: post
title: Hospital Lab
subtitle: 
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

new york has the most beds/person, with 0.00714261  

To obtain the dataset, I just asked for entries until the API gave an index error. The entries were placed into a list and separated by commas, so it created a table with rows and columns. Then, I looped through this table, giving each county a single entry in a dictionary, and assigning them their total beds per person (sum of each entry's beds/xhab) 

My process for this consisted of three main steps: Pulling the data, working the data, and sorting through the results. I did not work with anyone. Pulling the data consisted of a bit of trial and error, trying to get the API to do what I wanted. In retrospect, I probably could've taken from a local CSV for testing, as it might've saved me time during instead of waiting for the API to give me the whole dataset. Working the data was relatively quick and uneventful, mainly slowed down by the time it took to test. When it was done, I was left with a dictionary of counties and their beds/person. Finally, getting the highest value from this dictionary was also relatively quick and uneventful. The main thing I got from this lab is much more comfortable with APIs. 
