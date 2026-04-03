# BlazingChat - Realtime Chat App using Blazor WASM and SignalR

> BlazingChat is a fullstack realtime chat app using Asp.Net Core Blazor Web Assembly (WASM) and SignalR Core with SQL Server and EF Core - .Net 6

## To Run Locally
    
- Restore the packages (Rebuild the solution)
    
- Set the `BlazingChat.Server` project as startup project
    
- Change the Database connection string in `appsettings.Development.json` file in `BlazingChat.Server` Project
    ```
    "ConnectionStrings": {
        "Chat": "Data Source=.;Initial Catalog=BlazingChat; Integrated Security=True; Trusted_Connection=True;"
     }
     ``` 
     
- Run the migrations - to update the database using following Package Manager Console Command
    
    `Update-Database`

- Run the solution

-------------------------------


