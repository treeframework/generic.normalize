# Normalize

The `normalize` module is an exact clone of [Normalize.css](https://github.com/necolas/normalize.css/)
at version v4.0.0. Normalize.css <q>makes browsers render all elements more
consistently and in line with modern standards. It precisely targets only the
styles that need normalizing</q>.

## Installation

You can install `normalize` module via Bower, npm, Git Submodule, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-normalize --save
```

Once installed, `@import` into your project in its Generic layer:

```scss
@import "bower_components/tree-normalize/generic.normalize";
```

### Install using npm:

```sh
$ npm install tree-normalize --save
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/generic.normalize.git
```

Once installed, `@import` into your project in its Generic layer:

```scss
@import "generic.normalize/generic.normalize";
```

### Install via file download

The least recommended option for installation is to simply download
`_generic.normalize.scss` into your project and `@import` it into your project in its
Generic layer.

## Credits

[Normalize.css](https://github.com/necolas/normalize.css/) is a project by
[Nicolas Gallagher](http://nicolasgallagher.com/), co-created with [Jonathan Neal](http://jonathantneal.com/).

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
