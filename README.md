# BookStore
Book Store

 This application is used to manage a list of books and their authors. It is developed using the following technologies:

Entity Framework Core as the database provider.
MVC / Razor Pages as the UI Framework.

## Guide

Install ABP
dotnet tool install -g Volo.Abp.Cli

Try running the command abp --help. If you get a message stating that abp is not a known command, you may need to create a .zshrc file to allow you to access the ABP CLI from ZSH. Within Terminal, run the following commands:

vi ~/.zshrc
Paste export PATH=$HOME/.dotnet/tools:$PATH
Run the command :wq to write the file to disk and quit
Restart Terminal.app and you should be able to run abp --help

## DB

Enter admin as the username and 1q2w3E* as the password to login to the application. The application is up and running. You can start developing your application based on this startup template.