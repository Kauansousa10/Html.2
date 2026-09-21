
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Meu Blog</title>

    <style>
        body {
            font-family: Arial;
            background: #eee;
        }

        .formulario {
            max-width: 500px;
            margin: 30px auto;
            padding: 20px;
            background: white;
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .linha {
            display: flex;
            justify-content: space-between;
            gap: 10px;
        }

        .campo {
            display: flex;
            flex-direction: column;
            flex: 1;
        }

        input, select {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button {
            background: blue;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background: darkblue;
        }
    </style>
</head>

<body>

    <div class="formulario">
        <h2>Inscreva-se no Blog</h2>

        <form>
            <div class="linha">
                <div class="campo">
                    <label>Nome:</label>
                    <input type="text">
                </div>

                <div class="campo">
                    <label>E-mail:</label>
                    <input type="email">
                </div>
            </div>

            <label>Categoria:</label>
            <select>
                <option>Escolha uma categoria</option>
                <option>Tecnologia</option>
                <option>Educação</option>
            </select>

            <button type="submit">Enviar</button>
        </form>
    </div>

</body>
</html>

