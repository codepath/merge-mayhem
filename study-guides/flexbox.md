# Flexbox
## Creating a Flexbox Container and Items

You may be wondering, how do we even define or create a Flexbox container and items? Typically developers use the `div` HTML element to create sections that will then be defined as a Flexbox. In the CSS style file, we add a rule for these `div` containers that set the property `display` to the value `flex`.

```css
.container {
	display: flex;
}
```
In the example above, we create a rule that all `div` elements with the class name `container` will have the `display` property with value `flex` (aka a Flexbox!). Once you have defined a flex container, all elements inside automatically act as flex items.
