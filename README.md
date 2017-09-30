[nodeGame'](https://www.nodegame.org) command line interface (cli).

[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][downloads-url]
[![Linux Build][travis-image]][travis-url]

## Installation

```sh
$ npm install -g nodegame-cli
```

## Commands

The executable `nodegame(1)` exposes the following commands:


### create-game

Creates a new game folder:

```bash
$ nodegame create-game /tmp/mygame myname myemail@com
```

### update-conf

Update configuration file:

```bash
$ nodegame update-conf
```

### list

todo

### checkout

todo

### enable

todo

### disable

todo

### Other Command Line Options

This generator can also be further configured with the following command line flags.

    -h, --help          output usage information
    -V, --version       output the version number
        --git           add .gitignore
    -f, --force         force on non-empty directory

## Kudos

Initially Based on a fork of [Express
Generator](https://github.com/expressjs/generator).

## License

[MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/nodegame-cli.svg
[npm-url]: https://npmjs.org/package/nodegame-cli
[travis-image]: https://img.shields.io/travis/nodegamejs/cli/master.svg
[travis-url]: https://travis-ci.org/nodegamejs/cli
[downloads-image]: https://img.shields.io/npm/dm/nodegame-cli.svg
[downloads-url]: https://npmjs.org/package/nodegame-cli
