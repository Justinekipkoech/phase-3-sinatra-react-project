# Meal-Order-App

## Learning Goals

- This is a simple Meal Order App built using Sinatra web framework.



## Features
- User can sign up and log in.
- User can view the menu and add items to cart.
- User can place an order and view order history.
- Admin can add, update and delete menu items.
- Admin can view all orders.

### Dependencies
- This app requires the following dependencies:

- Ruby 2.7.3 or higher
- Sinatra gem
- SQLite3 gem
- Bcrypt gem
- Shotgun gem
- Start the server:
- Open your web browser and go to:[http://localhost:9292/]








# Installation
- Clone this repository:
- Install dependencies:
- Create the database:
- Seed the database (optional):


## Usage
- To sign up, click on the "Sign Up" link in the navigation bar and fill out the form.
- To log in, click on the "Log In" link in the navigation bar and enter your credentials.
- To view the menu, click on the "Menu" link in the navigation bar.
- To add items to cart, click on the "Add to Cart" button next to the item on the menu page.
- To place an order, click on the "Cart" link in the navigation bar, review your order, and click on the "Place Order" button.
- To view your order history, click on the "Orders" link in the navigation bar.
- To add, update or delete menu items (admin only).



bash
Copy code
git clone https://github.com/your-username/meal-order-app-sinatra.git

For this project, you must:

- Use Active Record to interact with a database.
- Have at least two models with a one-to-many relationship.
- At a minimum, set up the following API routes in Sinatra:
  - create and read actions for both models
  - full CRUD capability for one of the models: 
  The update action should be implemented using a form that is 
  pre-filled with existing values for the object. On submission of 
  the form, the object should update. Note: Using a like button or 
  similar will not meet the update requirement.
- Build a separate React frontend application that interacts with the API to
  perform CRUD actions.
- Implement proper front end state management. You should be updating state using a
  setState function after receiving your response from a POST, PATCH, or DELETE 
  request. You should NOT be relying on a GET request to update state. 
- Use good OO design patterns. You should have separate classes for each of your
  models, and create instance and class methods as necessary. 
- Routes in your application (both client side and back end) should follow RESTful
  conventions.
- Use your back end optimally. Pass JSON for related associations to the front 
  end from the back end. You should use active record methods in your controller to grab
  the needed data from your database and provide as JSON to the front end. You
  should NOT be relying on filtering front end state or a separate fetch request to
  retrieve related data.

For example, build a todo list application with a React frontend interface and a
Sinatra backend API, where a user can:

- **Create** a new todo
- **Read** a list of all todos
- **Update** an individual todo
- **Delete** a todo

A `Todo` can be tagged with a `Category`, so that each todo _belongs to_ a
category and each category _has many_ todos.

## Getting Started

### Backend Setup

This repository has all the starter code needed to get a Sinatra backend up and
running. [**Fork and clone**][fork link] this repository to get started. Then, run
`bundle install` to install the gems.

**Important**: Be sure you fork a copy of the repo into your GitHub account
before cloning it. You can do this by using the link above or by clicking the
"Octocat" button at the top of this page, then clicking "Fork" in the upper
right corner of the repo page.

[fork link]: https://github.com/learn-co-curriculum/phase-3-sinatra-react-project/fork

The `app/controllers/application_controller.rb` file has an example GET route
handler. Replace this route with routes for your project.

You can start your server with:

```console
$ bundle exec rake server
```

This will run your server on port
[http://localhost:9292](http://localhost:9292).

### Frontend Setup

Your backend and your frontend should be in **two different repositories**.

Create a new repository in a **separate folder** with a React app for your
frontend. To do this, `cd` out of the backend project directory, and use
[create-react-app][] to generate the necessary code for your React frontend:

```console
$ npx create-react-app my-app-frontend
```

After creating the project locally, you should also
[create a repository on GitHub][create repo] to host your repo and help
collaborate, if you're working with a partner.

### Fetch Example

Your React app should make fetch requests to your Sinatra backend! Here's an
example:

## Author
- Justine Limo


