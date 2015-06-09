##&lt;place-holder&gt; - *custom element to fill empty spaces*
###What is it for?
**Placeholder(&lt;place-holder&gt;)** element lets you fill empty spaces in your website for future images, ads or anything else. Now you can set up your page without content and see how it presents!
###Installation
This custom element uses [Polymer 1.0](http://www.polymer-project.org/), which is required for **placeholder** to work, so remember to download Polymer and import it to the page before using **placeholder**.

1. Download [Polymer](http://www.polymer-project.org/), using Bower.

    ```
	bower install --save Polymer/polymer
	```
2. Download **placeholder** using Git or Bower

	```
	git clone https://github.com/JMendyk/place-holder.git
	or
	bower install --save place-holder
	```
3. Import polymer
	
	```html
	<script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
	```
3. Import **placeholder** (and Polymer if not yet)

	```html
	<link rel="import" href="bower_components/place-holder/place-holder.min.html"> (minified version)
	or
	<link rel="import" href="bower_components/place-holder/place-holder.html">
	```
	
###Usage
Start using **placeholder** element by adding it to the html page  
```html
<place-holder></place-holder>
```  
by default element will fill parent element and have light-grey background with dark-grey text displaying width and height of itself.

You can customize **placeholder**'s appearance using following attributes:

|Type            |Attribute Name|Definition             |
|:--------------:|:------------:|:---------------------:|
|width           |width         |width                  |
|height          |height        |height                 |
|text color      |color         |color of the text      |
|background color|bg            |color of the background|

###Additional Info
Inspiration for me to create this element was [placehold.it](placehold.it), but using **placehold.it** is impossible if you are offline. Additionally **placehold.it** image weight and load time depends on the size of it and bandwidth, where **[PLACEHOLDER](https://github.com/JMendyk/place-holder)** does not have this problem because there is no generated image, only 480 bytes gzipped!
