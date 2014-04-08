# About

Mediaquery allows you to listen for ```mediaqueryactive``` and ```mediaqueryinactive``` js events and react accordingly.   When a specific media query is active the ```id``` of the mediaquery will be added to any elements in the ```for``` attribute as classes.   In the example below, the element with ```id="app"``` will have the class ```small_desktop``` when the mediaquery matches.

**Gotchas**
Since this component is built using javascript, the media query will fire after initial render.  This means that the user may see a "snap" from the default styles to the active style.

# Syntax

```html
<x-mediaquery id="small_desktop" for="app" media="only screen and (min-width : 400px) and (max-width : 600px)"></x-mediaquery>
```


# Create X-Tag Components

[Guide for creating X-Tag Components](https://github.com/x-tag/core/wiki/Creating-X-Tag-Components)

# Use X-Tag Components

[Using X-Tag components in your applications](https://github.com/x-tag/core/wiki/Using-X-Tag-Components-in-your-application)


