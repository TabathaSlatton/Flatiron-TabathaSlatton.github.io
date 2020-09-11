---
layout: post
title:      "CLI: Challenges, Learning Experiences, and Insight"
date:       2020-09-11 14:55:37 -0400
permalink:  cli_challenges_learning_experiences_and_insight
---


### Challenges:

 <p>I faced a number of challenges throughout this CLI project. The first being scale. I had a lot of big ideas for this project, but I knew going into it that I would not be able to get to all of them. I tackled this by using my background in teaching to know that it is better to over prepare with an idea of what will be cut than to underprepare and be unhappy with the result. With that in mind, I started with 17 user stories, some labled as *bonus*, others labeled as *expandable*. In addition, I had several that were not labled at all. The unlabled user stories were ones I for sure wanted. </p>
<p>The next challenge I faced while working on this project was scraping text nodes. These nodes were not attached to any parent containers. They were loose nodes. This was a challenge because I could not tell how to grab them with a css selector. <br><br>

` <h2 class="title">Alchemical Weapon Expertise<span style="float:right;">Level 7</span></h2> You’ve trained to more effectively wield the weapons you find in your lab. Your proficiency ranks for simple weapons, unarmed attacks, and alchemical bombs increase to expert. `


<br > <br> 
Something interesting I noticed about each of these text nodes is that they always followed an h2 with a class of title. After some googling, I found my solution! If I could select the h2 element (which I needed for the text inside anyway), I could used the method #next_sibling( ) to get the text node that followed. I tested this out with binding.pry and it worked! I was able to grab that text for my project. </p>



### Learning Experiences:

<p> As my cohort instructor says, the world is your oyster with scraping. I would not have been able to complete this specific project without scraping. There are no high rated CLIs for what I was working on, especially with the amount of information I was using. However, scraping definitely has it's downside. With scraping, you are at the mercy of whatever the developers decided to do for their HTML. I got very lucky with the website I wanted to use for the most part, but even so, there were definitely some funky parts that made it more of a challenge. I had an absolute blast and would 100% choose this project again for my CLI, but I can see issues with only having scraping as a tool in your toolbox. </p>

<p> Something I was aiming to add in was the ability to iterate over attributes in an object. I spent a long while within binding.pry and googling to figure this out. I even asked my software developer husband and my instructor during our office hours. From what I gathered from the conversations as well as googling, this is something I will be able to do in the future when we go over Rails and Active Record. While this was a challenge I was not able to solve in the time we had, I still think this was a very important learning experience. It really helped me solidify the principle of getting things working first, then getting them to work in a DRY and beautiful way. I was able to get the same result with a less exciting way and in the future, with more knowledge and more tools, I will be able to implement a better stratgegy. Something I really took away from this is no one has all of the answers and it is completely okay to be a beginner. I look forward to finding the solution to this problem in the future and plan on making a blog post about it when I do. The learning is never finished and that is super exciting to me. </p>


### Insight: 

<p> I gained a lot of insight from this project and I want to provide a list here of the top ten tips I would give to someone just starting a CLI project at Flatiron. This is based on what helped me, what helped others I've heard from in my cohort, and what I wish I would have done looking back. </p>
1. **Use your resources!** Learn.co, Google, and your cohort are your friends. Don't be afraid to check in with all three if you're stuck. 
2. **Choose a project you're excited about**. Let that excitement fuel you. Making something you could see yourself using adds a lot to it.
3. If you're going with a project that you'll need to scrape for, **make sure the HTML is consistant**. I was lucky that my first website was very scrapable, but not all are. 
4. **Make your user stories and flowchart.** It may seem silly, but it is incredibly useful and developers use it on the job. It is a great way to think through your project and narrow down the classes you'll need and the flow you want to take.
5. **Be prepared to cut/add features**. Life happens and we don't get a lot of time for this project. My power went out for two days during this so a few of the features I wanted got cut. Make sure to start with the features most important (the Minimal Viable Project) and add each feature one at a time.
6. **Learn about Git Branches**. Something that really helped me during this was creating branches each time I was working on a new feature. I wish I would have learned about that closer to the beginning of the project. This ensures you always have a working copy with your Master branch and you can merge the new branch into the master when you have tested to make sure the new feature works.
7. **Test often.** Don't wait until you've written 50 lines of code to test. If you do that, you may have to follow the flow of your program to figure out where the bug(s) are happening. Trust me. I did this at one point. It was a longer process than if I made sure to regularly test.
8. **Get your method working, THEN refactor.** Don't spend an hour trying to figure out the most efficient way of doing something. Get it working, then you can make it pretty. It takes less time and can actually lead to finding some creative solutions.
9. **Comment out before removing**. This may just be a me problem, by I can't count the amount of times I removed binding.pry or some other piece of code thinking I don't need it only to realize very quickly that I do. Comment it out, if it still works, then you can consider removing it.
10. Last, but not least,** take breaks.** Coding is one of those amazing things that you can actually find the solution for while not actually doing it. Stuck? Take a walk (or whatever you decide is a fitting break)! It can really help to think about the solution while not looking at it. Even if you're not focused on thinking about your code, coming back to it with a fresh mind can be super helpful.
