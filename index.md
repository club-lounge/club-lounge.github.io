## Table of Contents
* [Overview](#overview)
* [Team Members](#team-members)
* [Implementation](#implementation)
* [Future Systems](#future-systems)
* [Mock Up](#mock-up)

## Overview
Club lounge is an web application designed for UH club community that allows club to create their own club page and event.
This application will be made with:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

## Team members
1. Jun Miao
1. Nomin Boldbayar
1. Vince Khyla Rabang
1. Sang Jin Lee

#### Goals for the project:
* Landing page (the homepage of the website)
* Create a club page
* Join a club page
* Upcoming events page

## Implementation:

#### Jun Miao - *Landing page*
* If user is not logged in, site would only display the landing page with no navigation bar. From the landing page, there would be the site name and a little description about what the application would do. There would be two buttons at the center of the page to prompt user to either login or sign up.
* If user is logged in, then navigation bar would be visible with the appropriate options. On the landing page, the login and sign up options would be replaced with mini-window of upcoming events.

#### Nomin Boldbayar - *Upcoming events page*
* After user logs in, they can see the upcoming events page in the navigation bar. They can click on the link and it will show 
all the events hosted by the UH registered clubs. 
* All the events are formed as a card form of Semantic-UI React. Each card has information about the event itself, and who's hosting 
the event as well. In addition to the card, on each card, it will have two buttons, offering the user to register for the event and 
to see more information about the event. 

#### Vince Khyla Rabang - *Create a club page*
* When the admin is logged in, the admin will land on the admin page and on the navigation bar there will be a create club option. The admins are the only ones who can see the page.
* When the admin decides to create a club, the page will be a forum. The forum will ask the information of the club, such as the name, founder, email, etc. 

#### Sang Jin Lee - *Join a club page*
* There will be a search bar somewhere at the top where the user can search for the club that they would like to join.
* There will be a join button for each clubs and the user will be able to join however many clubs they desire.
* If the user has already join a certain club, a leave button will pop up if the user wants to leave the club that they have joined and will disappear once it is clicked.


## Future Systems:
* Different Navigation bar/pages for visitor/login-user/login club board members/administrator
* Abilities for Club page submition by user for admin approval
* Role system(club admin, etc) for club pages
* Display Upcoming event on the Club card
* Dynamic club pages
* Recommended Events page to offer the user based on their interests or attended events. 

## Mock up:

Display of recent event (like timestamped note) on the club card
![](http://courses.ics.hawaii.edu/ics314s20/morea/meteor-3/experience-meteor-digits-5-1.png)

Forms for creating a new club page
![](http://courses.ics.hawaii.edu/ics314s20/morea/meteor-3/experience-meteor-digits-4-1.png)
