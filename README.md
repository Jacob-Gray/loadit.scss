<img src="http://s27.postimg.org/o4m4qphb7/loader.png">
*Note: This is still under development, but will be released soon.*

A SCSS mixin that turns a single element into a loading icon, built with just CSS! No extra html elements needed, simply use a single element, and add the mixin in your SCSS:
```html
<div class="loadingDiv"></div>
```
```css
.loadingDiv{
  @include loadit-bars;
}
```
It can also take arguments, with many different animations available:
```css
.loadingDiv{
  @include loadit-target($color:red,$size:20px,$animation:wave);
}
```



