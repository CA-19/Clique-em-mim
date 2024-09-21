<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pergunta importante</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        button {
            font-size: 18px;
            padding: 10px 20px;
            margin: 10px;
        }
    </style>
</head>
<body>
    <h1>Me dá um beijo?</h1>
    <button id="yesButton">Sim</button>
    <button id="noButton">Não</button>
    <p id="response"></p>

    <script>
        const yesButton = document.getElementById("yesButton");
        const noButton = document.getElementById("noButton");
        const response = document.getElementById("response");

        yesButton.onclick = function() {
            response.textContent = "Hmmm tá querendo né?";
        };

        noButton.onmouseover = function() {
            noButton.textContent = "Sim";
        };

        noButton.onmouseout = function() {
            noButton.textContent = "Não";
        };
 noButton.onclick = function() {
            response.textContent = "Hmmm tá querendo né?";
        };
    </script>
</body>
</html>
