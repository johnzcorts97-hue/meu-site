/site-vendas
 ├── index.html
 ├── style.css
 └── script.js
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Loja Online</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Minha Loja</h1>
    <p>Os melhores produtos para você</p>
  </header>

  <main class="produtos">
    <div class="produto">
      <img src="https://via.placeholder.com/300" alt="Produto 1">
      <h2>Produto 1</h2>
      <p>Descrição do produto.</p>
      <span>R$ 99,90</span>
      <a href="https://wa.me/5500000000000?text=Quero%20comprar%20o%20Produto%201" target="_blank">
        Comprar
      </a>
    </div>

    <div class="produto">
      <img src="https://via.placeholder.com/300" alt="Produto 2">
      <h2>Produto 2</h2>
      <p>Descrição do produto.</p>
      <span>R$ 149,90</span>
      <a href="https://wa.me/5500000000000?text=Quero%20comprar%20o%20Produto%202" target="_blank">
        Comprar
      </a>
    </div>
  </main>

  <footer>
    <p>© 2025 - Minha Loja</p>
  </footer>

</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: #f4f4f4;
}

header {
  background: #0d6efd;
  color: white;
  padding: 20px;
  text-align: center;
}

.produtos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  padding: 20px;
}

.produto {
  background: white;
  padding: 15px;
  border-radius: 8px;
  text-align: center;
}

.produto img {
  width: 100%;
  border-radius: 5px;
}

.produto h2 {
  margin: 10px 0;
}

.produto span {
  display: block;
  margin: 10px 0;
  font-size: 18px;
  color: green;
}

.produto a {
  display: inline-block;
  padding: 10px 20px;
  background: #25d366;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}

footer {
  text-align: center;
  padding: 15px;
  background: #ddd;
}
console.log("Loja carregada com sucesso!");
