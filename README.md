# HTML-CSS

Código do index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Online</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bem-vindo a Hash & Tash!</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Produtos</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="produtos">
            <h2>Nossos Produtos</h2>
            <div class="produto">
                <h3>Produto 1</h3>
                <p>Descrição do produto 1.</p>
                <span>R$ 99,99</span>
                <button>Adicionar ao Carrinho</button>
            </div>
            <div class="produto">
                <h3>Produto 2</h3>
                <p>Descrição do produto 2.</p>
                <span>R$ 79,99</span>
                <button>Adicionar ao Carrinho</button>
            </div>
            <!-- Adicione mais produtos conforme necessário -->
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Loja Online. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
Código do styles.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
}

.produtos {
    padding: 20px;
}

.produto {
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 10px;
    margin-bottom: 20px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
