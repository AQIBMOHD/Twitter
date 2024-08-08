
# X Twitter X - A Twitter Clone

Welcome to X Twitter X, a social media platform inspired by Twitter! This application allows users to post tweets, like tweets, and follow other users, bringing the essential features of Twitter into a simple, easy-to-use interface.

## Features

- **User Authentication**: Sign up and log in securely with authentication.
- **Tweeting**: Post tweets with a character limit.
- **Like Tweets**: Like tweets from other users.
- **Follow Users**: Follow and unfollow users to see their tweets in your feed.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Tech Stack

- **Frontend**: React.js, HTML, CSS
- **Backend**: Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT (JSON Web Token)
- **Styling**: CSS (You may use a framework like Bootstrap or Tailwind CSS)
- **Version Control**: Git

## Installation and Setup

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm (Node Package Manager)
- MongoDB

### Steps

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/x-twitter-x.git
    cd x-twitter-x
    ```

2. **Install dependencies:**

    Navigate to the frontend and backend directories and install the dependencies:

    ```bash
    cd Frontend/twitterclone
    npm install
    ```

    ```bash
    cd Backend
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the backend directory and add the following environment variables:

    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the application:**

    To start the backend server:

    ```bash
    cd Backend
    npm start
    ```

    To start the frontend:

    ```bash
    cd Frontend/twitterclone
    npm start
    ```

5. **Access the application:**

    Open your browser and go to `http://localhost:3000` to see the frontend. The backend will be running on `http://localhost:5000`.

## Folder Structure

```plaintext
X Twitter X/
│
├── Backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── config/
│   └── server.js
│
└── Frontend/
    └── twitterclone/
        ├── public/
        ├── src/
        │   ├── components/
        │   ├── pages/
        │   ├── services/
        │   └── App.js
        └── package.json
