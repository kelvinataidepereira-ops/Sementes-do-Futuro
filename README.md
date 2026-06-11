# Sementes-do-Futuro
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Organização</title>
    
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="card">
        <h1>Olá, Mundo!</h1>
        <p>Este é um exemplo de código com arquivos separados.</p>
        <button id="meuBotao">Clique Aqui</button>
    </div>

    <script src="script.js"></script>
</body>
</html>/* Estilização da página */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f2f5;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

/* Estilização do card */
.card {
    background-color: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

/* Estilização do botão */
button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #0056b3;
}// Seleciona o botão pelo ID
const botao = document.getElementById('meuBotao');

// Adiciona um evento de clique ao botão
botao.addEventListener('click', () => {
    alert('Você clicou no botão! O JavaScript externo está funcionando.');
});
