<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Floche:3, ¿Puedo ser tu SanValentin?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffcccb;
            color: #fff;
            text-align: center;
            padding: 50px;
        }
        h1 {
            font-size: 36px;
            color: #e60000;
        }
        h2 {
            font-size: 28px;
            color: #ff6699;
        }
        .form-container {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 10px;
            display: inline-block;
            margin-top: 30px;
        }
        input, button {
            padding: 10px;
            margin: 10px;
            font-size: 16px;
            border-radius: 5px;
        }
        button {
            background-color: #ff6699;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #e60000;
        }
        .footer-message {
            margin-top: 40px;
            font-size: 22px;
            color: #e60000;
        }
        .cat-sticker {
            margin-top: 20px;
            width: 150px;
        }
    </style>
</head>
<body>

    <h1>¡Holiwi, Mi Niña Peshosha!</h1>
    <h2>¿Me Dejas ser tu San valentin :3?</h2>

    <div class="form-container">
        <p>Déjame saber si te gustaría pasar este Día de San Valentín juntos.</p>
        <form action="mailto:tu-email@ejemplo.com" method="POST" enctype="multipart/form-data">
            <input type="text" name="nombre" placeholder="Tu nombre" required><br>
            <textarea name="mensaje" rows="4" cols="50" placeholder="Escribe tu mensaje aquí..." required></textarea><br>
            <button type="submit">¡Sí, quiero ser tu San Valentín!</button>
</body>
</html>
