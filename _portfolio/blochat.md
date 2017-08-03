---
layout: post
title: BlocChat
feature-img: "img/sample_feature_img_2.png"
thumbnail-path: "https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/2030974/bloctalk_1x.png"
short-description: A messenger application

---
__Summary__

BlocChat is a messenger application that works with Google Firebase to provide an easy-to-use chat room.

__Explanation__

This project significantly reduced the assistance provided on each step of production.  During the course of building BlocChat I was required to use what I already knew about HTML, JavaScript, and AngularJS to produce to solutions to new problems.  I then had to link it to Firebase and ensure the two worked together in order to provide a clean experience for the user.

__Problems__

There were a number of small problems as I firmed up my knowledge of how AngularJS controller and services worked with each other.  When implementing functions there were a number of places I had to check to make sure it was installed correctly.  Scripts, injections, HTML views all had to be working properly on top of writing the proper functions using the proper input. One extremely frustrating problem that really sticks out in my head was installing a timestamp for each message.  I attempted a number of different methods.

__Solutions__

I finally was able to find a solution that worked for me with:
```
var d = new Date();
var datestring = ("0"+(d.getMonth()+1)).slice(-2) + "-" + ("0" + d.getDate()).slice(-2) + "-" +
    d.getFullYear() + " " + ("0" + d.getHours()).slice(-2) + ":" + ("0" + d.getMinutes()).slice(-2);
```

I had to re-arrange the month and date for an American eye.  There were a number of other solutions but I'm keeping this one in my back pocket because I know it works!

__Results__

This was a chance to put just a touch of my own flair into the application design.  The nuts and bolts was the real work, but getting to flex a little bit into the creating the proper look was a welcome distraction from the grinding on sometimes difficult code.  

__Conclusion__

I enjoyed creating BlocChat because it let me re-enforce Angular which is a framework I really enjoy.  The design concepts makes sense to me.  I also was able to do some design work and see what it takes to make a clean and easy looking design.  I would think of a touch I wanted to add then went and researched how to do it.  Overall a very satisfying project.
