# REST API - CRUD Posts

This is a simple REST API that allows users to **Create, Read, Update, and Delete** posts.

## Features
- Add a new post
- Get all posts
- Get post by ID
- Update a post
- Delete a post

## Technologies Used
- Node.js
- Express.js
- MongoDB (or your DB)
- JavaScript

## How to Run
```bash
npm install
npm start
API Endpoints
Method	 Endpoint	      Description
GET	    /posts	         Get all posts
GET	    /posts/:id	     Get single post
POST	/posts	         Create new post
PUT	    /posts/:id	     Update a post
DELETE	/posts/:id	     Delete a post

Example JSON Body (POST / PUT)
{
  "title": "Sample Title",
  "content": "Sample Content"
}

Author
Your Vaibhav Singh