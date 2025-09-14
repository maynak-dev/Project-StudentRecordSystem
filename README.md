# 🎓 Student Record System

A simple ASP.NET Core MVC web application to manage student information using Entity Framework Core and SQL Server. It supports full CRUD operations and uses Bootstrap for responsive UI.

---

## 🚀 Features

- Add new students with name, email, and GPA
- Edit existing student records
- Delete students
- View all students in a searchable table
- Validated forms using Bootstrap and Data Annotations
- Built with ASP.NET Core MVC (.NET 9) and EF Core

---

## 🛠️ Tech Stack

- ASP.NET Core MVC (.NET 9)
- Entity Framework Core
- SQL Server LocalDB
- Bootstrap 5
- Visual Studio 2022+

---

- List View of Students
- Add/Edit Student Forms
- Responsive layout using Bootstrap

---

## ⚙️ Getting Started

### Prerequisites

- [.NET 9 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)
- [Visual Studio 2022+](https://visualstudio.microsoft.com/)
- SQL Server LocalDB (installed with VS)

---

### Steps to Run

1. **Clone the repo**:
   ```bash
   git clone https://github.com/your-username/student-record-system.git
   cd student-record-system
Open in Visual Studio

Apply Migrations (creates database and Students table):

In Visual Studio → Tools → NuGet Package Manager → Package Manager Console:

Add-Migration InitialCreate
Update-Database
Run the app (F5 or Ctrl+F5)

🧠 Folder Structure

StudentRecordSystem/

│

├── Models/                → Student model

├── Data/                  → EF Core DbContext

├── Controllers/           → StudentsController with CRUD

├── Views/

│   └── Students/          → Index, Create, Edit Views

├── wwwroot/               → Static files (Bootstrap, CSS, JS)

├── appsettings.json       → Connection string

└── Program.cs             → App startup


🙋‍♂️ Author
Maynak
Feel free to connect on LinkedIn(https://in.linkedin.com/in/maynak-dey) or check out my other projects!(https://github.com/maynak-dev)
