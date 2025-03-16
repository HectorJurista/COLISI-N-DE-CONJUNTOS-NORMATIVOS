# COLISIÓN-DE-CONJUNTOS-NORMATIVOS
VENTANA PARA EXPLORAR LA COLISIÓN DE LOS CONJUNTOS NORMATIVOS
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El problema de colisión entre conjuntos normativos</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        #magnifying-glass {
            width: 200px;
            height: 200px;
            border: 2px solid #333;
            border-radius: 50%;
            position: relative;
            cursor: pointer;
            background-image: url('image.png');
            background-size: cover;
            background-position: center;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        #magnifying-glass::before {
            content: '';
            position: absolute;
            top: 10px;
            left: 10px;
            width: calc(100% - 20px);
            height: calc(100% - 20px);
            border-radius: 50%;
            border: 1px solid rgba(0, 0, 0, 0.2);
        }

        #handle {
            position: absolute;
            bottom: -15px;
            right: -15px;
            width: 40px;
            height: 40px;
            background-color: #333;
            border-radius: 50%;
        }

        h1 {
            margin-top: 20px;
            text-align: center;
        }
        
        #magnifying-glass a {
            text-decoration: none;
            color: white;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>El problema de colisión entre conjuntos normativos</h1>
    <div id="magnifying-glass">
        <a href="#">Explorar</a>
        <div id="handle"></div>
    </div>
</body>
</html>
