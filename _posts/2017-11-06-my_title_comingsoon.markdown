---
layout: post
title:      "my_title = "ComingSoon""
date:       2017-11-07 01:08:23 +0000
permalink:  my_title_comingsoon
---

For my CLI project I made a ruby gem called Coming Soon. I got the idea from an example that described making a gem where if you enter in your area code, you'd get movies playing nearby. I liked that idea but I didn't want to copy it. So I decided to make a gem that would just look for movies coming out soon even if they had limited screenings. My plan was to scrape movies off of imdb.com from the coming soon section. Then my gem would go into each movie and scrap additional information. Since I saw all the information I needed on the index page I was worried that I would have to stretch the project out by getting things I wasn't interested in for each movie like a full list of actors for each one. But it turned out that it was easier to get certian pieces of data from an individual movie section than from the index page on imdb.

By far the toughest part of this project was getting started. Creating a gem from scratch was difficult because it had been a whlie since I had done example exercises in the github section of the Learn course. I watched some tutorial videos and the video of Avi going through creating a gem helped a lot. But when I created my first github repository I had some files up that didn't need to be there. Once I got some help on how to create a repo, things moved quicker.

I followed the video Avi posted for the project the best I could. I really liked his ideas on coding. Code one thing at a time, make sure it works before you move onto the next thing. I didn't follow that advice all the time, but when I did the coding went smoother. I also planned out what classes I thought I'd need before I started to code as well as certain attributes and methods for each class. As I got to the end of my project I found that I didn't need some methods that I had made to I got rid of those while I was refactoring my code.

The project evolved a bit from what I thought it would be to what it actually became. The biggest changes came in how I thought it would be implemented and how it actually was. One of the things that bothered me was getting the proper release dates for movies. Since some movies first come out in their native country and later were released in the US, there were different dates on the details page of that movie and coming out soon page of imdb. The date on the coming soon page was the date I wanted but it was much harder to scrap. Once I had written the code for everything else I went back and fixed the scrapping for the dates. I then made a method for scrapping the dates and then adding those dates to the appropriate movies.

Overall I enjoyed the project, even when I couldn't figure out how to do things like scrap effectively or make a properly formated github repository. To sound cliche, it was a good learning experience. Next time I have a project like this I am going to try and get myself unstuck sooner whether that's asking around for help or looking up tutorials online.
