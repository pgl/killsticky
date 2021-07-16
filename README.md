# Kill Sticky

This is an updated version of [Alisdair McDiarmid](https://alisdair.mcdiarmid.org/)'s most excellent [Kill Sticky Headers](https://alisdair.mcdiarmid.org/kill-sticky-headers/).

It's a bookmarklet (a javascript function you can add to your bookmarks bar) that removes sticky elements in a webpage.

Add a new bookmark, and use the code below as the URL.

## Code

```
(javascript:void function(){(function(){var e,o=document.querySelectorAll("body *");for(e=0;e<o.length;e++){var t=getComputedStyle(o[e]).position;("fixed"===t||"sticky"===t)%26%26o[e].parentNode.removeChild(o[e])}})()}();
```
