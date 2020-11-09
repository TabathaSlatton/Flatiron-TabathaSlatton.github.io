---
layout: post
title:      "The Power of Bootstrap"
date:       2020-11-09 17:09:05 +0000
permalink:  the_power_of_bootstrap
---


During my previous Sinatra project, I just used CSS for styling. This was such a powerful learning experience for me and really boosted my confidence with CSS. Towards the end of the project, I dabbled with a CSS framework (materialize), but none of this made it into the final project. I decided after this experience to focus more on the front end of my next project with a CSS/Front-End framework. 

After talking with a current developer, I decided to style as I go. Right after generating my project with rails new and laying the foundation with Devise, I immediately began the process of styling and had NO regrets. [Bootswatch](https://bootswatch.com/) coupled with [Bootstrap](https://getbootstrap.com/) led to a really fun and worthwhile experience. These tools made it incredibly easy to get my visuals together. Bootstrap provided a ton of versitility while Bootswatch gave me a great palette to start with. It was so easy to get it going, I helped quite a few of my peers up their front-end game with Bootstrap as well. In addition, since Bootstrap is incredibly popular, anytime I wanted to make an item look a specific way, google usually led to a great solution. 

### What to keep in mind:

#### 1) It's simple to get going with Bootstrap

I highly recommend checking out the [getting started with Bootstrap page](https://getbootstrap.com/docs/4.0/getting-started/introduction/) for more information on getting your front-end going. For me, it was as simple as putting this line of code: `<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">` into the head of my application layout. Then if you want to integrate a theme from [Bootswatch](https://bootswatch.com/), you can download the bootstap.min.css file right into your stylesheets folder in your application (app/assets/stylesheets). From there, using the source code within Bootswatch theme preview will nine times out of ten give you EXACTLY what you need. 

#### 2) Don't be afraid to throw a class in and see what happens

The more I played around with Bootstap/Bootswatch, the more I noticed patterns. There is a LOT more functionality than may appear at first and once you dig into it, you'll notice that different classes do different things. For example, if you want to specifically change the color of a card or text, you can add the words "primary, info, warning, success, ect." into the class. What it changes completely depends on where this is in your class. Remember, if you break something, you're only a control+z away from it working again! 


#### 3) It's really easy to get stuck in the weeds. Know when to move on

Stying was a fantastic way for me to take a break from some of the challenging features I was trying to implement in my program. However, it is also VERY easy to spend way too much time and energy on styling rather than the logic in your project. Towards the beginning of my project, I'll be honest, I found myself way too invested in the appearance rather than the functionality of my program. Further into my project, I combatted this by only allowing myself to style after I finished a feature/part of the functionality. If you decide to add bootstrap to your project, make sure you set a plan and remind yourself of the purpose of your project. It's a whole lot of fun and helps make you more attached to your project, just make sure the priority of your program is it's functionality. 
