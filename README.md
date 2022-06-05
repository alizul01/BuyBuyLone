# buybuylone

# Webpack-Starter
Webpack is a bundler for javascript and others. We can packs many modules into a few bundled assets. Code Splitting allows for loading parts of the application on demand. Through "loaders", modules can be bundle.js 

<div align="center">
  <a href="https://github.com/webpack/webpack">
    <img width="200" height="200" src="https://webpack.js.org/assets/icon-square-big.svg">
  </a>
  <br>
  <br>

[![npm][npm]][npm-url]

[![node][node]][node-url]
[![deps][deps]][deps-url]
[![builds2][builds2]][builds2-url]
[![coverage][cover]][cover-url]
[![licenses][licenses]][licenses-url]
[![PR's welcome][prs]][prs-url]

  <br>
  <a href="https://dependabot.com/compatibility-score.html?dependency-name=webpack&package-manager=npm_and_yarn&new-version=latest">
    <img src="https://api.dependabot.com/badges/compatibility_score?dependency-name=webpack&package-manager=npm_and_yarn&version-scheme=semver&target-version=latest">
  </a>
	<a href="https://npmcharts.com/compare/webpack?minimal=true">
		<img src="https://img.shields.io/npm/dm/webpack.svg">
	</a>
	<a href="https://packagephobia.com/result?p=webpack">
		<img src="https://packagephobia.com/badge?p=webpack" alt="install size">
	</a>
	<a href="https://opencollective.com/webpack#backer">
		<img src="https://opencollective.com/webpack/backers/badge.svg">
	</a>
	<a href="https://opencollective.com/webpack#sponsors">
		<img src="https://opencollective.com/webpack/sponsors/badge.svg">
	</a>
	<a href="https://github.com/webpack/webpack/graphs/contributors">
		<img src="https://img.shields.io/github/contributors/webpack/webpack.svg">
	</a>
	<a href="https://gitter.im/webpack/webpack">
		<img src="https://badges.gitter.im/webpack/webpack.svg">
	</a>
</div>

[common-npm]: https://img.shields.io/npm/v/webpack.svg
[mini-css]: https://github.com/webpack-contrib/mini-css-extract-plugin
[mini-css-npm]: https://img.shields.io/npm/v/mini-css-extract-plugin.svg
[mini-css-size]: https://packagephobia.com/badge?p=mini-css-extract-plugin
[component]: https://github.com/webpack-contrib/component-webpack-plugin
[component-npm]: https://img.shields.io/npm/v/component-webpack-plugin.svg
[component-size]: https://packagephobia.com/badge?p=component-webpack-plugin
[compression]: https://github.com/webpack-contrib/compression-webpack-plugin
[compression-npm]: https://img.shields.io/npm/v/compression-webpack-plugin.svg
[compression-size]: https://packagephobia.com/badge?p=compression-webpack-plugin
[html-plugin]: https://github.com/jantimon/html-webpack-plugin
[html-plugin-npm]: https://img.shields.io/npm/v/html-webpack-plugin.svg
[html-plugin-size]: https://packagephobia.com/badge?p=html-webpack-plugin

[npm]: https://img.shields.io/npm/v/webpack.svg
[npm-url]: https://npmjs.com/package/webpack
[node]: https://img.shields.io/node/v/webpack.svg
[node-url]: https://nodejs.org
[deps]: https://img.shields.io/david/webpack/webpack.svg
[deps-url]: https://david-dm.org/webpack/webpack
[prs]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
[prs-url]: https://webpack.js.org/contribute/
[builds2]: https://dev.azure.com/webpack/webpack/_apis/build/status/webpack.webpack
[builds2-url]: https://dev.azure.com/webpack/webpack/_build/latest?definitionId=3
[licenses-url]: https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fwebpack%2Fwebpack?ref=badge_shield
[licenses]: https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fwebpack%2Fwebpack.svg?type=shield
[cover]: https://img.shields.io/coveralls/webpack/webpack.svg
[cover-url]: https://coveralls.io/r/webpack/webpack/

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)

## About <a name = "about"></a>

🏪 buybuylone is a simple e commerce platform for buying and selling technology products. You can get so many recommendation to improve your buying quality

## Getting Started <a name = "getting_started"></a>

Here is how to get started with buybuylone project:

### Prerequisites

```bash
npm install
```

### Development

Here is how to get started developing the project.

#### Javascript
1) Go to src
2) Make the javascript files
3) Go to the index.js, then import the modules you've make
4) Run npm run build:bundle to make the bundle.js

Example if you want to make navbar
```js
export default function bar() {
    const navbar = document.querySelector('#navbar');
    navbar.innerHTML = `<div> Hello World </div>`

    return navbar;
}
```

After you make the bar, go to the index.js

```js
import bar from './navbar.js';

bar();
```

Last, go to the terminal / bash
```bash
npm run build:bundle
```

#### Tailwindcss
1) Go to the bash and run this
```bash
npm run build:css
```
2) Go to the index.html than add the class
3) ctrl + s to save the file and reload the class from tailwindcss

## Usage <a name = "usage"></a>

Add notes about how to use the system.