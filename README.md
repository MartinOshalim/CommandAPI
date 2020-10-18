# CommandAPI
Simple .NET Core 3.1 MVC API that allows you to store, update, delete and update commands that you use day-to-day in case you forget them and need need somewhere to look them up thats not Google.

# Tech and patterns used:
* Dependency Injection
* Automapper - To map model to Dto models and vice-versa
* Repository pattern - SqlCommanderRep.cs encapsulates all the logic required to modify data in the commands table.
* Entity framework - Code first approach, build your model then create your database.
* Newtonsoft.Json & Microsoft.AspNetCore.JsonPatch - To serialize and deserialize JSON to support Patch Http verb.

# Possible future updates & improvements
* Logging
* Creating base classes for Command.cs
* Create common functions for checking if resource exists

# Credit
Les Jackson and the .NET 3.1 MVC Rest API Course - https://www.youtube.com/watch?v=fmvcAzHpsk8
