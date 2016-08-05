# BLT Project

This is a Composer-based installer for a Drupal 8 project utilizing [BLT](https://github.com/acquia/blt).

## Get Started
You will need the following installed:

* [Composer](https://getcomposer.org), obviously
* [Node](https://nodejs.org), which includes the NPM package manager

1. When you have those, run this command:

  ```
  $ composer create-project acquia/blt-project:8.x-dev MY_PROJECT --no-interaction
  ```
  Composer will create a new directory called MY_PROJECT containing a ```docroot``` directory with a full D8 codebase therein, including BLT.
1. Follow [remaining instructions in BLT](https://github.com/acquia/blt/blob/8.x/INSTALL.md#set-up-your-amp-stack) for setting up your local \*AMP stack and installing Drupal locally.

## License

Copyright (C) 2016 Acquia, Inc.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 2 as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
