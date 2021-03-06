# Ceylon.design

**One place for service teams to find styles, components and patterns for
designing government services.**

## Run locally

You'll need [Git](https://help.github.com/articles/set-up-git/) and [Node.js](https://nodejs.org/en/) installed to get this project running.

Note: You will need the [active LTS (Long-term support)](https://github.com/nodejs/Release#release-schedule) Node.js version for this project (as specified in [.nvmrc](./.nvmrc))

### Fork repository (optional)
If you're an external contributor make sure to [fork this project first](https://help.github.com/articles/fork-a-repo/)

### Clone repository

git clone git@github.com:Ceylon-Design/Ceylon.design.git # or clone your own fork

cd Ceylon-Design-Ceylon.design

### Using nvm (optional)
If you work across multiple Node.js projects there's a good chance they require different Node.js and npm versions.

To enable this we use [nvm (Node Version Manager)](https://github.com/creationix/nvm) to switch between versions easily.

1. [install nvm](https://github.com/creationix/nvm#installation)
2. Run `nvm install` in the project directory (this will use [.nvmrc](./.nvmrc))

### Install npm dependencies
```
npm install
```

### Start a local server
This will build sources, serve pages and watch for changes.
```
npm start
```

## Build
Build `./src` to `./deploy/public`
```
npm run build
```

## Run the Sass linter

We are using the [sass-lint][sass-lint] plugin to lint the Sass files in
`source/stylesheets`. You can run the linter from command line by running:

```
npm run lint
```

[sass-lint]: https://github.com/juanfran/gulp-scss-lint

## Ceylon.design Frontend packages

Design System consumes the [Ceylon.Design Frontend](https://github.com/Ceylon-Design/CeylonD-Frontend) package via [NPM](https://www.npmjs.com/).
This is defined in the [package.json](package.json) file.


