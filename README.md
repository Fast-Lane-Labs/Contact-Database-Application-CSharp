
# Contact Application
This is a contact management application built with C# and .NET.

![Contact Application](https://cdn.fastlane-israel.com/public/ContactApplicationFastLaneCSharp.png)

## Project Structure

The project is structured as follows:

- `Controllers/`: Contains the [`UserController`](Controllers/UserController.cs) which handles user-related operations.
- `Models/`: Contains the [`User`](Models/User.cs) model.
- `ContactApplication.Tests/`: Contains unit tests for the application, including [`UserControllerTests`](ContactApplication.Tests/UserControllerTests.cs).
- `Views/`: Contains the views for the application.
- `wwwroot/`: Contains static files like CSS and JavaScript.

## Setup

1. Clone the repository.
2. Build the project:
```
dotnet build
```

## Running the Application

1. Set `ContactApplication` as the startup project.
```
dotnet run
```

## Running the Tests

1. Open the Test Explorer in Visual Studio.
```
dotnet test
```
