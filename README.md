<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colégio Naval - Blog do Dia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #003366; /* Cor de fundo */
            background-image: url('images.jpeg'); /* Caminho da imagem de fundo */
            background-size: cover; /* Faz a imagem cobrir todo o cabeçalho */
            background-position: center; /* Centraliza a imagem */
            color: #fff;
            padding: 20px;
            text-align: center;
            position: relative;
        }
        .logo {
            max-width: 150px;
            position: absolute;
            top: 10px;
            left: 10px;
        }
        .container {
            max-width: 1000px;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #003366;
        }
        nav {
            margin: 10px 0;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
        }
        footer {
            background-color: #003366;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .blog-post {
            margin-bottom: 20px;
            padding-bottom: 20px;
            border-bottom: 1px solid #ccc;
        }
        @media (max-width: 600px) {
            .container {
                margin: 10px;
                padding: 10px;
            }
            .logo {
                max-width: 100px;
                top: 5px;
                left: 5px;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="imagens/colegio-naval.jpg" alt="Logo Colégio Naval" class="logo">
        <h1>Colégio Naval - Blog do Dia</h1>
        <nav>
            <ul>
                <li><a href="#destaque">Destaque</a></li>
                <li><a href="#blog">Blog do Dia</a></li>
                <li><a href="#local">Local em Destaque</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <section id="destaque">
            <h2>Destaque Paraibano</h2>
            <p>
                Jovem da cidade de Campina Grande, Paraíba, aos 17 anos, foi aprovado no Colégio Naval, ficando em 4º lugar no Brasil, com uma nota de 9,7. 
                Estudante de escola pública, Carlos Daniel estudava mais de 12 horas por dia, muitas vezes utilizando apenas o celular, para alcançar essa conquista. 
                Sua dedicação o levou a se tornar o mais novo integrante do Colégio Naval.
            </p>
        </section>

        <section class="blog-post" id="blog">
            <h2>Blog do Dia</h2>
            <p>Hoje vamos falar sobre o sucesso e a dedicação que levam à aprovação no Colégio Naval. Carlos Daniel compartilha suas dicas de estudo e estratégias para quem deseja seguir o mesmo caminho, mostrando que é possível conquistar grandes feitos com determinação.</p>
            <h3>Dicas de Estudo de Carlos Daniel</h3>
            <ul>
                <li>Estude por mais de 12 horas diárias.</li>
                <li>Utilize recursos online e aplicativos de estudo.</li>
                <li>Organize seu tempo de forma eficaz.</li>
            </ul>
        </section>

        <section id="local">
            <h2>Lugar em Destaque na Paraíba</h2>
            <p>Explore Campina Grande, conhecida como a "Rainha da Borborema", um importante centro cultural e tecnológico do estado.</p>
            <img src="imagens/campina-grande.jpg" alt="Campina Grande" style="width:100%; height:auto;">
        </section>
    </div>

    <footer>
        <p>Todos os direitos reservados para colégionaval.org.br | Contato: contato@colégionaval.org.br</p>
        <p>Siga-nos: <a href="https://facebook.com/collegionaval">Facebook</a> | <a href="https://twitter.com/collegionaval">Twitter</a></p>
    </footer>
</body>
</html>
