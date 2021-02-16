# @leny/konteks

> Dev env & config for NodeJS

* * *

## About

A collection of config files & scripts to install dev env & tools.  
This module contains common ESLint rules, Prettier config & some other useful stuffs (husky, etc.)

## Usage

You can also use the following command in your project:

	npx @leny/konteks

That will create the eslint config file *and* install the needed dependencies.
Simple and easy.

#### (optional) Create `pre-commit` git hook

You can also setup a git `pre-commit` hook to ensure that ESlint and Prettier are run *before* each commit, discarding commit if there's an error.

Simply use the `--with-hook` flag:

	npx @leny/konteks --with-hook

#### (optional) Create `lint` npm script

You can also setup a `lint` npm script to lint and prettify your files.

> 🖐 **NOTE:**the script assumes your files are in a folder called `src`. Correct the path in your package.json if needed.

Simply use the `--with-script` flag:

	npx @leny/konteks --with-script

* * *