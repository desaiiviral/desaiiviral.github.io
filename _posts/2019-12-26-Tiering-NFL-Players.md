---
title: "Tiering NFL Players!"
date: 2019-12-26T15:34:30-04:00
categories:
  - NFL
tags:
  - NFL
  - Fantasy
layout: splash
---

My passion project for Fall 2019 was to draft a winning fantasy football team. Diving deeper into my data science journey I decided to use a common machine learning technique, clustering, to be able to find the value in under-valued players. Using a common clustering alogirthmn known as Gaussian Mixture Modeling, I clustered NFL players, using their 2018 statistics, into different tiers (1,2,3...) to find players that the stats say are valued higher then a typical analyst would. 

For example, lets say we have a player named "Roger Rabbit" who most experts think will be the 50th pick in the draft but our model shows him being grouped with the wide receivers that are picked in the 10-15th range. This gives me a little insight in the fact that the player is severely undervalued by the general public compared to what the statistics are telling me. So I can pick him up with say the 40th pick while getting the value of a 15th pick.

Using this idea I wanted to build a fantasy football team that would hopefully get me my first ever win. I used it to draft players that the algorithmn said were better then the average public and was able to go 10-4 in the regular season! (1st Place and most points) Unfortunately I did lose in the first playoff round but sometimes you just are not lucky. But below are my resulting clusters for each position (QB, RB, WR, TE) in standard leagues and PPR leagues and underneath each picture is a comparison of my predicted "Tier 1" players vs the actual top players.

![QB-STD](/assets/images/QB-STD.png)

<div class="datatable-begin"></div>

Predicted Tier 1 Players (No Particular Order)    | Top N Players Ordered
------------------------------------------------- | ---------------------
Patrick Mahomes  | Lamar Jackson      
Dak Prescott | Dak Prescott 
Matt Ryan   | Russell Wilson
Ben Roethlisberger | Deshaun Watson 
Deshaun Watson   | Jameis Winston
Aaron Rodgers   | Josh Allen
Jared Goff   | Patrick Mahomes
Caw Newton   | Kyler Murray

<div class="datatable-end"></div>

![RB-STD](/assets/images/RB-STD.png)

![RB-PPR](/assets/images/RB-PPR.png)

![WR-STD](/assets/images/WR-STD.png)

![WR-PPR](/assets/images/WR-PPR.png)

![TE-STD](/assets/images/TE-STD.png)

![TE-PPR](/assets/images/TE-PPR.png)


[My twitter]: https://twitter.com/ViralVis
