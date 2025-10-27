**SUBMITTED BY**

Name: Hetav Manojbhai Chaudhari

Div: 5-B

Enrollment No: 202303103510371


#  NotesApp

A simple and elegant Notes Application built using **ASP.NET Core MVC** and **SQLite**.  
This app allows users to **Create, Read, Update, and Delete (CRUD)** notes easily in a clean and aesthetic interface.

---

## Description

NotesApp is a lightweight note management system developed as a personal project.  
It is designed with simplicity and productivity in mind — featuring a modern UI, fast performance, and a persistent local database using **SQLite**.

**Key Features:**
-  Add, Edit, Delete, and View notes  
-  Data stored locally using SQLite  
-  Clean and minimal Bootstrap 5 UI  
-  Built using ASP.NET Core MVC and Entity Framework Core  

---

##  Installation Steps

1. Clone the Repository
   ```bash
   git clone https://github.com/ChaudhariHetav/NotesApp.git
   cd NotesApp

2. Open the Project

Open the project folder in Visual Studio (recommended)
or
Use Visual Studio Code with the C# and .NET SDK extensions installed.

3️. Restore Dependencies

Restore all NuGet packages required for the project:

  ```bash
  dotnet restore

  ```

4️. Apply Database Migrations

Since you’re using SQLite, generate the database file:

  ```bash
  dotnet ef database update

  ```


This will create a notes.db file inside your project directory.

(If you don’t have the EF Core tools installed, run:)

  ```bash
  dotnet tool install --global dotnet-ef

  ```

5️. Build the Project

Compile the application to check for errors:

  ```bash
  dotnet build

  ```


6️. Run the Application

  Start the development server:

  ```bash
  dotnet run

  ```


Then open your browser and navigate to:

https://localhost:5001
or
http://localhost:5000



Tech Stack

- Frontend: Razor Pages, Bootstrap 5, Custom CSS

- Backend: ASP.NET Core MVC

- Database: SQLite with Entity Framework Core

- Language: C#







