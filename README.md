# SEIR-808 - Bloom

Everyone is an expert in their own field. We would like to expand on the gig economy to empower users to teach others the secrets of their trade. We love how social media has showcased, that there are many different ways to earn a living. There are experts in: AirBNB hosting, Cooking, Traveling, and even Coding. These experts can create a workshop for those who are curious in the field.

We want to empower the experts to grow their business and teach others how to navigate that path.  For the ones that want to learn, we want them to Bloom.

## User Stories

* As an unregistered user, I would like to sign up with email and password.
* As an unregistered user, I would like to see all of the courses.
* As a registered user, I would like to sign in with email and password.
* As a signed in user, I would like to change password.
* As a signed in user, I would like to sign out.
* As a registered user, I would like to create courses.
* As a registered user, I would like to edit courses.
* As a registered user, I would like to update courses.
* As a registered user, I would like to delete courses.
* As a signed in user, I would like to add and remove courses from a shopping cart.
* As a signed in user, I would like to purchase products in a shopping cart. 
* As a signed in user, I would like to see all my past courses.
* As an unregistered user, I would like to see all of the courses.

## Layout
![Main Layout](/img/mainlayout.png)

![Profile Layout](/img/profilelayout.png)

## Wireframes
![wireframe](/img/route.png)

## ERDs
![ERD](/img/cleanERD.png)

## RESTful Routes

### User
| HTTP METHOD | URL              | CRUD    | Response                              |
| ----------- | ---------------- | ------- | ------------------------------------- |
| GET | `/users/:id` | READ | return a specific user as json (status 200) |
| POST | `/users` | CREATE | create a user in the database and send back as json (status 201) |
| PUT | `/users/:id` | UPDATE | update a user in the database and send back as json (status 200) |
| DELETE | `/users/:id` | DESTROY | delete a user from the database (status 204) |


### Courses
| HTTP METHOD | URL              | CRUD    | Response                              |
| ----------- | ---------------- | ------- | ------------------------------------- |
| GET | `/courses` | READ | return all courses as json (status 200) |
| GET | `/courses/:id` | READ | return a specific course as json (status 200) |
| POST | `/courses` | CREATE | create a course in the database and send back as json (status 201) |
| PUT | `/courses/:id` | UPDATE | update a course in the database and send back as json (status 200) |
| DELETE | `/courses/:id` | DESTROY | delete a course from the database (status 204) |

## Contributors
- Prija Cash    | [github](https://github.com/prijacash)
- Jason Chen    | [github](https://github.com/jasonxchen)
- Zion Agrate   | [github](https://github.com/Agrate0718)
- Ian Dabinett  | [github](https://github.com/IanDab47)

## Tech Stack Used
- HTML / CSS / JavaScript
- React.js
- React Hooks
- Node.js
- Express
- MongoDB and Mongoose
- Git and GitHub
- JWT
- Axios
- Bcrypt for Node.js

## Install Instructions
- TBD install instructions


## MVP goals

**Functionality**
* [ ] User has ability to signup
* [ ] User can see all of the courses.

* [ ] User sign in with password and email
* [ ] User can change password.
* [ ] User can sign out

* [ ] User can create courses.
* [ ] User can edit courses.
* [ ] User can update courses.
* [ ] User delete courses.

* [ ] User can add to shopping cart
* [ ] User can use stripe https://github.com/azmenak/react-stripe-checkout
* [ ] User can see past orders
* [ ] As an unregistered user, I would like to see all of the courses.

**MVP Goals**
* [ ] Full Stack App - backend & front end from Unit 3
* [ ] Interactive Front End - modern front end
* [ ] Complete Product - CRUD - couple models
* [ ] Thoughtful User Stories - to know where to build / scrap
* [ ] Visually Impressive Design - wow future clients & employers
* [ ] Deploy online - publicly accessible

* [ ] Working app, built by whole team
* [ ] Link to your hosted app - URL in Github
* [X] Team hosted repository

**README**
* [ ] Completed README
* [X] Technology Used
* [ ] Couple Paragraphs General Approach you took
* [ ] Installation Instructions
* [ ] Link to User Stories
* [ ] Link to Wireframes
* [ ] RESTful routing chart
* [ ] Unsolved Problems / Major Hurdles

**Evaluation**
* [ ] Project Workflow
* [ ] Technical Requirement
* [ ] Creativity
* [ ] Code Quality
* [ ] Problem Solving


## Stretch goals

* [ ] Let users leave ratings on courses
* [ ] Let users follow other users
* [ ] Add video content
* [ ] Add real users and their curated courses