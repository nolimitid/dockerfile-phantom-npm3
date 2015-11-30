# nolimitid/node-phantom-npm3

Docker image based on [Nodesource's trusty:5.1.0](https://github.com/nodesource/docker-node) image, with PhantomJS, karma, and webpack. mainly used for development and continuous integration with [wercker](http://wercker.com).

## Included packages

|package name                 | version |
|-----------------------------|---------|
|nodejs                       |5.1.0    |
|phantomjs                    |1.9.19   |
|karma-cli (via npm)          |LATEST   |
|gulp-cli (via npm)           |LATEST   |
|mocha                        |LATEST   |
|webpack (via npm)            |LATEST   |

## Installation

`docker pull nolimitid/node-phantom-npm3`
