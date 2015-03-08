# &lt;plastic-paragraph&gt;

> A Polymer element to put any paragraph of text inside a shape you choose (Experimental)

![alt tag](http://hejty.github.io/demos/plastic-paragraph/preview.png)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install plastic-paragraph --save
```

Or [download as ZIP](https://github.com/hejty/plastic-paragraph/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/webcomponentsjs/0.5.2/webcomponents.min.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="plastic-paragraph/plastic-paragraph.html">
```

3. Start using it!

```html
<p is="plastic-paragraph"></p>
```

## Options

Attribute       | Options                                                       | Default                      | Description
---             | ---                                                           | ---                          | ---
`shape`         | `circle`, `rhomb`, `diagonal`, `sandglass`                    | `circle`                     | The `shape` attribute sets a wrapping shape
`size`          | *int*                                                         | `320`                        | The `size` attribute sets a size of an element

## Example

```html
<p is="plastic-paragraph" shape="circle" size="600">Web Components usher in a new era of web development based on encapsulated and interoperable custom elements that extend HTML itself. Built atop these new standards, Polymer makes it easier and faster to create anything from a button to a complete application across desktop, mobile, and beyond.</p>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request ;)

## History

For detailed changelog, check [Releases](https://github.com/hejty/plastic-paragraph/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
