# Web Frontend Stack

This is a basic web development stack based on yeoman angular generator.

## Contents:
- Angular 1.5.x
- Bootstrap 3
- Simple example containing some best practice's:
    - feature per folder
    - naming conventions
    - using "controller as"
- angularFileLoader - automatically sort ans inject AngularJS app files depending on module definitions and usage in index.html
- continuously runs js linting and unit tests

## Installation

	npm install -g bower grunt-cli
	npm install
	bower install

## Usage

Development mode

	grunt serve

Generate distribution package

	grunt dist

Preview distribution build

    grunt serve:dist