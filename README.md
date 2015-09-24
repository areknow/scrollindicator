# scrollindicator
scrollindicator.js is a jQuery plugin that adds a bar on your page, which indicates the percentage of the page that has been scrolled.

<br>
<hr>
###Depedencies
This is a jQuery plugin, so jQuery must be imported to your project prior scrollindicator.js script.

You can do this by importing the following line to your webpage inside the <head> tag:
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"> </script>
```

<br>
<hr>
###Initialization
To initialize the plugin add the following JavaScript code into your project:
```
(function($) {
    'use strict';
     
     $(document).ready(function() {
         
         $('body').scrollindicator();

     });
     
})(jQuery);
```
This plugin provides you some optional options which you can use to achieve customization. The options are presented below.
For instance:
```
$('body').scrollindicator({ 
            backgroundColor: 'transparent',
            color: 'black',
            gradientFinish: 'yellow',
            where: 'header',
            position: 'top',
            width: '5px'
 });
```

<br>
<hr>
###Manual
Plugin options are:

#####backgroundColor
behind the bar color, if omitted the default is transparent

#####color
bar's color

#####gradientFinish
if set, the bar has a gradient color and color option is used for gradientStart,
if both color and gradientFinish options are omitted, bar has a gradient blue color

#####where
bar's position, eg: 'header' to be placed in <header>, or '#myheader' to be placed in $('#myheader'),
if omitted, the bar by default is placed with fixed position at the top or at the bottom of the page according to position option

#####position
top or bottom, if top, the bar is placed at the top of $(where), if bottom, bar is placed at the bottom of $(where),
if omitted, the default is top

#####width
bar's width, if omitted, width is set to 5px by default

<br>
<hr>
<br>
Enjoy the script and let me know for any suggestions you may have for further enhancement!
<br>
Cheers!
