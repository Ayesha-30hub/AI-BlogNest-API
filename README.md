# AI BlogNest API

AI BlogNest is a REST API for creating, managing, and generating blog content using AI.

## Features

* Create and manage blog posts
* Generate blog content using AI
* Update and delete blogs
* Get all blogs and individual blog details
* RESTful API endpoints
* Easy API testing with Thunder Client

## Technologies Used

* Node.js
* Express.js
* MongoDB
* AI API
* Thunder Client

## API Testing

**Thunder Client** is used to test the API endpoints.
It helps send requests such as `GET`, `POST`, `PUT`, and `DELETE` and view the API responses.

## Installation

```bash
git clone <your-github-repository-url>
cd ai-blognest-api
npm install
```

Create a `.env` file and add your required environment variables.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection
AI_API_KEY=your_api_key
```

## Run the Project

```bash
npm start
```

The API will run on:

```text
http://localhost:5000
```

## API Endpoints

| Method | Endpoint         | Description      |
| ------ | ---------------- | ---------------- |
| GET    | `/api/blogs`     | Get all blogs    |
| GET    | `/api/blogs/:id` | Get a blog by ID |
| POST   | `/api/blogs`     | Create a blog    |
| PUT    | `/api/blogs/:id` | Update a blog    |


