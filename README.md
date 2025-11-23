# Project Title

## Description
Short explanation of what the project does.

## Tech Stack
- ASP.NET MVC
- Bootstrap 5
- C#
- SQL Server

## Features
- User login & registration
- CRUD operations for products
- Admin dashboard
- Responsive UI with Bootstrap 5

## Folder Structure
```
porfolio-santola/
│
├── Controllers/
│   ├── HomeController.cs
│   ├── AccountController.cs
│   └── (other controllers)
│
├── Models/
│   ├── ViewModels/
│   │   ├── UserViewModel.cs
│   │   └── ProductViewModel.cs
│   ├── DTOs/
│   ├── Entities/
│   └── (EF models or plain models)
│
├── Views/
│   ├── Shared/
│   │   ├── _Layout.cshtml
│   │   ├── _Navbar.cshtml
│   │   ├── _Footer.cshtml
│   │   └── _ValidationScriptsPartial.cshtml
│   │
│   ├── Home/
│   │   ├── Index.cshtml
│   │   └── About.cshtml
│   │
│   └── (other folders for controllers)
│
├── wwwroot/
│   ├── css/
│   │   ├── bootstrap.min.css
│   │   ├── site.css
│   │   └── custom/
│   │       └── dashboard.css
│   │
│   ├── js/
│   │   ├── bootstrap.bundle.min.js
│   │   ├── site.js
│   │   └── pages/
│   │       └── dashboard.js
│   │
│   ├── lib/  (optional for npm or static vendor files)
│   │   └── (3rd party plugins)
│   │
│   ├── img/
│   ├── uploads/
│   └── fonts/
│
├── Services/
│   ├── Interfaces/
│   ├── Implementations/
│   └── Helpers/
│
├── Data/
│   ├── AppDbContext.cs
│   ├── Migrations/
│   └── Seed/
│
├── Repositories/ (optional)
│   ├── IUserRepository.cs
│   ├── UserRepository.cs
│   └── (other repos)
│
├── Middleware/
│
├── DTOs/
│
├── wwwroot/ (static assets)
│
├── appsettings.json
├── Program.cs / Startup.cs
└── YourProject.csproj


## How to Run
1. Clone this repo
2. Open solution in Visual Studio
3. Setup database
4. Run the project


## Contributors
San Tola
