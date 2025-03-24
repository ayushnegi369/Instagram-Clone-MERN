# Instagram Clone

A fully functional Instagram clone built using **React Native** with features like user authentication, photo uploads, likes, comments, and more.

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🚀 [Installation](#installation)
5. 🛠️ [Configuration](#configuration)
6. 🕹️ [Usage](#usage)
7. 🌐 [API Endpoints](#api-endpoints)
8. 💡 [Contributing](#contributing)
9. 🔗 [License](#license)

## 🤖 Introduction

This project replicates the core functionalities of Instagram, including posting photos, following users, liking and commenting on posts, and managing user profiles.

## ⚙️ Tech Stack

- **Frontend**: React Native, Expo
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **Storage**: Cloudinary for image uploads
- **State Management**: Redux

## 🔋 Features

- User Registration & Login
- Image Upload with Cloudinary
- Like and Comment System
- Follow/Unfollow Users
- Profile Management
- Post Feed Display
- Real-time Updates

## 🚀 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ayushnegi369/Instagram-Clone.git
    cd Instagram-Clone
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the Expo server:
    ```bash
    npm start
    ```

## 🛠️ Configuration

Create a `.env` file in the project root with the following variables:

```env
MONGO_URI=your_mongo_database_url
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

## 🕹️ Usage

1. Register and log in to your account.
2. Upload images and create posts.
3. Like and comment on other users' posts.
4. Follow and unfollow users.
5. Edit your profile.

## 🌐 API Endpoints

- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `POST /api/posts` - Create a new post
- `GET /api/posts` - Get all posts
- `POST /api/posts/:id/like` - Like a post
- `POST /api/posts/:id/comment` - Comment on a post
- `GET /api/users/:id` - Get user profile
- `PUT /api/users/:id/follow` - Follow/Unfollow user

## 💡 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.

## 🔗 License

This project is licensed under the MIT License. See the LICENSE file for more details.

