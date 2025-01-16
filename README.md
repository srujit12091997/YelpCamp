# YelpCamp

YelpCamp is a web application that allows users to create and review campgrounds. This project is built using Node.js, Express, MongoDB, and EJS.

## Features

- View all campgrounds
- Create new campgrounds
- Edit existing campgrounds
- View detailed information about each campground
- Basic CRUD functionality

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed Node.js
* You have installed MongoDB
* You have npm (Node Package Manager) installed

## Installation

1. Clone the repository:
```bash
git clone <repository-url>

2. Install NPM packages:
npm install

3.Create a MongoDB database named 'yelp-camp'

4.Install required dependencies:

npm install express mongoose ejs ejs-mate method-override

5. Open web browser and visit:

http://localhost:3000
http://localhost:3000/campgrounds#
http://localhost:3000/campgrounds
http://localhost:3000/campgrounds/new
http://localhost:3000/campgrounds


Project Structure

YelpCamp/
├── models/
│   └── campground.js
├── views/
│   ├── campgrounds/
│   │   ├── edit.ejs
│   │   ├── index.ejs
│   │   ├── new.ejs
│   │   └── show.ejs
│   └── layouts/
│       └── boilerplate.ejs
├── app.js
└── package.json

API Routes

GET / - Landing page
GET /campgrounds - Show all campgrounds
GET /campgrounds/new - Form to create a new campground
POST /campgrounds - Create a new campground
GET /campgrounds/:id - Show specific campground
GET /campgrounds/:id/edit - Form to edit specific campground
PUT /campgrounds/:id - Update specific campground



