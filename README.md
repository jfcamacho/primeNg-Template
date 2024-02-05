# INTEGRATION OF PRIMENG TEMPLATE AND PRIMEFLEX COMPONENTS
These are different steps to implement a template from primeng and primeflex

## Prerequisites

Download the template from the PrimeNg repository [PrimeNg](https://primeng.org/templates)

## Starting a new project

Install the latest version of NodeJs from [Node Js](https://nodejs.org/en/download)

## Commands

`npm init -y` Create the package.json file to start the new project

`npm install primeng` Install primeNg

`npm install primeicons` Install prime icons

`npm install XXXX` Install additional packages

`npm install -g @angular/cli` Install Anfular CLI

## Process

Create angular project with `ng new myApp` and navigate to your new app, if it's version is greater than 14 use `ng new App --no-standalone`

Install primeng, primeicons and primeflex

Copy your theme into assets folder and copy the path of theme

If you have a licensed template, also copy sass directory into assets folder

Open the file `angular.json` and note down the theme's path into `architec > styles`

Free themes can be found in the resources folder in primeng

```
"styles": [
    "node_modules/primeng/resources/themes/tailwind-light/theme.css",
    "node_modules/primeng/resources/primeng.min.css",
    "node_modules/primeflex/primeflex.css"
    ...
]
```

Run the app with `npm start` inside myApp. It will open your browser at localhost:4200

`Your project is now ready for use`
