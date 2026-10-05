# Project-1: Student Management System

A small Python project I built to practice OOP. It keeps student records in memory and lets you add, view, search, update and delete them, and also work out each student's average marks.

## What it can do

- Add a student (it won't allow two students with the same ID)
- Show all students
- Search for a student by ID
- Update a student's age and standard
- Delete a student
- Show the average marks of every student

## How it's built

There are two classes:

**Student** stores the details of one student: `id`, `name`, `age`, `std` and `marks` (a list of numbers). The `describe()` method prints them in one line.

**Student_Manager** keeps a list of Student objects and has these methods:

- `add_student(student)`
- `display_students()`
- `search_student(student_Id)`
- `update_student(student_Id, new_age, new_std)`
- `delete_student(student_Id)`
- `display_avg_marks()`
  

## What I practised

- Writing classes and using `__init__`
- Working with a list of objects
- Loops, conditions and returning early from a method
