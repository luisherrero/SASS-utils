# SASS Utils

###Collection of sass mixins to improve browser compatibility issues and increase CSS development speed.



## How to use it
Import **utils.scss** in the main scss file to make it available in your project.

```
@import "utils.scss";
```

Below are an explanation of the different mixins:

##Linear Gradient (linearGradient)

```
// Generates linear and vertical gradients with two colors.

@include linearGradient(#F00, #C00);
```

##@font-face (fontface)
This mixin needs two arguments.
The first one is the name of the font we're going to use in the CSS. The second one is the url with the file name but without extension.

```
// Generates bulletproof font-face syntax.

@include fontFace('CoolFont', '/fonts/CoolFont');
```


## Version history

* 2012/07/19 - v1.0



## Licence
Copyright (c) 2012 [Luis Herrero Jimenez][web]  
Licensed under the MIT, GPL licenses.
[web]: http://luisherrero.es/
