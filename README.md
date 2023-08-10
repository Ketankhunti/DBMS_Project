# DBMS Project 

## Overview

This project is a Database Management System (DBMS) project that includes a simple user interface (UI) interacting with a REST API built using Golang. The project uses PostgreSQL as the underlying database to store and manage data.

The main components of this project are:
- User Interface (UI): A simple web-based user interface that allows users to interact with the application.
- REST API: A backend API developed using the Go programming language to handle data operations and serve as an interface between the UI and the database.
- PostgreSQL Database: The chosen database system to store, manage, and retrieve data efficiently.

## Features

- **User Interface:** UI provides different forms to insert data into database and retrieve data.

- **REST API:** The API built using Golang provides endpoints for CRUD (Create, Read, Update, Delete) operations on the database. It ensures proper handling of requests, data validation, and interaction with the PostgreSQL database.

- **PostgreSQL Database:** PostgreSQL is used as the backend database to store the application's data. It offers reliability, ACID compliance, and efficient querying capabilities.

## Setup Instructions

1. **Clone the Repository:**
   ```sh
   https://github.com/Ketankhunti/DBMS_Project.git
   cd DBMS_Project

## Run Instructions
1. **First we need to have all the tables in Postgres and it should be running.**

2. **Run the main.go file:**
   ```sh
   go run main.go
