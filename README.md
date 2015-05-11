# Vertical Line plugin for Chartist.js

[![Build Status](https://travis-ci.org/zubenkoivan/chartist-plugin-vertical-line.svg?branch=master)](https://travis-ci.org/zubenkoivan/chartist-plugin-vertical-line)

This is a simple plugin for Chartist.js that will add vertical line with optional label in a line chart.

Please visit http://gionkunz.github.io/chartist-js/plugins.html for more information.

## Available options and their defaults

```javascript
var defaultOptions = {
  position: undefined,
  label: undefined,
  className: 'vertical-line'
};
```

## Sample usage in Chartist.js

```javascript
var chart = new Chartist.Line('.ct-chart', {
  labels: ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday'],
  series: [
    [12, 9, 7, 8, 5],
    [2, 1, 3.5, 7, 3],
    [1, 3, 4, 5, 6]
  ]
}, {
  plugins: [
    Chartist.plugins.verticalLine({
      position: 'Tuesday'
    })
  ]
});
```
