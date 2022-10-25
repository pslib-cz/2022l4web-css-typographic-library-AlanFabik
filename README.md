# Typography CSS library
**Author:** [Alan Fabik](https://github.com/AlanFabik)
## Description
Utopia.css is a free typography library, which you can implement to your HTML code. Simply download the file and link via stylesheet to your code. The CSS file is fully responsive and works on every browser. Enjoy!
## Demo site
Link to **[demo](https://htmlpreview.github.io/?https://github.com/pslib-cz/2022l4web-css-typographic-library-AlanFabik/blob/master/docs/index.html)** site for preview.
## Signpost
1. [Download](#Download)
2. [Font](#Font)
3. [Colors](#Colors)
4. [Headings](#Headings)
5. [Text](#Text)
6. [Photos](#Photos)
7. [Buttons](#Buttons)
8. [Lists](#Lists)
9. [Tables](#Tables)
## Download
1. Download utopia.css **[docs/library](https://github.com/pslib-cz/2022l4web-css-typographic-library-AlanFabik/tree/master/docs/library)**
2. Add CSS file to Visual Studio Code
3. Link CSS file via stylesheet
```html
<link href="utopia.css" rel="stylesheet">
```
## Font
Utopia.css is using linked Google font. You can change the font, simply remove predefined font and paste yours.
```html
/* IMPORTED FONTS */
@import url('https://fonts.googleapis.com/css2?family=Bitter:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');

/* FONT LINK */
body{
    font-family: 'Bitter', serif;
}
```
## Colors
The predefined colors can be changed by `:root` selector.
## Heanings
You can use headings from `<h1>` to `<h6>`.
## Text
A standart paragraph is defined by `<p>` tag. There are also:
* `<b>` for bold text
* `<a>` for hypertext link
## Photos
To use image template, modify your wrapper as `<div class="photos>`
## Buttons
To add a button, add `class="button"` to `<a>` tag or `<button>` tag.
There are two types of predefined buttons:
* Black version
`<a class="button button-black">`
* White version
`<a class="button button-white">`
## Lists
You can also use HTML lists
* Ordered list `<ul class="num">`
```html
<ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ol>
```
* Unordered list `<ol class="point">`
```html
<ul>
    <li>Text 1</li>
    <li>Text 2</li>
    <li>Text 3</li>
</ul>
```
## Tables
You can use predefined table with standart `<table>` tag.
