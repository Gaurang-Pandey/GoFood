# GoFood

## Overview

GoFood is a dynamic and user-friendly food delivery system built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The platform enables users to browse through a variety of restaurants, select meals, customize their orders, and have their favorite food delivered to their doorstep.

## Features

- **User Authentication**: Secure login and registration using JWT for authentication.
- **Restaurant Browsing**: Explore a wide range of restaurants and cuisines.
- **Order Customization**: Customize your meals with various options and add-ons.
- **Cart Management**: Add, remove, and modify items in your cart before checkout.
- **Order Tracking**: Real-time updates on order status from preparation to delivery.
- **Order History**: View past orders and reorder your favorites with ease.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **Frontend**: React.js, Redux for state management, HTML5, CSS3
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Real-Time Updates**: WebSockets for live order tracking

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
