---
layout: post
title:      "My Rails Portfolio Project"
date:       2018-02-22 05:05:51 +0000
permalink:  my_rails_portfolio_project
---



I just finished my Rails portfolio project and I can say without a doubt that it was the most rewarding and challenging project yet! For my project, I chose to build an application that allows it's users to document their car collections and admire the car collections of others. Each user can add cars to their collection, add the awards that they have received at car shows etc. for each car, and delete or edit their cars.

My first challenge with the project was getting login with Facebook through the Devise gem to work. I was initially unable to get the gem to create new users upon authorization because my app was not pulling emails from Facebook, but eventually was able to get it to work after creating a new application on the Facebook developers console and transferring my original files to a new rails app.

The second challenge that I had was getting my award instances to assign themselves to the correct car upon creation. For a long time, they were just all becoming assigned to the car with id=1. I eventually found out that my set_car before_action method was setting the car_id using the user_id, and since I was user_1, the awards were all going to the car with car_id 1.

Those were the two main headscratchers over the course of the creation of the app, but aside from those, it was pretty smooth sailing. Overall, it was an awesome learning experience and I am really looking forward to continuing to work with rails in the future!
