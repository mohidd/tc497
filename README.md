# Instagram Clone

## Overview
This project is a full-stack web application that mimics core Instagram features. Users can create posts, comment on posts, and manage personalized profiles. The app is built with a React frontend, a Flask REST API backend, session-based authentication, and a PostgreSQL database.

## Table of Contents
- Overview
- Features
- Architecture
- Quickstart
- Usage
- FAQ
- Tech Stack

## Features
- User authentication with sessions
- Create and view posts
- Comment on posts
- User profiles with personal feeds

## Architecture
![Architecture diagram of the system showing React frontend, Flask API, and PostgreSQL database](docs/architecture_diagram_instagram_clone.png)

This diagram shows how the React frontend communicates with the Flask REST API using HTTPS and JSON. The backend handles authentication using server-side sessions and stores application data in a PostgreSQL database.

## Quickstart

### Prerequisites
- Node.js
- Python 3
- PostgreSQL

### Installation
1. Clone the repository  
2. Install backend dependencies  
3. Set up the PostgreSQL database  
4. Install frontend dependencies  
5. Start the backend and frontend servers  

(docs/gifs/setup.gif)

## Usage

### Creating a post
Users can upload a post and see it appear in their feed.

![GIF showing a user creating a post](create_post.gif)

### Commenting on a post
Users can leave comments on posts.

![GIF showing a user commenting on a post](comment.gif)

## FAQ
**How does authentication work?**  
Authentication is handled using server-side sessions managed by the Flask backend.

**Do I need a local database to run this?**  
Yes, PostgreSQL is required to store users, posts, and comments.

## Tech Stack
- Frontend: React, HTML, CSS, JavaScript  
- Backend: Flask, Python  
- Database: PostgreSQL  
- Authentication: Sessions
