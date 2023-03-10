#  Eau Claire's Salon

#### By Vera Weikel 

#### This is a project to build Basic Web Application using ASP .Net, EF Core, MVC, and SQL databases.

## Technologies Used

* .Net 6 SDK
* C#
* EFCore
* ASP.Net MVC
* Razor
* SQL 
* SQL Workbench

## Goals/Objectives

This project shows how to connect an ASP.NET Core MVC project to a MySQL database using [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/).

## Description

This is a website where for a salon owner able to select a stylist from a list, see their details, and see a list of all clients that belong to that stylist. Additionally, an owner may add new stylists when hired and is able to add new clients to a specific stylist. Else, none are displayed. The application has full create and read functionality.


## How To Run This Project

1. Clone this repo.
2. Open the terminal and navigate to this project's production directory called "InventoryPreparedness".
3. Within the production directory "InventoryPreparedness", create a new file called `appsettings.json`.
4. Within `appsettings.json`, put in the following code, replacing the `uid` and `pwd` values with your own username and password for MySQL. For the LearnHowToProgram.com lessons, we always assume the `uid` is `root` and the `pwd` is `epicodus`.

```json
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=vera_weikel;uid=[YOUR-MYSQL-LOGIN-NAME];pwd=[YOUR-MYSQL-PASSWORD];"
  }
}
```

5. Within the production directory "InventoryPreparedness", run `dotnet watch run` in the command line to start the project in development mode with a watcher.
4. Open the browser to _https://localhost:5001_. If you cannot access localhost:5001 it is likely because you have not configured a .NET developer security certificate for HTTPS. To learn about this, review this lesson: [Redirecting to HTTPS and Issuing a Security Certificate](https://www.learnhowtoprogram.com/lessons/redirecting-to-https-and-issuing-a-security-certificate).

## Database Import Instructions

* Open SQL workbench.
* Navigate to the "Administration" tab in SQL Workbench.
* Click "Data Import/Restore"
* Select the radio button "Import from Self-Contained File" and include file path to the sql file of this project that has been cloned to your machine.
* In "Default Schema to be Imported to" click "New".
* _Name the schema "project_name" then click "OK"._
* Once named, switch to "Import Progress" tab and click "Start Import".'

## Database Architecture
  <!-- https://ondras.zarovi.cz/sql/demo/ -->
  <!-- https://www.learnhowtoprogram.com/c-and-net/database-basics/to-do-list-animal-shelter-and-inventory-->
  <!-- ![alt text](Isolated.png "Title") -->

![alt](HairSalon/wwwroot/img/vw_database_structure.png "vw_database_structure")

## Known Bugss

* None

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Copyright (c) 2023 Vera Weikel 

