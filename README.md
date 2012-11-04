#Code Guidelines
===============

##HTML

###Doctype

Использовать правильное определение Doctype в соответствии с выбранным стандартом.

#### HTML5

	<!DOCTYPE html>

#### HTML 4.01 Strict, Transitional, Frameset

	<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
 
	<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">

	<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">

#### XHTML 1.0 Strict, Transitional, Frameset

	<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">

	<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">

	<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">

##CSS

###Общие рекомендации

1. Писать валидный код, по стандартам [W3C](http://www.w3.org/TR/). Для проверки пользоваться [валидатором](http://jigsaw.w3.org/css-validator/).
2. Не использовать CSS-хаки для задания стилей под определённую версию браузера
3. Писать стили в первую очередь для браузеров, которые работают по стандартам. Затем фиксить в остальных

###Порядок сортировки свойств
	
	/* POSITIONING */	position:relative;	top:0;	left:0;	display:block;	float:left;	clear:both;	overflow:hidden;	/* BOX MODEL */	margin:0 10px;	padding:10px 0;	width:100px;	height:100px;
	/* BLOCKS STYLES */	border:1px solid #000; 	background:#fff url() 0 0 no-repeat; 	/* PARAGRAPH STYLES */	vertical-align:top;	text-align:center;	line-height:1.4em;	text-indent:1em;	list-style:none;
		/* FONT STYLES */	font:bold 1em Arial;	color:#069;	
	/* OTHER */	cursor:pointer;
