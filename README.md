# Task Manager - ASP.NET Core 7 MVC

## English Version

### Overview
Task Manager is a web application built with ASP.NET Core 7 MVC that allows users to manage tasks effectively. It provides CRUD operations (Create, Read, Update, Delete) for tasks, user-friendly UI, and utilizes Entity Framework Core for data persistence.

### Features
- Task creation, editing, viewing, and deletion
- Responsive UI with Bootstrap 5
- Data persistence with Entity Framework Core and SQL Server
- Basic validation and error handling
- Migrations support for database schema updates

### Project Structure
- `Controllers/` - MVC Controllers handling HTTP requests
- `Models/` - Data models and view models
- `Views/` - Razor views for UI rendering
- `Repositories/` - Database context and data access layer
- `Migrations/` - EF Core migration files
- `wwwroot/` - Static files (CSS, JS, images)
- `appsettings.json` - Configuration settings including DB connection

### Prerequisites
- [.NET 7 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
- SQL Server or compatible database

### Setup & Run
1. Restore NuGet packages:
   ```
   dotnet restore
   ```
2. Apply database migrations:
   ```
   dotnet ef database update
   ```
3. Run the application:
   ```
   dotnet run
   ```
4. Open a browser and navigate to `https://localhost:5001` or the configured URL.

---

## Slovenská Verzia

### Prehľad
Task Manager je webová aplikácia postavená na ASP.NET Core 7 MVC, ktorá umožňuje efektívne spravovať úlohy. Poskytuje CRUD operácie (vytváranie, čítanie, aktualizácia, mazanie) pre úlohy, užívateľsky prívetivé rozhranie a využíva Entity Framework Core na persistenciu dát.

### Funkcie
- Vytváranie, úprava, zobrazenie a mazanie úloh
- Responzívne UI s Bootstrap 5
- Persistencia dát pomocou Entity Framework Core a SQL Server
- Základná validácia a spracovanie chýb
- Podpora migrácií pre aktualizácie databázovej štruktúry

### Štruktúra projektu
- `Controllers/` - MVC kontroléry spracovávajúce HTTP požiadavky
- `Models/` - dátové modely a view modely
- `Views/` - Razor views pre vykresľovanie UI
- `Repositories/` - databázový kontext a dátová vrstva
- `Migrations/` - EF Core migračné súbory
- `wwwroot/` - statické súbory (CSS, JS, obrázky)
- `appsettings.json` - konfiguračné nastavenia vrátane pripojenia k DB

### Požiadavky
- [.NET 7 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
- SQL Server alebo kompatibilná databáza

### Inštalácia a spustenie
1. Obnovte NuGet balíčky:
   ```
   dotnet restore
   ```
2. Aplikujte migrácie databázy:
   ```
   dotnet ef database update
   ```
3. Spustite aplikáciu:
   ```
   dotnet run
   ```
4. Otvorte prehliadač a choďte na `https://localhost:5001` alebo na nakonfigurovanú adresu.

---

**Enjoy managing your tasks efficiently!**  
**Prajem príjemné spravovanie úloh!**
