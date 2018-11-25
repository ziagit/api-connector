
# api-connector
This app is under development.
Currently working parts:
* Shopify server is connected to ERPnext, when an order creates in Shopify it will synched to ERPNext.
* Shopify server is connected to Social medias (Facebook, Pinterest)

# How to make this app work.
1)  Register/Specify your remotes url in file named `proxyconfig.json` (this proxy is created to solve CORS problems in server side)
2)  Create a private app in Shopify store and use its app id and app secret in shopify-erpnext service
3)  Create app in facebook and use its id and token in shopify-socialmedia service


# MyProject

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.2.

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
