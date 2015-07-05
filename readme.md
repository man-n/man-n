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
    -l, --link  link `man-n` to `man n`

  Examples:

    $ man-n browserify  # show the browserify documentation
    $ man-n --link      # link `man-n` to `man n`
    $ man n browserify  # show the browserify documentation
```

## Aliasing

Tired of typing that dash? Add the following to your `.bashrc`,
`.bash_profile`, or `.zshrc`

```sh
# Link `man-n` to `man n`
eval $(man-n --link)
```

...and from now on, you can just type `man n` to access package
documentation.

## License
[MIT](https://tldrlegal.com/license/mit-license)
