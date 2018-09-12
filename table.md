- What is CSS

- CSS in files

- Classes and IDs

- Divs

- Floating

- Positioning

- Margins

- Padding

- Borders

main css rules

border

in order to understand how to use rule `border` we need to undertand this 3 css rules
`border-width`:  width of border
`border-style`: style of border line. can be different, but usually we use only `solid`
`border-color`: color of border. we can have different colors, you can use names like `black, green, red`
but better to use HEX #ffffff, #000000 or RGB version rbg(255, 255, 0); if you work with design provided from designer, usually you'll use HEX version.


`border` is a shorthand of this 3 rules. first value related to witdh, second to style, third to color

You can also use borders for different sides of block. usually not used, but we'll cover it there quickly.
```
border-top: 1px solid blue;
border-bottom: 1px solid red;
border-left: 2px solid yellow;
border-right: 3px solid green;
```

border-radius:

help to change curve of corners
so if you want to have more rounded block, you'll need to increase the % of this corners




- Fonts

We'll not touch a lot about including fonts into HTML markup.
If you want to learn more, i advice you to read this articles.
it'll cover including custom fonts, different types of files, few approaches for connecting fonts and use them.
We'll include only a free google Fonts

we will go to google fonts website, choose Lato
include a different variants of this font, like light, bold, italic version
copy a generated link and paste this link into head part of our HTML page.


in order to inclide this font to our css rules, we'll add a `font-family` with this option.




- Styling text


we use a text color
we adjust fonts of our text


- Aligning text

- Images
IMG is a tag for displaying images
<img src="path to image" alt="">
ALT is not a required attribute, but for passing syntax validation is important to pass data
alt text will be displayed when you hover to this image and


- Styling links

Links is one of the majob things in web
link can be not just a text, with underline of it.
we can have a block elements, that was wrapped inside the A tag, image, etc.

simple link have this syntax
a href="www.google.com" target="blank">Visit Google Search website</a>

href is a place for link
it can be a inner page of website, like if we have a www.website.com, and go to www.website.com/blog ->
we can use "/blog"
target help to change logic of opening this link. so if you want to be redirected after clicking on the link, you can use this ---->
if you want to open that link into a new browser tab you should use this `target="blank"`  




you can include a different things inside the link tag
<a><img></a>

- Lists
there 2 types of lists numbered and unnumbered
not used frequently now, because we have extended number of elements to operate
<ul>
<li> item </li>
</ul>

<ol>
<li> item </li>
</ol>

basic styles are :


xxxxx


- Table

main items of table header, body, footer, table rows, table cells

header have th
footer have xxx
body have tbody, tr, xxx

you can combine cells, but right now it's not used a lot, because we

we can change a current looks a and feel of elements

we can also use a pseudo elements like ::odd ::even for this pseudo

we can also use a hover effect, in order to show where our mouse pointer is


- Pseudo classes
::after
you can apply some rules that will change after the element
::before
you can apply some rules that will change before the element
::odd
so all elements like 1,3,5,7... will follow to this rule
::even
so all elements like 2,4,6,8... will follow to this rule
::hover
used for links, in order to change it reaction for hovering mouse into it
::visited
if link was visited it can change
::focus


maybe css3 gradients
