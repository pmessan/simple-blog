# Simple Blog Website

This repo houses a simple blog website I built using NodeJS. Other technologies I used include:
* Express.js for the Http frmaework
* EJS for templating
* Mongoose to interface with MongoDB for storing the posts in a database 
* Lodash to help with URLs

## Features

* Upon loading the homepage, some default content is present, with a caption appearing when there are no posts in the database. 
* Bloggers can head to the '/compose' route to create a blog post, which will be accesible in the '/posts/:postid' route, or by simple clicking on the 'Read more' link for the desired blog post.

## Run it Locally
```
git clone https://github.com/?? && cd simple-blog
npm start
```
 Your server should now be live on https://localhost:3000