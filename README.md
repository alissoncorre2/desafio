<html>
<head>
<title>Untitled Document</title>
<style link rel="stylesheet" type="text/css" href="style.css.css">
@charset "utf-8";

div.gallery {
  border: 1px solid #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
}

* {
  box-sizing: border-box;
}

.responsive {
  padding: 0 6px;
  float: left;
  width: 24.99999%;
}

@media only screen and (max-width: 700px) {
  .responsive {
    width: 49.99999%;
    margin: 6px 0;
  }
}

@media only screen and (max-width: 500px) {
  .responsive {
    width: 100%;
  }
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}







.container {
	float:left;
  position: relative;
  width: 20%;
}

.image {
  opacity: 1;
  display: block;
  width: 10%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.container:hover .image {
  opacity: 0.3;
}

.container:hover .middle {
  opacity: 1;
}

.text {
  background-color: #4CAF50;
  color: white;
  font-size: 16px;
  padding: 16px 22px;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;;
}

li {
  float: left;
}

li a {
  display: block;
  color: #000000;
  text-align: center;
  padding: 16px;
  text-decoration: none;
}

	.cabecalho{
	width:1280px;
	margin:0 auto 0 auto;
	color:#000000;
	background-color: #F90;
	text-decoration: none;	
	text-align:center;
	text-height:auto;
		}
	.cabecalho2{
		width:1280px;
	margin:0 auto 0 auto;
		padding-bottom: 100px;
		background-color: #FBFBFB;
		}
	.corpo{
		padding-bottom:3%;
		width:1280px;
	margin:0 auto 0 auto;
		padding-top: 0;
		background-color:#FBFBFB;
		font:"Comic Sans MS", cursive;
		text-align:center;
		}
		.corpo1{
			whidth: 80%;
			background-color:#FBFBFB;
		/*	float:left;  */
			padding-left: 29%;
			
		}		
		.banner{
		width:1280px;
		padding-left:20%;
		padding-right:20%;
		margin:0 auto 0 auto;
		background-color:#FBFBFB;
		text-align:center;
		}
		.banner2{
	width:1280px;
	height:450px;
	margin:0 auto 0 auto;
	color:#000000;
	text-align:center;
		}
	.rodape{
		
		font-family:"Times New Roman", Times, serif;
		width:1280px;
		margin:0 auto 0 auto;
		padding-top: 0;
		background-color:#FBFBFB;
		text-align:center;
		}
		.rodape2{
		font-family:"Times New Roman", Times, serif;
		width:1280px;
		/*height:300px;*/
		margin:0 auto 0 auto;
		padding-top: 0;
		background-color:#FBFBFB;
		text-align:center;
		}

.alinhamento1{
	padding-left:5%;
	padding-top:10px;		
	float:left;}
	.alinhamento2{
		padding-top:20px;	
		padding-left: 30%;	
	float:left}
.alinhamento3{
	display: block;
		color:#000000;
		text-decoration:none;
		padding-top:10px;
		padding-left: 25%;	
	float:left;}
	.alinhamento4{
		font-family:"Comic Sans MS", cursive;
		font-size:12px;
		padding-left:15%;
	float:left;
	}
	.alinhamento5{
		width:800px;
		float:left;
		padding-left:100px;
		height:110PX;
		}
		.alinhamento6{
		width:400px;
		margin:0 auto 0 auto;
		float: left;
		padding-left:10%;
		}
		
		.alinhamento7{
		width:500px;
		float: left;
		padding-left:0%;
		}
		
		.alinhamento8{
		width:400px;
		float: left;
		padding-left:0%;
		}
		.alinhamento9{
		width:300px;
		float: left;
		padding-left:0%;
		padding-bottom:%;
		}
		.alinhamento10{
		width:230pxpx;
		margin:0 auto 0 auto;
		float: left;
		padding-left:20%;
		background:#p00;
		}
		.alinhamento11{
		width:230px;
		margin:0 auto 0 auto;
		float: left;
		padding-left:20%;
		background:#z50;
		}
.svg-icon path,
.svg-icon polygon,
.svg-icon rect {
  fill: #4691f6;
}
.svg-icon {
  width: 1em;
  height: 1em;
}
.svg-icon circle {
  stroke: #4691f6;
  stroke-width: 1;
}

a:link {
  color: #000000 ;
  background-color: transparent;
  text-decoration: none;
}
a:visited {
  color: #000000;
  background-color: transparent;
  text-decoration: none;
}
a:hover {
  color: #000000;
  background-color: transparent;
  text-decoration: underline;
}
a:active {
  color: #999 ;
  background-color: transparent;
  text-decoration: underline;
}/* CSS Document */


</style>

</head>
<body bgcolor="#FBFBFB">

<div class="cabecalho"><font  color="#333333" face="Comic Sans MS"><i> Outono está chegando...</i></font>
<font color="#333333" face="Comic Sans MS">TODAS AS NOVIDADES AQUI</font>
<u><a href="#">Novidade para o rosto</a></u>
<u><a href="#">Novidade para o corpo</a></u>
                        </div>
<div class="cabecalho2">

 <div class="alinhamento1">
 	<form action="" method="get">
    <label for="pesquisar"><svg class="svg-icon" viewBox="0 0 20 20">
							<path d="M18.125,15.804l-4.038-4.037c0.675-1.079,1.012-2.308,1.01-3.534C15.089,4.62,12.199,1.75,8.584,1.75C4.815,1.75,1.982,4.726,2,8.286c0.021,3.577,2.908,6.549,6.578,6.549c1.241,0,2.417-0.347,3.44-0.985l4.032,4.026c0.167,0.166,0.43,0.166,0.596,0l1.479-1.478C18.292,16.234,18.292,15.968,18.125,15.804 M8.578,13.99c-3.198,0-5.716-2.593-5.733-5.71c-0.017-3.084,2.438-5.686,5.74-5.686c3.197,0,5.625,2.493,5.64,5.624C14.242,11.548,11.621,13.99,8.578,13.99 M16.349,16.981l-3.637-3.635c0.131-0.11,0.721-0.695,0.876-0.884l3.642,3.639L16.349,16.981z"></path>
						</svg></label>
                <input name="pesquisar" type="text" id="pesquisar" value="pesquisa">
                        </form></div>
    <div class="alinhamento2">         <center> <font size="6" face="Verdana, Geneva, sans-serif" color="#FFCC99"> Vnda </font> </center>      </div>                    
<div class="alinhamento3">  <a href="#">Login/Minha conta</a><svg class="svg-icon" viewBox="0 0 20 20">
	<path d="M17.638,6.181h-3.844C13.581,4.273,11.963,2.786,10,2.786c-1.962,0-3.581,1.487-3.793,3.395H2.362c-0.233,0-0.424,0.191-0.424,0.424v10.184c0,0.232,0.191,0.424,0.424,0.424h15.276c0.234,0,0.425-0.191,0.425-0.424V6.605C18.062,6.372,17.872,6.181,17.638,6.181 M13.395,9.151c0.234,0,0.425,0.191,0.425,0.424S13.629,10,13.395,10c-0.232,0-0.424-0.191-0.424-0.424S13.162,9.151,13.395,9.151 M10,3.635c1.493,0,2.729,1.109,2.936,2.546H7.064C7.271,4.744,8.506,3.635,10,3.635 M6.605,9.151c0.233,0,0.424,0.191,0.424,0.424S6.838,10,6.605,10c-0.233,0-0.424-0.191-0.424-0.424S6.372,9.151,6.605,9.151 M17.214,16.365H2.786V7.029h3.395v1.347C5.687,8.552,5.332,9.021,5.332,9.575c0,0.703,0.571,1.273,1.273,1.273c0.702,0,1.273-0.57,1.273-1.273c0-0.554-0.354-1.023-0.849-1.199V7.029h5.941v1.347c-0.495,0.176-0.849,0.645-0.849,1.199c0,0.703,0.57,1.273,1.272,1.273s1.273-0.57,1.273-1.273c0-0.554-0.354-1.023-0.849-1.199V7.029h3.395V16.365z"></path>
						</svg>
                        </div>
 <div class="alinhamento4">
     <ul>
      <li><a href="#">Novidade</a></li>
      <li><a href="#">Perfumaria</a></li>
      <li><a href="#">Rosto</a></li>
      <li><a href="#">Corpo e Banho</a></li>
      <li><a href="#">Home</a></li>
      <li><a href="#">Naturais & Orgânicos</a></li>
      <li><a href="#">Presentes</a></li>
      <li><a href="#">Promoções</a></li>
      <li><a href="#">Linhas</a></li>
      
    </ul>
    </div>
</div>

    </div>
                        
<div class="corpo">
<center>
  <img src="img/img1.jpg" style="width:90%">
</center><br>
<font face="Comic Sans MS, cursive"><p align="center">Destaque da semana</p></font>
<hr width="87%" color="#CCCCCC" align="center" >

<div class="corpo1">
<div class="container">
  <img src="img/only-good-bergamota-e-lirio-57.jpg" alt="Avatar" class="image" style="width:100%">
  <p>Every Day Shampoo</p>
  <p>R$ 30,00</p>
  <p>Ou 10x de 3,00</p>
  <div class="middle">
    <div class="text">Ref:101214 Comprar</div>
  </div>
</div>


<div class="container">
  <img src="img/only-good-flores-e-caramelo-59.jpg" alt="Avatar" class="image" style="width:100%">
  <p>Supernatural Conditioner</p>
  <p>R$ 20,00</p>
  <p>Ou 10x de 2,00</p>
  <div class="middle">
    <div class="text">Ref:181219 Comprar</div>
  </div>
</div>


<div class="container">
  <img src="img/only-good-pimenta-e-melao-61.jpg" alt="Avatar" class="image" style="width:100%">
  <p>Pure Dry Shampoo</p>
  <p>R$ 39,90</p>
  <p>Ou 10x de 3,99</p>
  <div class="middle">
    <div class="text">Ref:231221 Comprar</div>    
  </div>
</div>
</div> 
<p align="center"><img src="img/img2.png" style="width:90%" ></p>
</div>


<div class="banner">
    
    <div class="responsive">
  <div class="gallery"><a href="https://playabeauty.com/blogs/playajournal/playa-hair-sunday-riley" target="_blank"><img src="img/banner1.jpg" alt="Cinque Terre" width="350" height="300">
    <div class="desc">Nightly Ritual: Playa x Sunday Riley x Lunya</div></a>
  </div>
</div>


<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="https://playabeauty.com/blogs/playajournal/get-real-the-difference-between-organic-and-natural-beauty-products">
      <img src="img/banner2.jpg" alt="Forest" width="350" height="300">
    
    <div class="desc">The Real Difference Between Organic and Natural Beauty Products</div></a>
  </div>
</div>

<div class="responsive">
  <div class="gallery"><a target="_blank" href="https://playabeauty.com/blogs/playajournal/kristen-shaw"><img src="img/banner3.jpg" alt="Northern Lights" width="350" height="300">
    <div class="desc">Kristen Shaw, Owner of Cabin Salon, Venice</div></a>
  </div>
</div>


<div class="clearfix"></div>

<div style="padding:6px;">
</div>
    
</div>
    
<div class=" banner2"> <a href="https://www.instagram.com/playa/" target="_blank"><img src="img/img3.png" style="width:90%"></a>
</div>


<div class="rodape"><br>
    <hr align="center" width="90%">
    <div class=" alinhamento5">
<p align="left"><strong>Stay in the Know!	</strong></p>
<p align="left">sign up for emails to get the scoop on new arrivals, special!</p>
<p align="left">sales and more.</p>
</div>


<div class="alinhamento6">
  <p>EMAIL ADDRES* </p>
  <form name="form1" method="post" action="">
    <label>
      <input type="text" name="textfield" id="textfield">
      <input type="button" name="textfield" id="textfield" value="SUBMIT">
    </label>
  </form>
  <p>&nbsp;</p>
  
</div>
<hr align="center" width="90%"><br>	
</div>
    </div>
    
<div class="rodape2">
   <div class="alinhamento7"> 
   <svg class="svg-icon" viewBox="0 0 20 20">
							<path d="M18.303,4.742l-1.454-1.455c-0.171-0.171-0.475-0.171-0.646,0l-3.061,3.064H2.019c-0.251,0-0.457,0.205-0.457,0.456v9.578c0,0.251,0.206,0.456,0.457,0.456h13.683c0.252,0,0.457-0.205,0.457-0.456V7.533l2.144-2.146C18.481,5.208,18.483,4.917,18.303,4.742 M15.258,15.929H2.476V7.263h9.754L9.695,9.792c-0.057,0.057-0.101,0.13-0.119,0.212L9.18,11.36h-3.98c-0.251,0-0.457,0.205-0.457,0.456c0,0.253,0.205,0.456,0.457,0.456h4.336c0.023,0,0.899,0.02,1.498-0.127c0.312-0.077,0.55-0.137,0.55-0.137c0.08-0.018,0.155-0.059,0.212-0.118l3.463-3.443V15.929z M11.241,11.156l-1.078,0.267l0.267-1.076l6.097-6.091l0.808,0.808L11.241,11.156z"></path>
						</svg>
                      fale com a gente<p>
  
  <svg class="svg-icon" viewBox="0 0 20 20">
						  <path d="M10,1.375c-3.17,0-5.75,2.548-5.75,5.682c0,6.685,5.259,11.276,5.483,11.469c0.152,0.132,0.382,0.132,0.534,0c0.224-0.193,5.481-4.784,5.483-11.469C15.75,3.923,13.171,1.375,10,1.375 M10,17.653c-1.064-1.024-4.929-5.127-4.929-10.596c0-2.68,2.212-4.861,4.929-4.861s4.929,2.181,4.929,4.861C14.927,12.518,11.063,16.627,10,17.653 M10,3.839c-1.815,0-3.286,1.47-3.286,3.286s1.47,3.286,3.286,3.286s3.286-1.47,3.286-3.286S11.815,3.839,10,3.839 M10,9.589c-1.359,0-2.464-1.105-2.464-2.464S8.641,4.661,10,4.661s2.464,1.105,2.464,2.464S11.359,9.589,10,9.589"></path>
					  </svg>
                      encontre um consultor </div>
  <div class="alinhamento8"> 
                      <ul style="text-align:left">
      <li><a href="#">Ajuda</a></li>
      <li><a href="#">Sobre nós</a></li>
      <li><a href="#">Serviços</a></li>
      </ul>
      <ul style="text-align:left">
      <li><a href="#">Folde</a></li>
      <li><a href="#">História</a></li>
      <li><a href="#">Maravilhas</a></li>
      </ul>
      <ul style="text-align:left">
      <li><a href="#">Tecno</a></li>
      <li><a href="#">Variedades</a></li>
      <li><a href="#">Assuntos</a></li>      
    </ul>
    </div style="text-align:left"> </div>
  <div class="alinhamento9">
   FOLLOW US<p></p>
    <svg class="svg-icon" viewBox="0 0 20 20">
							<path fill="none" d="M18.258,3.266c-0.693,0.405-1.46,0.698-2.277,0.857c-0.653-0.686-1.586-1.115-2.618-1.115c-1.98,0-3.586,1.581-3.586,3.53c0,0.276,0.031,0.545,0.092,0.805C6.888,7.195,4.245,5.79,2.476,3.654C2.167,4.176,1.99,4.781,1.99,5.429c0,1.224,0.633,2.305,1.596,2.938C2.999,8.349,2.445,8.19,1.961,7.925C1.96,7.94,1.96,7.954,1.96,7.97c0,1.71,1.237,3.138,2.877,3.462c-0.301,0.08-0.617,0.123-0.945,0.123c-0.23,0-0.456-0.021-0.674-0.062c0.456,1.402,1.781,2.422,3.35,2.451c-1.228,0.947-2.773,1.512-4.454,1.512c-0.291,0-0.575-0.016-0.855-0.049c1.588,1,3.473,1.586,5.498,1.586c6.598,0,10.205-5.379,10.205-10.045c0-0.153-0.003-0.305-0.01-0.456c0.7-0.499,1.308-1.12,1.789-1.827c-0.644,0.28-1.334,0.469-2.06,0.555C17.422,4.782,17.99,4.091,18.258,3.266"></path></svg>
                            
                        <svg class="svg-icon" viewBox="0 0 20 20">
							<path fill="none" d="M14.52,2.469H5.482c-1.664,0-3.013,1.349-3.013,3.013v9.038c0,1.662,1.349,3.012,3.013,3.012h9.038c1.662,0,3.012-1.35,3.012-3.012V5.482C17.531,3.818,16.182,2.469,14.52,2.469 M13.012,4.729h2.26v2.259h-2.26V4.729z M10,6.988c1.664,0,3.012,1.349,3.012,3.012c0,1.664-1.348,3.013-3.012,3.013c-1.664,0-3.012-1.349-3.012-3.013C6.988,8.336,8.336,6.988,10,6.988 M16.025,14.52c0,0.831-0.676,1.506-1.506,1.506H5.482c-0.831,0-1.507-0.675-1.507-1.506V9.247h1.583C5.516,9.494,5.482,9.743,5.482,10c0,2.497,2.023,4.52,4.518,4.52c2.494,0,4.52-2.022,4.52-4.52c0-0.257-0.035-0.506-0.076-0.753h1.582V14.52z"></path>
						</svg>
						<svg class="svg-icon" viewBox="0 0 20 20">
							<path fill="none" d="M11.344,5.71c0-0.73,0.074-1.122,1.199-1.122h1.502V1.871h-2.404c-2.886,0-3.903,1.36-3.903,3.646v1.765h-1.8V10h1.8v8.128h3.601V10h2.403l0.32-2.718h-2.724L11.344,5.71z"></path>
						</svg>
                        <svg class="svg-icon" viewBox="0 0 20 20">
							<path fill="none" d="M9.797,2.214C9.466,2.256,9.134,2.297,8.802,2.338C8.178,2.493,7.498,2.64,6.993,2.935C5.646,3.723,4.712,4.643,4.087,6.139C3.985,6.381,3.982,6.615,3.909,6.884c-0.48,1.744,0.37,3.548,1.402,4.173c0.198,0.119,0.649,0.332,0.815,0.049c0.092-0.156,0.071-0.364,0.128-0.546c0.037-0.12,0.154-0.347,0.127-0.496c-0.046-0.255-0.319-0.416-0.434-0.62C5.715,9.027,5.703,8.658,5.59,8.101c0.009-0.075,0.017-0.149,0.026-0.224C5.65,7.254,5.755,6.805,5.948,6.362c0.564-1.301,1.47-2.025,2.931-2.458c0.327-0.097,1.25-0.252,1.734-0.149c0.289,0.05,0.577,0.099,0.866,0.149c1.048,0.33,1.811,0.938,2.218,1.888c0.256,0.591,0.33,1.725,0.154,2.483c-0.085,0.36-0.072,0.667-0.179,0.993c-0.397,1.206-0.979,2.323-2.295,2.633c-0.868,0.205-1.519-0.324-1.733-0.869c-0.06-0.151-0.161-0.418-0.101-0.671c0.229-0.978,0.56-1.854,0.815-2.831c0.243-0.931-0.218-1.665-0.943-1.837C8.513,5.478,7.816,6.312,7.579,6.858C7.39,7.292,7.276,8.093,7.426,8.672c0.047,0.183,0.269,0.674,0.23,0.844c-0.174,0.755-0.372,1.568-0.587,2.31c-0.223,0.771-0.344,1.562-0.56,2.311c-0.1,0.342-0.096,0.709-0.179,1.066v0.521c-0.075,0.33-0.019,0.916,0.051,1.242c0.045,0.209-0.027,0.467,0.076,0.621c0.002,0.111,0.017,0.135,0.052,0.199c0.319-0.01,0.758-0.848,0.917-1.094c0.304-0.467,0.584-0.967,0.816-1.514c0.208-0.494,0.241-1.039,0.408-1.566c0.12-0.379,0.292-0.824,0.331-1.24h0.025c0.066,0.229,0.306,0.395,0.485,0.52c0.56,0.4,1.525,0.77,2.573,0.523c1.188-0.281,2.133-0.838,2.755-1.664c0.457-0.609,0.804-1.313,1.07-2.112c0.131-0.392,0.158-0.826,0.256-1.241c0.241-1.043-0.082-2.298-0.384-2.981C14.847,3.35,12.902,2.17,9.797,2.214"></path>
						</svg> </div>
                         </div>
                         <div class="rodape2">
                         <hr align="center" width="90%">
                         <div class=" alinhamento10">
                         
                         
                         <ul>
      <li><a href="https://www.spotify.com/br/legal/privacy-policy/">Privaci Policy</a></li>
      <li><a href="https://www.spotify.com/br/legal/end-user-agreement/">Terms</a></li>
      <li><a href="https://www.spotify.com/br/legal/copyright-policy/">CA Notice</a></li>
      <li><a href="https://www.spotify.com/br/legal/privacy-policy/">Accessibility</a></li>
      <li><a href="https://www.urbn.com/home">URBN.com</a></li>
    </ul>
</div></div>
</body>
</html>
