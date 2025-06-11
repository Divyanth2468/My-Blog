# My Blog

Welcome to **My Blog**! This repository contains the code for my personal blog built with **Flask**, **HTML**, and **CSS**. The blog offers basic authentication, a built-in blog editor, and auto-generated profile pictures. It's designed to be simple yet functional, with features like post management and user authentication.

## Table of Contents

- [About](#about)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## About

**My Blog** is a personal blogging platform built with Flask for backend functionality and HTML/CSS for the frontend. The blog includes:

- User authentication (Login and Logout)
- Blog post management (Create, Edit, and Delete posts)
- Auto-generated profile pictures for users
- Simple and clean design with mobile responsiveness

## Technologies Used

- **Flask** - Web framework for Python, used for building the server-side logic and API.
- **HTML** - Structure of the web pages.
- **CSS** - Styling and layout of the pages.
- **Basic Authentication** - Protects the blog and allows users to log in securely.
- **Profile Picture Generation** - Auto-generated avatars for user profiles.
- **SQLite** (or any other database) - Database for storing user information and blog posts.

## Features

- **Basic Authentication**: Secure login and logout functionality for users.
- **Blog Post Editor**: Users can create, edit, and delete their blog posts.
- **Profile Picture Generation**: Automatically generates a unique avatar for each user based on their email.
- **Mobile-Friendly Design**: Fully responsive design, making it easy to read and write blog posts on any device.
- **Simple Admin Interface**: Manage blog posts and user profiles with ease.

## Installation

To set up the project locally:

1. Clone the repository:

```bash
git clone https://github.com/Divyanth2468/My-Blog.git
```   

Navigate into the project directory:
   ```bash
   cd My-Blog
   ```

Install the required dependencies using pip:
   ```bash
   pip install -r requirements.txt
   ```

Set up the database (SQLite or any other database you're using):
   ``` bash
   python setup.py
   ```

Start the Flask development server:
   ```bash
   python app.py
   ```
Open your browser and visit http://127.0.0.1:5000 to access your blog.
