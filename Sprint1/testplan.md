# Test Plan Document

- [Author names](#author-names)
- [Introduction](#introduction)
- [Test Items](#test-items)
- [Test Features](#test-features)
- [Expected Response](#expected-response)
- [Testing Tasks](#testing-tasks)
- [Responsibilties](#responsibilities)
- [Schedule](#schedule)
- [Github Links](#github-links)
- [Email](#email)

## Authors

Christopher Simon\
Erica Butts\
Pooja Kittanakere Balaji\
Preyasha Patel

## Introduction
- We are going to create a web application using frontend frameworks, backend frameworks and API endpoint.
    - The Front-end UI using html and css.
    - The Restful API middle tier using express with platform NodeJs.
    - The Back-end database using SQLite.

- Following are the pages for application:
    - Dashboard
    - Login
    - Sign Up
    - New User

- UX, API middle tier and database going to be tested using mocha as well as manually.

## Test Items
- Username Input
- Password Input
- Login button 
- Sign up button 
- Sign out button
- Landing page 
- Signed in page 
- Signed out page
- Registration Form

## Test Features
Following are the test features to be tested:
- Entering information for existing user
- Data for both correct/incorrect username and password
- Registration for a new user
- Validation on sign out button
- Redirecting to the other pages

## Expected Response
Listed below are the responses that should be expected for particular items:
1. Username is found in the database and login is Success, the user will be directed to the login success page. 
2. User is prompted to re-enter credentials for incorrect login.
3. When a new user signs up, the user is added to the database and the user can login.
4. Upon login, the user will be directed to the login Success page.
5. The username input accepts alpha-numeric characters.
6. User is redirected to sign in/register sign up page.
7. User should see buttons to sign in or register on landing page.
8. User should see logout successful signed out and return to the login page. 
9. When user credentials are verified user is prompted for successful login and to landing page for login.

## Testing Tasks 
- Test plan and report to be prepared
- Execution of the tests to be done
- Manual test cases should be performed

## Responsibilities
- Each member of the team going to work on each and every concepts and collaborate with each other.
- We are going to help the other team members for completing the project.
- If we face any challenges during the implementation of the application
  - Then, all four of us will try to solve those obstacles by contributing our time and effort.

## Schedule
- It will take two to three days for designing the report and other two weeks for coding and testing.

| Step 	| Action                                                          	| Expected Response                                                                                                                                       	| Pass/Fail 	|
|------	|-----------------------------------------------------------------	|---------------------------------------------------------------------------------------------------------------------------------------------------------	|-----------	|
| 1    	| Username input  - for an existing user                          	| Username is found in the database and login is Success!  The user will be directed to the login success page.                                           	| Pass      	|
| 2    	| Username input  - for correct username but incorrect password   	| User is prompted to re-enter credentials for incorrect login                                                                                            	| Pass      	|
| 3    	| Username input  - for incorrect username but correct password   	| User is prompted to re-enter credentials for incorrect login                                                                                            	| Pass      	|
| 4    	| Username input  - for incorrect username and incorrect password 	| Username prompted to re-enter credentials for incorrect login                                                                                           	| Pass      	|
| 5    	| Signup  - for a new user                                        	| When a new user signs up  - the user is added to the database and the user can login.  Upon login, the user will be directed to the login Success page! 	| Pass      	|
| 6    	| Username text field input                                       	| The username input accepts alpha-numeric characters                                                                                                     	| Pass      	|
| 7    	| Password text field input                                       	| Password input accepts                                                                                                                                  	| Pass      	|
| 8    	| Sign out  - user clicks on sign out button                      	| User is redirected to sign in/register sign up page                                                                                                     	| Pass      	|
| 9    	| Landing page  - user visits website                             	| User should see buttons to sign in or register on landing page                                                                                          	| Pass      	|
| 10   	| Signed out page                                                 	| User should see logout successful signed out and return to the login page                                                                               	| Pass      	|
| 11   	| Sign in page                                                    	| When user credentials are verified user is prompted for successful login  and to landing page for login                                                 	| Pass      	|

## Github Links
[Christopher](https://github.com/cs5581)\
[Erica](https://github.com/deathloser)\
[Pooja](https://github.com/pkb94)\
[Preyasha](https://github.com/preyasha2810)


## Email
- Christopher
<cs558@njit.edu>

- Erica
<eab5@njit.edu>

- Pooja
<pk73@njit.edu>

- Preyasha
<pp54@njit.edu>
