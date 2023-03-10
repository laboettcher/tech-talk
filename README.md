# Tech Talk
![Github license](https://img.shields.io/badge/license-MIT-blue.svg)

## Description

Tech Talk is a tech blog where developers can publish their own blog posts and comment on other users' posts as well.

## Tabe of Contents

* [UserStory](#user-story)

* [AcceptanceCriteria](#acceptance-criteria)

* [Installation](#installation)

* [Mock-Up](#mock-up)

* [DeployedApplication](#deployed-application)

* [License](#license)

* [References](#references)

## User Story

```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

## Acceptance Criteria

```
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
```

## Installation

```
npm i
npm i express
npm i express-handlebars
npm i express-session
npm i mysql2
npm i sequelize
npm i connect-session-sequelize
npm i dotenv
npm i bcrypt
```

## Mock-Up

<img width="1192" alt="Screen Shot 2023-02-11 at 5 37 19 PM" src="https://user-images.githubusercontent.com/114205917/218288422-0fa75648-6724-4a54-a3e1-90c839bd13ef.png">

## Deployed Application

Check it out [here.](https://tech-talk-blog-2.herokuapp.com/)

## License 

```
 MIT
``` 

## References

* [Backdrop](https://docs.backdropcms.org/api/backdrop/functions?object_name=&summary=&page=35&order=file_name&sort=asc)

* [DeployHeroku](https://coding-boot-camp.github.io/full-stack/heroku/deploy-with-heroku-and-mysql)

* [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getFullYear)

* [MDN2](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)

* [SitePoint](https://www.sitepoint.com/understanding-module-exports-exports-node-js/)

* [StackOverflow](https://stackoverflow.com/questions/11817950/what-is-data-serialization)

* [StackOverflow2](https://stackoverflow.com/questions/27194359/javascript-pluralize-an-english-string)
