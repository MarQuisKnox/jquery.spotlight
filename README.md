# jquery.spotlight
jQuery Spotlight is a jQuery plugin which allows you to highlight elements in your page using a 'spotlight' effect. This plugin is highly customizable and requires no external css or images.

# Usage
* Initialization:
````
$(selector).spotlight({
	opacity: .5,				//spotlight opacity
	speed: 400,					//animateion speed
	color: '#333',				//spotlight colour
	animate: true,				//enable animation (if false 'speed' and 'easing' are irrelevant)
	easing: '',					//set easing from the jQuery Easing plugin
	exitEvent: 'click',		//set which event triggers spotlight to hide 
									//(must be a valid jQuery 'live' event type)
	onShow: function(){},	//callback function after spotlight is shown
	onHide: function(){}		//callback function after spotlight is hidden
});
````

* Un-spotlight:
````
$(selector).spotlight().unspotlight();
````

# Changes
* This fork adds the following features:
** unspotlight()

# License
* GPL v3

# Credits
* Dev7studios — http://dev7studios.com/demo/jquery-spotlight
