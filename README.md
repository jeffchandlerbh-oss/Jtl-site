<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JTL Engenharia e Perícias</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    color: #333;
}

header {
    background: #0c1c2c;
    color: white;
    padding: 20px;
    text-align: center;
}

nav {
    background: #132f4c;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background: url('https://images.unsplash.com/photo-1503387762-592deb58ef4e') no-repeat center;
    background-size: cover;
    color: white;
    padding: 120px 20px;
    text-align: center;
}

.hero h1 {
    font-size: 42px;
}

.btn {
    background: #f39c12;
    padding: 12px 25px;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    margin: 10px;
    display: inline-block;
}

section {
    padding: 50px 20px;
    max-width: 1100px;
    margin: auto;
}

h2 {
    color: #0c1c2c;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    background: #f4f4f4;
    padding: 20px;
    border-radius: 8px;
}

footer {
    background: #0c1c2c;
    color: white;
    text-align: center;
    padding: 20px;
}

</style>
</head>

<body>

<header>
    <h1>JTL Engenharia e Perícias</h1>
    <p>Construindo com excelência. Avaliando com precisão.</p>
</header>

<nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#portfolio">Portfólio</a>
    <a href="#contato">Contato</a>
</nav>

<section class="hero">
    <h1>Especialistas em Engenharia, Construção e Perícias</h1>
    <p>Atendimento em obras, avaliações e laudos técnicos</p>
    <a class="btn" href="#contato">Solicitar Orçamento</a>
    <a class="btn" href="#contato">Agendar Perícia</a>
</section>

<section id="sobre">
    <h2>Sobre Nós</h2>
    <p>
    A JTL Engenharia e Perícias atua no desenvolvimento de obras residenciais,
    comerciais e industriais, oferecendo soluções completas em construção civil,
    avaliações e perícias técnicas.
    </p>
</section>

<section id="servicos">
    <h2>Serviços</h2>

    <div class="grid">

        <div class="card">
            <h3>Construção Civil</h3>
            <p>Residências de alto padrão, galpões e reformas.</p>
        </div>

        <div class="card">
            <h3>Perícias Técnicas</h3>
            <p>Laudos judiciais e extrajudiciais com precisão técnica.</p>
        </div>

        <div class="card">
            <h3>Avaliações Imobiliárias</h3>
            <p>Métodos normatizados conforme ABNT.</p>
        </div>

        <div class="card">
            <h3>Patologia do Concreto</h3>
            <p>Diagnóstico e recuperação estrutural.</p>
        </div>

    </div>
</section>

<section id="portfolio">
    <h2>Portfólio</h2>

    <div class="grid">
        <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e" width="100%">
        <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab" width="100%">
        <img src="https://images.unsplash.com/photo-1509395176047-4a66953fd231" width="100%">
    </div>
</section>

<section id="contato">
    <h2>Contato</h2>

    <p><strong>Local:</strong> Brumadinho - MG</p>
    <p><strong>Telefone:</strong> (XX) XXXXX-XXXX</p>
    <p><strong>Email:</strong> contato@jtlengenharia.com.br</p>

    <form>
        <input type="text" placeholder="Nome" required><br><br>
        <input type="email" placeholder="Email" required><br><br>
        <textarea placeholder="Mensagem" required></textarea><br><br>
        <button class="btn">Enviar</button>
    </form>
</section>

<footer>
    <p>© 2026 JTL Engenharia e Perícias - Todos os direitos reservados</p>
</footer>

</body>
</html>
