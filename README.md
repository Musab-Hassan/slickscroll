<h1 align="center">
    <img src="/assets/Logo.png"/>
</h1>

Slickscroll is a JavaScript library that makes momentum & parallax scrolling quick and painless

**View Demo: [slickscroll.musabhassan.com](https://slickscroll.musabhassan.com)**

<blockquote>
<strong><i>Momentum Scrolling</i></strong><br>
Momentum Scrolling is the smooth and eased scrolling fancy websites have to allow the page to flow smoothly when scrolling.
</blockquote><br>


## Download & Setup

### Download
Manually download from *Releases*, from the `dist` directory, or npm.

npm
```
npm install --save slickscrolljs
```

### Setup

ES6 import
```javascript
import slickScroll from 'slickscroll.es.min.js';
```

HTML script tag
```html
<script src="slickscroll.min.js"></script>
```

Node require
```javascript
const slickScroll = require('slickscrolljs');
```

## Hello World
The hello world will apply the momentum scrolling to the element you specify.
```javascript
slickScroll.momentumScroll({
    root: "body"
})
```
The overflow property will be overridden with `auto` upon initialization. If you wish to change overflow to anything else, you must modify it after the initialization. Here is an example to hide overflow-x.

```javascript
slickScroll.momentumScroll({
    root: "body"
});

document.querySelector("body").style.overflowX = "hidden";
```

All the valid options aswell as documentation and Getting Started can be found in the `docs` directory.

## Browser Support

Browser | Version
| - | - |
Chrome | 61+
Edge | 80+
IE | None
Firefox | 48+
Opera | 48+
Safari | 13+

### License
MIT license.
Copyright (2021) Musab Hassan
