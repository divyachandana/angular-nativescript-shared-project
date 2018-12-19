# commands
npm i -g @nativescript/schematics
ng new --collection=@nativescript/schematics sharedproj --shared

tns run ios --bundle
tns run android --bundle
ng serve

if you got to update any tns modules use
tns info

sudo npm i -g nativescript@next
sudo npm i -g tns-core-modules@next
sudo npm i -g tns-android@next
sudo npm i -g tns-ios@next

# References
https://docs.nativescript.org/angular/code-sharing/creating-a-new-project

https://www.nativescript.org/nativescript-is-how-you-build-native-mobile-apps-with-angular/code-sharing-angular-and-nativescript

# sharedproj

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.0.

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
