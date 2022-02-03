# Update CSS variables with JS

![preview](preview.mov)

## What I learned

CSS properties and values are string;
To select CSS variables, select the root element with `document.documentElement`, and then modify the CSS rule of this element with `style.setProperty(propertyName,value)`

```js
document.documentElement.style.setProperty(
  `--${this.name}`,
  this.value + suffix
);
```
