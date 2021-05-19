# GOAL COMPONENTS

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.12.
# PROJECT DESCRIPTION
The target in the square brackets, [], is the property you decorate with @Input() in the child component. The binding source, the part to the right of the equal sign, is the data that the parent component passes to the nested component.
The key takeaway is that when binding to a child component's property in a parent component—that is, what's in square brackets—you must decorate the property with @Input() in the child component.
I have used the selector for the GoalDetailComponent and nested it into the GoalComponent, placing it after the goal name which is where we want to display the description of each goal.
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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
