# [Vegeta](https://github.com/kreativ-anders/vegeta)

Vegeta is a **crazy CSS framework** based on [Bulma](https://bulma.io).
The only difference is that Vegeta is using [CSS variables](https://caniuse.com/#feat=css-variables)!!!

<a href="https://github.com/kreativ-anders/vegeta"><img src="https://raw.githubusercontent.com/kreativ-anders/vegeta/master/vegeta-banner.png" alt="Vegeta: a Flexbox CSS framework" style="max-width:100%;" width="600" height="315"></a>

## Try it out now

Vegeta is not constantly in development! 

### [Prepros](https://prepros.io/)

**and**

### [VS Code](https://code.visualstudio.com/)


### Import
After Download, you can import the CSS file into your project using this snippet:

```html
<link rel="stylesheet" type="text/css" href="vegeta.css">
```

## CSS only

Vegeta is a **CSS** framework. As such, the sole output is a single CSS file: [vegeta.css](https://github.com/kreativ-anders/vegeta/blob/master/vegeta.css)

You can either use that file, "out of the box", or download the Sass source files to customize the [variables](https://bulma.io/documentation/overview/variables/).

*SPOILER: You can customize vegeta directly within the css!*

There is **no** JavaScript included. People generally want to use their own JS implementation (and usually already have one). Vegeta can be considered "environment agnostic": it's just the style layer on top of the logic.

## Browser Support

Vegeta uses [autoprefixer](https://github.com/postcss/autoprefixer) to make (most) Flexbox features compatible with earlier browser versions. According to [Can I use](https://caniuse.com/#feat=flexbox), Vegeta is compatible with **recent** versions of:

* Chrome
* Edge
* Firefox
* Opera
* Safari

Internet Explorer is not even partially supported. 

## Warning

There was no proper testing yet!