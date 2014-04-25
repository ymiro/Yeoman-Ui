---
tags:
- Emmet
- tutorial
- html
- css
permalink: /content/emmet-tutorial/
title: Introducing Emmet!  
created: 1398453017
layout: post
---

##### Did you ever wanted to create an “instant” html and css ?
If you answered “yes” then you are in the perfect place to meet the ultimate tool that will enhance your productivity and save you a lot of time when coding.
Some of you may know it as “Zen coding” and for quite some time (2012) it’s known as Emmet.

Emmet is a plugin for a text editor which greatly improves HTML & CSS workflow.
The idea behind it is to instantly expand simple abbreviations into complex code snippet.
The creator of Emmet is Sergey Chikuyonok.
It’s available for many popular text editors such as: Sublime text, Phpstrom, Eclipse, Aptana, TextMate, Coda, Nodepad++ and many more.

For those who don’t know what an abbreviation is ?
Abbreviation It’s a shortened form of a word or phrase. Usually, but not always, it consists of a letter or group of letters taken from the word or phrase.
Emmet use these abbreviations to parse them in runtime and transform them into structured code block, HTML, CSS, XSL syntax.
This tutorial will mainly review the abbreviations of the html and a little bit of the css.
for the complete list of available abbreviations use the official cheet sheet.
Let’s move on to the examples and let the cool part begin!

this abbreviation:
```
div#wrapper>div.box+ul#navigation>li*5>a{Item $}
```
will be transformed into:
```html
<div id="wrapper">
  <div class="box"></div>
  <ul id="navigation">
    <li><a href="">Item 1</a></li>
    <li><a href="">Item 2</a></li>
    <li><a href="">Item 3</a></li>
    <li><a href="">Item 4</a></li>
    <li><a href="">Item 5</a></li>
  </ul>
</div>
```
