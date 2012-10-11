#Code Guidelines
===============

##HTML


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
