---
layout: project
type: project
image: img/ham.png
title: "HappeningAtManoa"
date: 2023
published: true
labels:
  - Javascript
  - React
  - Meteor
  - MongoDB
summary: "HappeningAtManoa - Keep up with events around Manoa's Campus"
---

<img class="img-fluid" src="../img/ham.png">

Happening At Manoa is an application for members of the UH Manoa community to see what events are going on in their community as well as search for events that aligns with their interests. Our goal is to help build connectivity within the UH Manoa community with an application that will make knowing about and attending events more convenient.

Check out our Team's Github: ![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

### Built With

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Meteor JS](https://img.shields.io/badge/meteorjs-%23d74c4c.svg?style=for-the-badge&logo=meteor&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

## My Contributions, What I Learned, and Some Challenges

There were so many things that were introduced to me while working on this project, from working based off of issue-driven management, to working with others in one code base, and even in things such as design. 

My main contributions to this project was the development of the landing page, as well as the image upload feature. The biggest challenge I faced was how to actually implement that latter feature; Do we implement something like an AWS S3 instance or Google Bucket, then save the public URL to our database? Do we physically copy the uploaded image into our codebase directory? After struggling with this for a while, trying to determine the best course of action, I was able to reach a conclusion by talking with my teammates, Professor Port, and a guest speaker that had come into class that week. We decided that encoding the image into a Base64 string, and storing that string into our database would be the best course of action.

It felt like there was no one answer to that issue, and there never is. This challenge taught me that there are so many ways of doing the same thing, you just need to figure out what works best with all your other implementations. It also shed light on one of the most important aspects of doing this project: communication. In a group of 5 students, all with different backgrounds, experiences, schedules, and interests, communication was the number one factor to success. Being able to communicate ideas, concerns, and suggestions in a constructive, yet efficient way is so important when working in a group. It is definitely the number one thing I am taking away from this project.

## Screenshots
![landing-final-final](https://github.com/anthonywonjoon/anthonywonjoon.github.io/assets/89366304/febebf74-e90e-4910-ac2d-28586eab4cf3)
![about-real-m2](https://github.com/anthonywonjoon/anthonywonjoon.github.io/assets/89366304/c7c30e4f-7400-4537-9815-fb679b81f82c)

