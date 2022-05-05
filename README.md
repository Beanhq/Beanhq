<html>
	<nav id="COLORES">
<ul>
 <li><a href="#">PASTEL</a></li>
 <li><a href="#">GRISES</a></li>
 <li><a href="#">NEGROS</a></li>
 <li><a href="#">FRIOS</a></li>
 <li><a href="#">NEUTROS</a></li>
</ul>
</nav>
<!-- start nav -->
<nav id="menu">
<!-- start menu -->
<ul>
 <li><a href="#">Enlace 1</a></li>
 <li><a href="#">Enlace 2</a>
<!-- start menu desplegable -->
 <ul>
 <li><a href="#">Enlace 2.1</a></li>
 <li><a href="#">Enlace 2.2</a></li>
 <li><a href="#">Enlace 2.3</a></li>
 </ul>
<!-- end menu desplegable -->
 </li>
 <li><a href="#">Enlace 3</a></li>
 <li><a href="#">Enlace 4</a></li>
 <li><a href="#">Enlace 5</a></li>
</ul>
<!-- end menu -->
</nav>
<!-- end nav -->
	/* menu */

#menu ul {
 list-style:none;
 margin:0;
 padding:0;
}

/* items del menu */

#menu ul li {
 background-color:#2e518b;
}

/* enlaces del menu */

#menu ul a {
 display:block;
 color:#fff;
 text-decoration:none;
 font-weight:400;
 font-size:15px;
 padding:10px;
 font-family:"HelveticaNeue", "Helvetica Neue", Helvetica, Arial, sans-serif;
 text-transform:uppercase;
 letter-spacing:1px;
}

/* items del menu */

#menu ul li {
 position:relative;
 float:left;
 margin:0;
 padding:0;
}

/* efecto al pasar el ratón por los items del menu */

#menu ul li:hover {
 background:#5b78a7;
}
	/* menu desplegable */

#menu ul ul {
 display:none;
 position:absolute;
 top:100%;
 left:0;
 background:#eee;
 padding:0;
}

/* items del menu desplegable */

#menu ul ul li {
 float:none;
 width:150px
}

/* enlaces de los items del menu desplegable */

#menu ul ul a {
 line-height:120%;
 padding:10px 15px;
}

/* items del menu desplegable al pasar el ratón */

#menu ul li:hover > ul {
 display:block;
}
	</html>
