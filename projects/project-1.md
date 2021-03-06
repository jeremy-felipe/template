---
layout: project
type: project
image: images/nps-report.png
title: NPS Report User Tracker
permalink: projects/nps-report
date: 2017
labels:
  - Web Development
  - PHP
  - Javascript
  - Business Informatics
summary: My team and I developed a program to assist with improving the website based on user browsing habits and their submitted NPS scores.
---

<div class="ui images">
  <img class="ui image large rounded" src="../images/nps-homepage.png">
</div>

This project was developed as part of an internship at Intel®, and it's purpose is to link user data acquired from Google Analytics to their submitted Net Promoter Score (NPS), and then visualize it. Previously, the person in charge of analyzing these reports had no easy way to link the GA data and NPS of a user, and would typically have to infer the cause of their score based on their submitted group of interest. This was less than ideal, as the language of someone ecstatic enough or frustrated enough to give a strong enough score to warrant investigation is often not very constructive. Providing a means to track their movements through the site makes improving it far easier. 

The program pulled the data from the place where the GA data was stored, where the site data was stored, and where the NPS reports were stored, merged them together and threw them into a database on IDZ's servers. From there, the interface called and retrieved the data through a service layer. The program had a home page filled with user summaries which the Intel® employee could sort and filter to find certain attributes to study. Clicking on one of these would take the employee to another page with more detailed information about that user and visualized their path through the site on any of their sessions on hand. 

There isn't much more I should say on possibility of breaking Intel® confidentiality. I am also unsure about the code that I can upload for it; I'm sure the tables aren't going to give anything away, but I want to clear it with my former manager if I can before throwing anything up here. I want it noted however that this program only affects users who have signed up for an account on, and logged in to, IDZ. We did not track everyone coming into the site and checking things out. Any information gleaned about Intel® and its practices found in this project description is insignificant, can be acquired publicly, or gleaned from browser developer tools.



