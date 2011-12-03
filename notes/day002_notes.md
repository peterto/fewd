12/1/2011

Images types, Basic HTML, file directories

Image types:

Graphics:

JPEG
JPG
-Photoshop keeps the printing elements if you don't save it as web
-stripes down to 72DPI


PNG8 - 256 colors but doesn't support alpha channel
PNG24 - use for logos

GIF

SVG
Scalable vector graphics
-composed of lines instead of pixels
-Full transparency

The "e" in jpeg is just due to server acceptable types

jpeg: lossless compression

javascript supports 100% alpha

You always want 72PPI
Always RGB, never CMYK
Web only supports RGB

Make sure to have your extensions all lowercase, hyphens/underscores, preference to underscores

__HTML__

IMGS
HTML
FONTS
JS
CSS

IMGS

*TAGS*
<HTML>
<IMG SRC="IMG/YO.gif">
</HTML>

relative/absolute paths

*relative*
<IMG SRC="http://yahoo.com/img/nav/...">

*absolute*
<IMG SRC="IMG/NAV/BUTTON1.GIF">

rich emails: use absolute paths

doctypes: HTML5 takes away doctypes
recommends lowercase for everything

<HTML>
	<HEAD>
		<TITLE>
		*Character limit here* keep it short and simple
		</TITLE>
		
		*Use of link or style, linking is prefered*
		<STYLE>
			CSS is here
		</STYLE>

		<LINK rel="" url="*.css">
		<SCRIPT>
		JS
		</SCRIPT>
	</HEAD>
	
	<BODY>
		<DIV class="__">
			Class: 
			ID: 
		</DIV>
		<DIV ID="__">
			Class: 
			ID: 
		</DIV>
		
		*content goes here*
	</BODY>
	<FOOTER>
		*Only needed for HTML5*
	</FOOTER>
</HTML>

**For special characters, you need to use an & at the front.**
& = &amp;
e' = &acutee;
< = &gnu;
" = &quote;
' = '

**Class VS ID**
"#" = ID 
. = Class

.class {
can be used multiple times
}

#id{
can be used once
}

EX for class:
<style>
.big {
}
</style>
<div class="big">

<style>
#small {
}
</style>
<div id="small">

ruleset:
	
#selector {
	declaration (property: value;)
	declaration set (	property: value;
							property: value;
							property: value;
							property: value;)
 
	"ex: margin: 10px;"
	"ex: font-size: 15em;"
	"ex: background: #FFF;"
}

p --> hard break
returns with beginning of the line
br --> soft break
returns but keeps indentation

**p elements**
ex:
p.red {}
<p class="red">

**span element**
span used within other elements, such as p elements

ex:
p {
	color: #000;
}
.red {
	color: #F33;
}

<p>
my name is
	<span class="red">
	slim shady
	</span>
.
</p>

decorators:
<strong>
<i>
<ul>

.red {
	color: #F33;
	font-weight: bold;	
}

ex:
margin: 10px; <-- always need a semi-colon here.
		^
		|
	always needs a colon here.


.bunny {
	margin: 10px;
}

.santa {
	background: red;
}

***fonts***

***web safe fonts***: fonts that are already installed on the users computers.
					
font-family: arial, helvetica, sans-serif;
					^
					|
>> uses this font first if you have it, if not then
it'll use helvetica, then lastly will look for the first sans-serif it finds, then if it doesn't find a sans-serif font, it'll use a serif font.

web fonts:
	@fontface {
		otf: "fonts/br1";
		otf: "fonts/br2";
		otf: "fonts/br3";
		otf: "fonts/br4";
		otf: "fonts/br5";
	}

***JavaScript:***

<head>
	<title>===</title>
	<script>
		function name: {
			property: value;
		}
	</script
</head>

fade.js

*reset.css*
Zeroes out everything on your site for every browser.
Each browser has a predetermined number of settings.

px, pt, em, en

*What's the difference?*
-px, pt are hard values
-pt are relative to each browser
-em, en are relative values
em = en * 2
en = hyphen * 2

em, en is going to scale depending on the size of your browser.


