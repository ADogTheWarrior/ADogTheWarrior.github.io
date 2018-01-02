---
layout: post
title:      "Recipe Keeper"
date:       2018-01-02 23:41:35 +0000
permalink:  recipe_keeper
---


For my CRUD sinatra  project I decided to make something that would keep track of recipes, hence the name Recipe Keeper. It seemed like a simple project that could be expanded on later if I would like. It just has a user and a recipe class. If I do expand it I'd add an ingredient class so you could pick all the meals you want for the week and get a shopping list of everything that you need. The one drawback I see to this is that sorting the ingredients into different ones would be tedious either to do on the front end or making something that could do it on the back end. I'd look around and see how other apps handle similar issues before I made it happen.

My actual application is much simpler. It has a user that can only make changes to his own account and recipes. The user is able to look at any other user's account and recipes. There is also a page that has all of the recipes posted by everyone. Each recipe has a name, description, and directions. And that's basically it for the app, pretty simple.

Coding this project was much more enjoyable than the previous project. I first sat down and planned what my models would look like and how they would interact with each other. The next step was to get started on the actual coding. I used the corneal gem to stub out all of my initial classes. It a very useful ruby gem and I would recommend it to anyone for this project. After I had the stubs and the "Hello World" working I got to work on views and controllers. Getting the models to work how I wanted them was the only challenging thing. The rest of the project was just writing everything out.

Looking back it is neat to see how the views evolved. I didn't plan those out when I was planning the models because it felt like something that would be shaped by the models. And if I didn't like how my models were structured and changed them then I would have to change my views as well. As I coded my controller I would code the corresponding view. Sometimes when I moved on I would see that a previous view should have something I didn't put in so I'd make it happen. I like being able to code this way where I have a basic structure in mind and then make it happen.

Thank you for reading, have a good day!
