# Project-2: Library Management System

A menu-driven console program in Python for managing a library's books and members. You can issue books to members and take them back.

## What it can do

- Add, remove, search and display books
- Add, remove, search and display members
- Issue a book to a member
- Return a book
- Stop duplicate book IDs and member IDs
- Stop an already issued book from being issued again
- Only let the member who borrowed a book return it

## How it's built

The project has four classes:

- **Book** holds the book ID, title, author, category and status (Available or Issued). `issue_book()` changes the status and returns True, or False if the book is already issued.
- **Member** holds the member ID, name and a list of the book IDs they have borrowed.
- **Library** keeps the lists of books and members and does the real work: adding, removing, searching, issuing and returning.
- **LibraryManagementSystem** shows the menu, takes the user's input and calls the Library methods.

## Menu

```
------LIBRARY MANAGEMENT SYSTEM-----
1. Add Book
2. Remove Book
3. Search Book
4. Display Books
5. Add Member
6. Remove Member
7. Search Member
8. Display Member
9. Issue Book
10. Return Book
11. Exit
```

## How to run

Open `Project_2.ipynb` in Jupyter Notebook and run all the cells in order. The last cell starts the program and shows the menu. Type a number and follow the prompts.


## What I practised

- Making several classes work together
- Searching and updating lists of objects
- Building a menu with a `while` loop
- Using `try` / `except` to check input
