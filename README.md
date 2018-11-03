gengojs-mean-demo
===============

[![Greenkeeper badge](https://badges.greenkeeper.io/iwatakeshi/gengojs-mean-demo.svg)](https://greenkeeper.io/)

A single page MEAN app that demonstrates the use of Gengo, Jade, and best of all Angularjs.


###Note

The app is based on Scotch.io's [*Creating a Single Page Todo App with Node and Angular*](http://scotch.io/tutorials/javascript/creating-a-single-page-todo-app-with-node-and-angular) tutorial.

I've changed the app to where it now uses Jade template and also [gengo](https://github.com/iwatakeshi/gengojs) library which is a Uber for i18n translation.

##Install

```bash
sudo npm install
```

##Run

```bash
npm start
```
##Usage

Use Postman or add Japanese to your web browser's locale. Then browse to localhost:8080.
This app will output in Japanese when Accept-Language header is 'ja' and English for others.

##Requirements

* MongoDB
* Node
* NPM
