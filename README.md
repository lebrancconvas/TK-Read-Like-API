# TK Read (Application) API (Clone Playground Project)

## Overview

TK Read is an application for renting e-books.

## User Story

### Story 01

As a User, I want to rent books that I'm interested.

### Story 02

As a User, I must return books I rent on due date.

### Story 03

As a User, I must waiting for queues when another user doesn't return the book that I want to rent.

### Story 04

As an Admin, I can add new book data to the application.

### Story 05

As an Admin, I can update an information of the book on the application.

### Story 06

As an Admin, I can remove books from the application.

## Schema

### User Schema

- User ID: unsigned integer
- Username: string
- Display Name: string
- Profile Image: string (Image URL)
- Date of User Created: datetime
- Book Renting Lists: BookSchema[]

### Book Schema

- Book ID: unsigned integer
- Book Name: string
- Book Author: string
- Book Description: string (optional)
- Book Renting Duration: datetime
