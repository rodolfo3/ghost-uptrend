# Ghost Uptrend

Fork this project on [GitHub](https://github.com/sleonte/ghost-uptrend).
See a [live example](http://stefanleonte.com).

Ghost Uptrend is a fork of [Jekyll Uptrend](https://github.com/baus/jekyll-uptrend) theme, made for Ghost.

It uses Bootstrap and FontAwesome as submodules. If you don't know what that is, don't bother about it.

## Installation

1. Copy the contents of the .zip file into `/content/themes/`.
2. Restart your Ghost instance.
3. From the Ghost admin select ghost-uptrend as your theme.

**NOTE** - This theme is intended for my personal usage. Please make sure you read the `Usage` section.

## Usage

The theme uses your blog logo for the header image. Make sure it big enough or it will look nasty.

Make sure you edit all the social links - there are present in `header.hbs` and `footer.hbs` in the `partials` folder. To add new, just follow the existing template and [FontAwesome](http://fontawesome.io/examples/).

If you'd like to fiddle with the styles, play around with `/content/themes/ghost-uptrend/assets/css/up.less` and then compile the CSS. This will require a Ghost restart.

Disqus comments are integrated. Open post.hbs and edit `var disqus_shortname` with your shortname.

Syntax highlighting is done via [highlightjs](http://highlightjs.org/). You can change the colours by editing `<link rel="stylesheet" href="http://yandex.st/highlightjs/7.5/styles/tomorrow.min.css">` from `default.hbs` into something else ([see this](http://highlightjs.org/static/test.html)).

## Issues

Please open any issues you have with the theme [here](https://github.com/sleonte/ghost-uptrend/issues).