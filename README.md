# Easy-Page-Loader
Very easy and basic page loader, image can be created and downloaded from loading.io

##HTML
###Place right inside the opening of the <body> tag
```
<div class="loader"></div>
```

##CSS
###Place inside your main CSS file, or another file specific to loading elements
The background image I created and downloaded from loading.io and then places inside my _images directory. You can adjust this style as needed
```
.loader {
    position: fixed;
    top: 0;
    left: 0;
    width:100%;
    height:100%;    
    z-index: 99999999;
    background: url(../../_images/ring.gif) 50% 50% no-repeat rgb(255,255,255);
}
```

##Javascript, using jQuery
###Place inside your javascript file, or another file specific to action for the window.onload function
```
window.onload = function () {
    $(".loader").delay(250).fadeOut("fast");
}
```

Cheers,

//Brandon
