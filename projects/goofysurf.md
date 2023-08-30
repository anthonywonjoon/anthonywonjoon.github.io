---
layout: project
type: project
image: /img/discord-logo.png
title: "GoofySurf"
date: 2021
published: true
labels:
  - Javascript
  - Github
summary: "A Discord bot for tracking surf reports"
---

<img class="img-fluid" src="../img/discord-logo.png">

GoofySurf is a Discord Bot, built using the Discord.js library, that utlizies the Surfline API in order to pull accurate wave, wind, and tide data on surf spots around O'ahu.

Why?:
* To reduce the redudant checking and relaying of information from one surf app to however many friends you go surf with, by centralizing it all in one server, where they can all see the same message
* To make a project that is relevant to myself and the people around me, while developing my Javascript skills and using REST APIs.

### Built With

![JavaScript](https://img.shields.io/badge/-JavaScript-000000?style=flat&logo=javascript)
![Node.js](https://img.shields.io/badge/-Node.js-222222?style=flat&logo=node.js&logoColor=339933)

<!-- USAGE EXAMPLES -->
## Usage

### /surflist

Returns you all the spots that the bot is currently able to pull surf data from

![image](https://user-images.githubusercontent.com/89366304/205186413-1197912d-9efd-44b8-ab7c-9b99b3ab8119.png)

![image](https://user-images.githubusercontent.com/89366304/205186626-e173db1e-f36a-4ac3-a911-5d41e9d71ab7.png)

### /surfreport *location*

Returns you the updated surf report from the requested spot

Requires parameter, location, which can be found in /surflist

![image](https://user-images.githubusercontent.com/89366304/205186827-c18d7fb5-e591-4787-a89c-fa55a0ddffd8.png)

This command will give you the following information:

- Time that the data was pulled
- Wave height, measured in feet, as well as the human relation
- Wind direction, in relation with the shoreline, as well as wind speed and gusts, measured in KTS
- The current tide
- The scores for both the waves and wind, calculated by Surfline, ranging from "Ass", "Good", and "Optimal"

![image](https://user-images.githubusercontent.com/89366304/205186855-3ec5adc4-7d3e-4fc2-8959-7799193703bd.png)

<!-- ROADMAP -->
## Roadmap

- [ ] Add Changelog
- [ ] Figure out how to pull exact current data
- [ ] Add in more spots around Oahu and the other Hawaiian Islands
  - [ ] Maui
  - [ ] Big Island
- [ ] Add in mainland spots, starting with California

Project Link: [https://github.com/anthonywonjoon/goofysurf](https://github.com/anthonywonjoon/goofysurf)
