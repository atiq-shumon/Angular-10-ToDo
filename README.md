# MyTodoApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.0.

# MyTodoApp Details

* The application is in Angular 10 with recent version of Node and used Angular material component library, SCSS, flexbox layout module and template-driven forms. 
* Local Storage is used for storing the data.
* The application consists of two pages. The first page includes the list of to-dos and second page is for Edit/View or adding a new item with a calender showing current week.
* The calendar is made dynamic which highlights the current date and each to-do item is automatically stored with created date and time. 
* Angular Material chips is used for adding tag items in View/Edit page and all icons are material icons with outlined or filled feature.
* For maintaining Angular state management properly all page reloads are routed back to the Home page. 
* A simple validation in Edit/Add item where the Finish/Update button remains disabled until either of the description or project field is filled.
* Included Angular unit testing with Karma and Jasmine and maintained more than 80% code coverage. 

## How To install and run this repository in your local machine

Use git clone or download the folder to your local machine. Then run 

    npm install 

to download the required node modules in your downloaded folder. Then start the application using
	
    ng serve -o 

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Todo App Screenshots

![ipad-addlist](https://github.com/sreekanthkylm/Angular-10-ToDo/tree/master/assets/ipad-addlist.PNG)


## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
