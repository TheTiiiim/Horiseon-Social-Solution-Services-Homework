# Horiseon-Social-Solution-Services-Homework

This repository is my first homework assignment of UNH Coding Bootcamp.
The goal of the assignment was to refactor an existing webpage so that it includes semantic html tags and consolidate css selectors and properties.
I started by determining the organization of the page, at the top is a navbar with the logo at the left and a few navigation links to sections of the page on the right.

The content of the page starts with a large image which I put in a `figure`, then the content splits into two columns, which I named `main` and `aside` and both of these are split into 3 `section`s.

The given webpage gave each of the sections in the future `main` a class defining the positioning of the contained images. 
To prevent having specific classes defining positioning of each image I went and used psuedo-classes to grab the even and odd child `section`s of the `main` element and assigning image positioning from there.

The deployed project can be viewed [here](https://thetiiiim.github.io/Horiseon-Social-Solution-Services-Homework/)

![screenshot.png](https://raw.githubusercontent.com/thetiiiim/Horiseon-Social-Solution-Services-Homework/main/assets/images/screenshot.png)
