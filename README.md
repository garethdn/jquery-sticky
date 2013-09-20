# jQuery Sticky Plugin

A jQuery plugin to easily add functionality to fix elements to the top of the page on scroll.

### Installation

Include script after the jQuery library:

```html
<script type="text/javascript" src="/path/to/jquery-sticky.js"></script>
```

### Usage

```js
$('.menu').sticky( options )
```

### Options

#### stickyClass (string)

An optional class to be added to the element.

```js
stickyClass: 'sticky'
```

#### anchorClass (string)

An optional class to be added to the generated anchor.

```js
anchorClass: 'sticky-anchor'
```

#### activeClass (string)

Set the class that will be added to the element when it is fixed to the top of the page.

```js
activeClass: 'active'
```

### TODO

* If the height of the sticky element is changed (for example when active) the anchor retains the original height

## License

MIT License
(c) [Bruno Tarmann](http://tarmann.com.br) & [Gareth Nolan](http://ie.linkedin.com/in/garethnolan/)