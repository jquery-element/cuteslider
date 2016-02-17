# cuteslider

``` html
<script src="//code.jquery.com/jquery-3.0.0-alpha1.min.js"></script>
<script src="//jquery-element.github.io/jquery-element-2.0.0.js"></script>
<script src="//jquery-element.github.io/cuteslider-2.2.0.js"></script>

<input class="lorem" type="range"
	min="0" value="5" max="10" step="0.1"
	data-jquery-element="cuteslider"
/>
```

To make it **vertical** just add the attribute `data-cuteslider-vertical`, like:
``` html
<input class="lorem" type="range"
	min="0" value="5" max="10" step="0.1"
	data-jquery-element="cuteslider"
	data-cuteslider-vertical
/>
```

The attributes `min`, `max`, `value`, `step`, `data-cuteslider-vertical` can be modified by doing:
``` javascript
$( "input.lorem" ).attr({
	min: 0,
	max: 250,
	value: 0
})
```
and the element will be synchronized automatically.
