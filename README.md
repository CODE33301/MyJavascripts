# MyJavascripts
Made To Make Life Easy

# Description
Do you know that you can create JavaScript scripts with bookmarks? I will be showing you how to create one and you can use my custom scripts as examples and your usage.

# Scripts
* YouTube Full Screen
* Burl All IMG tags every 3 seconds

# YouTube Full Screen
This is made for a tiling window manager. To keep your screen organized.
```javascript
javascript:(()=>{   const currentUrl = window.location.href; var croptxt = currentUrl.substring(32, 50); var fullURL = "https://www.youtube.com/embed/" + croptxt; window.open(fullURL,"_self")   ;})();
```

# Burl All IMG tags every 3 seconds, to avoid any IMG tags for any reason.
This is made to blur all IMG tags
```javascript
javascript:(()=>{   setInterval( 'for (let i = 0; i < document.getElementsByTagName("img").length; i++) { document.getElementsByTagName("img")[i].style.filter = "blur(30px)"; }', 1000);   })();
```
