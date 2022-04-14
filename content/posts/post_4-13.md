---
title: "Prototype"
date: 2022-04-13T20:30:36-04:00
draft: false
---

```
This prototype is important because it illistrates how everything is suppose to look for me. Meaning that this prototype is not just a preview to my user, but also to me. Overall I think the idea is doable, but I do need to implement a machine learning model for my detection system. Currently that portion is still a mystery for me. Hopefully sometime in the future, I can implement it.

Description:

Logic: My research topic is tackling invisible virus. In another words, fileless malware. For those who know, fileless malware is nothing new. It is just a malware that lives in the memory. If you know all of that, why should you care? You should care because fileless malware could potentially be on your system, and you don't even know about it. You may be asking/thinking that you can just restart my system to get rid of these viruses. But in reality, who does that? If I ask a random person on campus, and ask them do they restart they machine everyday, what will they say? People will response with I don't. Because it is inconvenient and not that many people know about it.
 
With that in mind, what is the logic for your software? Logic is simple. I need a program that takes in data from a sql database, and comparing values. Currently I am hard coding it. In the future, the layout and program performance will be upgraded. I will be comparing a known value with a gather value. Let me explain. By using a command like `top` or `htop` you will get your system specs (works with mac and linux; windows is unknown). 

There will be queries within the program. The query will grab the necessary data and compare each other. For example if X when idle has a ram usage of 2000, but after data gathering, X ram usage is now 6000. We can conclude that the PC may be affected. This logic applies with CPU cycles and temperatures.  