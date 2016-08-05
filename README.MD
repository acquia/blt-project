# BLT Project

This is a Composer-based installer for a Drupal 8 project utilizing BLT.

## Get Started
You will need the following installed:

* [Composer](https://getcomposer.org), obviously
* [Node](https://nodejs.org), which includes the NPM package manager

When you have those, run this command:
```
$ composer create-project acquia/blt-project:8.x-dev MY_PROJECT --no-interaction
```
Composer will create a new directory called MY_PROJECT containing a ```docroot``` directory with a full D8 codebase therein, including BLT. You can then install it like you would any other Drupal site.
