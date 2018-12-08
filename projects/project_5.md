---
layout: project
type: project
image: images/miensfeld.png
title: UHM Flea Market
permalink: projects/UHM Flea Market
# All dates must be YYYY-MM-DD format!
date: 2018-12-8
labels:
  - C
  - Github
  - Software
summary: Many college campuses have a very active second hand market, and UH Manoa is no exception. College students try to stretch their limited income by buying used goods and by selling things they no longer need. Previously, students used websites and apps such as Facebook Marketplace, Craigslist, and Letgo, but they are open to the general public which can lead to problems such as scams, robberies, and general inconvienence. Now, with our app they will have a place to trade with other UH Manoa students. Students can feel safe knowing they aren't dealing with an anonymous (and potentially criminal) stranger, and they can meet eachother between classes instead of trying to meet someone half way across town.
---

# About UHM Flea Market

The UHM Flea Market is a Meteor application that will offer UHM students a chance to buy and sell everyday college needs, safely.

- Have students login with their UH credentials to access the system
- Connect buyers and sellers through UH credentials
- Items and services offered on this site will be geared specifically towards UHM students
images

# User Guide
[Here](https://uhm-flea-market.meteorapp.com/) a demo of the UHM Flea Market

You will be greeted by the following landing page: 
![](images/landing.png)


Once you logged in, you will be redirected to a login page where you must use your UH username and password:
![](images/login-page.png)


If you are a new user, you will be able to create a new account: 
![](images/create.png)


After logged in, users will be directed to the Home Page where user able to view items, cost, seller, and item condition:
![](images/M3userhome.png)


By clicking into the selected items, user will be able to view the items and seller in details. 
![](images/item_view.png)

User also able to leave message and contact the seller.
![](images/item_edit.png)

Directed from the Home Page, user able to view its profile, meeting history, past post, creating new post, and contact admin. 
![](images/userprofilepage2.png)

User will be able to add item to sell. 
![](images/add_item_page.png)

By clicking on the Messages button in the top right of several of the pages, you reach a DM feature with other users.
![](images/messages1.png)

# Developer Guide

1. install [Meteor](https://www.meteor.com/install).

2. Download a copy of The UHM Flea Market, or clone it using github.
  
3. cd into the app directory with:
```
$ cd app
```
4. Install libraries with:

```
$ meteor npm install
```

5. Run the system with:

```
$ meteor npm run start
```

The application will appear at [http://localhost:3000](http://localhost:3000).

# Development History

The development process for the UHM Flea market follows the [Final Project](http://courses.ics.hawaii.edu/ics314s17/morea/project-management/reading-screencast-idpm.html). The development consists of a sequence of Milestones that consist of issues corresponding to the tasks. GitHub projects are used to manage the processing of tasks during a milestone.  

The following sections document the development history of the UHM Flea Market.

## Milestone 1: Mockup Development and Authentication

Milestone 1 started on Nov 5, 2018 and completed Nov 15, 2018. 

The goal of Milestone 1 is to combine all of the groups idea developed during our own mockup of this project and combine these pages to create an application that is uniform in looks and has the links to the other pages. These pages will be developed as a Meteor app and will be implemented in order to get the routing to the other pages to work.

Mockups for the following pages were implemented during M1:

<img width="220px" height="140px" src="images/landing-page.png"/>
<img width="220px" height="140px" src="images/home-page.png"/>
<img width="220px" height="140px" src="images/itemview.png"/>
<img width="220px" height="140px" src="images/userprofilepage.png"/>

Milestone 1 was implemented as [UHM Flea Market Github Milestone 1](https://github.com/uhmfleamarket/postr/projects/1):

![](images/M1.png)

Milestone 1 consisted of 6 issues, and progress was managed via the [M1](https://github.com/uhmfleamarket/postr/issues):

![](images/M1-issues.png)

Each issue was implemented in its own branch, and merged into full-site-test-merge when completed:


## Milestone 2: Data Model Development

Milestone 2 started on Nov 15, 2018 to ended Nov 27, 2018.

The goal of Milestone 2 is to start working on the application's functionality by implementing the data model. 

Mockups for the following pages were implemented during M2:

<img width="220px" height="140px" src="images/landing.png"/>
<img width="220px" height="140px" src="images/login-page.png"/>
<img width="220px" height="140px" src="images/user-home-1.png"/>
<img width="220px" height="140px" src="images/user-home-2.png"/>
<img width="220px" height="140px" src="images/user-home-3.png"/>
<img width="220px" height="140px" src="images/itemview.png"/>
<img width="220px" height="140px" src="images/userprofilepage1.png"/>
<img width="220px" height="140px" src="images/messages.png"/>

Milestone 2 was implemented as [UHM Flea Market Github Milestone 2](https://github.com/uhmfleamarket/postr/projects/2):

![](images/M2.png)

Milestone 2 consisted of 11 issues and progress was managed through [Manoa Flea Market Github Milestone 2](https://github.com/uhmfleamarket/postr/issues):

![](images/issue2.png)

Each issue was implemented in its own branch, and merged into master when completed:

![](images/work2.png)

## Milestone 3

Milestone 3 started on Nov 28, 2018 and ended Dec 6, 2018.

The goal of Milestone 3 was to completet all the applications functionality and the appearance of the application. 

Mockups for the following pages were implemented during M3:

<img width="220px" height="140px" src="images/landing.png"/>
<img width="220px" height="140px" src="images/login-page.png"/>
<img width="220px" height="140px" src="images/create.png"/>
<img width="220px" height="140px" src="images/user-home-1.png"/>
<img width="220px" height="140px" src="images/user-home-2.png"/>
<img width="220px" height="140px" src="images/user-home-3.png"/>
<img width="220px" height="140px" src="images/add_item_page.png"/>
<img width="220px" height="140px" src="images/itemview.png"/>
<img width="220px" height="140px" src="images/userprofilepage2.png"/>
<img width="220px" height="140px" src="images/messages1.png"/>

Milestone 3 was implemented as [UHM Flea Market Github Milestone 3](https://github.com/uhmfleamarket/postr/projects/3):

![](images/M3_issues.png)

Each issue was implemented in its own branch, and merged into master when completed:
![](images/M3.png)

# Community Feedback
At the end of milestone 3, we recruited a few of our friends and classmates to look at our application and give us feedback on their inital impression, missing functionality-wise, and the overall ease of using the application. 

Each student reviewer was given a brief description of the purpose of the application. However, the biggest concerns we got back from the student reviewers was the lack of having the website completely finished. One of the biggest issue we had was there are no items in listed in our Market page. Listed below is the full response from each reviewer. This is complete anonymous so reviewers name will no be show, however, we have listed their major to see how their background affected how they saw the application. 

> 
> Some of the function did not seem to be working correctly. It is not effective to ask for URL when creating account. 
> The market page seemed incomplete since the item isn't added to the market page, however, it easy to keep track of items > on the userpage. The message did not seem to be working correctly either.  
> 
> -- <cite>UH Junior, Electrical Engineering</cite>
>
> 4/5. Would appreciate a feature to show if a user is online.
> -- <cite>UH Senior</cite>
>
> The user home page displays items quickly.
> -- <cite>UH Senior</cite>
>
> Nice layout. Very clear and to the point.
> -- <cite>UH Senior</cite>
>
> I like how you're able to scroll through.
> -- <cite>UH Senior</cite>
>
> Good! I like how it's user friendly.
> -- <cite>UH Senior</cite>
>

# The Team

## Austin Haigh
My goal for this project, apart from getting a good grade in this class, is mainly to finish another project that I can put on my resume. I'm best at backend development and have a few years of experience with Javascript. I hope to develop better team collaboration skills during this project.

## Jiayu Xu
My goal for this project is to have fun and create something that is interesting and useful. I want to apply the skills I learned so far in 311 into creating something amazing. I want the finished product to be attractive and easy to use. Payment system should be seamless and effective. Ebay, Craigslist, Letgo, is kind of ugly and complicated. The goal is to link sellers and vendors together hasslefree.I also want to create a effective escrow/ payment system to enable this. In general e-commerce is kind of clunky. We want to make peer to peer commerce more attractive. We want vendors and buyers to be ranked based on their performance.

## Zero Wu
My personal goal for this project is to have to get more experience on application creation. I find these experiences to be very useful in the field and it a good presentation to shows what I have work on and skill. Making selling produce page have become a very common in the modern day, it will be useful when I want to create my own product page in the future.

## William Cole
My personal goal for this project is to gain confidence building an application, and feel more confident as a "software developer".

## Davon Moss
My goal for this project is to experience working with a team to reach a finished product, so that I can bring that knowledge to the job market. I am mostly interested in developing the front-end of the application, and ensuring that our app is well desined and intuitive. I hope to learn more from my teammates about back-end and database design. 

# Big Picture Vision
Hopefully, tradr will become a useful and convenient tool for students looking to optimize their college experience. Tradr could even be extended past the UHM campus and become an application that is implemented across multiple campuses nationwide.
