# Simple React Redux Boilerplate

### Built with Webpack Babel and Gulp under the hood

This is an experimental [React](http://google.com) boilerplate App that I use to spin my front-end environment when I am building new applications.

Here's how it's set up:

* Babel
* Webpack
* Gulp
* Nightwatch - Selenium testing
* Jest - Unit Testing
* JSON Server
* Redux

## Project Structure

````
$ tree --charset unicode
.
|-- app
|   |-- bower_components
|   |-- css
|   |-- fonts
|   |-- images
|   |-- js
|   |-- src
|   |-- |-- actions
|   |-- |-- components
|   |-- |-- containers
|   |-- |-- reducers
|   |-- |-- store
|   |-- |-- views
|   |-- |-- index.ejs
|   |-- |-- index.js
|   |-- |-- routes.js
|   |-- index.html
|-- dist
|-- jsonserver
|-- node_modules
|-- test
|-- .babelrc
|-- .bowerrc
|-- .bowerrc_template
|-- .gitignore
|-- bower.json
|-- gulpfile.js
|-- jenkinsfile
|-- nightwatch.conf.js
|-- package.json
|-- README.md
|-- wct.conf.js
|-- webpack.config.js
````

## How To Set Up

1. Checkout the code
2. Navigate into the project directory
3. Run the following commands

```
yarn install

bower install
```

These commands will set up all the modules and libraries you need for the App.

To Run the App:

```
yarn run start
```

If you want to rebuild the dist folder:

```
yarn run build
```
