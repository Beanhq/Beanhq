<html>
	<body>
		<nav class="menuCSS3">
		<ul>
			<li><a href="#">Inicio</a></li>
			<li><a href="#">Empleados</a>
				<ul>
					<li><a href="#">Juan</a></li>
					<li><a href="#">Paco</a></li>
					<li><a href="#">Ramón</a></li>
					<li><a href="#">María</a></li>
				</ul>
			</li>
			<li><a href="#">FAQ</a></li>
			<li><a href="#">Contacto</a>
				<ul>
					<li><a href="#">Email</a></li>
					<li><a href="#">Mapa</a></li>
				</ul>

			</li>
		</ul>
	</nav>
.menuCSS3 ul {
		display: flex;
		padding: 0;
		margin: 0;
		list-style: none;
	}
	.menuCSS3 a {
		display: block;
		padding: 2em;
		background-color: #F9B53C;
		text-decoration: none;
		color: #191C26;
	}
	.menuCSS3 a:hover {
		background-color: #CC673B;
	}
	.menuCSS3 ul li ul {
		display: none;
	}
	.menuCSS3 ul li a:hover + ul, .menuCSS3 ul li ul:hover {
		display: block;
	}
	</body>
	</html>
