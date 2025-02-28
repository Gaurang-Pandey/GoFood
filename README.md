# GoFood

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/Gaurang-Pandey/GoFood/actions)  
[![GitHub issues](https://img.shields.io/github/issues/Gaurang-Pandey/GoFood)](https://github.com/Gaurang-Pandey/GoFood/issues)

## Overview

GoFood is a dynamic and user-friendly food delivery system built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The platform enables users to browse through a variety of restaurants, select meals, customize their orders, and have their favorite food delivered to their doorstep.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Features

- **User Authentication**: Secure login and registration using JWT for authentication.
- **Restaurant Browsing**: Explore a wide range of restaurants and cuisines.
- **Order Customization**: Customize your meals with various options and add-ons.
- **Cart Management**: Add, remove, and modify items in your cart before checkout.
- **Order Tracking**: Real-time updates on order status from preparation to delivery.
- **Order History**: View past orders and reorder your favorites with ease.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
- ![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
- ![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
- ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-token&logoColor=white)
- ![WebSockets](https://img.shields.io/badge/WebSockets-000000?style=for-the-badge&logo=websockets&logoColor=white)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Gaurang-Pandey/GoFood.git
   cd GoFood
   ```

2. **Install backend dependencies**:

   ```bash
   cd backend
   npm install
   ```
3. **Install frontend dependencies**:
   ```bash
   cd ../src
   npm install
   ```
4. **Set up environment variables**:
   
   • Create a .env file in the backend directory with the following content:
   
      ```env
      PORT=5000
      MONGODB_URI=your_mongodb_connection_string
      JWT_SECRET=your_jwt_secret_key
      ```
6. **Start the development servers**:

   • Backend:

      ```bash
      cd backend
      npm start
      ```
   • Frontend:
   
      ```bash
      cd ../src
      npm start
      ```

The frontend will typically run on http://localhost:3000/ and the backend on http://localhost:5000/.

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/YourFeature).
3. Commit your changes (git commit -m 'Add YourFeature').
4. Push to the branch (git push origin feature/YourFeature).
5. Open a pull request.

## Acknowledgements
• Thanks to the open-source community for the tools and inspiration.
• Special mention to any collaborators or mentors.
