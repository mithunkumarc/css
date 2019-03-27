.css file
<head>
<link rel="stylesheet" href="styles.css"></link>
</head>


------------
selectors

using tag names as selctor


p {
	color : blue;
}

color : property, value : blue

--------------------------


type selectors 

using tag names

h1{
	color : blue;
}



--------------------
applying css using
class and id attributes

class : mutliple times: begins with .
id : one time : begins with #

---------------


dont use space while defining class style
style1 stype2

style2 considered as second style

space indicate multiple classes



-----------------------
-- combining style

-- 
<h1 class= "style1 style2">outside div</h1>

.style1{
    font-size: 25px;
}

.style2{
    color: darkgreen;
}




-------------

descendent selectors

div h1{
    color : red;
}

p div h2{
}


all h1 inside div get effected


--------------------

group multiple selectors

h1, h2 , h3 {
	color : red;
}


------------------


pseudo class selectors

* pseudo class selectors
 specify a state of element.

* keywords are combined with another
 selector , using a colon

# works only when hovered(state)
a:hover {
	color:black;
}

list of pesudo classes : 
https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes

----------------

links dont inherit style from parent 
tags/selectors


------------
block level

takes entire line
paragraph div h p



inline level

takes space equal to cotent
width = conten


add background color to test inline or block level



-------

use 
display : block
display : inline-block

to change inline default height 
and weight

