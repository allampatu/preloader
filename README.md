# preloader
jQuery function to do preloader

````
jQuery(window).load(function() { // makes sure the whole site is loaded
    jQuery('.icon').fadeOut(); // will first fade out the loading animation
    jQuery('.loading').delay(400).fadeOut('slow'); // will fade out the white DIV that covers the website.
    jQuery('body').delay(400).css({'overflow':'visible'});
});

```
