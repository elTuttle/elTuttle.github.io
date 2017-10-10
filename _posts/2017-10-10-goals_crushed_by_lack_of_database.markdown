---
layout: post
title:      "Goals Crushed by Lack of Database"
date:       2017-10-10 06:16:46 +0000
permalink:  goals_crushed_by_lack_of_database
---


My initial intent for my Data Gem project was to make a six degrees of seperation app based off the Kevin Bacon game (https://en.wikipedia.org/wiki/Six_Degrees_of_Kevin_Bacon). But the exponential amount of data being iterated through after the second degree of seperation made the process so slow to load that it wouldn't be of any use as a gem. What I found though was that I had the ability to pull data from any https://www.rottentomatoes.com/ actor or film page and decided to change the direction of the application from a six degrees of seperation application to an application that gives data of a specific actor. With some added functions to the actor class and simplification of the six degrees of seperation function, I was able to build a gem that with just one actor name can give you their entire filmography, every co-star, and allows you ask if they've worked with a specific actor and tell you which films they were in together.
