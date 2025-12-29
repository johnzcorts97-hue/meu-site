
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Minha Loja Online</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Minha Loja</h1>
    <nav>
        <a href="#produtos">Produtos</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section class="banner">
    <h2>Venda online com qualidade e confiança</h2>
    <p>Os melhores produtos para você</p>
</section>

<section id="produtos" class="produtos">
    <h2>Nossos Produtos</h2>

    <div class="card">
        <h3>Produto 1</h3>
        <p>Descrição breve do produto.</p>
        <a href="https://seulink.com" target="_blank">Comprar</a>
    </div>

    <div class="card">
        <h3>Produto 2</h3>
        <p>Descrição breve do produto.</p>
        <a href="https://seulink.com" target="_blank">Comprar</a>
    </div>

    <div class="card">
        <h3>Produto 3</h3>
        <p>Descrição breve do produto.</p>
        <a href="https://seulink.com" target="_blank">Comprar</a>
    </div>
</section>

<section id="sobre" class="sobre">
    <h2>Sobre a Loja</h2>
    <p>
        Somos uma loja focada em oferecer produtos de qualidade,
        com segurança e confiança para nossos clientes.
    </p>
</section>

<section id="contato" class="contato">
    <h2>Contato</h2>
    <p>Email: johnzcorts97@gmail.com</p>
    <p>WhatsApp (47) 992656376</p>
</section>

<footer>
    <p>© 2025 - Minha Loja. Todos os direitos reservados.</p>
</footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #111;
    color: #fff;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav a {
    color: #fff;
    margin-left: 20px;
    text-decoration: none;
    font-weight: bold;
}

header nav a:hover {
    color: #00aaff;
}

.banner {
    background: linear-gradient(to right, #111, #333);
    color: #fff;
    text-align: center;
    padding: 80px 20px;
}

.produtos {
    padding: 40px;
    text-align: center;
}

.produtos h2 {
    margin-bottom: 30px;
}

.card {
    background: #fff;
    padding: 20px;
    margin: 15px;
    display: inline-block;
    width: 250px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.card a {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 15px;
    background-color: #111;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

.card a:hover {
    background-color: #00aaff;
}

.sobre, .contato {
    padding: 40px;
    background-color: #fff;
    text-align: center;
    margin-top: 20px;
}

footer {
    background-color: #111;
    color: #fff;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}
