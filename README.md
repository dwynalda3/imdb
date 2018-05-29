# \<371_IMDB\>

Semester Project in CIS371 - recreating IMDB

## Project Requirements
* ~~(10 %) User authentication system (login/logout)~~
* (15 %) The data of your web app should be stored on Firebase. Your data should include the following two types
    * Private per-user data accessible only to its authenticated owner
    * ~~Shared data accessible to all users~~
* (10 %) ~~Acquire your own data to populate your database. You can copy the data from web sources~~
* ????? ~~(20 %) Build your app using Polymer custom elements (own elements as well as 3rd-party ones)~~ (I think)
* (10 %) ~~Include (at least) a section that shows data from the database in a nicely formatted table/list.~~
* (10 %) ~~Design a “form” (not necessarily an HTML form) to allow your users to make changes to the data (insert & delete)~~
* (10 %) Use CSS to customize the visual styles of your web app and custom elements

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then r*n `polymer serve` to serve your application locally.*
## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
