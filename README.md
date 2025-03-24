# Blogging Website with Real-time Chat

This is a blogging website that allows users to write, edit, like, and comment on blogs. It also includes real-time chat functionality, JWT authentication, Google sign-in, and search by tag and title. The website is designed to be user-friendly, utilizing Redux for state management. The backend supports CRUD operations and is connected to MongoDB for data storage.

## Features

- **Blogging**: Write, edit, like, and comment on blogs.
- **Real-time Chat**: Interact with other users in real-time through a live chat feature.
- **Authentication**: Secure login using JWT and Google Authentication.
- **Search**: Search blogs by tags or titles.
- **Pagination**: Easily navigate through blogs with pagination.
- **Redux**: Manages the app state to ensure a smooth user experience.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/avinashkrishna07/BloggerStop.git
cd BloggerStop/
```

### 2. Setup for Client and Server

#### Client Setup

Navigate to the client folder:

```bash
cd client
```

Install dependencies using Yarn:

```bash
yarn
```

Set environment variables:

- Add the MongoDB connection string (`MONGODB_URL`) and the port number (`PORT`) in the environment file or directly in the client code if necessary.

Start the client:

```bash
yarn start
```

#### Server Setup

Navigate to the server folder:

```bash
cd server
```

Install dependencies using Yarn:

```bash
yarn
```

Set environment variables:

- Set the MongoDB connection string (`MONGODB_URL`) and the port number (`PORT`) in the `.env` file.

Start the server:

```bash
node index.js
```

### 3. Access the Application

Once both the client and server are running, you can access the website by opening:

```
http://localhost:<client-port>
```

## Technologies Used

- **Frontend**: React, Redux, React-Router, Material-UI
- **Backend**: Node.js, Express.js, MongoDB
- **Authentication**: JWT, Google Authentication
- **Real-time**: Socket.io
