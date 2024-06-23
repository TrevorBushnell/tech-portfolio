---
description: "A place to see my Splatoon 3 battle data"
featured_image: ""
tags: []
weight: 4
title: "Splatoon 3 Battle Dashboard"
---

I'm a huge Nintendo fan in my free time, and Splatoon 3 is a game that I play on and off. As a part of having the game, Nintendo has a service in the form of an app for your phone that lets you view statistics of your previous battles that you have participated in. What's awesome is that people way smarter than me found a way to reverse-engineer the API controlling the app to allow you to permanently save your battle data using various online free services. I personally use [stat.ink](https://stat.ink/) to manage my Splatoon battle data. Not only does this website host all of my Splatoon battle data, it also hosts data about all battles played by all players across the world. Combining this with my data science knowledge, I created a Splatoon 3 dashboard with Streamlit to view my performance in Splatoon 3. What's more - I've set up automatic jobs that continuously download and update my data daily. This way, my dashboard is continuously up-to-date with my latest gameplay data. 

Currently, I've taken this project down so that I can do a complete rehaul of the project. The major work I'm doing right now is migrating to a SQLite database rather than attempting to store and merge hundreds of csv files. 

Tasks included:

* Use GitHub Actions to continuously download my personal and worldwide battle data
* Use Streamlit to host a dashbord of my Splatoon battle statistics
