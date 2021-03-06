# Angular 2 and TypeScript Workshop

The Angular 2 and TypeScript workshop is a full day workshop 
written and presented by [@JeremyLikness](https://twitter.com/JeremyLikness) for [Connect.Tech 2016](http://connect-js.com). 
The workshop leverages cross-platform solutions so  developers on any of the major (Windows, Linux, and OSX) platforms
can take advantage of it. Prior knowledge and experience with web applications and JavaScript 
is highly recommended to get the most out of the workshop. It is designed to benefit 
users who have no Angular exposure as well as those familiar with Angular 1.x. Successful 
installation of the prerequisites is important to complete prior to the workshop to 
ensure the best possible experience (this will help minimize any potential issues with Wi-Fi availability and bandwidth). 

## Pre-requisites

The following cross-platform resources will be required to participate in this workshop:

Node.js environment (LTS): [Install from this Link](https://nodejs.org/en/)

>**Note:** Issues have been reported with the latest version of `npm` package manager. Some report that rolling back to a previous version works. These labs were tested with version 3.10.5. On MacOS systems it has been verified that Node 6.x with npm 3.10.8 works.

Angular-CLI scaffold and rapid development tool: `npm i -g angular-cli@1.0.0-beta.16` 

Visual Studio Code Interactive Development Environment (IDE): [Install from this Link](https://code.visualstudio.com/) 

.NET Core Backend Platform: [Install from this Link](https://www.microsoft.com/net/core)

*Optional* Container Platform: Docker [Install from this Link](https://docs.docker.com/engine/installation/)

You may want to look ahead and complete the initial set up and `npm install` steps for various 
modules to pre-load the dependent packages and save development time during the workshop. For the advanced lab that uses .NET Core, you will also need to run `dotnet restore` in the project root. 

Make a few starter projects like this: 

`ng new connect-ts-ng2`

`ng new dependency-injection`

`ng new data-binding`

`ng new reactive` 

For the Advanced: 

`npm i -g yo` 

`npm i -g generator-aspnetcore-spa` 

`mkdir advanced` 

`cd advanced` 

`yo aspnetcore-spa` 

(Chose Angular 2 and the default project name).

>**Note** This repository contains several projects in their finished state. Many of the labs
>involve transitory states to teach functionality in an iterative fashion. Although you can run
>the existing labs, it is recommended you walk through the code tutorials to receive the full benefit.
>For the existing labs, change to the root directory of any given lab and run `npm install` then `ng serve` 
>to view the lab. For the labs you work on, it is suggested you create your own parent level folder, i.e. `lab`, 
>to run the labs from (so you will end up with `lab\connect-ts-ng2` and `lab\dependency-injection` etc.)

## Modules 

The following modules will be covered in the workshop.

### 1. Angular Intro (30 minutes)

A quick background introduction to Angular, its history, and its use in
modern web applications.

[Click here for the lab](./00Intro.md)

### 2. Angular "Hello, World." (30 minutes)

A quick and easy Angular project.

[Click here for the lab](./0AHelloWorld.md)

#### 2a. JavaScript 

The project in JavaScript.

#### 2b. TypeScript 

The project in TypeScript. 

### 3. Angular-CLI (20 minutes)

A command line tool to scaffold and rapidly develop Angular 2 apps.

[Click here for the lab](./10AngularCLI.md)

### 4. TypeScript (1 hour)

A quick introduction to TypeScript and its various benefits.

[Click here for the lab](./1ATypeScript.md)

### 5. Components, Directives, and Pipes (30 minutes)

Getting started with the basics.

[Click here for the lab](./20CompDirPipe.md)

### 6. Dependency Injection (30 minutes)

Understanding lifetime and providers.

[Click here for the lab](./2ADependencyInjection.md)

### 7. Data-Binding (30 minutes)

How data flows from parents through to children. 

[Click here for the lab](./30DataBinding.md)

### 8. Asynchronous Operations and RxJS (30 minutes)

[Click here for the lab](./3ARxJS.md)

### 9. Advanced Topics (30 minutes)

[Click here for the lab](./40Advanced.md)

* Scaffold a full .NET Core SPA app with database
* Examine routing 
* Containerize

### 10. Optional Topic: Migration

(This is a discussion topic)