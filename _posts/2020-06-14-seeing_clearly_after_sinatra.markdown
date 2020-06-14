---
layout: post
title:      "Seeing clearly after Sinatra"
date:       2020-06-14 06:00:50 +0000
permalink:  seeing_clearly_after_sinatra
---


Learning to code is a brain intensive activity.  As I wrap up my Sinatra lessons, I chose to work on a project that relates to a topic that I know affected my brain power throughout my learning journey.  As a woman, PMS symptoms affect my mind and body at least 7 days out of a given month.  This hampers how much time I get to put towards my learning journey.  Though there are existing apps on the market, I thought it would be a great idea to create one of my own as practice.

Building the Period.Tracker App gave me a sense of clarity that I had not found since my journey to code began.  As I wrote the code line by line, concepts that had me confused doing the labs suddenly seemed clear. I’m glad I had the opportunity to build from scratch and look forward to creating a better product in future iterations of this App.

In creating my app, I finally understood how to write the relationships between models in my app and how they connect.  In this instance, the Period.Tracker App allows a woman to create a period entry to keep track of her menstrual cycle each month so she can estimate when PMS symptoms may occur.  This would mean that each user would have a relationship of `has_many` periods, however a period entry would only `belongs_to` one user.  Future iterations of this project would allow me to expand on relationships by adding new models that can create  `has_many, through` relationships, like a user as it relates to many notes through a period.

I was most excited about implementing input validations on the app.  This meant it would feel like a real app that can be used in the real world.  The new user would not be saved without the necessary information in each field.  A user would not be able to create an account using an email address that is already used to create an account. It was also clear to me how helper methods are effective in keeping the code clean.  By creating helper methods in the ApplicationController for this app, I was able to utilize them in other parts of the app without having to write a significant number of lines of code repeatedly.

Overall, the process of creating this app has truly motivated me to keep going on this journey.  I am energized to see all the things I can do in Rails.

