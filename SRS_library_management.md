# Library Management System (Java – Console Based)

## 1. Introduction

### 1.1 Purpose
This document describes the requirements of a console-based Library Management System developed using Java. It is intended for developers and evaluators.

### 1.2 Scope
The system manages basic library operations such as adding books, issuing and returning books, and searching records through a command-line interface.

## 2. Overall Description

### 2.1 Product Perspective
The Library Management System is a standalone Java application with a command-line interface (no graphical user interface required for the core system).

### 2.2 User Classes and Characteristics
- Admin: Manages books and users; can add, update, delete, and issue books.
- User: Searches for books, borrows (issues) books, and returns books.

### 2.3 Operating Environment
- Java 8 or higher
- Command Line Interface (CLI)
- Supported platforms: Windows, Linux, macOS

## 3. Functional Requirements
- FR-1: The system shall allow users to log in using credentials.
- FR-2: The system shall allow Admin to add, update, and delete books.
- FR-3: The system shall allow Admin to issue books to users.
- FR-4: The system shall allow users to return issued books.
- FR-5: The system shall allow users to search books by title or author.

## 4. Non-Functional Requirements
- The system shall be menu-driven and easy to use.
- The system shall respond to user actions within 2 seconds.
- The system shall handle invalid input gracefully.

## 5. Constraints
- The system must be developed using Java.
- A graphical user interface (GUI) may optionally be developed and used in the future, but the initial implementation is console-based.

## 6. Conclusion
This SRS defines the basic requirements for the Java-based console Library Management System.
