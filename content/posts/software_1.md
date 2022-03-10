---
title: "Software_1"
date: 2022-03-09T21:14:04-05:00
draft: false
---

### About

Describe the software resource and explain its relevance to your topic. Please include the link to the software resource.

	- SQLMAP 
	- documentations (github repo)
	- git@github.com:sqlmapproject/sqlmap.git

---

### Features

Outline the main features of the software. Why is this software necessary for your work?

	- SQLMAP is a testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers.
	- It is open source, (so its free)
	- Supports 6 different types of injection techniques 
	- Support to directly connect to the database without passing via a SQL injection (by entering its ip address)
	- Automatic recognition of password hash formats and support for cracking them
	- Support to dump database tables entirely
	- You can seatch for a specific database, tables, and columns per user request

---

### Obtaining the resource

Where do you find this software resource? Is it an open source project? an online tool? How do you install it? Are there any libraries that are also necessary to install?
	
	- If you do a simple google search you should find a website called sqlmap.org
	- Open source 
	- The program is on github (you can clone the repo) 
	- Download it from a zip file

---

### Setup

Include steps of all necessary steps to get the software to run (for example, installations). Include the commands to run if necessary.

	- Installation: 
		- before installation, make sure to have xcode up to date (ver 9 min)
		- open terminal
		- enter command: 
			- ruby -e "$(curl -fsSL https://raw.githubsercontent.com/Homebrew/install/master/install)" </dev/null 2>/dev/null
		- enter password for your machine
		- after that enter this command 
			- brew install sqlmap
	- congrats you have installed SQLMAP :)

---

### Execution
 - pictures are in the images folder (same repo)
How do you get the resource ready to use? Are there inputs to know? Please show a step-by-step guide (in a tutorial format) for readying the resource for your work. Include screenshots of successful execution and use of the software.
	- enter this command to bring up an help list (good for beginners)
		sqlmap -h
	- if you are an advance coder or hacker, there are more commands on the github website under Wiki, go to usage (on the right side of the screen). 
	- enter command to see how the program runs
		sqlmap --wizard
	- enter the website below for testing purposes only (it will fail)
		- website: https://localhost/
	- press `enter` if you don't have post data
		- look at image 4
	- press 1, 2, or 3 for different level of injection difficulty
		- look at image 5
---

### Helpful resources

Include some of the relevant resources (links, articles, etc.) that you used to write in your tutorial.

	- Youtube video for reference 
		- https://www.youtube.com/watch?v=nVj8MUKkzQk&t=989s
		- https://sqlmap.org
		- https://github.com/sqlmapproject/sqlmap

---

(Did you remember to add your name and GitHub account name and date to the top of this document?)
