<img src="http://s27.postimg.org/o4m4qphb7/loader.png">
*Currently version 0.9*

A SCSS mixin that turns a single element into a loading icon, built with just CSS! 
How to use
-
Import the _loadit.scss file:
```css
@import "loadit";
```
Then add your loaders like this:
No extra html elements needed, simply use a single element, and add the mixin in your SCSS:
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
[Demos](http://jacob-gray.github.io/loadit.scss/samples)
-
[Documentation](http://jacob-gray.github.io/loadit.scss/docs)
-



