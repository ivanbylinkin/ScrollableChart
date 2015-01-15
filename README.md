# ScrollableChart
Plugin for Chart.js that allows you create a scrollable Bar/Line chart.
This is a very simple plugin written in jQuery and is available under the [MIT license].

## Basic Usage ##

Setup HTML for a chart (refer to Chart.js documentation for more details: http://www.chartjs.org/docs/ )

*you must add a next and previous button somewhere that will connect to the chart.
NOTE: the next and previous buttons must have a data-shift attribute denoting whether it is "next" or "prev"

Ex.
```html
	<div data-shift="prev">
		<span>Left</span>
	</div>
	<div>
		<canvas id="canvas"></canvas>
	</div>
	<div data-shift="next">
		<span>Right</span>
	</div>
```
Once you have the basic HTML setup initialization is pretty simple.
You need to pass an object to the plugin with the following possible values:
data: an array of data for the chart, this is the dataset data passed to Chart.js
labels: an array of equal length to the data to label the data, this is the 

// HALTED UNTIL ADJUSTMENT IS MADE TO THE PLUGIN TO SUPPORT MULTIPLE DATASETS
