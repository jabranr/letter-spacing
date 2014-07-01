# &lt;letter-spacing&gt;

An inline custom element to provide `letter-spacing` CSS styling to its contents.

## Install

``` shell
$ bower install letter-spacing
```

## Usage

Import `platform.js`, `polymer.js` and `letter-spacing.html` into HTML document.

``` html

// Get Polymer
<script src="//www.polymer-project.org/platform.min.js"></script>
<script src="//www.polymer-project.org/polymer.min.js"></script>

// Import letter-spacing element
<link rel="import" href="dist/letter-spacing.html" />

```

Starting using it:

``` html
<letter-spacing value="3px">Text goes here</letter-spacing>
```


## Demo

[See live demo](http://www.jabran.me/letter-spacing/)


## Options

Attribute  | Options                              | Default             | Description
---        | ---                                  | ---                 | ---
`value`   | *String*                             | ``                  | Spacing value i.e. '3px' or '-3px'

## Basic use example

``` html
<letter-spacing value="3px">This text is spaced with letter-spacing custom element.</letter-spacing>
```

Results in above text spaced by given value.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin new-feature`
5. Submit a pull request

## License

[MIT License](http://opensource.org/licenses/MIT)