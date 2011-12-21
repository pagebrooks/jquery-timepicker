Introduction
============

The jQuery TimePicker is a simple plug-in that allows the user to enter a time or optionally select a time of day from a list.

![Time Picker](https://github.com/pagebrooks/jquery-timepicker/raw/master/docs/images/screenshot.png)

Usage
=====

Using standard jQuery syntax, simply select the text input elements that will become time picker controls.  In the example
below, the startTime element is transformed into a time picker control when the document loads.

CSS

```
<style type="text/css">
		
	.timePicker {
		border: 1px solid gray;
		overflow-y: scroll;
		height: 120px;
		width: 180px;
		position: absolute;
		background-color: #fff;
	}
		
	.timePicker ul {
		list-style-type: none;
		padding: 0;
		margin: 0;
	}
		
	.timePicker ul li p {
		padding: 3px;
		margin: 0;
	}
	
	.timePicker ul li:hover, .timePicker-selected {
		background-color: gray;
		color: #fff;
	}
		
</style>
```

HTML

```
<script src="Scripts/jquery-TimePicker-1.0.0.js" type="text/javascript"></script>
...
...
<input type="text" id="startTime"></input>
```

SCRIPT

```
<script type="text/javascript">
	
	$(function() {
		
		$("#startTime").timePicker();
		
	});

</script>

```