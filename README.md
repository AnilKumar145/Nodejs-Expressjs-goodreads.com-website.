## Introduction to EXPRESS JS

- Third-Party Packages
  - nodemon
- SQLite Methods

  - get()
  - run()
    
This repository is a Node.js and Express.js implementation for interacting with the Goodreads.com website through a set of APIs. The purpose of these APIs is to provide essential functionality for managing book data, authors, and related information. The following APIs are included:

1. **Get Books:**

   - Endpoint: `/books/`
   - Description: Retrieve a list of books with details such as title, author, and other relevant information.

2. **Get Book:**

   - Endpoint: `/books/:bookId/`
   - Description: Retrieve detailed information about a specific book using its unique identifier.

3. **Add Book:**

   - Endpoint: `/books/`
   - Method: `POST`
   - Description: Add a new book to the database, providing details like title, author, genre, etc.

4. **Update Book:**

   - Endpoint: `/books/:bookId/`
   - Method: `PUT`
   - Description: Update the information of a specific book, allowing modifications to title, author, or any other relevant attributes.

5. **Delete Book:**

   - Endpoint: `/books/:bookId`
   - Method: `DELETE`
   - Description: Remove a book from the database based on its unique identifier.

6. **Get Author Books:**
   - Endpoint: `/authors/:authorId/books/`
   - Description: Retrieve a list of books written by a specific author, using the author's unique identifier.

These APIs aim to facilitate the seamless integration of Goodreads.com functionality into Node.js and Express.js applications. Developers can use these endpoints to perform common operations related to book management and author information within their projects.
