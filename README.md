# Primary.css

> A Superclean, Minimal, Sass-based CSS Framework.

## Table of Contents

* [Introduction](#Introduction)
* [Installation](#installation)
* [Structure](#structure)
* [Customize Your Build](#customize-your-build)
* [Browser Support](#browser-support)
* [License](#license)

## Introduction

Primary.css provides a robust CSS foundation of HTML typography, forms, and elements that are easy to customise and style.

## Installation

There are several ways of installing the awesome that is primary.css:

### Install manually

Download the compiled and minified [Primary CSS file](https://github.com/amazingSurge/primary-css/releases/). And include `primary.css` located in `/css` in your website or Web app &lt;head&gt; part.

```html
<link rel="stylesheet" href="primary.min.css" />`
```

### Install from CDN

Alternatively, you can use the [unpkg](https://unpkg.com/) CDN to load compiled primary.css.

```html
<link rel="stylesheet" href="https://unpkg.com/primary.css@1.0.0/css/primary.min.css" crossorigin="anonymous">
```

### Install with NPM

Install primary.css for your Node powered apps with the [npm package](https://www.npmjs.com/package/primary.css):

```bash
npm install primary.css
```

### Install with Yarn

Install primary.css with [yarn](https://github.com/yarnpkg/yarn):

```bash
yarn add primary.css
```

### GitHub

Clone the repo from GitHub download the source CSS, and documentation files.

```bash
git clone https://github.com/amazingSurge/primary-css.git
```

## Structure

The file tree for the install looks like this:

```
├───dist                    // Dist files (git ignored)
│   ├───primary.css
│   └───primary.min.css
├───docs                    // Documentation
│   ├───index.html
│   └─── ...
├───scss                    // Scss source files
│   ├───base/
│   ├───elements/
│   ├───utilities/
│   └───primary.css
├───README.md
├───config.js
├───gulpfile.babel.js
├───Gemfile
└───package.json
```

## Customize Your Build

You can customize your version of primary.css by editing SASS files in `/scss` directory or removing unneeded components from `.scss` source files.

Just follow the following steps:

1.  Make sure you have the following tools installed: [node](https://nodejs.org/download/), [bundler](http://bundler.io/), [babel](https://babeljs.io/docs/usage/cli/#installation), [gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#install-the-gulp-command), [sass](http://sass-lang.com/install).

2.  Clone the project:

        git clone https://github.com/amazingSurge/primary-css.git

3.  Install the dependencies:

        bundler install
        npm install

When completed, you’ll be able to run the various commands provided from the command line.

### Gulp commands

Task name            | Description                                                      
:--------------------|:----------------------------------
`gulp default`       | compiles everything just once.
`gulp build`         | alias to `gulp styles`.
`gulp styles`        | compile all scss from `scss` to `dist` folder. 
`gulp beautify`      | beautify your source files in `scss` folder.
`gulp watch`         | watchs for changes in `scss` folder and rebuilds parts of the site as necessary.
`gulp version:major` | MAJOR version when you make incompatible API changes
`gulp version:minor` | MINOR version when you add functionality in a backwards-compatible manner
`gulp version:patch` | PATCH version when you make backwards-compatible bug fixes.
`gulp version`       | alias to `version:path`.

## Browser Support

Primary.css uses [Autoprefixer](https://github.com/postcss/autoprefixer) to make most styles compatible with earlier browsers. Primary.css is designed for modern browsers. For best compatibility, these browsers are recommended:

- Chrome (last 4)
- Microsoft Edge (last 4)
- Firefox (last 4)
- Safari (last 4)
- Opera (last 4)
- Internet Explorer 10+

## License

The code is available under the [MIT](https://github.com/amazingSurge/primary-css/blob/master/LICENSE) license.
