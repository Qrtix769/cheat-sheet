[![](../../../../../../../icons/backward.png)](../../NET.md)
Before creating any validators, you will need to add a reference to FluentValidation.dll in your project. The simplest way to do this is to use either the NuGet package manager, or the dotnet CLI.

Using the NuGet package manager console within Visual Studio run the following command:

```
Install-Package FluentValidation
```

Or using the .NET Core CLI from a terminal window:

```
dotnet add package FluentValidation
```

For integration with ASP.NET Core, install the [FluentValidation.AspNetCore](https://www.nuget.org/packages/FluentValidation.AspNetCore/) package from Visual Studio:

```
Install-Package FluentValidation.AspNetCore
```

or from the command line:

```
dotnet add package FluentValidation.AspNetCore
```