***Review***

**Images**
-PNG8
-PNG24
-JPEG/JPG
-SVG
-GIF

**HTML**
<!doctype html>
<html>
	<head>
		<title></title>
		<script><script>
		<link>
		<style></style>
	</head>
	<body>
		<p>
		</p>
	</body>
<html>

**notes**
do not put commas in values.

block VS inline
-block
	container:
	<p>
>> the quick brown fox jumped over the moon. the quick brown fox jumped over the moon. the quick brown fox jumped over the moon. the quick brown fox jumped over the moon. the quick brown fox jumped over the moon. the quick brown fox jumped over the moon. the quick brown fox jumped over the moon. 
	</p>
-inline

p {
	width: 300px;
}
.callout {
	font-size: 20px;
}

<p> today <span class="callout"> only $100 <span> now </p>

span won't work inline
<width>
<height>
<i>
<strong>
padding

p {
	width: 300px;
}
p.callout {
	font-size: 20px;
	bg-color: red;
	width: 400px;
	padding: 10px;
}

<p> homerun</p>
<p class="callout"> strikeout </p>

<p class="callout"> strikeout </p> 
> uses the p.callout for width. If p.callout does not specify a width, then it uses the default for p.
> 

<p>	Look
		<i>At
		Me
</p>
<p>
	hello
</p>

At me will be italized, nothing after.

superscript = sup
subscript = sub

<link> font-family or stylesheet
<img class="monster">

block elements
<ul>
<ol>

<ul>
	<li></li>
	<li></li>
</ul>

- item one
- item two
- item three

<ol>
	<li></li>
	<li></li>
	<li></li>
</ol>

1. item one
2. item two
3. item three

ul.name {
	display: (block);
				(inline);
				(table);
}


ul {
	display: block;	
}
<ul>
	<li></li>
</ul>
<ul>
	<li></li>
	<li></li>
	<li></li>
</ul>

block
_______		
|		|
_______
_______
|-----|
_______
_______
|-----|
_______

inline
_______ 	_______ 	_______
|		|	|		|	|		|
_______ 	_______ 	_______


inline styles win out over block styles

float:
	

z-index:

