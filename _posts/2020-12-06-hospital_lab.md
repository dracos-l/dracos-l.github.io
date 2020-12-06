---
layout: post
title: Hospital Lab
---

## My Process and Answer

 For this lab, the first thing I did was call the csv using a python file, which then printed into the terminal. I used the url and key on the documentation page and ran through every line of the csv using a for loop, and one issue I had in this section was that I was using json() when I just needed to be using text. I got through that fairly quickly, and moved onto cleaning the csv. The main time-consuming part was going through the bed standardizations. However, after doing this and adding in a couple values(such as washington's population), I could start writing the python code to run through the csv and find the highest bed per person in a county. This was fairly straightforward, given that we have done it several times, and the code is attached. Through this, I was able to find that __nassau(ACUTE)__ has the most hospital beds per person!

## Some other information

 In this lab, I worked partly with Ethan and Lucca. I didn't have much trouble, except with the errors with json which were quickly resolved. The cleaning of the dataset was a little arduous, but I decided that making everything 1000HAB would be easiest, because then I could just multiply some by 2 or divide by 2, depending on the county and bed type. Some main takeaways from this lab were that cleaning is very boring without music, and that if I am getting errors that I can't figure out immediately(json), try mixing things up and asking others!