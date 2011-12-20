Introduction
============

The jQuery TimePicker is a simple plug-in that allows the user to enter a time or optionally select a time of day from a list.

Usage
=====

Using standard jQuery syntax, simply select the text input elements that will become time picker controls.  In the example
below, the startTime element is transformed into a time picker control when the document loads.

```
<input type="text" id="startTime"></input>
```

```
<script type="text/javascript">
	
	$(function() {
		
		$("#startTime").timePicker();
		
	});

</script>

```