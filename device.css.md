---
layout: page
#title: Device.css
permalink: /
---
### About
Device.css is a project that helps you to display app screenshots including phones, tablets and screens easily with pure CSS file sized 29Kb only.
They are scalable and use CSS3 styles to enable you to use vector graphics that looks sharp on any resolution. 

### Example


	<link rel="stylesheet" href="device.css" type="text/css">

	<div class="iphone-6 white"></div>


	

### Results
<div class="macbook-air" style="font-size: 4px; vertical-align: middle;">
	<video width="100%" autoplay loop >
	  <source src="docs/demo.mp4" type="video/mp4" />
		Video is not supported
	</video>
</div>


<div class="iphone-6 white" style="font-size: 4px; vertical-align: middle;">
        <img src="background/screenshots/main_screen_detail.png"/>
</div>
<div class="iphone-6 black" style="font-size: 4px; vertical-align: middle;">
	<video width="250" autoplay loop >
	  <source src="background/videos/fnscreencast.mp4" type="video/mp4" />
	   <img src="background/screenshots/main_screen_detail.png"/>
	</video>
</div>
<div class="mac" style="font-size: 4px;"></div>

<div class="iphone-6 white landscape" style="font-size: 4px;"></div>

<div class="ipad-mini-3 white" style="font-size: 4px;"></div>
<br>
<p>Check out more extensive demo <a href="http://codepen.io/waterplea/pen/jPqBdr">here</a>.</p>

### Usage

1. Include `iphone6.css` or generate your custom subset of devices.
`<link rel="stylesheet" type="text/css" href="css/device.css">`
2. Add model name from the [list](#modelslist) to your div's classes  
`<div class="iphone-6 white"></div>`
3. You can scale the phone using font-size style, with font-size of 12px being 100% screen size, 6px - 50% etc.  
`<div class="iphone-6 white" style="font-size:6px"></div>`

{: #modelslist }
### Supported devices list with options:

- iPhone 6
	- base CSS class: *iphone-6*
	- required color scheme CSS class *black* or *white*
	- optional CSS class *landscape* for horizontal orientation  
Example: `<div class="iphone-6 black landscape"></div>`
- iPad Mini 3
	- base CSS class: *ipad-mini-3*
	- required color scheme CSS class *black*, *white* or *gold*
- Macbook Air
	- base CSS class: *macbook-air*
- iMac
	- base CSS class: *imac*

### Requirements
Safari 6.1+, Chrome 26.0+, Opera 15.0, FireFox 16.0+, IE 10+  
iOS Safari 7.1+  
Android Browser 4.4+, Chrome for Android 42+

### Sources
Sources available in repository [famer/device.css](http://github.com/famer/device.css).

### Issues 

If you find some bugs or issues feel free to submit report in [issues section](https://github.com/famer/device.css/issues).

### License

Device.css and its sources are released under [MIT](http://opensource.org/licenses/MIT) license.

### Share

<div id="fb-root"></div>
<a href="https://github.com/famer/device.css"><img style="position: absolute; top: 0; right: 0; border: 0;" src="https://camo.githubusercontent.com/365986a132ccd6a44c23a9169022c0b5c890c387/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6769746875622f726962626f6e732f666f726b6d655f72696768745f7265645f6161303030302e706e67" alt="Fork me on GitHub" data-canonical-src="https://s3.amazonaws.com/github/ribbons/forkme_right_red_aa0000.png"></a>

<div style="float:left; margin: 0 10px 0 0;">
	<script src="//platform.linkedin.com/in.js" type="text/javascript"> lang: en_US</script>
	<script type="IN/Share" data-counter="right"></script>
</div>

<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v2.3&appId=154079051320662";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>

<div style="float:left; margin: -4px 10px 0 0;" class="fb-like" data-href="http://famer.github.io/device.css/" data-layout="button_count" data-action="like" data-show-faces="false" data-share="false"></div>
<a style="float:left;" href="https://twitter.com/share" class="twitter-share-button" data-url="http://famer.github.io/device.css/" data-via="locationsphere">Tweet</a> <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>

### Copyright
Devices are created with CSS magic by [Alex Inkin](http://waterplea.bandcamp.com/), project managed by [Timur Tatarshaov](http://famer.github.io). You are free to use it anywhere according to MIT license.
© 2015

