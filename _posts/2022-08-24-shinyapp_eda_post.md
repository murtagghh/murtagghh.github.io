---
layout: single
title: "ShinyApp EDA with myBand data"
tags: ["myBand", "EDA", "Shiny", "analysis", "sleep"]
---

Hi! In this entry I want to share a little project I did with the visualization R shiny library. The goal of the developped Shiny App is to do some simple Exploratory Data Analysis (EDA) with the data of the sleep times that the myBand 4 I wear on my wrist has recorded for the first half of the year (more or less). The App is full interactive and allows the user to choose the dates between which he wants to do the exploration and also to choose if he wants to study all the weekdays or if he wants to put the spotlight on a specific day. The user can visualize the following graphs:

<ol>
  <li>Table: contains the main measures of centralisation and position of the different variables in the data</li>
  <li>Sleep time series graph: shows the total sleep time of each day of the data with a red line at the height of 08:00, 07:00 and 06:00 in order to see the when the duration of sleep has been right or not.</li>
  <li>Sleep phases series graph: shows for each day the time spent in each phase of sleep. Deep sleep is the ideal phase that determines the quality of the rest.</li>
  <li>Sleep phases(mean): shows a bar chart representing the average time spent in each phase on each of the nights of the data.</li>
  <li>Correlation: shows some graphs with the correlation between the total time sleeping and the time of deep sleep  in order to explore if there is a direct relationship between the duration of sleep and the quality of rest.</li>
</ol>

It's easy to draw conclussions just playing a bit with the app and, before you say anything, the first half of this year is the period in which I have been finishing my studies, including the two final degree projects, so don't judge my lack of sleep please &#128512;.

