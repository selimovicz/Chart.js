# Integration

Chart.js can be integrated with plain JavaScript or with different module loaders. The examples below show how to load Chart.js in different systems.

## ES6 Modules

```javascript
import Chart from 'path/to/Chartjs/src/chart.js'
var myChart = new Chart(ctx, {...})
```

## Script Tag

```html
<script src="path/to/Chartjs/dist/Chart.js"></script>
<script>
var myChart = new Chart(ctx, {...})
</script>
```

## Common JS

```javascript
var Chart = require('path/to/Chartjs/src/chart.js')
var myChart = new Chart(ctx, {...})
```

## Require JS

```javascript
require(['path/to/Chartjs/src/chartjs.js'], function(Chart){
    var myChart = new Chart(ctx, {...})
})
```