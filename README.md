"# MyCalendar" 



try and follow steps from :
https://www.youtube.com/watch?v=JvDsnoFU5d8&list=PLCtRwOgYlDn_4Ydf58KCiDhKsZ76H-FHs&index=8

[I'm an inline-style link](https://www.google.com)

and:
https://blog.auberginesolutions.com/blog/how-to-integrate-jquery-fullcalendar-in-angular/


## 1. create a new Angular project named full-calendar-demo:
```
// generate angular project
ng new my-calendar

// go to project directory
cd my-calendar

// start local server
ng serve --open
```

## 2. Install JQuery, moment.js and FullCalendar packages:
```
// install other dependencies ( JQuery and moment ) with 
// fullcalendar
npm install jquery moment fullcalendar --save

// install JQuery types for typescript support
npm install --save-dev @types/jquery
```



## 3. Create a new component named full-calendar:
```
ng g c full-calendar
```


