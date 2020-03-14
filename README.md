# Fixie .NET Core Project Template
[![Fixie.NetCore.ProjectTemplates](https://img.shields.io/badge/nuget-1.0.0-blue)](https://www.nuget.org/packages/Fixie.NetCore.ProjectTemplates) [![Twitter Follow](https://img.shields.io/twitter/follow/jasontaylordev.svg?style=social&label=Follow)](https://twitter.com/jasontaylordev)

A project that contains Fixie tests that can run on .NET Core on Windows, Linux, and MacOS. The initial version supports Fixie 2.2.0 on .NET Core 3.1.

## Quick Start
Fixie is a .NET test framework similar to NUnit and xUnit, but with an emphasis on low-ceremony defaults and flexible customization. Official documentaion can be found at https://fixie.github.io.

Install the .NET Core project template:

```
$ dotnet new --install Fixie.NetCore.ProjectTemplates
```

Create the new project:

```
$ mkdir FixieTests
$ cd FixieTests
$ dotnet new fixie
```

Install a third-party assertion library such as [Shouldly](https://github.com/shouldly/shouldly) or [FluentAssertions](https://fluentassertions.com/):

```
$ dotnet add package FluentAssertions
```

Run your tests from the command line by executing:

```
$ dotnet test

Starting test execution, please wait...

A total of 1 test files matched the specified pattern.

Test Run Successful.
Total tests: 1
     Passed: 1
 Total time: 1.3061 Seconds
```

To run your tests from inside Visual Studio, open Test Explorer (**Test** \ **Windows** \ **Test Explorer**). Rebuild your solution and click **Run All** to get started.