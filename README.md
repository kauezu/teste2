<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jogo de Pergunta</title>
</head>
<body>
    <h1>Qual seu filme favorito?</h1>
    <p>Responda à pergunta!</p>

    <script>
        let resposta = prompt("me diz ai, qual seu filme favorito?").toLowerCase();

        if (resposta === "homem aranha 3") {
            alert("Meus parabéns! Otimo filme");
        } else if (resposta === "não sei") {
            alert("Sabe de nada hein 😡");
        } else {
            alert("Credo, que mal gosto voce tem!.");
        }
    </script>
      <a href="https://www.seufilme.org/">filme</a>
</body>
</html>
