<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scaits - Boas Vindas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #121212;
            color: #ffffff;
        }

        .welcome-container {
            text-align: center;
            background-color: #1f1f1f;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }

        h1 {
            margin-bottom: 20px;
            color: #1DB954;
        }

        input {
            display: block;
            margin: 10px auto;
            padding: 10px;
            width: 80%;
            max-width: 300px;
            border: none;
            border-radius: 5px;
            outline: none;
        }

        button {
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #1DB954;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #17a04d;
        }
    </style>
</head>
<body>
    <div class="welcome-container">
        <h1>Bem-vindo ao Scaits</h1>
        <p>Crie seu cadastro para começar</p>
        <form action="contatos.html" method="GET">
            <input type="text" placeholder="Seu Nome" required>
            <input type="number" placeholder="Código Ex: 259" required>
            <button type="submit">Cadastrar</button>
        </form>
    </div>
</body>
</html>


