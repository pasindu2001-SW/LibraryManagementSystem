# Library Management System

## Overview
The Library Management System is a software solution designed to simplify and optimize library operations. It serves both library administrators (staff) and members, offering features to manage books, user accounts, reservations, and loan processes. The system includes two dedicated interfaces: the Admin Dashboard for staff and the Member Dashboard for library users, ensuring role-specific functionality.

## What It Does
1. For Members:
   - Search and browse books.
   - View book details.
   - Borrow and return books.
   - Reserve books and cancel reservations.
   - Manage their personal profile and view borrowing history.

2. For Admins:
   - Add, update, and remove books from the catalog.
   - Register and manage library members.
   - Track overdue items and manage reservations.
   - Generate reports and monitor library statistics.

Key Entities
1. Books: 
   - Represent the library's collection.
   - Key attributes: Title, Author, ISBN, Publication Year, Availability.

2. Members:
   - Represent the users of the library.
   - Key attributes: Member ID, Name, Email, Borrowed Books, Reservation History.

3. Librarians:
   - Represent the library staff who manage the library.
   - Key attributes: Employee ID, Managed Library, Administrative Rights.

4. Authors:
   - Represent book authors.
   - Key attributes: Author ID, Name, Biography, Books Written.

5. Loan Transactions:
   - Represent the borrowing and returning of books.
   - Key attributes: Member, Book, Loan Date, Return Date.

6. Reservations:
   - Represent book reservations made by members.
   - Key attributes: Member, Book, Reservation Date, Expiration Date.

7. Library:
   - Represents the main library system.
   - Key attributes: Name, Location, List of Books, List of Members.

## Planned Improvements
-Integration with external libraries for broader access and inter-library loans.
-Development of a mobile application for user convenience.
-Enhanced analytics dashboard for deeper insights and advanced reporting.

