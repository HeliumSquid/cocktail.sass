![](http://i.imgur.com/bBylLMW.png)
# Cocktail.sass
A simple material design library for Sass.

[![Dependency Status](https://david-dm.org/HeliumSquid/cocktail.sass.svg)](https://david-dm.org/HeliumSquid/cocktail.sass)
![](https://img.shields.io/badge/colours-21-orange.svg)

## Contents

- [Install](#install)
- [Usage](#usage)
- [Content](#content)
  - [Colours](#colours)
  - [Buttons](#buttons)
  - [Rounded Buttons](#rounded-buttons)
  - [Action Buttons](#action-buttons)
  - [Fixed](#fixed)
- [Dependencies](#dependencies)
- [License](#license)

## Install

### Manually

[Download here.](https://github.com/HeliumSquid/cocktail.sass/archive/master.zip)

### Bower

```bash
$ bower install cocktail.sass

```

## Usage

```bash
// All of Cocktail.sass
@import "cocktail.sass/assets/cocktail.sass";
```

## Content

### Colours:

$black: #000000

$white: #ffffff

$red: #f44336

$pink: #e91e63

$purple: #9c27b0

$deep_purple: #673ab7

$indigo: #3f51b5

$blue: #2196f3

$light_blue: #03a9f4

$cyan: #00bcd4

$teal: #009688

$green: #4caf50

$light_green: #8bc34a

$lime: #cddc39

$yellow: #ffeb3b

$amber: #ffc107

$orange: #ff9800

$deep_orange: #ff5722

$brown: #795548

$grey: #9e9e9e

$blue_grey: #607d8b

### Buttons:

.button

.button-black

.button-white

.button-red

.button-pink

.button-purple

.button-deep-purple

.button-indigo

.button-blue

.button-light-blue

.button-cyan

.button-teal

.button-green

.button-light-green

.button-lime

.button-yellow

.button-amber

.button-orange

.button-deep-orange

.button-brown

.button-grey

.button-blue-grey

```bash
<a class="button" href="">Button</a>

<a class="button button-red" href="">Button</a>
```

### Rounded Buttons:

.button-rounded

```bash
<a class="button button-rounded" href="">Button</a>

<a class="button button-rounded button-red" href="">Button</a>
```

### Action Buttons:

.button-action

```bash
<a class="button button-action" href="">Button</a>

<a class="button button-action button-red" href="">Button</a>
```

### Fixed

.fixed

```bash
<a class="button button-action fixed" href="">Button</a>
```

## Dependencies

You'll need the following installed:

- Latest Sass: `$ gem install sass`
- Latest Grunt CLI: `$ npm install -g grunt-cli`
- [Node.js and npm](http://nodejs.org/download/)

```bash
$ npm install
```

- grunt-contrib-concat
<<<<<<< HEAD
=======
- grunt-contrib-jshint
>>>>>>> fd6f7d080356e2b4a0d23f0a4523d8d280e23a40
- grunt-contrib-sass
- grunt-contrib-uglify
- grunt-contrib-watch

To run all of this at once you can use:
<<<<<<< HEAD

```bash
$ grunt default
```

To automatically recompile the Sass files:
=======
>>>>>>> fd6f7d080356e2b4a0d23f0a4523d8d280e23a40

```bash
$ grunt default
```

## License

Created by and copyright HeliumSquid. Released under the MIT license.
