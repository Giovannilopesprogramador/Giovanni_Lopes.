# Giovanni_Lopes.
portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Giovanni Lopes</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link para seu arquivo CSS (opcional) -->
</head>
<body>
    <header>
        <h1>Giovanni Lopes</h1>
        <p>Desenvolvedor JavaScript em busca de oportunidades</p>
    </header>

    <section id="about">
        <h2>Sobre Mim</h2>
        <p>Sou um entusiasta do desenvolvimento JavaScript com uma forte paixão por aprender e contribuir em equipes de desenvolvimento. Estou animado para me juntar a uma equipe talentosa e crescer como desenvolvedor.</p>
    </section>

    <section id="skills">
        <h2>Habilidades Técnicas</h2>
        <ul>
            <li>JavaScript (ES6+)</li>
            <li>HTML5 / CSS3</li>
            <li>React</li>
            <li>Node.js</li>
            <li>Git / GitHub</li>
            <li>Trabalho em equipe</li>
            <li>Resolução de problemas</li>
            <li>Comunicação eficaz</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contato</h2>
        <p>E-mail: <a href="mailto:giolozbr@gmail.com">giolozbr@gmail.com</a></p>
        <!-- Formulário de Contato  -->
        <form action="processar_formulario.php" method="POST">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>

            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

            <button type="submit">Enviar Mensagem</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Giovanni Lopes. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
