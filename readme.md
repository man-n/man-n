# man-n
View npm package READMEs with `man(1)`.

![screenshot of man-n showing the browserify docs](screenshot.png)

## Installation
```sh
$ npm install -g man-n
```

## Usage
```sh
$ man-n <package>
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
