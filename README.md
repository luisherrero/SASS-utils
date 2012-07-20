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

```
// Generates bulletproof font-face syntax.

@include fontface(iconFont);
```


## Version history

* 2012/07/19 - v1.0



## Licence
Copyright (c) 2012 [Luis Herrero Jimenez][web]  
Licensed under the MIT, GPL licenses.
[web]: http://luisherrero.es/
