# AngularPrettier

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.1.0.

## Prettier

## Installation

Install prettier with NPM or YARN:

```bash
npm i prettier -D
```

Create a `.prettierrc` file with the following content:

```json
{
  "singleQuote": true,
  "trailingComma": "es5"
}
```

And also a `.prettierignore`:

```
package.json
package-lock.json
yarn.lock
dist
```

### Set up tslint-config-prettier

Install via npm or yarn:

```bash
npm i tslint-config-prettier -D
```

Create/update the `tslint.json` file with the following content:

```json
{
  "extends": [
    "tslint:recommended",
    "tslint-config-prettier"
  ]
}
```

That's that.

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
