### ExchangeBoardgames

This is a clone of the website boardgames.stackexchange.com in ASP.NET Core 7. It's still under development, but it will have 3 applications:

* A Razor Pages application for the frontend
* A .NET Core library for business logic
* A backend to deal with EFCore and the database

All the applications are developed on Linux and will be deployed on Linux too. I'm using PostgreSQL for the database, and the database models were generated from scaffolding Stack Exchange anonymized public data dumps.
