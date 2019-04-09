# egjs-infinitegrid [![npm version](https://badge.fury.io/js/%40egjs%2Finfinitegrid.svg)](https://badge.fury.io/js/%40egjs%2Finfinitegrid) [![Build Status](https://travis-ci.org/naver/egjs-infinitegrid.svg?branch=master)](https://travis-ci.org/naver/egjs-infinitegrid) [![Coverage Status](https://coveralls.io/repos/github/naver/egjs-infinitegrid/badge.svg?branch=master)](https://coveralls.io/github/naver/egjs-infinitegrid?branch=master)

A module used to arrange card elements including content **infinitely** according to layout type. With this module, you can implement **various layouts** composed of different card elements whose sizes vary. It guarantees **performance** by maintaining the number of DOMs the module is handling under any circumstance

![infinitegrid](https://github.com/naver/egjs-infinitegrid/raw/master/demo/assets/image/infinitegrid.gif)

## Layouts
The InfiniteGrid can use various layouts.

![layout](https://github.com/naver/egjs-infinitegrid/raw/master/demo/assets/image/layout.gif)

- [GridLayout](https://naver.github.io/egjs-infinitegrid/#GridLayout): The GridLayout is a layout that stacks cards with the same width as a stack of bricks.
- [JustifiedLayout](https://naver.github.io/egjs-infinitegrid/#JustifiedLayout): JustifiedLayout is a layout that the card is filled up on the basis of a line given a size.
- [FrameLayout](https://naver.github.io/egjs-infinitegrid/#FrameLayout): FrameLayout is a layout that allows you to place cards in a given frame.
- [SquareLayout](https://naver.github.io/egjs-infinitegrid/#SquareLayout): SquareLayout is a layout that places all cards like squares on a checkerboard, and important cards are n times larger.
- [PackingLayout](https://naver.github.io/egjs-infinitegrid/#PackingLayout): The PackingLayout is a layout that shows the important cards bigger without sacrificing the weight of the cards.

## Benchmark
[![eg.infiniteGrid benchmark](https://img.youtube.com/vi/6Kv-NV0dZXw/0.jpg)](http://www.youtube.com/watch?v=6Kv-NV0dZXw)

eg.infiniteGrid benchmark: append item performance with [masonry](https://masonry.desandro.com/)


## Documents
- [Get Started and Demos](https://naver.github.io/egjs-infinitegrid/)
- [InfiniteGrid Options](https://github.com/naver/egjs-infinitegrid/wiki/InfiniteGrid-Options)
- [API documentation](https://naver.github.io/egjs-infinitegrid/release/latest/doc/)
- [Migrating from v2.0 to v3.0](https://github.com/naver/egjs-infinitegrid/wiki/Migrating-from-v2.0-to-v3.0)
- Articles
  - [Introducing eg.InfiniteGrid, a new library for implementing a card layout](https://github.com/naver/egjs-infinitegrid/wiki/Introducing-eg.InfiniteGrid,-a-new-library-for-implementing-a-card-layout) [[Korean](http://d2.naver.com/helloworld/4874130)]
  - [Card-based design and eg.InfiniteGrid 3.0](https://medium.com/@sculove/card-based-design-and-eg-infinitegrid-3-0-a84616496671) [[Korean](http://d2.naver.com/helloworld/0637045)]

## Third party applications
[@egjs/react-layout](https://github.com/naver/egjs-infinitegrid/tree/master/packages/react-layout): A react component that can easily use egjs-infinitegrid's layouts

[@egjs/react-infinitegrid](https://github.com/naver/egjs-infinitegrid/tree/master/packages/react-infinitegrid): A react component that can easily use egjs-infinitegrid


## Download and Installation

Download dist files from repo directly or install it via npm. 

### Packaged version
> Packaged version is not an official distribution.
> Is just to provide for ease use of 'egjs-infinitegrid'.

- **latest version**

|| Uncompressed | Compressed |
|---|----|---|
|No Dependency<br/>([@egjs/component](https://github.com/naver/egjs-component))| [infinitegrid.js (170.1kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.js)| [infinitegrid.min.js (46.2kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.min.js)|
|All| [infinitegrid.pkgd.js (179.9kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.pkgd.js) | [infinitegrid.pkgd.min.js (47.7kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.pkgd.min.js)|(https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.min.js)
|GridLayout| [infinitegrid.gridlayout.js (128.4kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.gridlayout.js) | [infinitegrid.gridlayout.min.js (37.1kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.gridlayout.min.js) |
|JustifiedLayout| [infinitegrid.justifiedlayout.js (136.2kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.justifiedlayout.js) | [infinitegrid.justifiedlayout.min.js (38.4kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.justifiedlayout.min.js)|
|FrameLayout| [infinitegrid.framelayout.js (131.5kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.framelayout.js) | [infinitegrid.framelayout.min.js (37.8kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.framelayout.min.js) |
|SquareLayout| [infinitegrid.squarelayout.js (137.9kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.squarelayout.js) | [infinitegrid.squarelayout.min.js (39.2kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.squarelayout.min.js) |
|PackingLayout| [infinitegrid.packinglayout.js (130.9kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.packinglayout.js) | [infinitegrid.packinglayout.min.js (38kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/infinitegrid.packinglayout.min.js) |
|Parallax| [parallax.js (13.3kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/parallax.js) |[parallax.min.js (4kb)](https://naver.github.io/egjs-infinitegrid/release/latest/dist/parallax.min.js)|

- **Specific version**
    * https://naver.github.io/egjs-infinitegrid/release/[VERSION]/dist/[FILE_NAME]


### Installation with npm

The following command shows how to install egjs-infinitegrid using npm.

```bash
$ npm install @egjs/infinitegrid
```

The following code shows how to import InfiniteGrid, Parallax.

```js
import InfiniteGrid, {GridLayout, JustifiedLayout, ...} from "@egjs/infinitegrid";
import Parallax from "@egjs/infinitegrid/dist/parallax";
```

## Supported Browsers
The following are the supported browsers.

|Internet Explorer|Chrome|Firefox|Safari|iOS|Android|
|---|---|---|---|---|---|
|8+|Latest|Latest|Latest|7+|2.3+(except 3.x)|

* If you want to use in IE8, please use polyfill.

## Dependency

egjs-infinitegrid has the dependencies for the following libraries:

|[egjs-component](https://github.com/naver/egjs-component)|
|----|
|2.0.0+|


## How to start developing egjs-infinitegrid?

For anyone interested to develop egjs-infinitegrid, follow the instructions below.

### Development Environment

#### 1. Clone the repository

Clone the egjs-infinitegrid repository and install the dependency modules.

```bash
# Clone the repository.
$ git clone https://github.com/naver/egjs-infinitegrid.git
```

#### 2. Install dependencies
`npm` is supported.

```
# Install the dependency modules.
$ npm install
```

#### 3. Build

Use npm script to build egjs-infinitegrid

```bash
# Run webpack-dev-server for development
$ npm start

# Build
$ npm run build

# Generate jsdoc
$ npm run jsdoc
```

Two folders will be created after complete build is completed.

- **dist** folder: Includes the **infinitegrid.js** and **infinitegrid.min.js** files.
- **doc** folder: Includes API documentation. The home page for the documentation is **doc/index.html**.

### Linting

To keep the same code style, we adopted [ESLint](http://eslint.org/) to maintain our code quality. The [rules](https://github.com/naver/eslint-config-naver/tree/master/rules) are modified version based on [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).
Setup your editor for check or run below command for linting.

```bash
$ npm run lint
```

### Test

Once you created a branch and done with development, you must perform a test running `npm run test` command before you push code to a remote repository.

```bash
$ npm run test
```
Running a `npm run test` command will start [Mocha](https://mochajs.org/) tests via [Karma-runner](https://karma-runner.github.io/).


## Bug Report

If you find a bug, please report it to us using the [Issues](https://github.com/naver/egjs-infinitegrid/issues) page on GitHub.


## License
egjs-infinitegrid is released under the [MIT license](https://raw.githubusercontent.com/naver/egjs/master/LICENSE.txt).


```
Copyright (c) 2015 NAVER Corp.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
