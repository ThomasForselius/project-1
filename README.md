# Friend Feud

Friend Feud is a social multi event real life game where friends compete against or with eachother to gain points in every event througout the year.
The website will act as a live results page, where current standings and coming events are displayed in chronological order. 

There will be a register page where you sign up and apply to comepte in one of these games. 
Anybody can register, and as soon as you have registered, you can create your own game of events. 


![Responsice Mockup](https://github.com/lucyrush/readme-template/blob/master/media/love_running_mockup.png)

## Features 

- Landing page ; will have a short but fun description of what the game is and how it works
- About the game ; this page will describe what the game is in more detail and what rules are applied
- Events ; this page will show all the planned events throughout the year, with dates, type of activity, teams or solo, location. (future bonus feature: make events "mystery event", where only date, time and location are displayed)
- Results ; will display the current results of the current game you are a part of
- Sign up / Login ; a new user will sign up for an account to be able to join a game, while an existing user can log in and either administrate(if they created a game), or edit an existing game they created


### Existing Features

- __Navigation Bar__

  - Featured on all pages except admin page(future feature), the full responsive navigation bar includes links to the Logo, Home page, results page, events page and Sign Up page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)

- __The landing page__

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
  - "red thread swirling downward, left to right and vice versa with a card for each event
    - onClick : will pop up a larger version of that eventcard with more details

![Events page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __Results page__ 

  - This page will show the current (and past) results, wins and losses. 
  - One main card will display the total score so far in the whole game
  - separate cards will display the top 3 scores of each individual event
    - onClick : will pop up more detailed info about that event i.e.  all contestants and their scores

![Results](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __The Sign Up Page__

  - This page will allow the user to either register or log in to the webpage. 
  - When they register they will have to provide First name (required), last name (optional) email (required) and password (required).
  - when they login they can edit their email, password and name. Also they can choose to delete their account from the site
  - Future feature: log in as admin to CRUD an event
 
![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)






For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- "Mystery event" function; where the admin can check an event as mystery, so only time, location and date are displyed for extra fun factor
- Admin page ; give people the opportunity to CRUD (create, read, update and delete) event information
- light / dark mode
- user page where users can upload profile picture that shows in the results list

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

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

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

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

-->
