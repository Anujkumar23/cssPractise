# CSS Selector
A CSS selector select the  HTML element(s) that we want to style.
CSS selector "find" the element and then we can select it.

CSS Selector are divided into find category.
1. Simple Selector.
2. Combinator selector
3. Pseudo-Code -selector
4. pseudo element -selector
5. Attribute Selector

# Box Sizing
The CSS box-sixzing allow us to include padding and border in the toal height aand width.

If we use box-sizing :content box then the  width and height will calculate like 
width+heght+padding+border;
And the size of the div will bigger then the actual size because it add padding and border.

If we use box-sizing : border-box; then the padding and border will include in the height and width.


# CSS FONTS
Fonts is used on the text to style and size them .It add value to the text.

# Generic Font Families
We have five generic font families:
1. Serif
2. Sans-serif
3. Monospace
4. Cursive
5. Fantasy

In CSS, we use font-family property to specify the font of  a text.
font-family property should hold several font names to ensure maximum capabilities between browser/operating system.

#  Web Safe Fonts
Web Safe fonts are fonts that are universally installed across all browser and devices.

# FallBack Fonts
There is a chance that a font is not found or is not installed properly.
So it is important to use a Fallback fonts.
In the font-family property,If the first font does not work,the browser will try the next one,and next one.
Always end the list with  generic font family.


# CSS Font Style
The font-style is mostly used to specify italic text.
The property has three value:
1. normal
2. italic
3. oblique


# Font weight 
The font-weight property specifies the weight of the font:
1. normal
2. bold

# Font Varient
The font-varient property specifies whether a text should dispaly in a small -caps font or not.
In small-caps font ,all lowercase letters are converted to uppercase letter but converted  upercase letters appears in smaller font size then the oroginal size.

# CSS Font Size
The font-size property specifies the size of the text.
The font-size value can be an absolute, or relative size.

# Set Font size with Pixel
Setting the text size with pixels will give full control over the text size:

# Set font size with em
With this we can allow user to resiz ethe text.
1 em =16px by default.
The size can be calculated from pixel to em using this formula: pixels/16=em.

# Responsive Font Size
The text size can be set with a vw unit, which means "viewport width".
The text size follow the sizw of browser window.

# The CSS Font Property
It is possible to specify all individual font property in one property.
Font Property in shorten way:
font-style
font-varient
font-weight
font-size/line-height
font-family.


# CSS Display property
The display property is most important CSS property for controlling layout.
It specify how an element is displayed.
Every element has a default display value depending on what type of element it is.

# Block level Element
A block level element start on a new line and take up the full width available.
The <div> element is a block level element.
Example:
<div>
<h1>to <h6>
<p>
<form>
<header>
<footer>
<section>

# Inline Element
An inline element does not start with a new line and only takes up as much width as necessary.
Example:
<span>
<img>
<a>

# Display:none
It is commonly used with js to hide and show element without recreating and deleting them.

# Display:inline -block
If we compare display inline-block with display:inline,with inline-block we can set height/width and top and bottom padding/margin are respected but display inline they are not.

compare to display:block ,The difference is that display:inline block does not add a line break after the element.

# CSS Position Property
The position property specifies the type of positioning method used for an  element.(static,relative,absolute,fixed,sticky).

1.Static :- It is a Default Value. Element render in order,as they appear in the document flow.

2. absolute:-The element is positioned relative to its first positioned(non static) ancestor element.
