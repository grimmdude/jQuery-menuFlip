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
You can optionally specify the text you want to use for the flipped menu item using the `data-flipped-text` attribute in each link:
```
<li><a href="link1.html" data-flipped-text="Flipped Text">Link 1</a></li>
```

JS:
```js
$('#menuFlip').menuFlip({
    li_height       : '20px', 
    flip_speed      : 150, 
    flipped_class   : 'flipped_item', 
    mouseover       : function() {}, 
    mouseout        : function() {}
});
```