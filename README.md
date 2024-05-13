# CSS BOX MODEL

The CSS Box Model is a fundamental concept in web development that defines how different parts of an HTML element work together to create the visual representation of that element on a webpage. Let’s break it down:

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

**Table of Contents** _generated with [DocToc](https://github.com/thlorenz/doctoc)_

- [CSS BOX MODEL](#css-box-model)
  - [1. Content:](#1-content)
  - [2. Padding:](#2-padding)
  - [3. Border:](#3-border)
  - [4. Margin:](#4-margin)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 1. Content:

The content area is where text, images, or other media appear within the element. <br>
It’s the innermost part of the box.

## 2. Padding:

Padding clears an area around the content. <br>
It provides space between the content and the border. <br>
You can set padding using CSS properties like ` padding-top, padding-right, padding-bottom, and padding-left.`

## 3. Border:

The border surrounds the padding and content. <br>
It defines the visible edge of the element. <br>
You can set the border using properties like `border-width, border-style, and border-color.`

## 4. Margin:

The margin clears an area outside the border. <br>
It creates space between adjacent elements. <br>
You can set the margin using properties like `margin-top, margin-right, margin-bottom, and margin-left.`

The example below is a CSS code showing all properties of CSS Box Model.

```css
div {
  width: 300px; /* Width of the content area */
  border: 15px solid green; /* Border around the padding and content */
  padding: 50px; /* Space around the content */
  margin: 20px; /* Space outside the border */
}
```

Here is the respective html code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Box Model</title>
  </head>
  <body>
    <div>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Qui sed id
      similique reiciendis eveniet suscipit officia dolore laboriosam dolor.
      Quam amet porro atque quas optio dolor ipsam ipsa quasi iure!
    </div>
  </body>
</html>
```

The above CSS and HTML code above give a layout that is displaced as in the image below.

![An images showing all the CSS Box models, that is, content, margin, border and margin](./assets/Box%20Model%20CSS.png)

In summary these are the CSS Box Models we are talking about:

![Summary of CSS Box Models displaying the margin, border, padding and content](./assets/Box%20Model%20Summary.png)
