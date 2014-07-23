##&lt;place-holder&gt; - *custom element to fill empty spaces*
###What is it for?
**Placeholder(&lt;place-holder&gt;)** element lets you fill empty spaces in your website for future images, ads or anything else. Now you can set up your page without content and see how it presents!
###Installation
This custom element uses [Polymer](http://www.polymer-project.org/), which is required for **placeholder** to work, so remember to download Polymer and import it to the page before using **placeholder**.

1. Download [Polymer](http://www.polymer-project.org/) (if you don't have it already), using Git or Bower. **Placeholder** uses only basics of Polymer, so you don't have to download whole project.

    ```
	git clone https://github.com/Polymer/polymer.git
	git clone https://github.com/Polymer/platform.git
	or
	bower install --save Polymer/polymer
	```
2. Download **placeholder** using Git or Bower

	```
	git clone https://github.com/KubaBest/place-holder.git
	or
	bower install --save place-holder
	```
3. Import **placeholder** (and Polymer if still not)

	```
	<script src="POLYMER_PLATFORM_PARENT_FOLDER/platform/platform.js"></script>
	<link rel="import" href="POLYMER_PARENT_FOLDER/polymer/polymer.html">

	<link rel="import" href="PLACE-HOLDER_PARENT_FOLDER/place-holder/place-holder.html">
	```
	
###Usage
The fastes way to start using **placeholder** element is to just add it to html page  
```
<place-holder></place-holder>
```  
by default element will fill parent element and have light-grey background with dark-grey text displaying width and height of itself.

You can customize elements appearance using following attributes:

|Type            |Attribute Name|Definition                                |
|:--------------:|:------------:|:----------------------------------------:|
|width           |width         |width of the placeholder                  |
|height          |height        |height of the placeholder                 |
|text color      |color         |color of the text in the placeholder      |
|background color|bg            |color of the background of the placeholder|

###Additional Info
My inspiration to create this element was [placehold.it](placehold.it), I thought that using **placehold.it** might be impossible if you are offline. **placehold.it** image weight and load time depends on the size of it and bandwidth. **[PLACEHOLDER](https://github.com/KubaBest/place-holder)** does not have this problem because there is no generated image, just 790 bytes of minified HTML+CSS+JS.
