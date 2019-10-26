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
