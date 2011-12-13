review:

block element and inline elements

HI

block elements:
identifying tags

<div>
<p>
<h1>

can control for block elements: background, font, color, line-height, height, width, margin, padding

________________________
| ======= ====== ======|
| ======= ====== ======|
| ======= ====== ======|
| ======= ====== ======|
| ======= ====== ======|
|             _______  |
|             |_____|  |
|                      |
________________________

e.g.

<div class="==">

	<span class="==">===</span>

	<div class="box">==</div>

</div>

inline elements:
<strong>
<i>
<span>

Won't support the following characteristics
margin
padding
height
width

because of hardbreaks, inlines don't support certain elements.

If a class isn't defined, then the stylesheet doesn't apple

<div class="box">
	<div class="box1">==
	<p>
		<span class="color">===
	
		</span>
	</p>
	</div>
</div>

e.g.
<div class="btn color"></div>

nesting styles, the second one will win out, so color of the color class will win out.

.btn {
color: red;
}

.color {
color: blue;
}


block and inline elements
with tags <div>
<div>
<span>
<p>
<strong>
<i>


body {
	font-size: 100%;
}


a href
can be used as a block element, but more likely it'll be used as an inline 
link - just an unvisited link
hover - when your mouse is over the link
focus - clicked
active - when you're on the page
visited - when you've visited the page

a.boy:link

letter-spacing
word-spacing

font: 10px/20px, arial;