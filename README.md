# CIS350-hw1: Guess The Celebrity (Design)


## Survey:

We are interested in learning more about your views on software design.
Before starting the homework, please take the survey at https://upenn.co1.qualtrics.com/jfe/form/SV_8IjCWJzkXOF5cFg
that will gather your opinions. The survey should take about 5 minutes to complete.

## Instructions:
 
You will create an **app that implements the “Guess The Celebrity” game.*** 
If you are not familiar with the game, you can play a version of it at https://uquiz.com/quiz/B9MuCO/guess-that-celebrity.
The app will have a web and a mobile frontend, and a backend.


In this assignment, we will work on the design of the app.

- You will implement the web view/frontend in hw2
- You will implement mobile view/frontend in hw3
- You will test the web view, and refactor your code in hw4
- You will test, implement and deploy the entire app in hw5


## App Requirements:
 
- The user should enter their name (it will be stored along with their score). Your program should validate this as an alphanumeric string. No password is required
- If it is the first time that the username is entered, then it is stored. If it is a returning user, then their previous best score will be retrieved from the database
- Your app should display a picture of a celebrity one at a time and ask the user to guess/pick the celebrity's name. You should provide 4 potential answers with one being the correct one 
- Your app should contain at least 10 celebrities (10 questions) 
- Your app should pick the celebrity randomly (no hardcoding!) 
- Your app should keep track of the user’s score  
- Your app should display three scores while the user is playing the game: the user's current score, the user’s best score, and the app overall best score with the name of the user 
- Your app should have an option to display the top "k" players (username + scores) sorted by scores descending
- It is okay to keep "k" as a constant. For example, your app could only display the top 10 players 
- Your app should allow the user to delete their information from the app


## Design Tasks:
### Domain Modeling and UI Design:

- Your will convert all the requirements into user stories. You should have at least 4 user stories addressing login, attempting a question, displaying leaders, and deleting account
- You will create a userflow diagram (at least 4) for each user story. Your path in your diagrams must be exhaustive
- You will wireframe and prototype all the user stories based on the user flow diagrams. We strongly recommend that you use Figma, but tools like Lucidchart will work as well 
- You should create wireframes and prototypes for  mobile and web. Create a prototype for each user story
- Provide a class diagram for the app. It is okay to only provide the attributes and their types

### Architecture Design:

- We will use a MVC (Model-View-Controller) Restful architecture.
- You will create an exhaustive sequence diagram for each user story
- You will use SwaggerHub to create an interactive documentation of your Rest API


## Submission:

- All your UML diagrams should be exported as images, and included in the wiki of your GitHub repo
- Provide URLs to your wireframes and prototypes and Rest API documentation
- You wiki should be well organized.
- Only the last commit before your submission will be graded

## Collaboration:

- You are allowed to work with only one classmate
- You are allowed to use the same GitHub repo
- Include the name of both contributors in the wiki
- Use GitHub issues and pull requests to organize and track your work
- Each student must submit the Github repo to GradeScope

## Useful Links:

- https://creately.com/blog/diagrams/user-flow-diagram/
- https://www.lucidchart.com/blog/why-user-flow-diagrams-are-worth-your-time
- https://creately.com/blog/diagrams/sequence-diagram-tutorial/
- https://support.smartbear.com/swaggerhub/docs/tutorials/getting-started.html

