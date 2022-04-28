---
title: "4 28post"
date: 2022-04-28T01:16:45-04:00
draft: false
---



My central goal for this assignment is to create a prototype that could take in live data and use it for comparison. For instance I need to find a way to get cpu cycle and ram usage every second. I would like to say that this portion is done. And I could successfully gathered live data. 

My next step is to create an experiment and test my live data that I just created. My research question is as follows. Can my prototype detect file less malware by using machine learning? Using cpu cycle and ram usage as a base, is it possible? Will it show up? 

For my experiment I want to find information regarding my own machine. I want to find a way to collect live data from `top` and `htop`. Currently that has been complete and I have successfully collected data from those sources. For my experiment I want to test if my prototype can handle spikes in data. For instance what happens when my cpu usage went from 20 to 80 than 35. How will my prototype handle that? Will it crash my code? In terms of what I need to find in order to answer my question, I need more data. But more importantly I need to know more about machine learning and the different types of machine learning algorithms.  

This will probably be solved in the future, when I get more knowledge in machine learning, but currently I want to find a way to compare old data to new data. 


result: 


After running my program, I have successfully gather data and putting them into a csv file. This is the most important step. Afterwards I can plot them and see if there are any connections or similarity. In the future, there will be a machine learning aspect to my project. But currently I would like to show something, instead of nothing. 


```
CPU,RAM
68.2,64.2
64.0,64.2
62.3,64.0
64.2,64.0
60.1,63.8
57.2,63.9
58.2,63.8
68.0,64.4
65.8,64.3
73.9,64.8
```

The above block of numbers is from my csv file called mycsv.csv. As you can see, numbers are changing every row and every column. My previous version does not take in live data. So plotting my last version does not really make sense. But now, since it contain real data, I can do something with it. 