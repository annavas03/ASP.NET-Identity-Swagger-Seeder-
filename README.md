# ASP.NET-Identity-Swagger-Seeder-
"Demonstrates the use of ASP.NET Core Identity for authentication, Swagger for API documentation, and a Seeder for populating the database with initial data."

**Database SQLite**

"ConnectionStrings": {
  "DefaultConnection": "Data Source=app.db"
}

dotnet ef migrations add InitIdentity
dotnet ef database update


