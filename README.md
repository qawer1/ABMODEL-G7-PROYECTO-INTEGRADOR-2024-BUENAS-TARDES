<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iniciar Sesión</title>
    <link rel="stylesheet" href="Styles.css">
</head>
<body>
    <div class="login-container">
        <div class="login-box">
            <h2>Iniciar Sesión</h2>
            <form action="Login.aspx" method="post">
                <div class="textbox">
                    <input type="text" name="username" placeholder="Usuario" required>
                </div>
                <div class="textbox">
                    <input type="password" name="password" placeholder="Contraseña" required>
                </div>
                <button type="submit" class="btn">Iniciar Sesión</button>
            </form>
            <p>¿No tienes cuenta? <a href="Register.aspx">Regístrate</a></p>
        </div>
        <div class="login-logo">
            <img src="logo.png" alt="Logo" class="logo">
        </div>
    </div>
</body>
</html>
