---
layout: page
#title: Device.css
permalink: /
---

### About

Device.css is a project helping you to display app screenshots including phones, tablets and screens easily with pure css.

### Examples

Example of usage

```
	<div class="iphone-6 white"><img src="background/Places.png"/></div>
```

#### Result
<div class="iphone-6 white" style="font-size: 4px;">
	<img src="background/screencast.gif"/>
</div>
<div class="iphone-6 black" style="font-size: 4px;">
	<img src="background/screencast.gif"/>
</div>

### Usage

1. Include `device.css` or generate your custom subset of devices.
`<link rel="stylesheet" type="text/css" href="css/device.css">`
2. Add model name from the [list](#modelslist) to your div's classes  
`<div class="iphone-6 white"></div>`
3. You can scale the phone using font-size style, with font-size of 12px being 100% screen size, 6px - 50% etc.  
`<div class="iphone-6 white" style="font-size:6px"></div>`


### CSSes list:

- iphone6.css: iPhone 6 Silver, Space Gray, vertical and landscape
	- iphone6.silver.css: iPhone 6 Silver vertical
	- iphone6.silver.landscape.css: iPhone 6 Silver vertical and landscape
	- iphone6.space-gray.css: iPhone 6 Space Gray vertical
	- iphone6.space-gray.landscape.css: iPhone 6 Space Gray vertical and landscape

### Supported devices list with css options (will continue to grow):

- iPhone 6
	- base css class: *iphone-6*
	- required color scheme css class *black* or *white*
	- optional css class *landscape* for horizontal orientationi  
Example: `<div class="iphone-6 black landscape"></div>`

### License

Device.css and its sources are released under [MIT](http://opensource.org/licenses/MIT) license.

© 2015 Alex Inkin with support of Timur Tatarshaov
