# CordovaAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.9.

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

## For getting started
after fetching repository<br />
install dependencies<br />
`cd cordova-angular`<br />
angular dependencies<br />
`npm install`<br />
for cordova<br />
`cd cordova-angular`(inside cordova-angular)<br />
`npm install`<br />
install and configure cordova platforms and plugins<br />
`cordova prepare`<br />

## start building
`cd ..` (in to root directory)<br />
`ng build`<br />
`cd cordova-angular`<br />
`cordova run browser` (to preview in browser)<br />
`cordova build android` (to generate debug app inside plateforms/android/build/outputs/apk/android-debug.apk)<br />
