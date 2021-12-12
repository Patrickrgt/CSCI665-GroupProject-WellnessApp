# Wellness

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.11.

## Setup

Run `npm i` to install any additional libraries on the system.

## Components

`dashboardcomponent.html` is the front-end of the dashboard application, which includes the search bar with the like system implementation.
`dashboardcomponent.ts` contains all the functionality of the dashboard which includes and like and dislike system and event handling for showing the likes tab.

`mealplancomponent.html` is the front-end for friends list, random recipe inspiration, meal-plan generation, and friend recipe recommendations.
`mealplancomponent.ts` contains all the functionality of the meal plan which includes fetching user friends, fetching recipe recommendations, generating meal plans, adding friend functionality, etc.

`authguard.ts` contains the functionality of the login system which includes sign-in, sign-up, resend the verification email, logout, set user, and get user.
components `signup`, `signin`, and `verify` email is respective to components in the login system.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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
