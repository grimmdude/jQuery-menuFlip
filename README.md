jQuery menuFlip
===============

Create flipping menu links with this extremely lightweight jQuery plugin.

##Usage
HTML:
```html
<ul id="menuFlip">
    <li><a href="link1.html">Link 1</a></li>
    <li><a href="link1.html">Link 1</a></li>
    <li><a href="link1.html">Link 1</a></li>
    <li><a href="link1.html">Link 1</a></li>
</ul>
```

JS:
```js
$('#menuFlip').menuFlip({});
```

The flipped links have a class of 'flipped_item' by default so can style as you like.

##Options
These are the default options, however you can pass a map of the keys with different values into the plugin to override them.
```js
{
    'li_height' : '20px', 
    'flip_speed' : 150, 
    'flipped_class' : 'flipped_item', 
    'mouseover' : function() {}, 
    'mouseout' : function() {}
}