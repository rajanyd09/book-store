
# Book Store Management System

This project is a comprehensive Book Store Management System built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to manage available books with features such as updating, deleting, and searching for books.

## Features

- **Manage Available Books**: Update, delete, and search for pre-available books.
- **User-Friendly Interface**: A responsive and intuitive interface built with React.
- **Shopping Cart**: Manage a shopping cart for adding and removing books.
- **Favorites**: Add and manage favorite books.
- **Orders**: Place and manage orders.

## Technologies Used

- **Frontend**: React.js, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB


## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm (Node Package Manager)
- MongoDB

### Installation

1. **Clone the repository**

    ```sh
    git clone https://github.com/Mankaran7/book-store-management.git
    ```

2. **Navigate to the project directory**

    ```sh
    cd book-store-management
    ```

3. **Install server dependencies**

    ```sh
    cd backend
    npm install
    ```

4. **Install client dependencies**

    ```sh
    cd ../frontend
    npm install
    ```

### Running the Application

1. **Start the MongoDB server**

    ```sh
    mongod
    ```

2. **Start the backend server**

    ```sh
    cd backend
    npm start
    ```

    The backend server will run on `http://localhost:1000`.

3. **Start the frontend server**

    ```sh
    cd ../frontend
    npm start
    ```

    The frontend server will run on `http://localhost:3000`.

### Usage

- Open your browser and go to `http://localhost:3000`.
- Use the interface to manage available books, shopping cart, favorites, and orders.


## API Routes

### User Routes

- `POST /api/v1/user/register`: Register a new user.
- `POST /api/v1/user/login`: Login a user.

### Book Routes

- `GET /api/v1/books`: Get all available books.
- `PUT /api/v1/book/:id`: Update a book by ID.
- `DELETE /api/v1/book/:id`: Delete a book by ID.

### Cart Routes

- `GET /api/v1/cart`: Get all items in the cart.
- `POST /api/v1/cart`: Add an item to the cart.
- `DELETE /api/v1/cart/:id`: Remove an item from the cart.

### Favorite Routes

- `GET /api/v1/favorites`: Get all favorite books.
- `POST /api/v1/favorite`: Add a book to favorites.
- `DELETE /api/v1/favorite/:id`: Remove a book from favorites.

### Order Routes

- `GET /api/v1/orders`: Get all orders.
- `POST /api/v1/order`: Place a new order.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.


## Contact

Mankaran Singh - [LinkedIn](https://www.linkedin.com/in/mankaran7) 

Project Link: [https://github.com/Mankaran7/book-management](https://github.com/Mankaran7/book-management)


