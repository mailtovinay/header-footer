
# header-footer
* header-footer provides the following features:
* Displays header and footer with the type attribute.

## Dependencies
```js
"dependencies": {
"polymer": "^2.0.2"
} 

```

## Installation

The element can be installed using bower

```js 

bower install  header-footer --save

```

### Importing component into page/component: 
```html
<link rel="import" href="./bower_components/header-footer/header-footer.html" />

```
### Usage

```html

<header-footer></header-footer>

```

### Attributes

```html
Adding 'type' header/footer to component  will enbale header and footer respectively.
ex. <header-footer type="header"></header-footer>

Adding 'logo' to component  will enbale logo.
ex. <header-footer logo="header.png"></header-footer>

Adding 'tagline' to component  will enbale tagline.
ex. <header-footer tagline="Tagline"></header-footer>

Adding 'tagline' to component  will enbale tagline.
ex. <header-footer tagline="Tagline"></header-footer>

Adding 'menu' to component  will enbale menu Items i.e buttons/link.
ex. <header-footer menu="{{menuItems}}"></header-footer>
menuItems is a Array of Objects

Adding 'copyright' to component  will enbale copyrights.
ex. <header-footer copyright="My Copyrights"></header-footer>

```

### sample menuItems data
Adding data inside 'menu' attribute

```html
<header-footer menu="{{menuItems}}"></header-footer>

```

```js

static get properties () {
return {
menuItems: {
type: Array,
value: [{"name" : "My Account"},{"name" : "My Transcations"},{"name" : "Logout"}],
}
}
}

``` 
