# Web class CSS 1

1. CSS syntax

```css
p {
  color: red;
  text-align: center;
}
```

1. CSS selector
- Simple selectors (select elements based on name, id, class)

```css
p {
  text-align: center;
  color: red;
}
```

1. [Combinator selectors](https://www.w3schools.com/css/css_combinators.asp) (select elements based on a specific relationship between them)

```css
#para1 {
  text-align: center;
  color: red;
}
```

1. [Pseudo-class selectors](https://www.w3schools.com/css/css_pseudo_classes.asp) (select elements based on a certain state)

```css
.center {
  text-align: center;
  color: red;
}
```

1. [Pseudo-elements selectors](https://www.w3schools.com/css/css_pseudo_elements.asp) (select and style a part of an element)

```css
p {
  text-align: center;
  color: red;
}
```

1. The CSS grouping selector

```css
h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

p {
  text-align: center;
  color: red;
}
```

1. **How To Add CSS**

**External CSS**

```css
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

1. Internal CSS

```css
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
} 
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

1. **Inline CSS**

```css
<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>
```

1. **CSS Margins**

```css
p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}

```

1. **CSS Padding**

```css
div {
  padding-top: 50px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left: 80px;
}
```

1. **CSS Border Style**

```css
p.dotted {border-style: dotted;}
p.dashed {border-style: dashed;}
p.solid {border-style: solid;}
p.double {border-style: double;}
p.groove {border-style: groove;}
p.ridge {border-style: ridge;}
p.inset {border-style: inset;}
p.outset {border-style: outset;}
p.none {border-style: none;}
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
```

1. **CSS Lists**

```css
ul.a {
  list-style-type: circle;
}

ul.b {
  list-style-type: square;
}

ol.c {
  list-style-type: upper-roman;
}

ol.d {
  list-style-type: lower-alpha;
}
```

1. **CSS Functions Reference**

# CSS Functions

CSS functions are used as a value for various CSS properties.

| Function | Description |
| --- | --- |
| https://www.w3schools.com/cssref/func_attr.php | Returns the value of an attribute of the selected element |
| https://www.w3schools.com/cssref/func_calc.php | Allows you to perform calculations to determine CSS property values |
| https://www.w3schools.com/cssref/func_conic-gradient.php | Creates a conic gradient |
| https://www.w3schools.com/cssref/func_counter.php | Returns the current value of the named counter |
| https://www.w3schools.com/cssref/func_cubic-bezier.php | Defines a Cubic Bezier curve |
| https://www.w3schools.com/cssref/func_hsl.php | Defines colors using the Hue-Saturation-Lightness model (HSL) |
| https://www.w3schools.com/cssref/func_hsla.php | Defines colors using the Hue-Saturation-Lightness-Alpha model (HSLA) |
| https://www.w3schools.com/cssref/func_linear-gradient.php | Creates a linear gradient |
| https://www.w3schools.com/cssref/func_max.php | Uses the largest value, from a comma-separated list of values, as the property value |
| https://www.w3schools.com/cssref/func_min.php | Uses the smallest value, from a comma-separated list of values, as the property value |
| https://www.w3schools.com/cssref/func_radial-gradient.php | Creates a radial gradient |
| https://www.w3schools.com/cssref/func_repeating-conic-gradient.php | Repeats a conic gradient |
| https://www.w3schools.com/cssref/func_repeating-linear-gradient.php | Repeats a linear gradient |
| https://www.w3schools.com/cssref/func_repeating-radial-gradient.php | Repeats a radial gradient |
| https://www.w3schools.com/cssref/func_rgb.php | Defines colors using the Red-Green-Blue model (RGB) |
| https://www.w3schools.com/cssref/func_rgba.php | Defines colors using the Red-Green-Blue-Alpha model (RGBA) |
| https://www.w3schools.com/cssref/func_var.php | Inserts the value of a custom property |
1. **CSS Variables**

```css
body { background-color: #1e90ff; }

h2 { border-bottom: 2px solid #1e90ff; }

.container {
  color: #1e90ff;
  background-color: #ffffff;
  padding: 15px;
}

button {
  background-color: #ffffff;
  color: #1e90ff;
  border: 1px solid #1e90ff;
  padding: 5px;
}
```
