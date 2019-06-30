Html / Css
Html: 
div- division. -> header,fotter, content , side content sobi division diyei thakbe..


<b><strong>
<em><i>
<mark>
<del>
<sup>
<sub>

<a> - link

<a href="https://www.google.com" target="_blank">click here </a>

<center> - center font

<ul> - unorder list kono list dakhabena.

<ol> - order list num 1,2,3 dakhabe.


<li> - list.

 Fix – drop down list  a fix use kora jabena.
Selector::#000
<bdo> - lakha dan dik theke porar jonno.

  <abbr title="secondary school certificate"> SSC </abbr>

<q> - qutattion tag

<Blockquote> - dane and bame block kore se jaiga nibe.

<dl>
	<dt>coffe </dt>
	<dd>-black coffe life<dd>
</dl>

<hr> -  horizontal rule..

<pre>  - 


<p> -  font size default 1 em;  Default 100%; default 16px;
		











<div> - middle point kono webpage newoar jonno use korbo.
<svg> - scalable vector graphics.
<iframe> - youtube, all of the website to including in iframe. Tag
<video> <audio> - controls to all video audio.













1.	Webpage er jonno akta – div.
2.	Headerbanner jonno – div.
3.	 Menu – div
4.	 Slider jonno – div
5.	 Maincontent  - div.
6.	 Content title – side title – 2 div.
7.	 Fotter  - div.






attribute:

<href>
<meta charset=”UTF-8”>  - language change korar jonno.

Get – secured noy
POST – secure

<select>
	<option value="volvo">Volvo</option>
</select> - drop down box.


<form action="#">
		
			<h2> Chose your Browser </h2>
			
			<input list="browsers">
		
			<datalist id="browsers">
<option value="Internet Explorer">
<option value="Mozila firefox">
<option value="Google Chrome">

			</datalist>
		
		
		</form>


<p dir="rtl"> This is paragraph</p>
Text show to rtl…






css:

id - #
class - . (dot)
css rest code: margin 0; padding 0;
body{
	font-family:Arial; font-size:14px; line-height:20px; color:#000000;
}

Margin:50px auto, - sob pase 50 px jaiga nibe then majkhane jabe.

display:block; - oi line a vitore se block thakbe then moddhe ashbe.
       overflow:hidden – oi line dukhbena sobi block;

line-height – 20px; - ak line theke r ak line suru hobe..
color:red

font-size:50px; - fontsize baranor jono

list-style:none; - list er (.)gol gulo muse felonor jonno.

Float:left – list gulo horizontal thakbe vertical na theke. R dane sore jabe.


Display:block – oi line a kono kisu dukhbena sobi block.

Padding  - vitore jaiga sore sore niye nai.

border-right : 2px solid #982402  dan pase border thakbe 2 px er jar color o thakbe

text-decoration: none – default underline -- tag delete hoye jabe.


Hover – background a color dile hover pabe.

Float:right –  dan pase jabe.

Margin:20px, auto; - majkhane jaoa.

Upor nise 20px, -  dane bame sore ashbe auto.

Css reset code - *{ margin:0; padding:0}

Padding  –  vitore barbe;

Margin –  baire barbe.

Display:block  – oi line a r kisu dukhbena sobi block.

Line-height – 15px; - r akta new line suru hobe. 
border-right:0;  ( eiter moddhe last-child)  - dan paser border remove hobe.

Float:left – bame sore jave, 
Border-right – 1px solid #fff – dane akta border hobe 1px er and color hobe sada.
ul li a padding-  jototuku padding hobe tototuku jaiga jure link hobe..

ul li  padding – sudhu mattro text ta jure link hobe.

      Ul li a – display block

    Font-weight – normal, bold 100,200,300
    Font-style –   italic, normal, initial
    Font-family -  arial, sens-serif
    Font-variant – small-caps, all-small-caps
    Text-transform -  upper-case
    Text-transform -  lower-case
    Line-height  –  akta line theke ar akta line  er  durrotoo.
 


Margin – margin 4 prokar-  left, right ,top, bottom
Just margin use korle ei 4 dik theke jaiga niye nibe.
R Jodi alada alada use kori tahole alada alada jaiga niye nibe..
Padding – padding 4 prokar – left , right , top , bottom,  tobe etake baluner moton folate hobe..
   background-image:url(happykids.jpg);
  background-size:100px,80px; bamdane 100, upor nise 80px;







Border: 1px solid red
                          Overflow , display property
Overfollow- scroll
Display – none, inline, block;
<span> - display block korle moddhe use kora hoy
Display:none- thakbena kisu content er moddhe.
Display:block- se akai pura block jaiga nibe..
Display:inline – <span> inline tag er maddhome content er maddhome chole jabe.
Float: left , right, none;

 linear and radial Gradiant?
background: linear-gradient(red,green); by default botoom,

background: linear-gradient(to top,red,green);
background: linear-gradient(to right,red,green);
background:radial-gradient(black,white,red);
background:radial-gradient(black 10%,white 20%,red 30%);

 
Cursor:pointer
.mydiv:hover – cursor niye gele hover korbe.
.mydiv:active – cursor niye gele click obostai se active

					Css transform/transitation
transition:background 2s ease; background.  properites change hobe tobe trasitioner moddhe diye.


















Transform :







Transform rotate, scale 









 






   CSS Animation property:       0 1 
Border-radius- 50% 10px;















   CSS Animation property:       0 2  
.mydiv{
	width:150px;
	height:150px;
	background: red;
	border-radius: 50%;
	animation-name:animate;
	animation-duration:3s;
	animation-iteration-count:6;	
}

@keyframes animate{
	
	10%{background:red;}
	20%{background:green; width:300px;}
	50%{background:blue;}
	60%{background:yellow; height:350px;}
	100%{background:black;}
}

 

 

 

   dl – definition list
 <dt> tag -  defines a term/name in a description list.
<dd> - (describes each term/name).
 
<td> - table data
<tr> - table row
				<td>01 </td>
				<td>Java </td>
				<td>Html/Css </td>
				<td>Photoshop </td>
			</tr>

<thead> - table er header. Automatic, bold, cener hishabe ashes.
 
Colspan – akta row  nibe. 2 hole se 2 ta row nibe.
border-collapse: collapse; - table er sob pase border hobe, single border.

Form design
 
 
 
