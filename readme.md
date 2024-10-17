# Instagram Clone

This repository contains the source code for an Instagram-like application, consisting of both the frontend and backend components.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)


## Features

- User authentication (login and registration)
- Photo sharing and posting
- Like and comment functionality
- User profiles with avatar support
- Responsive design for mobile and desktop
- Image uploading and storage on AWS S3
- Account verification via email


## Technologies Used

### Frontend
- **Framework:** React
- **Styling:** Tailwind CSS Shadcn
- **State Management:** Recoil
- **Routing:** React Router

### Backend
- **Framework:** NestJS
- **Database:**  PostgreSQL
- **Authentication:** JWT (JSON Web Tokens)
- **Image Storage:** AWS S3


## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/username/instagram.git
   cd instagram
2. **Initialize Submodules**

   ```bash
   git submodule update --init --recursive
3. **Install Backend Dependencies**

   ```bash
   cd backend
    npm install
4. **Install Frontend Dependencies**

   ```bash
    cd ../frontend
    npm install

5. **Create a .env File**

      create a .env file as per the .env.example file and fill in the values
   

6. **Run the Backend Server**

   ```bash
    npm run start:dev

7. **Run the Frontend**

   ```bash
   npm run start
   ```