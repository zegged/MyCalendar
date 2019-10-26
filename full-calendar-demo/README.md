"# MyCalendar" 

follow steps from :
https://medium.com/aubergine-solutions/how-to-integrate-jquery-fullcalendar-in-angular-c35728cfeeb2



## Step-1.
Let’s first create a new Angular project named full-calendar-demo:
```
// generate angular project
ng new full-calendar-demo
// go to project directory
cd full-calendar-demo
// start local server
ng serve --open
```

## Step-2.
Install JQuery, moment.js and FullCalendar packages:
```
// install other dependencies ( JQuery and moment ) with 
// fullcalendar
npm install jquery moment fullcalendar --save
// install JQuery types for typescript support
npm install --save-dev @types/jquery
```

## Step-3.
Create a new component named full-calendar:
```
ng g c full-calendar
```





# FullCalendarDemo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
