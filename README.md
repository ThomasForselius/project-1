# FriendFeud - project documentation

This is the README.md descriptive file of the project FriendFeud;
an original web project from Thomas Forselius, studying font-end webdevelopement at CodeInstitute. 

# Table of Contents

>1. [What is FriendFeud?](#what-is-it)
>2. [UX Design and wireframe mockup](#ux-design)
>3. [Features](#features)
>4. [](#)
>5. [](#)
>6. [](#)


# What is it?

* Friend Feud is a social multi-event real life game where friends compete against, or with eachother to gain points in every event througout the year.
* The website will act as the main informative hub for the game, with a live results page(future feature using js), about page with information about the game and a sign-up page where you can join. 
* The idea behind the game is to target a very wide audience, to appeal to as many people as possible. 
Events will be of varying character, from both physical to intellectual, so as many people as possible can - and most importantly - feel the possibility to participate. 
* This game is the brainchild of Thomas Forselius, a student of CodeInstitute front-end developer program. I wanted a project where I could incorporate as many of the course's different parts as possible. This way I could get an immediate use for the knowledge I learn and be able to apply it in practice as well as in theory. 


# UX Design

## Responsive mockup of the webpage

![Responsive Mockup](https://thomasforselius.github.io/project-1/images/responsive.png)

* On of the most important features of webpages today is being responsive, since the largest amount of people view webpages on their mobile devices. Responsive websites are a must, if your goal is the keep the interest of the visitor
* My idea when creating this page is that I wanted to simple and esthetically pleasing design without too much flashy functions and design elements that draw attention away from the original idea and purpose. 
* The basic design was done in Figma - a free, easy to use online wireframing tool
* Colors used are simple - I wanted to keep it simple with a high contrast for maximum accessibility; 
    - Black text on white background - for main text 
    - White text on dark background - for menu and hero header text
* The background I chose is a group of people gathered in the sunrise/sunset to give a friendly sense of sharing fun events with friends. This background image cought my eye due to the very subtle nature of it; there's nothing distracting about the image so you concentrate on the webpage itself, but still get a sense of context of friendship
* The background image works well as a full page background that isn't too distracting, but also very well on responsive media
* Navigation styling is done with resposiveness in mind, so the desktop and tablet version of the menus are the same. 
  The width of the menu is adaptive so it's as resposive as possible.

## Links 

* There are 
  * Home
  * What is it?
  * Events
  * Results
  * Sign up / Login


# Features 

## Existing features 

* Landing page ; has a very short but informative description of what the game is and how it works
  - also has a call to action in the form of a button that takes the user to the page where they can register for the game
* About the game ; this page describes what the game is in more detail like rules and a brief history of how the game came about
* Events ; shows all the planned events throughout the year, with dates, type of activity, teams or solo, location
* Results ; displays the current standings of the active game
* Sign up / Login ; a new user will sign up for an account to be able to join a game, while an existing user can log in and either administrate(if they created a game), or edit an existing game they created
* Slight interest boosting functions are used; like fading bakground color on "join-button" and fading border color of input elements of the register form, to keep people's intrest in simple ways.


## Navigation Bar

* The navigation bar is displayed on all pages, the full responsive navigation bar includes links to the Index page, results page, events page and Sign Up page and is identical in each page to allow for easy navigation.
* This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 
* There are two types of menu bars on the page; both whitch are mutually exclusive via @mediaquery in _style.css_ to fit responsive design and mobile devices
* The links in the menu are the following: 
      * Home, What is it?, Events, Results, Sign up / Login 

## _Desktop and tablet version_

![Nav Bar Desktop](https://thomasforselius.github.io/project-1/images/menu_desktop.png)

## _Mobile version_

![Nav Bar mobile - closed](https://thomasforselius.github.io/project-1/images/menu_mobile.png)
![Nav Bar mobile - open](https://thomasforselius.github.io/project-1/images/menu_mobile2.png)


* The landing page

  - This page introduces the visitor to a photograph of friends playing a game or racing gocarts as an example
  - This section SHORTLY ( ca 5-10 seconds after entering page) describes what the game is about and how they sign up
    - Selling point nr 1 - get their attention

![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- __About page__

  - More detail regarding what the game is about, how many players, what type of activities, counting points
  - The user will get to see reasons they also should sign up for the friend feud. 
    - Note: this is selling point nr 2 - keep and increase their attention

![About page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- __Events section / page__

  - This section will allow the user to see exactly when the events will happen, where they will be located and what they will be. 

![Events page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __Results page__ 

  - This page will show the current (and past) results, wins and losses. 
  - One main card will display the total score so far in the whole game


![Results](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __The Sign Up Page__

  - This page will allow the user to either register or log in to the webpage. 
  - When they register they will have to provide First name (required), last name (optional) email (required) and password (required).
  - when they login they can edit their email, password and name. Also they can choose to delete their account from the site
 
![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)



## Future features

* There will be a register page where you sign up and apply to comepete in one of these games. 
Anybody can register, and as soon as you have registered, you can create your own game of events. 
* Log in as admin to CRUD(create, read, update, delete) an event and edit scores
* User page - where users can upload profile picture that shows in the results list
* Bonus feature: make events "mystery event", where only date, time and location are displayed
* Live results - will display the current results of the current game you are a part of when logged in
* Light / dark mode

* _Events_
  * Design ideas for events page with cards
    * red thread swirling downward, left to right and vice versa with a card for each event
      * onClick : will pop up a larger version of that eventcard with more details
    * separate cards will display the top 3 scores of each individual event
      * onClick : will pop up more detailed info about that event i.e.  all contestants and their scores


For some/all of your features, you may choose to reference the specific project files that implement them.
In addition, you may also use this section to discuss plans for additional features to be implemented in the future:



## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://thomasforselius.github.io/project-1/ 


## Credits 


- Credit for pop-down menu when on mobile device goes to https://isabelcastillo.com/pure-css-mobile-toggle-menu




<!-- 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 
--> 

### Content 

- The readme file was copied from CodeInstitute's template for the first project in their 5p front-end dev course
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- CSS validation was done by using the following website: 
- HTML validation was done by using the following website: 
- Responsive validation was done by using the following website: [Am I responsive](http://ami.responsivedesign.is/)
- The icons on the page were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site

<!-- 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

-->
