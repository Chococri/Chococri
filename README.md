<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Práctica diseño menú</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <nav>
        <ul>
            <li><a href="#" class="Logotipo"> Logo </a></li>
        </ul>
        <ul>
            <div>
        <li><a href="secciones/Portafolio.html"> Portafolio </a></li>
        <li><a href="secciones/Productos.html"> Productos </a></li>
        <li><a href="secciones/Envíos.html"> Envíos </a></li>
        <li><a href="secciones/Acerca_de.html"> Acerca de </a></li>
        <li><a href="secciones/Contacto.html"> Contacto </a></li>
            </div>
            <div>
                <li><a href="#">Registrarse</a></li>
                <li><a href="#" class="login">Iniciar sesión</a></li>
            </div>
        </ul>
    </nav>
</body>
</html>

nav ul div li .login {
    background: #f006b6;
    border-radius: 16px;
    color: #ffffff;
    display: flex;
    padding: 16px 48px;
}
