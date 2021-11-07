# p5.mapper

This library is designed to making projection mapping easy using the popular, easy-to-learn JavaScript library, [p5.js](https://p5js.org/). Created by [Jenna deBoisblanc](https://jdeboi.com/).

* [Examples](examples)
* [Reference](reference/README.md)

You'll find the library, `p5.mapper.min.js`, in the dist folder of this repo. Include the library in your `index.html` (after loading p5.js).

```html
<script type="text/javascript" src="p5.mapper.min.js"></script>
```


## Acknowledgements

The logic of this library builds upon and/or adapts:
* [David Bouchard's (Java) Processing Keystone Library](http://keystonep5.sourceforge.net/)
* [Jenny Louthan, projection transform algorithms](https://github.com/jlouthan/perspective-transform) 

## TODOs
* There is a bug when a surface is created; the width of the surface cuts cut by this.res... something todo with this.res -1 when creating the surface?