# Scroll-Top-JavaScript-Jquery

```javascript
function irA(identify){
	var top = ($(identify).offset().top - 150);

	$('html, body').animate({
        scrollTop: top
    }, 500);

    return false;
}
```
