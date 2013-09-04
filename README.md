modalEffects-ajax
=================

A little addition to Codrops Nifty Modal Script that allows for Ajax support

Simply swap your modalEffects.js for this one, and add

```
var ajaxEvent = new CustomEvent(
	'ajaxLoaded'
);

document.dispatchEvent(ajaxEvent);
```

to your Ajax callback.
