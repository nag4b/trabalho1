<!DOCTYPE html>
<html lang="pt-Br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Bem-vindo!</h1>
    <p>Estamos felizes em recebê-lo em nossa página.</p>
    
    <form id="nomeForm">
        <label for="nome">Por favor, digite seu nome:</label>
        <input type="text" id="nome" name="nome" required>
        <button type="submit">Enviar</button>
    </form>

    <p id="saudacao"></p>

    <script>
        document.getElementById('nomeForm').addEventListener('submit', function(e) {
            e.preventDefault();
            var nome = document.getElementById('nome').value;
            document.getElementById('saudacao').textContent = 'Olá, ' + nome + '! É um prazer te conhecer.';
        });
    </script>
</body>
</html>
