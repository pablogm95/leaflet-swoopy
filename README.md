# :arrow_heading_down: Leaflet Swoopy Arrow Plugin

You can find the docs on the plugin [website](https://wbkd.github.io/leaflet-swoopy/).

![swoopy screenshot](https://raw.githubusercontent.com/wbkd/leaflet-swoopy/master/docs/leaflet-swoopy-screenshot.png)


## Installation

You need [Leaflet](http://leafletjs.com/) in order to run this plugin.

Install with npm/yarn:
```shell
$ npm install leaflet-swoopy
```

Or download the minified library from [unpkg](https://unpkg.com/leaflet-swoopy/build/Leaflet.SwoopyArrow.min.js) or [jsDelivr](https://cdn.jsdelivr.net/npm/leaflet-swoopy).
```html
<script src="https://unpkg.com/leaflet-swoopy"></script>
```

## Usage

```javascript
import L from 'leaflet';
import 'leaflet-swoopy';

// create leaflet map ...

const swoopy = L.swoopyArrow([53.52, 13.4], [53.525, 14.41], {
  label: 'Hi!',
  labelFontSize: 12,
  iconAnchor: [20, 10],
  iconSize: [20, 16]
}).addTo(map);
```
