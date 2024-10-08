# Hugo Starter Site

This is my favorite way to code static websites. It's a Hugo site with the following front-end technologies built in.

### CUBE CSS

I copied much of the inspiring [cube-boilerplate](https://github.com/Set-Creative-Studio/cube-boilerplate/tree/main) into this Hugo enviroment.

### Hotwired Turbo

I use [@hotwired/turbo](https://github.com/hotwired/turbo) to speed everything up for free.

## Installation

```sh

git clone https://github.com/jameskerr/hugo-starter

mv hugo-starter my-cool-site # rename to something you want

cd my-cool-site

yarn

hugo server
```

## CSS Instructions

Add your own CSS files anywhere in these directories to have them automatically included.

- `assets/css/variables/`
- `assets/css/global/`
- `assets/css/compositions/`
- `assets/css/blocks/`
- `assets/css/utilities/`

Take a look at `assets/css/main.css` for how it all is stitched together. Also visit the docs for [CUBE CSS](https://cube.fyi/) and [Utopia](https://utopia.fyi/).

## JS Instructions

Add your JavaScript files to `assets/js`, then import then into `assets/js/main.js`. These will get build using Hugo's [js.Build pipe](https://gohugo.io/hugo-pipes/js/).

Enjoy!

Authored by [James Kerr](http://jameskerr.blog)
