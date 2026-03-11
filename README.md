# MvcMovie

This is an ASP.NET Core MVC application managing a database of movies.
It demonstrates basic model-view-controller patterns and interacts with an SQLite database using Entity Framework Core.

## Getting Started

### Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/download/dotnet/10.0) or later.

### Build and Run

1.  Restore dependencies and build the project:
    ```bash
    dotnet build MvcMovie.csproj
    ```

2.  Run the application:
    ```bash
    dotnet run
    ```
    The application will typically be accessible at `http://localhost:5000`. Navigate to `/Movies` to see the listing.

## Features

* List all movies.
* Create, read, update, and delete (CRUD) operations on movies.
* Filter movies by genre and release year.
