---
layout: post
title: Airports Lab
subtitle: The heatmap took an ungodly amount of time...
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---
![AirportsHeatmap](/assets/img/airportsHeatmap.png)
![AltitudeDistribution](/assets/img/altitudeDist.png)
First, let's take a loot a the latitude and longitude of all the airports in the dataset. By building a heatmap from the data, we see that there's a massive number of airports in Europe, and the East and West coasts of the US. We can also see that Russia has a very low density of airports, along with Canada; presumably this is because the high latitude makes aviation difficult. Finally, we can make out the Sahara desert. This information strongly supports the US and Europe being the world leaders, as they have by far the highest density of airports in the world.  

Now, we can move onto analysing the altitude of the world's airports, as, while the heatmap is cool, it's not exactly statistical analysis. The violin plot represents the raw data of the altitude distribution. As for the actual information, Q1 is 63ft, Q2 is 1203ft, and the mean is 1016ft. Just from this, we see that most of the airports are between 0 and 1500 ft; however, the mean is being pulled upwards by a large number of high outliers. There's a strong upward tail, with values reaching up to 15,000ft, and a considerable number of values at 5000ft. Thus, after applying the 1.5IQR rule, our mean comes down to 549ft, dropping significantly. This distribution makes sense, as, while you can't go too far below sea level, you can certainly climb very high, making the data extremely susceptible to these outliers. 