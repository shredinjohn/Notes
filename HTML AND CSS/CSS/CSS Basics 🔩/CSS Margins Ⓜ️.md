
Note : Create Space around elements, outside of any defined borders 

```css
p{
  margin-top:0px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}
```

#### Shorthand Property (anti-clockwise)

```css
margin: top right bottom left;
```

### Shorthand 3-value 

```css
margin : top (right & left) bottom;
```

#### Shorthand 2-value

```css
margin : (top & bottom) (right & left);
```

#### Shorthand 1-value

```css
margin : (top,bottom,right,left) /*All in one*/
```

### Auto value

Note: To set the margin property to `auto` to _horizontally_ center the element within its container

``` css
p{
margin : auto;
}
```

### Inherit Property

`This example lets the left margin of the <p class="ex1"> element be inherited from the parent element (<div>)`
```css
div {  border: 1px solid red;  
  margin-left: 100px;}  
  
p.ex1 {  margin-left: inherit;}

