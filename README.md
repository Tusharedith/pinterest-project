# Pinterest Clone

Welcome to the Pinterest Clone project! This project is a web application that replicates the core functionalities of Pinterest, allowing users to browse and pin images, and create boards. It is built using modern web technologies, 🚀🚀🚀

Here are some screenshots of the project:

### Home Page
![Home Page](myapp/Screenshot%202024-08-16%20042243.png)

![Acc. View](myapp/Screenshot%202024-08-16%20042136.png)

![Upload view](myapp/Screenshot%202024-08-16%20042259.png)

## Table of Contents

- Features
- Technologies
- Setup
- Usage
- Contributing


## Features

- User authentication (Sign up, Sign in, Sign out)
- Create, edit, and delete boards
- Pin images to boards
- Follow/unfollow other users
- Responsive design for different screen sizes
- Infinite scrolling for image feed
- Search for pins, boards, and users

## Technologies

- **Frontend:** HTML, CSS, JavaScript, React
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Styling:** Tailwind CSS


## Setup

To run this project locally, follow these steps:

### Prerequisites

- Node.js (v14 or higher)
- MongoDB

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Tusharedith/pinterest-project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd pinterest
    ```
3. Install dependencies for both the frontend and backend:
    ```bash
    # Install server dependencies
    cd backend
    npm install
    
    # Install client dependencies
    cd ../frontend
    npm install
    ```

### Environment Variables

Create a `.env` file in the `backend` directory and add the following environment variables:

```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

