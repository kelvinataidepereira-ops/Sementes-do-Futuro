# Sementes-do-Futuro
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AgroShop - Produtos para o Campo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">🌾 AgroShop</div>
        <div class="carrinho">
            🛒 Carrinho: <span id="contador-carrinho">0</span> itens
        </div>
    </header>

    <section class="banner">
        <h2>As melhores soluções para a sua lavoura</h2>
        <p>Insumos, ferramentas e tecnologia para o produtor rural.</p>
    </section>

    <main class="vitrine">
        
        <div class="produto-card">
            <div class="produto-img">🌱</div>
            <h3>Semente de Soja Premium</h3>
            <p class="descricao">Alta produtividade e resistência a pragas.</p>
            <p class="preco">R$ 180,00</p>
            <button class="btn-comprar">Adicionar ao Carrinho</button>
        </div>

        <div class="produto-card">
            <div class="produto-img">🚜</div>
            <h3>Insumo Orgânico 20kg</h3>
            <p class="descricao">Fertilizante natural para enriquecimento do solo.</p>
            <p class="preco">R$ 95,00</p>
            <button class="btn-comprar">Adicionar ao Carrinho</button>
        </div>

        <div class="produto-card">
            <div class="produto-img">🔧</div>
            <h3>Kit Ferramentas Agro</h3>
            <p class="descricao">Enxada, podadeira e ferramentas essenciais.</p>
            <p class="preco">R$ 240,00</p>
            <button class="btn-comprar">Adicionar ao Carrinho</button>
        </div>

    </main>

    <footer>
        <p>&copy; 2026 AgroShop - Soluções para o Agronegócio.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>v/* Configurações Gerais */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f6f4;
    color: #333;
}

/* Cabeçalho */
header {
    background-color: #2e6f40; /* Verde Agro */
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

.carrinho {
    background-color: #1e4629;
    padding: 10px 15px;
    border-radius: 20px;
    font-weight: bold;
}

/* Banner */
.banner {
    background-color: #8d6e63; /* Tom de terra */
    color: white;
    text-align: center;
    padding: 40px 20px;
}

.banner h2 {
    margin: 0 0 10px 0;
}

/* Vitrine de Produtos */
.vitrine {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
    padding: 40px 20px;
}

/* Card do Produto */
.produto-card {
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    width: 280px;
    padding: 20px;
    text-align: center;
    transition: transform 0.2s;
}

.produto-card:hover {
    transform: translateY(-5px);
}

.produto-img {
    font-size: 50px;
    margin-bottom: 15px;
}

.produto-card h3 {
    margin: 10px 0;
    color: #2e6f40;
}

.descricao {
    font-size: 14px;
    color: #666;
    height: 40px;
}

.preco {
    font-size: 18px;
    font-weight: bold;
    color: #2e6f40;
    margin: 15px 0;
}

/* Botão de Compra */
.btn-comprar {
    background-color: #ff9800; /* Laranja para destaque */
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold;
    width: 100%;
    transition: background 0.2s;
}

.btn-comprar:hover {/* Configurações Gerais */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f6f4;
    color: #333;
}

/* Cabeçalho */
header {
    background-color: #2e6f40; /* Verde Agro */
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

.carrinho {
    background-color: #1e4629;
    padding: 10px 15px;
    border-radius: 20px;
    font-weight: bold;
}

/* Banner */
.banner {
    background-color: #8d6e63; /* Tom de terra */
    color: white;
    text-align: center;
    padding: 40px 20px;
}

.banner h2 {
    margin: 0 0 10px 0;
}

/* Vitrine de Produtos */
.vitrine {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
    padding: 40px 20px;
}

/* Card do Produto */
.produto-card {
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    width: 280px;
    padding: 20px;
    text-align: center;
    transition: transform 0.2s;
}

.produto-card:hover {
    transform: translateY(-5px);
}

.produto-img {
    font-size: 50px;
    margin-bottom: 15px;
}

.produto-card h3 {
    margin: 10px 0;
    color: #2e6f40;
}

.descricao {
    font-size: 14px;
    color: #666;
    height: 40px;
}

.preco {
    font-size: 18px;
    font-weight: bold;
    color: #2e6f40;
    margin: 15px 0;
}

/* Botão de Compra */
.btn-comprar {
    background-color: #ff9800; /* Laranja para destaque */
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold;
    width: 100%;
    transition: background 0.2s;
}

.btn-comprar:hover {
    background-color: #e68a00;
}

/* Rodapé */
footer {
    background-color: #222;
    color: #aaa;
    text-align: center;
    padding: 15px;
    font-size: 14px;
    margin-top: 20px;
}
    background-color: #e68a00;
}

/* Rodapé */
footer {
    background-color: #222;
    color: #aaa;
    text-align: center;
    padding: 15px;
    font-size: 14px;
    margin-top: 20px;
}
// Cria uma variável para guardar a quantidade de itens no carrinho
let totalItensCarrinho = 0;

// Seleciona o elemento de texto do carrinho pelo ID
const contadorTexto = document.getElementById('contador-carrinho');

// Seleciona TODOS os botões de comprar da página
const botoesComprar = document.querySelectorAll('.btn-comprar');

// Passa por cada botão e adiciona a função de clique
botoesComprar.forEach((botao) => {
    botao.addEventListener('click', () => {
        // Incrementa o contador
        totalItensCarrinho++;
        
        // Atualiza o número que aparece na tela
        contadorTexto.textContent = totalItensCarrinho;
        
        // Mensagem de confirmação (opcional)
        alert('Produto adicionado ao carrinho com sucesso! 🌾');
    });
});
