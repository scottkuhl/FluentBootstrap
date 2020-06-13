# Fluent Bootstrap

The goal of this project is to apply **default variables to Bootstrap** based on
the guidelines from the [Microsoft Fluent Web](https://github.com/OfficeDev/office-ui-fabric-core) project.
It does **not** attempt to make Bootstrap look like a clone of the Fluent project.
The changes are very lightweight, should allow you to adjust them easily,
and not prevent you from upgrading to newer versions of Bootstrap.

Other projects like [WinStrap](https://github.com/winjs/winstrap) and 
[Fluent Design from MDB](https://github.com/mdbootstrap/bootstrap-fluent-design) have gone much deeper into making a
Fluent clone but projects like these tend to get left behind and stuck on a particular
version of Bootstrap because of this.  WinStrap is set to Boostrap 3.3.7 with Windows 8 guidelines and MDB
is set to 4.0.0 with older Windows 10 based guidelines.

## How to use in your project

Copy the three Bootstrap based SASS files into your project and compile them.  

1. light.scss - contains base variables.
2. dark.scss - builds upon the light.scss file and renders a dark theme.  You don't need this one if you are going for a light theme.
3. bootstrap.scss - set the above theme to the one you want and update the bootstrap target path.

## The Settings

- Bootstrap's greys have been mapped to Fluent UI's [Neutrals](https://developer.microsoft.com/en-us/fluentui#/styles/web/colors/neutrals).

- Bootstrap's base colors have been mapped to Fluent UI's [Shared](https://developer.microsoft.com/en-us/fluentui#/styles/web/colors/shared).

- Bootstrap's primary colors have been mapped to Fluent UI's [Messaging](https://developer.microsoft.com/en-us/fluentui#/styles/web/colors/messaging).

- Bootstrap's shadows and radius have been mapped to Fluent UI's [Elevation](https://developer.microsoft.com/en-us/fluentui#/styles/web/elevation).

- Bootstrap's grid breakpoints have been mapped to Fluent UI's [Layout](https://developer.microsoft.com/en-us/fluentui#/styles/web/layout).

- Bootstrap's typography has been mapped to Fluent UI's [Typography](https://developer.microsoft.com/en-us/fluentui#/styles/web/typography).

- The Dark theme colors are based on Darkly settings from [Bootswatch](https://github.com/thomaspark/bootswatch).

## Sample Project

The FluentBootstrap project is a sample project based on ASP.NET Core that uses these SASS files.  It contains
a default page like the ones from the Bootswatch project for testing changes.

### Special Thanks

A special thanks to all the [Bootstrap](https://github.com/twbs/bootstrap), 
[Fluent UI](https://github.com/OfficeDev/office-ui-fabric-core) and 
[Bootswatch](https://github.com/thomaspark/bootswatch) contributors for making this possible.