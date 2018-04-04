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