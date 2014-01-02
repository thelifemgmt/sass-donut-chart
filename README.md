Sass Donut Chart
================

Simple Donut Chart scss mixin. Still in development.

[View Demo](http://seanstopnik.com/lab/sass-donut-chart/)


How to Use
---

First import the 'donut-chart.scss' file into your project.

To create Donut Charts, in your main project scss file, just @include the donut-chart @mixin. Size, colors, and percentage is passed as arguments to the mixin.

<b>Examples</b>

	Standard Chart
	@include donut-chart('CHART CLASS NAME', PERCENTAGE, CHART SIZE(px), WIDTH OF GRAPH(px), BASE COLOR, CENTER COLOR, GRAPH COLOR);
	
	Custom Size for Percentage Number in Center
	@include donut-chart('CHART CLASS NAME', PERCENTAGE, CHART SIZE(px), WIDTH OF GRAPH(px), BASE COLOR, CENTER COLOR, GRAPH COLOR, TEXT COLOR, TEXT SIZE);
