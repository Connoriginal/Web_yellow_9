# Developer documentation #
This documentation will help you understand more about our codes of the web.
Short explanation of the files are offered. Some files do not have explanations.
If you want to report a bug, ask a question, get more information, [Contact Us](https://github.com/TaeUnisef/Web_yellow_9)

## Summary ##

- [General](#general)
- [Structure](#structure)
    * [Languages](#languages)
    * [Assets](#assets)
    * [Html](#html)
    * [Images](#images)
    * [Slider](#slider)
	* [License](#license)
	* [README.md](#readme.md)
- [Credits](#credits)

## General ##
- Author :  Yoon Chan Woong, Choi Jin Woo

## Structure ##
Web-yellow-10
```
├────RemoteSystemsTempFiles
├────assets
├────html
├────images
├────slider
├────LICENSE
├────README.md
├────.DS_STORE
```

|File/Folder|Description|
|---|---|
|**assets**|Contains files that determine the basic frame of the web|
|**html**|Contains files that import sources from assets|
|**images**|Contains images that are shown in card news and in the main screen|
|**slider**|Contains files that supports sliding actions in the web(dragging, movement by keys|
|**LICENSE**|Contains text that guarantees our license in our web|
|**README.md**|Contains text that includes basic description of our web|


### Languages ###
CSS, HTML, Javascript is used in this code.


### Assets ###
```
├── ss
    ├── font-awesome.min.css
        ├── main.css
		...
├── fonts
	├── FontAwesome.otf
	├── fontawesome-webfont.eot
	├── fontawesome-webfont.svg
		...
├── js
	├── jquery.min.js
	├── main.js
		...
├── sass
	├── base
		├── _page.scss
		├── _typography.scss
	├── components
		├── _box.scss
		├── _button.scss
		├── _form.scss
			...
	├── layout
		├── _footer.scss
		├── _header.scss
			...
	├── libs
		├── _functions.scss
		├── _mixins.scss
			...
	├── ie8.scss
	├── ie9.scss
		...
```
|File/Folder|Description|
|---|---|
|**css**|ie8.css,ie9.css : Includes support in Internet Explorer 8 and 9|
|**main.css**|main.css : Basic structure in web, using this file in main.html|
|**fonts**|Define the font family,boldness,size,and the style of a text|
|**js**|Contains java script files|
|**scss**|Contains scss files that help us use css|

### Html ###
```
├── cate_html
	├── DS_Store
	├── cur_ev.html
	├── default.html
	├── ittech.html
	├── license.html
	├── life.html
	├── map.html
├── news_html
	├── DS_Store
	├── Al.html
	├── FB_research.html
	├── clinical_ex.html
	├── deathPenalty.html
	├── default.html
	├── jap.html
	├── neighbor.html
├── DS_Store
├── main.html
```


|File/Folder|Description|
|---|---|
|**cate_html**|Contains codes that create 'Menu' tab on the right side of the web|
|**cate_html/cur_ev.html**|Contains codes that display card news of the "Current issues" category|
|**cate_html/default.html**|Contains codes that provide basic frame of category|
|**cate_html/ittech.html**|Contains codes that display card news of the "IT and Technology" category|
|**cate_html/license**|Contains codes that displays 'License Warranty' on the web|
|**cate_html/life**|Contains codes that display card news of the "Life" category|
|**cate_htm/map**|Contains codes that display maps so that you can contact us offline|
|**news_html**|Contains codes that create card news|
|**news_html/default.html**|Contains codes that provide basic frame of news|
|**main.html**|Contains codes that display the main screen of the web|


### Images ###
```
├── Ai
	├── .DS_Store
	├── 1.jpg
		...
├── clinical
	├── .DS_Store
	├── 1.jpg
		...
├── deathPenalty
	├── .DS_Store
	├── 1.jpg
		...
├── jap
	├── .DS_Store
	├── 1.jpg
		...
├── .DS_Store
├── banana.jpg
├── logo.jpg
	...
```

|File/Folder|Description|
|---|---|
|**news**|Contains card news image files |
|**banana.jpg**|Our logo image file|
|**pic01~15.jpg**|Basically given image files|


### Slider ###
```
├── svg/loading/static-svg
	├── ball-triangle.svg
	├── circles.svg
	├── double-tail-spin.svg
		...
├── trasitions
	├── slideshow-transition-builder-controller.min.js
	├── slideshow-transitions(360).html
├── bower.json
├── component.json
├── jquery-1.9.1.min.js
├── jssor.slider.min.js
├── package.json
```


|File/Folder|Description|
|---|---|
|**jssor.slider.min.js**|Contains codes that supports the use of "Jssor Slider"|
|**jquery-1.9.1.min.js**|Contains codes that supports the use of jquery, a javascript library made for HTML client-side scripting simplification|


### License ###
File that guarantees the license of our web(MIT).

### README.md ###
Basic introduction of our web.

## Credits ##
Basic template : [Phantom by HTML5UP](https://html5up.net)

Image slider : [jssor slider](https://www.jssor.com)

Map : [Google Maps api](https://developers.google.com/maps/documentation/javascript/adding-a-google-map?hl=ko)

Reference : [LouisBarranqueiro/hexo-theme-tranquilpeak](https://github.com/LouisBarranqueiro/hexo-theme-tranquilpeak/blob/master/docs/developer.md#build)
