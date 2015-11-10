<img src="http://s15.postimg.org/g2uq520h5/loader.png">
A SCSS mixin that turns a single element into a loading icon, built with just CSS!

*Note: This is still under development, but will be released soon.*

To add a loader simply call the mixin in your SCSS:
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



