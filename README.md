# &lt;letter-spacing&gt;

An inline custom element to provide `letter-spacing` CSS styling to its contents.

## Install

```
bower install letter-spacing
```

## Usage

Import `platform.js` and `polymer.html`

```
<script src="bower_components/platform/platform.js"></script>
<link rel="import" href="bower_components/polymer/polymer.html" />
```

Import `letter-spacing.html`

```
<link rel="import" href="dist/letter-spacing.html" />
```

Starting using it:

```
<letter-spacing value="3px">Text goes here</letter-spacing>
```

## Options

Attribute  | Options                              | Default             | Description
---        | ---                                  | ---                 | ---
`value`   | *String*                             | ``                  | Spacing value i.e. '3px' or '-3px'

## Basic use example

```
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