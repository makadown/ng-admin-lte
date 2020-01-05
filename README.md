# NgAdminLte

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.21.

Proyecto guiado por:

https://www.youtube.com/watch?v=47UW2U50TDA


## Prerrequisitos

NodeJs, TypeScript y Angular CLI

## Instalación

1- ng new ng-admin-lte

2- npm install admin-lte@^3.0 --save

3- Agregar en angular.json

``` json
            "styles": [
              "src/styles.css",
              "node_modules/admin-lte/plugins/fontawesome-free/css/all.min.css",
              "node_modules/admin-lte/dist/css/adminlte.min.css"
            ],
            "scripts": [
              "node_modules/admin-lte/plugins/jquery/jquery.min.js",
              "node_modules/admin-lte/plugins/bootstrap/js/bootstrap.bundle.min.js",
              "node_modules/admin-lte/dist/js/adminlte.min.js"
            ]
```

4- Generar componentes Content, ControlSidebar (setting), Footer, MainSidebar y Navbar (menu)

5- Copiar el código html que corresponde a cada componente desde starter.html

6- Llamar a cada componente en app.component.html

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
