# bulma-ember-test

This README outlines the details of collaborating on this Ember application.
A short introduction of this app could easily go here.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)
* [Bulma](https://bulma.io/)

## Installation

* `git clone <repository-url>` this repository
* `cd bulma-ember-test`
* `npm install`
* `npm install bulma`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `npm run lint:js`
* `npm run lint:js -- --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

## MY NOTES

This is a test project to learn Ember.js and Bulma.
What about this? does this work now?

bulma new nameOfProject
cd nameOfProject
ember server

http://localhost:4200/ //go here now

>>Let's create a new template using the ember generate command.
ember generate template application

>>The application template is always on screen while the user has your application loaded. In your editor, open app/templates/application.hbs and add stuff


//INSTALLING Bulma
//add to index
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.6.2/css/bulma.min.css">
    <script defer src="https://use.fontawesome.com/releases/v5.0.6/js/all.js"></script>

>>Then create a ember-cli-sass  NPM dependency and create a SCSS file in your App called styles/app.scss  with the following import statement:
@import "bulma";

ember install ember-font-awesome


//updating sass
sass .\app\styles\app.scss .\app\styles\app.css

//add new routes (pages)
ember generate route routeName

## FONT AWESOME
https://fontawesome.com/icons?d=gallery