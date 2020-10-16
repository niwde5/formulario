# formulario
esta es la practica de la maqueta una página web estática con formulario de registro, a la cual deberá implementar estilos aplicando herencia y agrupación de selectores

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width,initial-scale=1.0">
	<link href="https://fonts.googleapis.com/css?family=lato:400,900"rel=stylesheet">
	<link rel "stylesheet" href=".//css/reset.css">
	<link rel="stylesheet" href=".//css/main.css">
	<title>Formulario</title>
</head>
<body>

	<div class="container">
		<div class="form_top">
			<h2>Formulario<span>Registro</span></h2>
		</div>
		<form class="form_reg"action="">
			<input class="input" type="text" placeholder=&#128100;Nombre" required autofocus>
			 <input class="input" type="email" placeholder=&#9993;Email" required>
			<input class="input" type="tel" placeholder=&#128222;Telefono" required>
			<input class="input" type="text" placeholder=&#8962;Direccion" required>
		<div class="btn_form">
			<input class="btn_submit" type="submit" value="REGISTRAR">
			<input class="btn_reset" type="reset" value="LIMPIAR">
		</div>
		</form>
	</div>
</body>
</html>
