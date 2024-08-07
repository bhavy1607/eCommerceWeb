# E-Commerce Project

**Student Name**: Bhagy Ghetiya  
**Student Number**: 8876667  
**Date**: 7/22/2024

### Technology Stack

**Frontend**: ReactJS  
**Backend**: Node.js with Express  
**Database**: MongoDB (Atlas)

### Project Setup

1. **Project Initialization**: Repository created on GitHub and cloned to local machine.
2. **Frontend Setup**: Initialized ReactJS project.
3. **Backend Setup**: Initialized Node.js project with Express and connected to MongoDB (Atlas).

### Database Schema Design


**Products Schema (MongoDB)**

- `_id` : ObjectId
- `name`: String
- `description`: String
- `price`: Number
- `category`: String
- `stock`: Number
- `imageUrl`: String

**Users Schema (MongoDB)**

- `_id` : ObjectId
- `username`: String
- `password`: String
- `email`: String

**Category Schema (MongoDB)**

- `_id` : ObjectId
- `name` : String
- `description` : String

**Carts Schema (MongoDB)**

- `_id` : ObjectId
- `userId` : ObjectId
- `productId` : ObjectId
- `quantity`: Number
- `totalAmount` : Number

**Reviews Schema (MongoDB)**
{
- `_id` : ObjectId
- `productId` : ObjectId
- `userId` : ObjectId
- `rating` : Number
- `comment`: String
- `date` : Date
}


**Orders Schema (MongoDB)**

- `_id` : ObjectId
- `userId` : ObjectId
- `productId` : ObjectId
- `quantity`: Number
- `totalAmount` : Number
- `status` : String
- `orderDate` : Date

### Frontend Setup

1. Basic structure set up for React components, including directories for components and services.
2. State management planned to handle user sessions and cart data.

### Notes

- The project is set up using Git and GitHub for version control.
- Further development will include implementing user interfaces for product listings, shopping cart, and checkout.
