# Big Tomato Case Study - Final Assessment

Great work team! Farmer Toma Toe is very pleased with the MVP of his website. He thinks after a few more features he can deploy the site to his domain www.getsauced.farm. Toma’s daughter, Cherry, is addicted to FarmBook (the agriculture industry’s version of Facebook) and browses their FarmFeed (appropriately nicknamed “The Fertilizer”) all day long. After watching Cherry scroll through her feed, Toma realizes that the next feature he needs for his site is an announcements feed and he would like to name the feed, "The Vine".

The EY Developers have discussed the requirements with Toma at length. They have provided the following requirements and user stories for the announcements feed.

Note: If you completed the Big Tomato Case Study Intermediate Assessment - you will not be using that code repository. We have provided a blank slate for you.

## Pre-requisites:

* Register for a github account (if you do not already have one)
* Install Dependencies
* [Git tools](http://msysgit.github.io/)
* [Node JS](https://nodejs.org/en/)

## Setting Up Local Repository

Your local repository should be set up from the previous exercise. Add your code to your existing repository (i.e., "surname-final-assessment") based on the new requirements. 

## Requirements:

### General

* Use git branching (i.e., do not push code to master).
* Write all angular code (AngularJS 1.x) consistent with the [John Papa Style Guide](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md).
* DO NOT USE ES6 or later.
* Stick to the requirements, however, if you feel that there are other opportunities to improve the code or create new features feel free to do so.
* Remember, styling is important! This is going directly to a client. Feel free to add all custom styles to the main.css file.
* Your application should be mobile friendly.
* The application requires you to use Toma's Tomato Farm API. The API allows you to retrieve Tomato and Farm information.
  * The API has the following endpoints:
    * `http://localhost:3000/announcements` - Get All Announcements
    * `http://localhost:3000/owners` - Get All Announcement Owners
* We have created the basic file structure for your new code. Use this as guidance but feel free to change/add/remove additional files where you see fit. 
* In certain files we have indicated where to add your code. Use this as guidance but it does not indicate every section you may need to add code. Additionally, you need to add code to every section indicated if you do not see fit. 

## Part II

In Part II of the final assessment you will continue to work on the announcements feed. You will be adding additional features and professional styling. Refer to User Stories for the specific requirements. Please note that you may need to manipulate the data to fulfill all requirements. 

#### User Stories

* As a user, I want to see the Announcement 'Type' font-awesome icon included in the announcement.
  * The data includes a font awesome class style which can be used in the announcement. 
* As a user, I want to view the date in the following format: MMM. DD, YYYY (e.g., Jan. 15, 2018).
* As a user, I want all announcements to be default sorted by date (the most recent announcement at the top of the news feed).
  * Make sure the feed is being sorted by the actual date and not the string value of the date. 
* As a user, I want to be able to filter (not sort) announcements by Type (use a drop down menu).

Note: Make sure to use CSS to style the announcement feed and components so that it is professional and presentable. Feel free to use bootstrap - the framework has already been included in the application. This is the final product that will be going on Toma's website. 