# house-party

## Build With Us
This Electrode component example is created by following our [Getting Started](https://electrode-io.github.io/docs/build_component.html): Intermediate Guide. We start with our out-the-box Electrode Component generator and you will learn how to make a dynamic reusable component with a live demo.


## Demo & Examples

To build the examples locally, run:

```
npm install
npm start
```

Then open [`localhost:4000`](http://localhost:4000) in a browser.


## Installation

The easiest way to use house-party is to install it from NPM and include it in your own React build process (using [Browserify](http://browserify.org), [Webpack](http://webpack.github.io/), etc).

You can also use the standalone build by including `dist/house-party.js` in your page. If you use this, make sure you have already included React, and it is available as a global variable.

```
npm install house-party --save
```


## Usage

```
var HouseParty = require('house-party');

<HouseParty>Example</HouseParty>
```


## Development (`src`, `lib` and the build process)

**NOTE:** The source code for the component is in `src`. A transpiled CommonJS version (generated with Babel) is available in `lib` for use with node.js, browserify and webpack. A UMD bundle is also built to `dist`, which can be included without the need for any build system.

To build, watch and serve the examples (which will also watch the component source), run `npm start`. If you just want to watch changes to `src` and rebuild `lib`, run `npm run watch` (this is useful if you are working with `npm link`).

Built with :heart: by [Team Electrode](https://github.com/orgs/electrode-io/people) @WalmartLabs.

## License

Copyright (c) 2016 james-mcintyre.
