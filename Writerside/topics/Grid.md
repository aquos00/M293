# Grid

How to make something a Grid:

```CSS
.Container{
    display: grid;
}
```

I recommend to use it when you want something to like it is in a Table:

```CSS
.galery {
    display:grid;
    grid-template-columns: auto auto auto;
}
```

with the `grid-template-collumns:` tag you can tell the Grid how many Columns there should be and how wide they are.  
I mostly use the `auto` because it automatically adjusts the width of the Columns to fit the Content.

Example of grid:

![GridExample.png](GridExample.png)

Code:

HTML:

```html

<div class="container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
    <div class="item">5</div>
</div>
```

CSS:

```css
.container {
  background-color: blue;
  display: grid;
  grid-template-columns: auto auto;
  justify-content: center;
  align-items: center;
  
}
.item {
  width: 98px;
  height: 98px;
  background-color: aqua;
  border: black solid 2px;
  text-align: center;
  line-height: 75px;
  font-size: 75px;
}
```