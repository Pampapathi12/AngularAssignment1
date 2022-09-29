# EmployeeCrudOperations

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.4.

# Project Setup in Local
create folder name: Project in your system
goto this project repository select the repo path
install git version control system in your pc
open Project folder inside right click mouse and select git cli option 
> git clone reponame
-> open visual studio code 
PS D:\Project>cd AngularAssignment1
## Package install

npm i @angular/fire

npm i @angular/core

build project -> PS D:\Project>cd AngularAssignment1 ng build

run application -> PS D:\Project>cd AngularAssignment1 ng serve

## Creatting component services modal follow steps

PS D:\Project>cd AngularAssignment1 ng generate component component_name
ng generate service service_name
ng generate directive directive_name


## If any error like
[{
	"resource": "/d:/Project2/AngularAssignment1/src/app/modal/edit-employee/edit-employee.component.ts",
	"owner": "typescript",
	"code": "7016",
	"severity": 8,
	"message": "Could not find a declaration file for module 'tslib'. 'd:/Project2/AngularAssignment1/node_modules/tslib/tslib.js' implicitly has an 'any' type.\n  Try `npm i --save-dev @types/tslib` if it exists or add a new declaration (.d.ts) file containing `declare module 'tslib';`",
	"source": "ts",
	"startLineNumber": 7,
	"startColumn": 1,
	"endLineNumber": 11,
	"endColumn": 3
}]

Ans- just close the visual studio code and repoen


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
