# DatingApp

It is a project for training .NET Core Web APIs and Angular 10. Hence, the repository has two main folders: DatingApp-SPA and DatingApp.API. Designing the backend side is made by a general .NET structure. For the frontend side, no specific design pattern is used.

The general theme of the project is dating. A user can list other users, monitor others’ profiles, create, edit and delete his/her profile.

## Before Running

Before installing this program, follow the instructions below. (If you have already installed these requirements, disregard this part.)
* Install .NET SDK 3.1+ [here](https://dotnet.microsoft.com/download/dotnet/3.1)
* Install Node.js [here](https://nodejs.org/en/)
* Install Angular by using the command below.
```
npm install - g @angular/cli
```
* Install EF Core by using the command below.
```
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
```

## How To Run

* Use the dotnet restore command for package management in the DatingApp.API folder.
```
dotnet restore
```
* Use the npm install command for module management in the DatingApp-SPA folder.
```
npm install
```
* Start .NET with the command below in the API folder.
```
dotnet watch run
```
* Start Angular with the command below in the client-app folder.
```
ng serve
```
