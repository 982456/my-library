# Library Management System - README

## Overview
This is a simple Library Management System application that allows librarians to manage books, borrowers, and book lending operations. The system provides basic CRUD (Create, Read, Update, Delete) functionality for both books and borrowers, as well as features to issue and return books.

## Features

### User Authentication
- Secure login system with username and password
- Success message upon successful login

### Book Management
- Add new books with title, author, publication year, and number of copies
- Edit existing book information
- Delete books from the system with confirmation dialog
- View all books in a tabular format with BookID, Title, Author, Year, and Available Copies

### Borrower Management
- Add new borrowers with name, email, and phone number
- Edit existing borrower information
- Delete borrowers from the system with confirmation dialog
- View all borrowers in a tabular format with BorrowerID, Name, Email, and Phone

### Book Lending
- Issue books to borrowers with issue date and due date
- Return books with confirmation dialog
- View all issued books with IssueID, Book Title, Borrower Name, Issue Date, and Due Date
- Filter to show returned books

## Screenshots

1. Login Screen
2. Successful Login
3. Book Management View
4. Adding a New Book
5. Editing a Book
6. Deleting a Book
7. Borrower Management View
8. Adding a New Borrower
9. Editing a Borrower
10. Deleting a Borrower
11. Issued Books View
12. Issuing a Book
13. Returning a Book

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/library-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd library-management-system
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the application:
   ```bash
   npm start
   ```

