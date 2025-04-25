# 🧩 WebApplication11 - User Module CRUD (.NET 6 MVC Project)

**WebApplication11** is a .NET 6 MVC project designed to implement complete **CRUD operations** for a basic **User module**. It demonstrates core software development principles like **layered architecture** (DAL/BAL), **form validation**, and clean UI separation using **Razor views**.

---

## 🚀 Features

- ✅ Create, Read, Update, Delete (CRUD) operations for Users  
- 🔐 User Registration & Login module (optional)  
- 🧾 Frontend & Backend validation  
- 🧱 Follows layered architecture:
  - **DAL** – Data Access Layer
  - **BAL** – Business Access Layer
- 🖼️ Clean UI using Razor View Engine  
- 💡 Code structured using MVC best practices

---

## 🛠️ Tech Stack

- 💻 .NET 6 MVC  
- 🖥️ Razor Pages / Views  
- 💾 SQL Server  
- 🧰 Entity Framework Core  
- 🧑‍💻 Visual Studio 2022+

---

## 📁 Folder Structure

```
WebApplication11/
├── BAL/               # Business logic
├── DAL/               # Data access logic
├── Controllers/       # Main controller (e.g. UserController)
├── Models/            # User model and view models
├── Views/
│   └── User/          # Razor views for CRUD operations
├── wwwroot/           # Static assets (CSS, JS)
├── Program.cs
├── Startup.cs
└── appsettings.json
```

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Arman-Gilani/WebApplication11.git
   ```

2. **Open the solution in Visual Studio 2022**

3. **Update the connection string** in `appsettings.json` to match your local SQL Server

4. **Apply EF Core Migrations** (if applicable)
   ```bash
   dotnet ef database update
   ```

5. **Run the project** and test CRUD operations

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change or improve.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
