## Generative i/o

source:

1. https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.5.2/p5.min.js
2. https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.5.2/addons/p5.dom.js

refferences:

1. https://medium.com/@engineerwithoutfear/using-p5-js-on-codepen-efd443fc661

sandbox:

1. https://editor.p5js.org/gbenedisgrab/sketches/IgHP-KOs

```js
function setup() {
  createCanvas(500, 500);
  background(120);
}
function draw() {
  fill(233, 11, 44); // color to fill the shapes
  stroke(1); // stroke color
  strokeWeight(2);
  line(20, 20, 160, 60); // line from (20,20) to (160,60)
  fill(23, 44, 223);
  rect(170, 170, 120, 70); // rectangle on (170,170) with 120x70 size
  fill(223, 212, 44);
  ellipse(120, 130, 100, 100); // ellipse on (120,130) with height 100 and width 100, which makes it a circle
  noLoop();
}
```

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1

## Header 2

### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
