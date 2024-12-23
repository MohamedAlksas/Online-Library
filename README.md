# Internship Bookstore Project

Welcome to the Bookstore Web Application! This project was developed using **ASP.NET MVC** and **Entity Framework**. This app allows users to sign up as either **Authors** or **Users** and provides distinct functionalities for each role.

## Project Features

### User Roles:
1. **Authors**
   - Can add new books to the bookstore.
   - Can view and manage orders related to their books.
   
2. **Users**
   - Can browse and purchase books.
   - Can search for authors by name.
   - Can view, edit, or cancel their book orders.

### Screenshots
Include some sample screenshots here:

- **Home Page** – Displaying available books.
![Home Page](/Images/view%20availabe%20books.jpg)
- **Author Dashboard** – Showing book management options.
![Author Dashboard](/Images/view%20author%20profile.jpg)
- **Search Authors** – Find authors by their name.
![Home](/Images/search%20by%20author%20name.jpg)

## Installation and Setup

### Prerequisites
- **Visual Studio** (preferably 2022 or later)
- **.NET Core SDK** (version 6.0 or higher)
- **Microsoft SQL Server** (for database setup)

### Steps to Run the Project
1. **Clone the Repository**
   ```bash
   git clone https://github.com/hafez599/ITI_BookStore
   cd BookstoreApp

2. **Database Configuration**
    - Open appsettings.json.
    - Update the connection string to match your SQL Server configuration Like in the image below.
    ![Datebase](/Images/database.jpg)

    3. **Database Migration**
    - Open the Package Manager Console in Visual Studio.
    - Run the following command to apply migrations:
    ```bash
    add-migration migrationName
    Update-Database

3. **Run the Application**
    - Press F5 or run the project through Visual Studio to launch it.
