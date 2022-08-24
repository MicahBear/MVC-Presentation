# MVC-Presentation
Presentation on Model, View, Controller with additonal notes on mongoose schema and express router

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
Put to use the research I have done on the architecture design pattern Model View Controller. I will continue improve and share this research so other Software Engineers can improve with me. Making this information accessible and approachable is the priority.
### The challenge

Research and understand and apply

### Screenshot

![](./screenshot.jpg)


### Built with
- Canva

### What I learned

MVC
Model - is the database
View - is the client
Controller - is the server

the Model -- anything that interacts with data
- Adding and Retrieving items from DB
- Processing data from or to the database
- Speaks only with the Controller

the View -- anything that displays to the user
- This is the only thing the user ever sees
- Think of good old fashioned HTML/CSS
- Speaks only with the Controller --- doesn't really talk to the controller it Listens to the controller. The controller tells the view what to do

the Controller -- anything that interacting with the user
     ---Anytime you send a request to the server the controller is what is receiving the request/ what is processing the request.
- Processes GET/POST/PUT/DESTROY requests
- All server-side logic
- The Middle Man
	- Takes info from user
	- Processes info and talks to the DB if needed
	- Receives info from DB
	- Speaks to View to explain presentation to the viewer


### Continued development

- Update further with technical language
- Add animations
- Add additional references to benefical and accessible resources.

### Useful resources


