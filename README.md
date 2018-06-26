# Jasmine framework for testing JavaScript code
===============================================

## Table of Contents
* [About](#about)
* [Project](#project)
* [Installation](#installation)
* [Contributing](#contributing)

### About

Jasmine is a behavior-driven development framework for testing JavaScript code. It does not depend on any other JavaScript frameworks. It does not require a DOM.

### Project

A project is a part of Udacity Nanodegree program. The project teaches how to write tests with different scenarios such as testing combined with asynchronous requests etc.


### Installation

To install current project run in you terminal

```
git clone git@github.com:VolodymyrPliuta/frontend-nanodegree-feedreader.git
```
1.  Open index.html
2.  Make changes in js/app.js
3.  To see what test are passed refresh you browser
4.  To write custome unit tests. Open jasmine/spec/feedreder.js

It had already installed Jasmine but if your want to install on you project follow the instructions below.

run in your terminal to install Jasmine globally

```
npm install -g jasmine
```
#### Init a Project

Initialize a project for Jasmine by creating a spec directory and configuration json for you.

```
jasmine init
```
Change directory for writing your tests

```
cd spec
```

Create any file with .spec.js - extension and write your test inside of the file

```
touch test.spec.js
```
## YOU ARE READY TO WRITE YOUR FIRST TEST!!!

### example:

```
describe('Hello world', () => {
  it('hello test', () => {
  });
});
```
Go to your project  directory and run:

```
jasmine
```
## Contributing

Any person should feel free to contribute to this project. All requests will be reviewed


