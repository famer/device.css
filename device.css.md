---
layout: page
#title: Device.css
permalink: /
---

### About

Device.css is a project helping you to display app screenshots including phones, tablets and screens easily with pure CSS.

### Example

```
	<div class="iphone-6 white"></div>
```

### Results

<div class="iphone-6 white" style="font-size: 4px; vertical-align: middle;">
	<img src="background/Places.png"/>
</div>
<div class="iphone-6 black" style="font-size: 4px; vertical-align: middle;">
	<video width="250" autoplay loop>
	  <source src="background/videos/fnscreencast.mov" type="video/mp4" />
	</video>
</div>


### Usage

1. Include `iphone6.css` or generate your custom subset of devices.
`<link rel="stylesheet" type="text/css" href="css/iphone6.css">`
2. Add model name from the [list](#modelslist) to your div's classes  
`<div class="iphone-6 white"></div>`
3. You can scale the phone using font-size style, with font-size of 12px being 100% screen size, 6px - 50% etc.  
`<div class="iphone-6 white" style="font-size:6px"></div>`


### CSSes list:

- iphone6.css: iPhone 6 Silver, Space Gray, vertical and landscape
	- iphone6.white.css: iPhone 6 Silver vertical
	- iphone6.white.landscape.css: iPhone 6 Silver vertical and landscape
	- iphone6.black.css: iPhone 6 Space Gray vertical
	- iphone6.black.landscape.css: iPhone 6 Space Gray vertical and landscape

### Supported devices list with css options (will continue to grow):

- iPhone 6
	- base css class: *iphone-6*
	- required color scheme CSS class *black* or *white*
	- optional CSS class *landscape* for horizontal orientationi  
Example: `<div class="iphone-6 black landscape"></div>`

### Requirements
Safari, Chrome, Opera, FireFox  
IE 10+ 

### Sources
Sources available in repository [famer/device.css](http://github.com/famer/device.css)

### License

Device.css and its sources are released under [MIT](http://opensource.org/licenses/MIT) license.

### Copyright
© 2015 Alex Inkin with support of Timur Tatarshaov
