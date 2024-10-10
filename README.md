# Feedback-do-produto-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback de Produto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
        }
        label {
            display: block;
            margin: 10px 0 5px;
        }
        input, textarea, select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Feedback de Produto</h2>
    <form action="#" method="POST">
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="produto">Produto:</label>
        <select id="produto" name="produto" required>
            <option value="">Selecione um produto</option>
            <option value="produto1">Produto 1</option>
            <option value="produto2">Produto 2</option>
            <option value="produto3">Produto 3</option>
        </select>

        <label for="avaliacao">Avaliação:</label>
        <select id="avaliacao" name="avaliacao" required>
            <option value="">Selecione uma avaliação</option>
            <option value="1">1 - Muito Ruim</option>
            <option value="2">2 - Ruim</option>
            <option value="3">3 - Regular</option>
            <option value="4">4 - Bom</option>
            <option value="5">5 - Excelente</option>
        </select>

        <label for="comentario">Comentários:</label>
        <textarea id="comentario" name="comentario" rows="4" required></textarea>

        <button type="submit">Enviar Feedback</button>
    </form>
</div>

</body>
</html>
