Here's a sample **README.md** for your GitHub repository that details the login/signup functionality, MongoDB integration, EJS templating, profile section, and other features you've implemented.

---

# Authentication & Profile Management System

A simple full-stack web application built using **Node.js**, **Express.js**, **MongoDB**, **EJS**, and **Multer**. This project provides user authentication (login and signup) and includes a profile management section where users can post notes, upload profile images, and like posts.

## Features

- **User Authentication (Login/Signup)**: 
  - User registration with email, password, and basic details.
  - Login with email and password.
  - Session management using **JWT** (JSON Web Tokens) to authenticate users.
  
- **Profile Section**:
  - Users can view their profile and upload a profile image using **Multer**.
  - Users can create, edit, and delete posts (notes) on their profile page.
  - Users can like and unlike posts.

## Technologies Used

- **Node.js**: Backend JavaScript runtime environment.
- **Express.js**: Web framework for Node.js to handle routing and middleware.
- **MongoDB**: NoSQL database for storing user data and posts.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.
- **EJS**: Embedded JavaScript templating engine for rendering dynamic HTML views.
- **Multer**: Middleware for handling file uploads (used for profile image uploads).
- **JWT**: JSON Web Token used for session management and user authentication.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
   cd your-repository-name
   ```

2. **Install dependencies**:
   Make sure you have **Node.js** and **npm** installed. Then run the following command:
   ```bash
   npm install
   ```

3. **Create a `.env` file**:
   Add your environment variables for the database connection and JWT secret. Create a `.env` file in the root of the project and add the following:
   ```env
   MONGO_URI=mongodb://your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   COOKIE_SECRET=your_cookie_secret_key
   ```

4. **Run the application**:
   Start the development server:
   ```bash
   npm start
   ```

   The app should now be running at `http://localhost:3000`.

## Usage

### Registration

1. Navigate to the **signup** page by clicking the **Create Account** button on the login page.
2. Enter your details (email, password, name, etc.) and click **Create Account**.
3. You will be redirected to the **login** page where you can log in with your newly created credentials.

### Login

1. After registering, log in using your email and password.
2. Once logged in, you will be redirected to your **profile page**.

### Profile Page

1. **Post a Note**: On the profile page, you can create a new post by typing in the content and submitting it.
2. **Upload Profile Image**: You can upload a profile image by selecting a file and submitting the form.
3. **Edit Post**: Click on a post to edit its content and save the changes.
4. **Like Post**: You can like a post by clicking on the "Like" button. If you've already liked the post, you can unlike it.

### Logout

- To log out, click the **Logout** button in the profile section. You will be redirected to the login page.





## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

