# 📚 Book Store Application

## Overview

The Book Store Application is a web-based platform where users can browse, add, update, delete, and purchase books. The application allows filtering books based on various criteria such as authors, rating, top-selling, and publishers. It also includes user authorization features, enabling users to sign up and log in.

## Features

1. **📖 Book Management**:
   - ➕ Add new books.
   - ✏️ Update existing book details.
   - 🗑️ Delete books from the inventory.
   - 🔍 View details of books.
   - 🛒 Purchase books (increments count without backend processing).

2. **🔍 Filtering and Sorting**:
   - 📚 Filter books by authors.
   - ⭐ Filter books by rating.
   - 📈 Filter books by top-selling.
   - 🏢 Filter books by publisher.

3. **🔐 User Authorization**:
   - 📝 User sign up.
   - 🔑 User login.
   - 🕒 Session management.

## 🛠️ Technologies Used

- **Backend**: Node.js, Express, MongoDB, Mongoose.
- **Frontend**: EJS, HTML, CSS, JavaScript.
- **Authentication**: Passport.js, bcrypt.

## Requirements

- **Node.js**: Install from [nodejs.org](https://nodejs.org/)
- **MongoDB**: Install from [mongodb.com](https://www.mongodb.com/)

## ⚙️ Setup and Installation

1. **📥 Clone the Repository**:
   ```bash
   git clone https://github.com/Amitdahiya08/Book-Store-App.git
   cd book-store
   ```

2. **📦 Install Dependencies**:
   ```bash
   npm install
   ```

3. **⚙️ Setup MongoDB**:
   - Ensure MongoDB is running on your local machine or provide a MongoDB URI.
   - Update the `mongoUrl` variable in the `app.js` file with your MongoDB URI:
     ```javascript
     const mongoUrl = 'mongodb://127.0.0.1:27017/BookStore';
     ```

4. **🚀 Start the Server**:
   ```bash
   npm start
   ```
   The application will be available at `http://localhost:8080`.

## 📂 Project Structure

```
book-store/
│
├── models/
│   └── bookSchema.js
│   └── userSchema.js
│
├── public/
│   └── css/
│       └── styles.css
│
├── views/
│   └── books.ejs
│   └── index.ejs
│   └── login.ejs
│   └── signup.ejs
│
├── app.js
├── package.json
├── README.md
```

## 🚀 Usage

1. **🏠 Home Page**:
   - Access the home page at `http://localhost:8080/`.
   - Browse available books.

2. **🛠️ Manage Books**:
   - ➕ Add new books through the add book form.
   - ✏️ Edit and update existing books.
   - 🗑️ Delete books from the inventory.

3. **🛒 Purchase Books**:
   - Click the "Buy Now" button to increment the purchase count of a book.
   - Currently there is no backend for purchase

4. **🔍 Filter Books**:
   - Use filters on the home page to narrow down books by authors, rating, top-selling, and publishers.

5. **🔐 User Authorization**:
   - 📝 Sign up for a new account.
   - 🔑 Log in with existing credentials.
   - 🕒 Manage session for authenticated actions.

## 🤝 Contributing

Contributions are welcome! Please create an issue or submit a pull request for any enhancements or bug fixes.
---