# &lt;is-mobile&gt;

Custom web component element to detect mobile browser, based on script [here](http://detectmobilebrowsers.com/).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install is-mobile --save
```

Or [download as ZIP](https://github.com/nopjia/is-mobile/archive/master.zip).

## Usage

1. Import Web Components polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

1. Import the element:

    ```html
    <link rel="import" href="bower_components/is-mobile/is-mobile.html">
    ```

1. Use the element:

    ```html
    <is-mobile></is-mobile>
    ```

## Attribute

`mobile` - boolean - indicates whether mobile browser is detected.
The attribute is set only once on the creation of the element.
It should not be set or overwritten, otherwise the value will be lost.

For example, this is how the element will appear on mobile browser:

```html
<is-mobile mobile="true"></is-mobile>
```
Also, `document.querySelector("is-mobile").mobile` will return boolean `true`.

## License

[MIT License](http://opensource.org/licenses/MIT)
