<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Día de la Mujer</title>
    <style>
        body {
            text-align: center;
            background-color: pink;
            font-family: Arial, sans-serif;
        }
        #mensaje {
            font-size: 24px;
            margin-top: 50px;
        }
        #entradaClave {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>🌸 Feliz Día de la Mujer para ti de Matías 🌸</h1>
    <input type="text" id="clave" placeholder="Ingresa la clave">
    <button onclick="verificarClave()">Enviar</button>
    <p id="mensaje"></p>
    <script>
        function verificarClave() {
            var clave = document.getElementById("clave").value;
            var mensaje = document.getElementById("mensaje");
            
            if (clave === "0987") {
                document.body.style.backgroundColor = "pink";
                mensaje.innerText = "No hay nada";
            } else if (clave === "1234") {
                mensaje.innerText = "La leyenda cuenta que el Leatherface se estaba masturbando cuando se le cayó su motosierra encima de su polla y se la cortó. Muy enojado, salió con su motosierra y dijo que si él no tenía polla, nadie tendría polla y empezó a cortar pollas";
            } else if (clave === "0623") {
                mensaje.innerText = "¡Felicidades! Es la clave correcta. Feliz día, que la pases muy bien y que no te lancen un elefante bomba con jetpack y una ametralladora";
            } else {
                mensaje.innerText = "Clave incorrecta";
            }
        }
    </script>
</body>
</html>
