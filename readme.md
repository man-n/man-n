# man-n
View npm package READMEs with `man(1)`.

![screenshot of man-n showing the browserify docs](screenshot.png)

## Installation
```sh
$ npm install -g man-n
```

## Usage
```sh
$ man-n -h
  Usage: man-n [options] <package>

  Options:

    -h, --help  output usage information
    -l, --link  default to man(1)

  Examples:

    $ man-n browserify          # show browserify docs
```

## Aliasing

Tired of typing that dash, or even that `n`? Add the following to your
`.bashrc`, `.bash_profile`, or `.zshrc`

```sh
# Link `man-n` to `man`
$ alias "man=man-n --link"
```

...and from now on, you can just type `man browserify` to access package
documentation. However, **man**(1) will prefer normal man pages, so when you
wan’t to get the readme of **which**(n), use `man n which` instead of
`man which`.

## Development

Several useful commands

* See current open issues on GitHub `npm run isses`
* Commit current changes with commit message wizard `npm run commit`
* Remove fuzzy dependency versions `npm run exact`

## License
[MIT](https://tldrlegal.com/license/mit-license)
