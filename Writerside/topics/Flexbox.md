# Flexbox

Flexbox is really simple:

```CSS
* {
  display: flex;
 }
```

I recommend that you use a container, for example if you want to center an Element:

```CSS
.Container {
    display: flex;
    justify-content: center;
    align-items: center;
}
```

Example of Flexbox:

![flexboxExample.png](flexboxExample.png)

Code:

HTML

```html

<div class="container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
    <div class="item">5</div>
</div>
```

CSS

```css
div.item {
    width: 98px;
    height: 98px;
    background-color:aqua;
    border: black solid 2px;
    text-align: center;
    line-height: 75px;
    font-size: 75px;
}
div.container {
    background-color: blue;
    display:flex;
    align-items: center;
    justify-content: center;
    height: 120px;
    gap: 1%;
}
```