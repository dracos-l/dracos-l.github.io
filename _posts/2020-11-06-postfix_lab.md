---
layout: post
title: Postfix Lab
subtitle: Evaluating a Postfix Dataset
---

## The Average!
 
 Starting it off strong, The value I got for the average was __529.91__!


## How do we use a stack for postfix?

 So how I used a stack to evaluate the postfix expressions was that ever time an integer came up in the dataset, I added it to the stack. Building up all of the numnbers in the stack, they only interact with each other when a function comes along. Then, the top two numbers in the stack get either added,subtracted,or multiplied, and then pushed back into the stack. This process continues until the line of postfix is completed! A helpful website for visualizing this method is linked [here](https://www.free-online-calculator-use.com/postfix-evaluator.html).

## My method and other stuff

 The first thing that I did in the process of working out the postfix was that I read through the hints and thought that an ```evaluate()``` would be very useful. I typed out the data reader code quickly, and slapped a place-holder in so that once I wrote my evalate code, I would already have it set to go(I also pasted in the Stack code, as the hints said). Then, in an effort to understand postfix and how I could use stacks to read through them, I did a bit of research online, using mainly the site I linked above. Based on that research, I figured out how to use a stack to evaluate postfix, and I put it into place with my code. Luckily I didn't have many issues with this lab, which is nice, but also would have been nice to have a bit more of a challenge :). I helped out Lucca and Ethan(because by the time they got the assignment on Tuesday I had basically finished my code). It was a nice wrap up to stacks, especially including datasets again. Like I said, this was basically just writing 1 def, so in the future might be nice to have a couple more to write!(Like the optional one that generated it. Would have been interesting to have to create our own csv with 100 lines and then evaluate it. Just a thought).