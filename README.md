<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rosas Amarillas para mi Reyna</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffea00;
        }

        #rose {
            font-size: 30px;
            color: red;
            animation: roseAnimation 2s infinite;
        }

        @keyframes roseAnimation {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }

        #message {
            font-size: 20px;
            margin-top: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div id="rose">&#127801;</div>
    <div id="message">Usted nunca será espectadora mi Reyna I &lt;3 R</div>

    <script>
        // JavaScript no es necesario para esta animación estática, pero puedes usarlo para interactividad adicional si lo deseas.
    </script>
</body>
</html>
