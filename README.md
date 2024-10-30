# Twitter(Work in Progress)

A social media application that allows users to create, comment, like, and manage their posts. This project is built using the MERN stack (MongoDB, Express, React.js, Node.js) and features user authentication, image uploads, and real-time notifications.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- ⚛️ **User Authentication**: Secure login and registration using JSON Web Tokens (JWT).
- 👥 **Suggested Users**: Users can follow suggested profiles based on interests.
- ✍️ **Creating Posts**: Users can create new posts and share their thoughts.
- 💬 **Commenting on Posts**: Users can comment on posts made by others.
- ❤️ **Liking Posts**: Users can like posts they enjoy.
- 🔒 **Delete Own Posts**: Users can delete their posts.
- 📝 **Edit Profile Info**: Users can update their profile information.
- 🖼️ **Edit Cover and Profile Images**: Users can upload and change their images using Cloudinary.
- 🔔 **Notifications**: Users receive notifications for likes, comments, and follows.
- 🌐 **Deployment**: Deployed for public access.

## Tech Stack
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Image Hosting**: Cloudinary
- **Data Management**: React Query for data fetching and caching

## Installation

1. Clone the repository:
   
2. Build the app

   ```shell
   npm run build
   ```

    Start the app

   ```shell
   npm start
   ```   
3. Create a .env file and add the following environment variables:
   ```bash
   MONGO_URI=...
   PORT=...
   JWT_SECRET=...
   NODE_ENV=...
   CLOUDINARY_CLOUD_NAME=...
   CLOUDINARY_API_KEY=...
   CLOUDINARY_API_SECRET=...


## Usage
- Visit http://localhost:3000 in your web browser.
- Register or log in to start using the application.
- Explore features such as creating posts, commenting, liking, and following users.
