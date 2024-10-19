<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Contacto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 500px;
            margin: 20px auto;
            padding: 0 20px;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        input, textarea {
            margin-bottom: 10px;
            padding: 8px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h2>Formulario de Contacto</h2>
    <form action="https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox">
        <input type="text" name="nombre" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu email" required>
        <textarea name="mensaje" placeholder="Tu mensaje" required></textarea>
        <input type="submit" value="Enviar">
    </form>
</body>
</html>
