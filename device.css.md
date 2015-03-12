---
layout: page
#title: Device.css
permalink: /device
---

### About

Device.css is a project helping you to display app screenshots including phones, tablets and screens easily with pure css.

### Examples

Example of usage

```
	<div class="iPhone4s"><img src="background/Places.png"/></div>
```

#### Result

<div class="iPhone4s"><img src="background/screencast.gif"/></div>

### Usage

1. Include `device.css` or other required css file from the [list](#csslist)  
`<link rel="stylesheet" type="text/css" href="css/device.css">`
2. Add model name from the [list](#modelslist) to your div's classes  
`<div class="iPone6"></div>`


### CSSes list:

- device.css: you need all available devices
- phones.css: you need all available phone devices(iPhones, Samsungs, BBRY)
- tablet.css: you nee all available tablets(iPads, Android Tablets)
- iphone.css: all iphone models(iPhone 4S, iPhone 5, iPhone 6, iPhone 6 Plus)
- samsung.css: all samsung devices (Galaxy S, Galaxy S3, Galaxy S4)

Separate css for separate devices:

- iphone6.css: only iPhone 6 appearance
- galaxys5.css: only Samsung Galaxy S5

### Supported devices list:

- iPhone 4S (class: *iPhone4S*)
- iPhone 5 (class: *iPhone5*)
- Samsung Galaxy S4 (class: *galaxyS4*)
