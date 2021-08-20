body{
	font-family: 'Roboto', sans-serif;
	color: #333;
}
a:link, a:visited, a:active{
	color: #E9967A;
	text-decoration: none;
}
a:hover{
	text-transform: uppercase;
}
.linha{
	width: 960px;
	margin: 0 auto;
	overflow: auto;
	padding: 5px 0;
}
.coluna{
	padding: 0 10px;
	float: left;
}
.col1{
	width: 60px;
}
.col2{
	width: 140px;
}
.col3{
	width: 220px;
}
.col4{
	width: 300px;
}
.col5  {
 width: 380px;
 float: right;
}
.col6{
	width: 460px;
}
.col7{
	width: 540px;
}
.col8{
	width: 620px;
}
.col9{
	width: 700px;
}
.col10{
	width: 780px;
}
.col11{
	width: 860px;
}
.col12{
	width: 940px;
}
/*estilos reutilizáveis*/
.sem-padding{
	padding: 0 !important;
}
.sem-margin{
	margin: 0 !important;
}
h1, h2, h3, h4, h5, h6{
	font-weight: 500;
	margin: 15px 0 10 0px;
}
ul li, ol li{
	margin-bottom: 5px;
}
ul.inline li, ol.inline li{
display: inline;
margin-right: 15px;
}
ul.inline li:last-child, ol.inline li:last-child{
margin-right: 0px;
}
ul.sem-marcador, ol.sem-marcador{
	list-style: none;
}
a.botao, input.botao{
	background: #FFE4C4;
	padding: 5px 5px 10px 10px;
	border-radius: 3px;
	color: #E9967A;
	cursor: pointer;
	margin: 5px 5px 0 0;
	display: inline-block;
	border: none;
}
a.botao:hover, input.botao:hover{
	background: #FFDAB9;
	text-decoration: none;
}
img{
	max-width: 100%;
	height: auto;
}
/*layout do site*/
.header{
	background: #FFE4C4;
}
h1.logo{
	display: inline;
	font-weight: 700;
	color:#E9967A;
	letter-spacing: -3px;
}
.conteudo-extra{
	background: #FFFAF0;
}
.footer{
	
	padding: 20 px 0;
	text-align: center;
	font-weight: 100;
}
.menu{
	text-transform: lowercase;
	text-align: right;
	margin-top: 25px;
}
.menu li a{
	padding: 5px 10px;
	border-radius: 3px;
}
.menu li a:hover{
	text-decoration: none;
	background: #FFE4C4;
	color:#E9967A;
}
ul.noticias li{
clear: both;
display: block;
overflow: hidden;
margin-bottom: 20px;
}
ul.noticias li img{
	width: 70px;
	height: auto;
	margin-right: 10px;
	float: left;
}
ul.noticias li h4{
	margin: -2px 0 5px 0;
	font-weight: 500;
}
ul.noticias li p{
	margin: 5px 0;
	font-weight: 300;
}
ul.noticias li p a{
	font-weight: 500;
}
.contato label{
	display: block;
	font-size: 20px;
	font-weight: 300;
}
.contato input, .contato textarea{
	display:block;
	margin-bottom: 20px;
	padding: 5px 2%;
	width: 90%;
}
form input[type="radio"] {
	display: inline;
	font-size: 20px;
	font-weight: 300;
	width: 20px;
}
.contato textarea{
	height: 150px;
}
.contato input.botao{
	width: auto;
}
