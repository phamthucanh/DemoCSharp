# Demo project: Testing MacOS web applications with C# and .NET Core

## Setup
1. Prerequisites: You need to install the following:
- .NET Core
- Visual Studio Code.
- To make Selenium testing easier, install any recording test tools as Selenium IDE/Silk WebDriver...

2. Setup your test project with NUnit:
- Config to use .NET Core in Visual Studio Code, detailed steps following this document: https://code.visualstudio.com/docs/languages/dotnet
- Then install the required packages:

`dotnet add package Selenium.WebDriver -- version 3.6.0`

`dotnet add package Selenium.Support -- version 3.6.0`

`dotnet add package NUnit -- version 3.8.1`

`dotnet add package NUnit3TestAdapter -- version 3.8.0`

`dotnet add package Microsoft.NET.Test.Sdk -- version 15.3.0`

## Create your very first tests in the project.
`dotnet new console`
Then begin your coding!

## To run the tests, run this command.

`dotnet test`

Or if you want to specify the test, run:

`dotnet test -t="<SearchPattern>"`

## How this test will look like:
![Jul-13-2021 01-34-06](https://user-images.githubusercontent.com/32291707/125338504-79911a80-e37a-11eb-85a3-5f3166b870af.gif)


## References:
https://medium.com/@rakeshmick/running-c-nunit-based-selenium-webdriver-tests-in-visual-studio-code-in-mac-os-osx-8f8360652834
https://community.microfocus.com/adtd/b/sws-alm/posts/testing-web-applications-on-macos-with-c-and-net-core
