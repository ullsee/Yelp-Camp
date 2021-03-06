# [Trip-Reviews](http://bit.ly/trip1review)
A full-stack Node.js project from my web dev course with RESTful routing

## Initial Setup
![landing](./images/landing.png)
* Add Landing Page
* Add Campgrounds Page that lists all campgrounds

Each Campground has:
* Name
* Image

## Layout and Basic Styling
* Create header and footer partials
* Add in Bootstrap

## Creating New Campgrounds
* Setup new campground POST route
* Add in body-parser
* Setup route to show form
* Add basic unstyled form

## Style the campgrounds page
![home](./images/home.png)
* Add a better header/title
* Make campgrounds display in a grid

## Style the Navbar and Form
* Add a navbar to all templates
* Style the new campground form

## Add Mongoose
* Install and configure Mongoose
* Setup campground model
* Use campground model inside of routes

## Show Page
* Review the RESTful routes we've seen so far
* Add description to the campground model
* Show db.collection.drop()
* Add a show route/template

## Refactor Mongoose Code
* Create a models directory
* Use module.exports
* Require everything correctly!

## Add Seeds File
* Add a seeds.js file
* Run the seeds file every time the server starts

## Add the Comment model!
![comment](./images/post.png)
* Make comment errors go away!
* Display comments on campground show page

## Comment New/Create
![comment-add](./images/comment-add.png)
* Discuss nested routes
* Add the comment new and create routes
* Add the new comment form

## Style Show Page
* Add sidebar to show page
* Display comments nicely

## Finish Styling Show Page
* Add public directory
* Add custom stylesheet

## Authentication Pt. 1 - Add User Model
* Install all packages needed for auth
* Define User model

## Authentication Pt. 2 - Register
![signup](./images/sign-up.png)
* Configure Passport
* Add register routes
* Add register template

## Authentication Pt. 3 - Login
![login](./images/login.png)
* Add login routes
* Add login template

## Authentication Pt. 4 - Logout/Navbar
* Add logout route
* Prevent user from adding a comment if not signed in
* Add links to navbar

## Authentication Pt. 5 - Show/Hide Links
* Show/hide auth links in navbar
* Refactor The Routes
* Use Express router to reoragnize all routes

## Users + Comments
* Associate users and comments
* Save author's name to a comment automatically

## Users + Campgrounds
* Prevent an unauthenticated user from creating a campground
* Save username+id to newly created campground

## Editing Campgrounds
![edit](./images/edit.png)
* Add Method-Override
* Add Edit Route for Campgrounds
* Add Link to Edit Page
* Add Update Route

## Deleting Campgrounds
* Add Destroy Route
* Add Delete button

## Authorization Part 1: Campgrounds
![user-post](./images/delete.png)
* User can only edit his/her campgrounds
* User can only delete his/her campgrounds
* Hide/Show edit and delete buttons

## Editing Comments
![edit-comments](./images/comment-edit.png)
* Add Edit route for comments
* Add Edit button
* Add Update route
Campground Edit Route: /campgrounds/:id/edit Comment Edit Route: /campgrounds/:id/comments/:comment_id/edit

## Deleting Comments
* Add Destroy route
* Add Delete button
Campground Destroy Route: /campgrounds/:id Comment Destroy Route: /campgrounds/:id/comments/:comment_id

## Authorization Part 2: Comments
![delete-comments](./images/comment-delete.png)
* User can only edit his/her comments
* User can only delete his/her comments
* Hide/Show edit and delete buttons
* Refactor Middleware to a single file

## Adding in Flash!
![flash1](./images/flash1.png)
![flash2](./images/flash2.png)
* Install and configure connect-flash
* Add bootstrap alerts to header
