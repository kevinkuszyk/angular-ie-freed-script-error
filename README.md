# Angular IE freed script error

This repro contains a sample app to repro both [angular/zone.js#933](https://github.com/angular/zone.js/issues/933) and [angular/zone.js#1001](https://github.com/angular/zone.js/issues/1001).  

Both of these issues are intermittent.  Starting the app and then refreshing IE a few times is usually enough to reproduce one or both of them.

![image](https://user-images.githubusercontent.com/2734580/35444117-624945b4-02a5-11e8-8b89-672c3083b431.png)

----

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
