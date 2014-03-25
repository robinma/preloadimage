preloadimage.js,a javascript lib,preload image width and height.
============

#####use javascript to preload image,render image to document before,get image width and height;

******

#API

###preloadimage(imgUrl,[readyFn],[loadFn],[errorFn])
```
/**
*   imgUrl {String}  images url
*   readyFn{Function} when image had load
*   loadFn {Function} when image start load
*   errorFn{Function} when load error
*/

example:
preloadimage('http://developer.github.com/images/logo_developer.png',function(){
  var img=this;
  var width=img.width,height=img.height;
  
  console.log("I get it width:",width," height:",height);
})
```

