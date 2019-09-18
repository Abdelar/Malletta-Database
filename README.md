# Malletta: A User-Friendly Access Database

This project was the subject of my second year internship.  
Malletta Database is a desktop application that allow the [INPT](https://www.inpt.ac.ma/ "INPT Website")'s financial department to enter, store and edit data along with applying calculations and filters, in order to get more relevant and useful data.  
>This repo contains a **production version** as well as a **development version** of the database.

![demo](images/demo.gif "demo")

## Features

* Data integrity
* Security
* User-friendly interface
* Navigable
* Buttons and Tooltips
* Automated calculations (TVA,...)
* Filters (By project, account, date, ...)
* Shortcut links to speed up the process

## Tools

* Visual Basic for Applications
* Access macros
* SQL

## Installation

1. Make sure you have a recent version of Microsoft Access installed on your machine. If not, download [Microsoft Access 2016 Runtime](https://www.microsoft.com/en-us/download/confirmation.aspx?id=50040 "access 2016 runtime download").
2. Double click to open production version.
3. Double click and hold shift to open the `development` version of the database.
4. Enter the default password : 0000
5. Add project, account and sub account items before everything else. (you need them to be available when creating the rest of the structure!)

## Development Version

> You may want to remove this `code` from the welcome page load event in the development version to toggle on the **ribbon** and have it visible by default.

``` Visual-basic
Private Sub Form_Load()
DoCmd.ShowToolbar "Ribbon", acToolbarNo
End Sub
```

## Using Shortcut Links

![form](images/shortcut.gif "Speed Up The Process")

## The Home Page

![form](images/HomePage.PNG "Home Page")

## A Submenu

![form](images/SituationFinancière.PNG "A Submenu")

## Example of a Form Page

Perfect for data entry.

![form](images/Opérations.PNG "Form Example")

## Example of a Report Page

A report prepare data to be printed or exported in many formats.

![form](images/Projects.PNG "Report Example")

## More Stuff

Check out some of my other projects on my [personal website](https://abdelar.github.io "My Personal Website"). You can follow me on [LinkedIn](https://www.linkedin.com/in/elaroussi/ "LinkedIn Page") or check out my [art portfolio](https://dribbble.com/Elaroussi "Dribbble Page").
