# Development envoirment
All files in the `octoprint_filamentmanager/static/js` directory will be build with [Gulp](https://gulpjs.com/), from the source in `static/js`, and not modified directly. The build process includes:
- static code analysis with [ESLint](https://eslint.org/)
- transcompiling to ES5 with [Babel](https://babeljs.io/)
- concatinating all files into one file `filamentmanager.bundled.js`


## Prerequisites
0. Install [NodeJS](http://www.nodejs.org/) and [NPM](https://www.npmjs.com/) with your package manager

0. Install development dependencies with `npm install`


## Build
0. Check the source code with `npx gulp lint`

0. Start the build process with `npx gulp build`