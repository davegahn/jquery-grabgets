jquery-GrabGets 
==============

Grab and parse GET parameters from url and put, select and check elements of selected form

Requires jQuery v1.6 or later

<a href="http://dontforget.pro/examples/get-put-form.php" target="blank">DEMO</a>

Capabilities:
==============

- Simple initialising

- Supported all form's elements include multiple select list

- Friendly with special and cyrillic characters

- Work with same name inputs (exclude multiple selects)

Call:
==============
<pre>
$(document).ready(function() {
	$('SELECTOR OF FORM').grabgets({
	  hidden: false // do not replace values in hidden inputs (defaulth is true)
	});
});
</pre>

==============

additional description (in russian): http://dontforget.pro/javascript/jquery-plagin-dlya-parsinga-url-stroki-s-get-parametrami-i-vstavki-znacheniy-v-formu/
