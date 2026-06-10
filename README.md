# Sementes-do-Futuro
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AgroShop - Produtos para sua Fazenda</title>
    <style>
        /* Estilos Gerais */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f7f9f6;
            color: #333;
        }

        /* Cabeçalho */
        header {
            background-color: #1b4332;
            color: white;
            padding: 1rem 2rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.6rem;
            font-weight: bold;
        }

        .carrinho-status {
            background-color: #2d6a4f;
            padding: 8px 15px;
            border-radius: 20px;
            font-weight: bold;
        }

        /* Banner */
        .banner {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1592417817098-8f3d6eb18865?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80') center/cover;
            height: 300px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        .banner h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        /* Vitrine de Produtos */
        .main-container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .titulo-secao {
            color: #1b4332;
            margin-bottom: 25px;
            font-size: 1.8rem;
            border-bottom: 2px solid #d8f3dc;
            padding-bottom: 10px;
        }

        .grid-produtos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .produto-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 8px rgba(0,0,0,0.06);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            border: 1px solid #e9ecef;
        }

        .produto-img {
            height: 200px;
            background-size: cover;
            background-position: center;
        }

        .produto-info {
            padding: 15px;
            text-align: center;
        }

        .produto-nome {
            font-size: 1.1rem;
            color: #2d6a4f;
            margin-bottom: 8px;
            font-weight: 600;
        }

        .produto-preco {
            font-size: 1.3rem;
            color: #1b4332;
            font-weight: bold;
            margin-bottom: 15px;
        }

        .btn-comprar {
            background-color: #52b788;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
            transition: background 0.2s;
        }

        .btn-comprar:hover {
            background-color: #40916c;
        }

        /* Rodapé */
        footer {
            background-color: #1b4332;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 60px;
        }
    </style>
</head>
<body>

    <header>
        <div class="header-container">
            <div class="logo">🌱 AgroShop</div>
            <div class="carrinho-status">🛒 Itens: <span id="contador-carrinho">0</span></div>
        </div>
    </header>

    <section class="banner">
        <h1>Tudo para a sua Produção</h1>
        <p>As melhores ferramentas, sementes e insumos com entrega rápida no campo.</p>
    </section>

    <main class="main-container">
        <h2 class="titulo-secao">Destaques da Semana</h2>
        
        <div class="grid-produtos">
            
            <div class="produto-card">
                <div class="produto-img" style="background-image: url('https://images.unsplash.com/photo-1595681242673-41136952337b?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80');"></div>
                <div class="produto-info">
                    <div class="produto-nome">Enxada de Aço Forjado</div>
                    <div class="produto-preco">R$ 79,90</div>
                    <button class="btn-comprar" onclick="adicionarAoCarrinho()">Adicionar ao Carrinho</button>
                </div>
            </div>

            <div class="produto-card">
                <div class="produto-img" style="background-image: url('https://images.unsplash.com/photo-1530595467537-0b5996c41f2d?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80');"></div>
                <div class="produto-info">
                    <div class="produto-nome">Sementes de Milho Híbrido (1kg)</div>
                    <div class="produto-preco">R$ 45,00</div>
                    <button class="btn-comprar" onclick="adicionarAoCarrinho()">Adicionar ao Carrinho</button>
                </div>
            </div>

            <div class="produto-card">
                <div class="produto-img" style="background-image: url('https://images.unsplash.com/photo-1416879595882-3373a0480b5b?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80');"></div>
                <div class="produto-info">
                    <div class="produto-nome">Regador Plástico Pro 10L</div>
                    <div class="produto-preco">R$ 34,90</div>
                    <button class="btn-comprar" onclick="adicionarAoCarrinho()">Adicionar ao Carrinho</button>
                </div>
            </div>

            <div class="produto-card">
                <div class="produto-img" style="background-image: url('https://images.unsplash.com/photo-1589923188900-85dae523342b?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80');"></div>
                <div class="produto-info">
                    <div class="produto-nome">Luvas de Proteção de Raspa</div>
                    <div class="produto-preco">R$ 19,90</div>
                    <button class="btn-comprar" onclick="adicionarAoCarrinho()">Adicionar ao Carrinho</button>
                </div>
            </div>

        </div>
    </main>

    <footer>
        <p>&copy; 2026 AgroShop - Ferramentas e Insumos Agrícolas</p>
    </footer>

    <script>
        let totalItens = 0;

        function adicionarAoCarrinho() {
            totalItens++;
            document.getElementById('contador-carrinho').innerText = totalItens;
            alert("Produto adicionado ao carrinho com sucesso!");
        }
    </script>

</body>
</html>
