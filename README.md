# ElementsBuildTesting

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.9.

Custom `ng-build` sample adapted from `ngx-build-plus` project sample - https://github.com/manfredsteyer/ngx-build-plus
This example `Angular Elements` project uses `ngx-build-plus` package to extend the default Angular CLI without the need to `ng eject`...

 - build a single bundle instead of two bundles (quicker)
 - exclude certain packages from the build
 

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

# 1

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

In this setup `ng-build-plus` replaces the default builder. Using extra flags during build:

```
ng build --prod --extraWebpackConfig webpack.extra.js --output-hashing none --single-bundle true\

```

# 2 

Run `ng build:plugin` to build the project with a plugin that run  pre and post build. See `~hook/` directory. 

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.



## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Troubleshooting

Schema validation failed with the following errors:
  Data path ".budgets[1].type" should be equal to one of the allowed values. | https://github.com/manfredsteyer/ngx-build-plus/issues/133


