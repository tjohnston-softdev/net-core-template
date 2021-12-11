### .NET Core Template Instructions

1. Create a new folder. This will be your project root.
2. Open a terminal inside the created root folder.
3. Initialize the .NET project with: `dotnet new console -o HelloWorld`
4. Navigate back to the root folder.
5. Create the solutions file with: `dotnet new sln`
6. Add the .NET project to the solutions file with: `dotnet sln add HelloWorld`
7. Create a new folder inside the root named: `HelloWorld.Tests`
8. Navigate to `./HelloWorld.Tests`
9. Create the NUnit testing project with: `dotnet new nunit`
10. Navigate back to the root folder.
11. Add the NUnit project to the solutions file with: `dotnet sln add HelloWorld.Tests`

To run the .NET script, execute `dotnet run` inside the `HelloWorld` folder.

To run the unit tests, execute `dotnet test` inside the root folder.
