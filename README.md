# FriendFeud - project documentation

This is the README.md descriptive file of the project FriendFeud;
an original web project from Thomas Forselius, studying font-end webdevelopement at CodeInstitute. 

The homepage can be found on the following link: [FriendFeud](http://www.friendfeud.se)


# Table of Contents

>1. [What is FriendFeud?](#what-is-it)
>2. [UX Design and wireframe mockup](#ux-design)
  >- [Typography](#typography)
  >- [Color Scheme](#color-scheme)
>3. [Existing Features](#features)
>4. [Future Features](#future-features)
>5. [Technologies](#technologies)
>6. [Testing](#testing)
>7. [Deployment](#deployment)
>8. [Credits](#credits)


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

## Typography

There are only two fonts used, to keep it simple and clean. 
  * Italiana - a serif font used for Hero text and navigation
  ![Italiana](https://thomasforselius.github.io/project-1/images/italiana_ss.png)
    > Link to Google fonts https://fonts.google.com/specimen/Italiana 
  * Manrope - a sans serif font used for all other text due to it's good readability
  ![Manrope](https://thomasforselius.github.io/project-1/images/manrope_ss.png)
    > Link to Google fonts https://fonts.google.com/specimen/Manrope

## Color Scheme

The main idea behind the whole concept is keeping it simple. Therefor I chose black and white with some subtle hints of color. 

  * White text: 
    - Navigation
    - Header text
    - Text in sign up form
    - Call to action button on first page

    The reason I chose white text color for these is because of the dark background on the webpage, so the white makes for great contrast

  * Black text: 
    - Header on main text container
    - Main information text

    The reason I chose black text color for these is because of the white background for the main information, so the black makes for great contrast

  * Other color features: 
    - Mobile device responsive drop down menu has a blurred black background. 
    The reason for this is mostly to 'spice' up the design in a very simple yet intresting way, in contrast to most other mobile menus which are a plain color with no transparency. 
    
    _It's a rich feature with a low price tag_
    - Fading in dark background on the call to action button on the first page. 
    The first reason for this is to make a simple but intresting design feature to keep the user intrested and get a slightly 'alive' feel of the page. 
    The second reason is that I wanted to try something new that I haven't tried, and I fel that this effect would suit the page perfectly due to it's clean nature
    - Fading in red outline of input text areas on sign up page
    The first reason I chose this is to draw attention to the current input text box 
    The second reason is I like to play around with effects and experiment with new ideas I haven't tried before
    _To be honest, this is probably the strongest reason haha_

# Features


## Navigation Bar

* The navigation bar is displayed on all pages, the full responsive navigation bar includes links to the Index page, results page, events page and Sign Up page and is identical in each page to allow for easy navigation.
* This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 
* There are two types of menu bars on the page; both whitch are mutually exclusive via @mediaquery in _style.css_ to fit responsive design and mobile devices
* The links in the menu are the following: 
      * Home, What is it?, Events, Results, Sign up / Login 

## _Desktop and tablet version_

![Nav Bar Desktop](https://thomasforselius.github.io/project-1/images/menu_desktop.png)

## _Mobile version_ 
  - When clicked on 'Menu' the pop-down menu will appear with blurred background
  - This menu has the attribute 'Sticky' , so it is always at thte top of the screen


![Nav Bar mobile - closed](https://thomasforselius.github.io/project-1/images/menu_mobile.png)

![Nav Bar mobile - open when clicked](https://thomasforselius.github.io/project-1/images/menu_mobile_active.png)


## Links 

* These are the links to easily navigate around the website. 
  They are always available on all pages to increas the easy of use when moving around on the page. 

  * Home
      - This is the first page the user sees when visiting the page;
      It has a very short but informative description of what the game is and how it works.
      also has a call to action in the form of a button that takes the user to the page where they can register for the game. 
  * What is it? 
      - this page describes what the game is in more detail like rules and a brief history of how the game came about. 
  * Events
      - shows all the planned events throughout the year. Each event will have a card with the following information: 
        Date, type of activity, team event or solo, location and directions how to get there
  * Results 
      - Displays the current standings of the active game you are participating in. At the moment this feature is a work in progress since it will be utilizing javascript and a database, which are outside of my knowledge as of today. 
      There is a graphical mockup of what the leader board may look like when it launches
  * Sign up / Login _note 
      - This is a future feature due to the need for database and javascript knowledge which I do not have right now


## Pages

* The landing page / Home
  This is the first page the user sees when visiting the page;
  It has a very short but informative description of what the game is and how it works.
  also has a call to action in the form of a button that takes the user to the page where they can register for the game. 
  This section SHORTLY ( ca 5-10 seconds after entering page) describes what the game is about and how they sign up; this is where the call to action button is on the first page

  _Selling point - get their attention. by writing a small but intresting bit of info about the game you keep or increase people's attention to keep them on the page_

![Landing Page](https://thomasforselius.github.io/project-1/images/home_splash.png)

* What is it? ; this page describes in more detail what the game is about, how many players, what type of activities, how points are counted as well as rules and regulations

![What is it?](https://thomasforselius.github.io/project-1/images/what_splash.png)

* Events ; shows all the planned events throughout the year.
    Each event will have a card with the following information: 
      Date
      Type of activity
      Team event or solo
      Cost
      Location and directions how to get there

![Events page](https://thomasforselius.github.io/project-1/images/events_splash.png)

* Results ; displays the current standings of the active game you are participating in. 
    At the moment this feature is a work in progress since it will be utilizing javascript and a database, which are outside of my knowledge as of today. 
    There is a graphical mockup of what the leader board may look like when it launches

![Results](https://thomasforselius.github.io/project-1/images/results_splash.png)

* Sign up / Login _note: this is a future feature due to the need for database and javascript knowledge which I do  
    not have right now
    A new user will sign up for an account to be able to join a game.
    Existing user/s can log in and either administrate(if they created a game), or edit an existing game they created

  _At the moment, when you fill out the register form_

    This page will allow the user to either register or log in to the webpage. 
    When they register they will have to provide the following information: 
      First name (required)
      Last name (Required)
      Email (required)
      Password (required)

    In the future, when they log in they can edit their email, password, name, upload an avatar and choose to delete their account from the site by entering password as a confirmation 
    _Required tech for full funcitonality: deeper CSS knowledge_

![Sign up](https://thomasforselius.github.io/project-1/images/signup_splash.png)


## Future features

* Sign up page; 
    There will be a register page where you sign up and apply to comepete in one of these games. 
    Anybody can register, and as soon as you have registered, you can create your own game of events. 
    * At the moment this is just a mockup since the I don't know the required tech
    >_Required tech for full funcitonality: Javascript and database knowledge_
* Log in as admin to CRUD(create, read, update, delete) an event and edit scores
    >_Required tech for full funcitonality: Javascript and database knowledge_
* User page - where users can upload profile picture that shows in the results list
    >_Required tech for full funcitonality: Javascript and database knowledge_
* Bonus feature: make events "mystery event", where only date, time and location are displayed
    >_Required tech for full funcitonality: Javascript and database knowledge_
* Live results - will display the current results of the current game you are a part of when logged in
    >_Required tech for full funcitonality: Javascript and database knowledge_
* Light / dark mode
    >_Required tech for full funcitonality: deeper CSS knowledge_

* Events page;
  * Design ideas for events page with cards
    * red thread swirling downward, left to right and vice versa with a card for each event
      * onClick : will pop up a larger version of that eventcard with more details
    * separate cards will display the top 3 scores of each individual event
      * onClick : will pop up more detailed info about that event i.e.  all contestants and their scores

  >_Required tech for full funcitonality: Javascript and database knowledge_



# Technologies


* Figma
  * Figma is a free web software for drawing design mockups easily. I used that as a visual kind of brainstorming when drawing up the wireframe
* HTML
  * This is the markup language that makes up the structure of the webpage
* CSS
  * This is the styling languange that gives the webpage it's visual design
* Google Fonts
  * There are two fonts imported from Google Fonts used on the whole page: 
    * Italiana
    * Manrope
* VS Code
  * the IDE (Integrated developer environment) that is used to code everything, commit and push to github with the git method
* Google Chrome
  * Web browser for viewing the webpage
* Google Chrome developer tools
  * Used for inspecting and bug testing the webpage and responsive design
* Git verison control via GitHub
  * Git is the version control software used to commit and push code to the GitHub repository 
* GitHub
  * this is where the source code and images is stored online - also called a repository.
    The live page uses the main branch in the Github repository. 
    >_All coming updates will each be using a separate branch for a function, to ensure easy updating and version control_
* Testing:
  * W3C HTML Validator
  * W3C Jigsaw CSS validator
  * Chrome Dev tools Lighthouse Accessibility validator

# Testing 

The whole building of a website is an ongoing test and coarse debugging process, which is very nice, since you get virtually immediate feedback when working with the visual part. 

Building this website I have used VS Code for the coding, while Google Chrome for the visual feedback on a local server extension. This lets me test the webpage out before commiting and pushing it to Github for live testing with online extensions and validators like Lighthouse, W3C html validator and W3C CSS validator. 

My testing procedure is conducted on the live Github repository using the following tech / apps / extensions / plugins / webpages: 

* Web browser
  * Google Chrome
  * Safari
* Visual 
  * Both HTML structure and CSS styling is tested on each web browser
* Functionality testing
  * Each link is tested on both browsers against all separate links on the page. 
    i.e.(home -> events; events -> results; results -> what is it? etc etc.)
    > No broken links found
  * Responsive design tested automatically with http://ami.responsivedesign.is
  * Responsive sizing tested manually with Chrome Dev tools Inspector
    * Desktop version on screen size larger than 850px 
    * Tablet version on screen size between 440px - 850px
    * Mobile version on screen size between 220px - 440px
      * No further testing required on smaller screen sizes since no current devices use such small resolutions. 
        _Well; that would be a smart watch, but that's just madness, if it's even possible._
    

* Last series of checks
  * Go through HTML code and clear commented code, clear double empty lines so that no more than one empty line in a row is found. 
  * Check that all images appear in both the webpage and the readme.md file

### Validator Testing 

* HTML
  * No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthomasforselius.github.io%2Fproject-1%2Findex.html)
* CSS
  * No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fthomasforselius.github.io%2Fproject-1%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)
* Accessibility via Lighthouse extension
  [Lighthouse](https://thomasforselius.github.io/project-1/images/lighthouse_validator.png)
* Responsive validation was done by using the following website: [Am I responsive](http://ami.responsivedesign.is/)

### Unfixed Bugs

Known bugs: 
  * Drop down menu doesn't close on mobile screens when using Safari
  * www.kompiskampen.se is bought, but not yet linked to the github page

## Deployment

* The site was deployed to GitHub pages through VS Code commit and push commands. The steps to deploy are as follows: 
  * In the GitHub repository, navigate to the Settings tab 
  * From the source section drop-down menu, select the Master Branch
  * Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

* Once the main branch has been deployed I commit and push from VS Code to the Github repo and main branch. 


The live github link can be found here - https://thomasforselius.github.io/project-1/
Also, the following domains have been bought: 
  * www.frienfeud.se (working domain name)
  * www.kompiskampen.se (not working at the moment)


## Credits 

* Credit for pop-down menu when on mobile device goes to https://isabelcastillo.com/pure-css-mobile-toggle-menu


## Media

* Background image is taken from www.pixabay.com - a page with royalty free images for commercial use without attribution
https://pixabay.com/photos/people-friends-together-happy-kid-4050698/


### Content 

- The readme file was copied from CodeInstitute's template for the first project in their 5p front-end dev course
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- CSS validation was done by using the following website: 
- HTML validation was done by using the following website: 

