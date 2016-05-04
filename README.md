# Introspect

A web app that helps you better understand yourself and the traits you are attracted to in others. Based on the traits you found attractive in past and current love interests, this app will analyze and represent the data in a way that may reveal patterns and surface the traits most important to you.

There is still much work to do on this web app! We have decided to keep the repository private, but would still like to display the work we have thus far. Check it out on [Heroku](https://gentle-reef-66432.herokuapp.com), or take a look at the photos below.

## Overview

The user starts by selecting the traits that are important to them in a relationship. These traits fall under predetermined categories. Within each category, the user can select a favorite trait.

![Traits](imgs/traits.png)

Create a chronological list of relationships, including crushes, boy/girlfriends, and hookups. Easily edit this list at any time.

![Interests](imgs/interests.png)

From the data in this list, Introspect will create a history bar graph that displays all interests in relation to the time the user and interest were together and their affinity to each other.

![History Graph](imgs/history_graph.png)

Clicking through this bar graph takes us to individual break downs of each interest. From here, the user can assign a score to each interest based on how they met their desired traits.

![Donut Graph](imgs/donut_graph.png)

Once the user has filled out their interests and traits, they can recieve a custom analysis of what they find truly important in a relationship. Users initially selected which traits were important to them in each category. They can also select the top five relationship where they were happiest or least happy. Introspect looks at all of this data, and creates a bubble graph representing the traits that were most prevalent in these relationships compared to the traits the user initially identified as important to them.

![Dissonance](imgs/dissonance.png)

## Stack

Introspect backend was created and accessed with MongoDB and the Mongoid Gem. The app is built with Ruby on Rails and JavaScript. Visual representations of our users' data are built with D3. Bootstrap helped us quickly design the frontend.

## Team

This project was completed with a team of four Dev Bootcamp students.

<a href='https://github.com/kmeyer313'>Katie Meyer</a> | <a href='https://github.com/torihuang'>Tori Huang</a> | <a href='https://github.com/tenzaej'>Eric Tenza</a>
:---: | :---: | :---:
<img src="imgs/katie_meyer.jpeg" alt="Katy Meyer" height="150"> | <img src="imgs/tori_huang.jpeg" alt="Tori Huang" height="150"> | <img src="imgs/eric_tenza.jpeg" alt="Eric Tenza" height="150">
 **<a href='https://github.com/shavah'>Jones Melton</a>**| **<a href='https://github.com/ty-doerschuk'>Tyler Doershuk</a>**
<img src="imgs/jones_melton.jpeg" alt="Jones Melton" height="150"> | <img src="imgs/tyler_d.png" alt="Tyler Doershuk" height="150">