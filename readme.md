# imagemin-cli

> Minify images

*Issues with the output should be reported on the `imagemin` [issue tracker](https://github.com/imagemin/imagemin/issues).*


## Install

```
$ npm install --global imagemin-clif
```


## Usage

```
$ imagemin --help

  Usage
    $ imagemin <path|glob> ... --out-dir=build [--plugin=<name> ...]
    $ imagemin <file> > <output>
    $ cat <file> | imagemin > <output>

  Options
    -p, --plugin   Override the default plugins
    -o, --out-dir  Output directory

  Examples
    $ imagemin images/* --out-dir=build
    $ imagemin foo.png > foo-optimized.png
    $ cat foo.png | imagemin > foo-optimized.png
    $ imagemin --plugin=pngquant foo.png > foo-optimized.png
    $ imagemin --overwrite foo.png
    $ imagemin --overwrite fixtures/*
    $ find fixtures/ -name 'test.*' |xargs imagemin --overwrite
```


## Related

- [imagemin](https://github.com/imagemin/imagemin) - API for this module


## License

MIT © [imagemin](https://github.com/imagemin)
