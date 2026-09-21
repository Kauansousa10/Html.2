
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Blog</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #eeeeee;
        }

        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 10px;
        }

        main {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
        }

        .formulario {
            max-width: 600px;
            margin: auto;
            padding: 25px;
            background-color: white;
            border-radius: 8px;
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .linha {
            display: flex;
            justify-content: space-between;
            gap: 15px;
        }

        .campo {
            display: flex;
            flex-direction: column;
            gap: 5px;
            flex: 1;
        }

        label {
            font-size: 16px;
            font-weight: bold;
        }

        input, select {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
        }

        button {
            background-color: #3498db;
            color: white;
            padding: 12px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #217dbb;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
        }

        @media (max-width: 600px) {
            .linha {
                flex-direction: column;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>Meu Blog</h1>

        <nav>
            <a href="#inicio">Início</a>
            <a href="#sobre">Sobre</a>
            <a href="#inscricao">Inscrição</a>
        </nav>
    </header>

    <main>

        <section id="inicio">
            <h2>Bem-vindo ao Meu Blog!</h2>
            <p>Este é um blog criado para compartilhar informações e conhecimentos.</p>
        </section>

        <section id="sobre">
            <h2>Sobre o Blog</h2>
            <p>Aqui você encontrará conteúdos sobre diversos assuntos.</p>
        </section>

        <section id="inscricao">
            <div class="formulario">

                <h2>Inscreva-se no Blog</h2>

                <form>

                    <div class="linha">

                        <div class="campo">
                            <label for="nome">Nome:</label>
                            <input type="text" id="nome" placeholder="Digite seu nome">
                        </div>

                        <div class="campo">
                            <label for="email">E-mail:</label>
                            <input type="email" id="email" placeholder="Digite seu e-mail">
                        </div>

                    </div>

                    <div class="campo">
                        <label for="categoria">Categoria favorita:</label>

                        <select id="categoria">
                            <option>Escolha uma categoria</option>
                            <option>Tecnologia</option>
                            <option>Educação</option>
                            <option>Esportes</option>
                            <option>Entretenimento</option>
                        </select>
                    </div>

                    <div class="campo">
                        <label for="mensagem">Mensagem:</label>
                        <input type="text" id="mensagem" placeholder="Digite uma mensagem">
                    </div>

                    <button type="submit">Enviar inscrição</button>

                </form>

            </div>
        </section>

    </main>

    <footer>
        <p>Meu Blog - 2026</p>
    </footer>

</body>
</html>
