# Badj's 

**add instantly &amp; easily social badges to your websites**

Badj's is a jQuery plugin that eases badges integration in your websites.

## Get started

1. Download CSS & JS files & include it in your web page
2. Make sure you include jQuery API (v1.10 or further)
3. Include a list element which will contains badges, for example :


```html
<ul class="badjs">
<li data-badj="mail" data-url="mailto:test@example.com"></li>
</ul>
```

4. Include the javascript that will initiate badges, for example :

```javascript
$(document).ready(function() {

	$('.badjs li').each(function() {

		$(this).badjIt();

	});

});
```

## Examples

Example is better than precept, you can find a working example in docs/ folder.


