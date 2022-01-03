# cascadingstylesheet

https://kazihabiburrahmann.github.io/cascadingstylesheet/

CSS									01 January 2022
2.1
CSS = Cascading Style Sheet. 

2.2
Types of CSS – Internal (Embedded), External, Inline.
style tag is need to do CSS.
style tag is used to css. Style tag must be in front of head tag. Then fix the tag which we want to style
</p> 
<style> 
p{ color: blue; 
   } 
</style>
Color type: Hexa, RGB, RGBA where a is opacity

2.3
Background Color.
font size, height, weight.
CSS units. Ex: px, cm, mm, in, pt, pc.
relative lengths.
em	Relative to the font-size of the element (2em means 2 times the size of the current font) 
ex	Relative to the x-height of the current font (rarely used) 
ch	Relative to the width of the "0" (zero) 
rem	Relative to font-size of the root element 
vw	Relative to 1% of the width of the viewport* 
vh	Relative to 1% of the height of the viewport* 
vmin	Relative to 1% of viewport's* smaller dimension 
vmax	Relative to 1% of viewport's* larger dimension
%	Relative to the parent element

2.4 ID vs Class
Same elements হলে id দিতে হবে এবং style করতে চাইলে css এ # দিতে হবে। এছাড়াও class দিব কয়েকজন কে একই style দিব আর class বুঝাতে css e . দিব।

2.5 A Group Of Elements, Style A Small Portion Of Text 
div is used to made a group. 
Span tag is used to style a portion of text.

2.6 Border, margin
Border = width, solid or dotted or other type, color name.
dotted, dashed, solid, double, groove - Defines a 3D grooved border. The effect depends on the border-color 
value ridge - Defines a 3D ridged border. The effect depends on the border-color value 
inset - Defines a 3D inset border. The effect depends on the border-color value 
outset - Defines a 3D outset border. The effect depends on the border-color value 
none - Defines no border 
hidden - Defines a hidden border

Margin- One value all side, 
               two value - one for top-bottom, another for left-right, 
               three value - one for top middle for left-right last one for bottom. 
               four value – top, right, bottom, left.
               
2.7 Padding, Different Ways To Set Padding, CSS Box Model
Padding is reverse or margin. That means it use on inside. Where margin is used on outside.
For width 50% we must right 
{ width: 50%; 
margin: 0 auto;}
CSS Box Model
Explanation of the different parts of CSS BOX MODEL:
•	Content - The content of the box, where text and images appear
•	Padding - Clears an area around the content. The padding is transparent
•	Border - A border that goes around the padding and content
•	Margin - Clears an area outside the border. The margin is transparent


2.8 Text Align, Display, Inline, Block, Inline-Block
Text type css, Font type css, block element, inline element.
inline element have <span class="a">no margin or padding but</span> allow other elements beside them.  inline-block element have <span class="b">margin or padding and</span> also allow other elements beside. block element have <span class="c">margin or padding and do not</span>  allow other elements beside</p>

2.9 External CSS
Have to make a link in html with external css. Name should be style.css
<link rel="stylesheet" href="css/style.css">

2.10 CSS Module Summary

Summery, Border hw. 
