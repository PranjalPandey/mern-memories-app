# MERN Memories App

This is a full-stack web application built using the MERN stack (MongoDB, Express.js, React, Node.js) that allows users to share and discover memories.

**[Link to the GitHub Repository: [https://github.com/PranjalPandey/mern-memories-app](https://github.com/PranjalPandey/mern-memories-app)]**

## Table of Contents

* [Features](#features)
* [Technologies Used](#technologies-used)
* [Setup Instructions](#setup-instructions)
    * [Prerequisites](#prerequisites)
    * [Installation](#installation)
    * [Running the Application](#running-the-application)
* [Folder Structure](#folder-structure)
* [API Endpoints](#api-endpoints) (Optional - if you have a clear list)
* [Contributing](#contributing)
* [License](#license)
* [Author](#author)

## Features

* **Create Memories:** Users can create posts with text, images, and tags to share their memories.
* **Browse Memories:** Users can view all shared memories, filter by tags, and search for specific memories.
* **Like Memories:** Users can like other users' memories.
* **Update Memories:** Users can edit their own memories.
* **Delete Memories:** Users can delete their own memories.
* **Authentication:** (If implemented) User authentication (signup, login) to manage their posts.
* **Pagination:** (If implemented) Efficiently display a large number of memories by loading them in pages.
* **Search and Tags:** (If implemented) Search for memories by keywords and filter by tags.

## Technologies Used

* **Frontend:**
    * React
    * Redux (or Context API) for state management (If used)
    * Material UI (or other UI library) for styling
    * Axios for making API requests
* **Backend:**
    * Node.js
    * Express.js
* **Database:**
    * MongoDB
* **Other:**
    * (Mention any other libraries or tools used, e.g., CORS, Body-parser)

## Setup Instructions

### Prerequisites

* Node.js (LTS version recommended)
* npm (or yarn)
* MongoDB (Install locally or use a cloud service like MongoDB Atlas)

### Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/PranjalPandey/mern-memories-app.git](https://github.com/PranjalPandey/mern-memories-app.git)
    cd mern-memories-app
    ```

2.  **Install backend dependencies:**

    ```bash
    cd server  # or backend, depending on your folder name
    npm install
    ```

3.  **Install frontend dependencies:**

    ```bash
    cd client  # or frontend, depending on your folder name
    npm install
    ```

4.  **Create a `.env` file in the `server` directory:**

    * Add your MongoDB connection string:

        ```
        CONNECTION_URL = <YOUR_MONGODB_CONNECTION_STRING>
        PORT = 5000 (or your desired port)
        ```

### Running the Application

1.  **Start the backend server:**

    ```bash
    cd server
    npm start  # or nodemon server.js (if using nodemon)
    ```

2.  **Start the frontend development server:**

    ```bash
    cd client
    npm start  # or yarn start
    ```

3.  **Open your browser and navigate to `http://localhost:3000` (or the port your frontend is running on).**

## Folder Structure
