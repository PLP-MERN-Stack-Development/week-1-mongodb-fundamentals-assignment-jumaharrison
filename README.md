[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19737494&assignment_repo_type=AssignmentRepo)
# MongoDB Fundamentals Assignment

This assignment focuses on learning MongoDB fundamentals including setup, CRUD operations, advanced queries, aggregation pipelines, and indexing.

## Assignment Overview

You will:
1. Set up a MongoDB database
2. Perform basic CRUD operations
3. Write advanced queries with filtering, projection, and sorting
4. Create aggregation pipelines for data analysis
5. Implement indexing for performance optimization

## Getting Started

1. Accept the GitHub Classroom assignment invitation
2. Clone your personal repository that was created by GitHub Classroom
3. Install MongoDB locally or set up a MongoDB Atlas account
4. Run the provided `insert_books.js` script to populate your database
5. Complete the tasks in the assignment document

## Files Included

- `Week1-Assignment.md`: Detailed assignment instructions
- `insert_books.js`: Script to populate your MongoDB database with sample book data

## Requirements

- Node.js (v18 or higher)
- MongoDB (local installation or Atlas account)
- MongoDB Shell (mongosh) or MongoDB Compass

## Submission

Your work will be automatically submitted when you push to your GitHub Classroom repository. Make sure to:

1. Complete all tasks in the assignment
2. Add your `queries.js` file with all required MongoDB queries
3. Include a screenshot of your MongoDB database
4. Update the README.md with your specific setup instructions

db.books.insertMany([
  {
    title: "MongoDB Basics",
    author: "John Doe",
    genre: "Technology",
    published_year: 2020,
    price: 29.99,
    in_stock: true,
    pages: 320,
    publisher: "TechPress"
  },
  {
    title: "Node.js in Action",
    author: "Jane Smith",
    genre: "Technology",
    published_year: 2018,
    price: 35.00,
    in_stock: true,
    pages: 400,
    publisher: "NodePub"
  },
  {
    title: "The Great Gatsby",
    author: "F. Scott Fitzgerald",
    genre: "Fiction",
    published_year: 1925,
    price: 10.00,
    in_stock: true,
    pages: 218,
    publisher: "Scribner"
  },
  {
    title: "React Essentials",
    author: "Tom White",
    genre: "Technology",
    published_year: 2021,
    price: 42.50,
    in_stock: false,
    pages: 350,
    publisher: "CodeHouse"
  },
  {
    title: "1984",
    author: "George Orwell",
    genre: "Fiction",
    published_year: 1949,
    price: 8.99,
    in_stock: true,
    pages: 328,
    publisher: "Harcourt"
  },
  {
    title: "Clean Code",
    author: "Robert C. Martin",
    genre: "Technology",
    published_year: 2008,
    price: 50.00,
    in_stock: true,
    pages: 464,
    publisher: "Prentice Hall"
  },
  {
    title: "A Brief History of Time",
    author: "Stephen Hawking",
    genre: "Science",
    published_year: 1988,
    price: 15.00,
    in_stock: false,
    pages: 256,
    publisher: "Bantam"
  },
  {
    title: "The Art of War",
    author: "Sun Tzu",
    genre: "Philosophy",
    published_year: -500,
    price: 12.00,
    in_stock: true,
    pages: 112,
    publisher: "Penguin"
  },
  {
    title: "Python Crash Course",
    author: "Eric Matthes",
    genre: "Technology",
    published_year: 2019,
    price: 39.99,
    in_stock: true,
    pages: 544,
    publisher: "No Starch Press"
  },
  {
    title: "The Road",
    author: "Cormac McCarthy",
    genre: "Fiction",
    published_year: 2006,
    price: 14.95,
    in_stock: true,
    pages: 287,
    publisher: "Vintage"
  }
])
