<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registro de Usuário</title>
    <style>
        body {
            background-color: #007BFF; /* Cor de fundo azul */
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: white;
        }

        .form-container {
            background-color: #ffffff;
            color: #000;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px;
        }

        .form-container h1 {
            text-align: center;
            color: #007BFF;
        }

        label {
            font-size: 16px;
            margin-bottom: 8px;
            display: block;
        }

        input[type="text"], input[type="email"], input[type="tel"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        button {
            width: 100%;
            padding: 12px;
            background-color: #000; /* Cor do botão preto */
            color: #fff;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #333;
        }
    </style>
</head>
<body>

    <div class="form-container">
        <h1>Registro de Usuário</h1>
        <form action="#" method="POST">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>

            <label for="telefone">Número de Telefone:</label>
            <input type="tel" id="telefone" name="telefone" required>

            <button type="submit">Registrar</button>
        </form>
    </div>

</body>
</html>
