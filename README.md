<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monkey Jurista - Consultoria Jurídica</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Consultoria</a></li>
                <li><a href="#">Agendamento</a></li>
                <li><a href="#">Login</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>Consultoria Jurídica de Qualidade</h1>
            <p>Receba orientação jurídica personalizada e eficiente.</p>
            <a href="#consultar" class="btn">Agendar Consulta</a>
        </section>
        <section id="consultar" class="consulta">
            <h2>Consulta Jurídica</h2>
            <form action="/consultar" method="POST">
                <input type="text" name="nome" placeholder="Seu nome" required>
                <input type="email" name="email" placeholder="Seu e-mail" required>
                <textarea name="mensagem" placeholder="Descreva seu problema jurídico" required></textarea>
                <button type="submit" class="btn">Enviar Consulta</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Monkey Jurista - Todos os direitos reservados</p>
    </footer>
</body>
</html>
