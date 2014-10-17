# My Color Box

I especially love this " lightbox " so I let it organized in a very simple way to install wordpress.

* Based (100%) on available <b>ColorBox</b> project: 
`https://github.com/jackmoore/colorbox`

## Install
Add in your theme
* add css/colorbox.css into theme/css/
* add images/* on your theme/images/
* add js/colorbox.js on your theme/js/
* after on your header add 

```markup
<link rel="stylesheet" type="text/css" href="<?php bloginfo('stylesheet_directory'); ?>/css/colorbox.css" />
<script type="text/javascript" src="<?php bloginfo('stylesheet_directory'); ?>/js/colorbox.js"></script>
```


## How to use

* Add in your `<a href=“#divHiddem” rel=“colorBox”>Link</a>`.
* Hiddem your master div on `display=“none”` and inside then add yours `div’s` you will display on **colorbox**.
