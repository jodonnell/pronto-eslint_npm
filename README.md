# Pronto runner for ESLint (using eslint from npm)

[![Code Climate](https://codeclimate.com/github/doits/pronto-eslint_npm.svg)](https://codeclimate.com/github/doits/pronto-eslint_npm)
[![Build Status](https://travis-ci.org/doits/pronto-eslint_npm.svg?branch=master)](https://travis-ci.org/doits/pronto-eslint_npm)
[![Gem Version](https://badge.fury.io/rb/pronto-eslint_npm.svg)](http://badge.fury.io/rb/pronto-eslint_npm)
[![Dependency Status](https://gemnasium.com/doits/pronto-eslint_npm.svg)](https://gemnasium.com/doits/pronto-eslint_npm)

Pronto runner for [ESlint](http://eslint.org), pluggable linting utility for JavaScript and JSX. [What is Pronto?](https://github.com/mmozuras/pronto)

Uses system wide installed eslint in contrast to [pronto-eslint][pronto-eslint].

[pronto-eslint]: https://github.com/mmozuras/pronto-eslint

## Prerequisites

You'll need to install [eslint by yourself with npm][eslint-install].

[eslint-install]: http://eslint.org/docs/user-guide/getting-started

## Configuration

Configuring ESLint via [.eslintrc and consorts][eslintrc] and excludes via [.eslintignore][eslintignore] will work just fine with pronto-eslint.

[eslintrc]: http://eslint.org/docs/user-guide/configuring#configuration-file-formats
[eslintignore]: http://eslint.org/docs/user-guide/configuring#ignoring-files-and-directories
