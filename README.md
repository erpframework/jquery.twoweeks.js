jquery.twoweeks.js
==================

A simple jQuery plugin to display a rolling two week calendar that you can use to select dates.

Setup:
1.  Include the JS at the bottom of your page:
<script type="text/javascript" src="jquery.twoweeks.js"></script>

2.  Include the CSS in the head of your page:
<link type="text/css" href="twoweeks.css" rel="stylesheet">

3.  Create an empty placeholder in your page:
<div id="select-date" class="two-weeks"></div>

4.  Instantiate the plugin (after the page loads):
$('#select-date').twoweeks(); // two weeks

5.  Add a click handler to select the date:
$('#select-date .day').on('click', function(){

  var date = $(this).attr('data-date'); // contains the selected date

});

