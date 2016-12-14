# mnml-reset

Because sometimes, even [Normalize](http://github.com/necolas/normalize.css) can seem too much.

````css
* {
    box-sizing: border-box;
}
    *:after,
    *:before {
        box-sizing: inherit;
    }
html,
body {
    margin: 0;
    padding: 0;
    text-rendering: geometricPrecision;
    -webkit-font-smoothing: antialiased;
    -webkit-text-size-adjust: 100%;
        -ms-text-size-adjust: 100%;
}
