# Box model

box model은 4가지 요소로 구성

- Margin, Border, Padding, Content

<img src="C:\Users\heech\AppData\Roaming\Typora\typora-user-images\image-20200614122342291.png" alt="image-20200614122342291" style="zoom:67%;" />

| Box model |                                                              |
| --------- | ------------------------------------------------------------ |
| Content   | ContentThe content of the box, where text and images appear  |
| Border    | A border that goes around the padding and content            |
| Padding   | Clears an area around the content. The padding is transparent |
| Margin    | Clears an area outside the border. The margin is transparent |







# Display

The `display` property specifies if/how an element is displayed.

Every HTML element has a default display value depending on what type of element it is. The default display value for most elements is `block` or `inline`.



### Block-level Element

A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).

Examples of block-level elements:  `<div>`, `<h1> - <h6>`, `<p>`,`<form>`,`<header>`,`<footer>`,`<section>`



### Inline Element

An inline element does not start on a new line and only takes up as much width as necessary.

Examples of inline elements:  `<span>`, `<a>`, `<img>`



### Inline-block

Compared to `display: inline`, the major difference is that `display: inline-block` allows to set a width and height on the element. Also, with `display: inline-block`, the top and bottom margins/paddings are respected, but with `display: inline` they are not.

Compared to `display: block`, the major difference is that `display: inline-block` does not add a line-break after the element, so the element can sit next to other elements.





