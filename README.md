<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora</title>
    <link href="https://fonts.googleapis.com/css2?family=Fraunces&display=swap" rel="stylesheet">
    <link href="Estilo.css" rel="stylesheet" />
    <script src="Display.js" type="text/javascript"></script>
    <script src="Calcula.js" type="text/javascript"></script>
    <script src="Index.js" type="text/javascript" defer></script>
</head>
<body>
    <div class="container">
        <div class="calculadora">
            <div class="display">
                <div id="valor-anterior"></div>
                <div id="valor-actual"></div>
            </div>
            <button class="col-2" onclick="display.borrarTodo()">C</button>
            <button onclick="display.borrar()">&larr;</button>
            <button class="operador" value="dividir">%</button>
            <button class="numero">7</button>
            <button class="numero">8</button>
            <button class="numero">9</button>
            <button class="operador" value="multiplicar">X</button>
            <button class="numero">4</button>
            <button class="numero">5</button>
            <button class="numero">6</button>
            <button class="operador" value="restar">-</button>
            <button class="numero">1</button>
            <button class="numero">2</button>
            <button class="numero">3</button>
            <button class="operador" value="sumar">+</button>
            <button class="col-2 numero">0</button>
            <button class="numero">.</button>
            <button class="operador" value="igual">=</button>
        </div>
    </div>
</body>
</html>
