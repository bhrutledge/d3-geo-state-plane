# d3.geo.statePlanes

All state planes projections for D3

[Live demo](http://bl.ocks.org/gka/f2aabf4a516e16a5190f25fd1923406f)

```js
var proj = d3.geo.statePlanes('NY');
```

By default, the projection will be scaled and translated to fit the state into a 1000px * 600px rect, but you can easily scale for a different output size by passing width and height as additional parameters:

```js
// center NY into a 500px * 350px viewport
var proj = d3.geo.statePlanes('NY', 500, 350);
```
