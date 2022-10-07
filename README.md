# Hair Salon Manager

#### By Skylan Lew

#### Independent Project 9 for Epicodus

## Technologies Used

- C#
- .NET 5
- ASP.NET Core MVC
- Entity
- MySQL
- Javascript
- HTML

## Description

This application allows the user to track stylists and their clients for a hair salon using a MySQL database.

The user can create Stylists, and Clients under already existing Stylists in a one to many relationship. They may not create Clients if there is no Stylists.

Stylists and Clients can be edited, where any information about them may be changed, except for their ID.

Stylists and Clients may be deleted.

Deleting a stylist also deletes their clients, if there are any. The deletion confirmation page shows a list of the Stylist's clients.

## Setup/Installation Requirements

- Import `skylan_lew.sql` as a new schema with name `skylan_lew`
- Create a file named `appsettings.json` in the project folder `/HairSalon/`
- Put the following code inside `appsettings.json`, making sure to set your uid and pwd:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=skylan_lew;uid=YOURUSERNAME;pwd=YOURPASSWORD;"
  }
}
```

### Requires

- [.NET 5](https://dotnet.microsoft.com/en-us/download/dotnet/5.0) - <https://dotnet.microsoft.com/en-us/download/dotnet/5.0>
- MySQL - Recommend [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)

### Download/Run Instructions (git)

- clone: `$ git clone https://github.com/doublespoiler/hair-salon.git` or Code>Download ZIP
- navigate to project folder: `$ cd /HairSalon`
- restore: `$ dotnet restore`
- build: `$ dotnet build`
- run: `$ dotnet run`

## Known Bugs

## License

[MIT](https://choosealicense.com/licenses/mit/)
`[MIT](https://choosealicense.com/licenses/mit/)`

Copyright (c) 2022 Skylan Lew
