# Sistematizacao-PDW-2024.1
Sistematização de Programação e Desenvolvimento Web. Projeto 01 - Uma landing page estática apresentando as principais informações da clínica, bem como seus principais serviços.

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clínica Asa Sul</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #f0f0f0;
            padding: 20px;
            text-align: center;
        }

        .logo img {
            max-width: 150px;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-left: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #333;
            font-size: 18px;
        }

        nav ul li a:hover {
            color: #007bff;
        }

        section#servicos {
            padding: 50px 0;
            background-color: #fff;
            text-align: center;
        }

        .servico {
            margin-bottom: 30px;
        }

        .servico h3 {
            color: #007bff;
        }

        .servico p {
            color: #555;
        }

        section#contato {
            background-color: #f0f0f0;
            padding: 50px 0;
            text-align: center;
        }

        form {
            max-width: 600px;
            margin: 0 auto;
        }

        label, input, textarea {
            display: block;
            margin-bottom: 20px;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
        }

        button {
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #0056b3;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        .redes-sociais a {
            color: #fff;
            margin: 0 10px;
        }

        .redes-sociais a:hover {
            color: #007bff;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Clínica Asa Sul">
        </div>
        <nav>
            <ul>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="servicos">
            <h2>Nossos Serviços</h2>
        <div class="servico">
            <h3><a href="#consultas" target="_blank">Consultas</a></h3>
        </div>
        <div class="servico">
            <h3><a href="exames" target="_blank">Exames</a></h3>
        </div>
        <div class="servico">
            <h3><a href="fisioterapia" target="_blank">Fisioterapia</a></h3>
        </div>
        <div class="servico">
            <h3><a href= "pediatria" target="_blank">Pediatria</a></h3>
        </div>
        <div class="servico">
            <h3><a href= "tratamento de lesões" target="_blank">Tratamento de Lesões</a></h3>
        </div>
        <div class="servico">
            <h3><a href= "cirurgias">Cirurgias</a></h3>
        </div>
        <!-- Adicione mais serviços conforme necessário -->
    </section>

    <footer>
        <div class="endereco">
            <p>Endereço: XXXX Sul, Bloco AX, Ed. XXXXXXX, Número XXX - Asa Sul, Brasília, DF</p>
        </div>
        <div class="redes-sociais">
            <a href="https://www.facebook.com/" target="_blank">Facebook</a>
            
            <a href="https://www.instagram.com/" target="_blank">Instagram</a>
        
        </div>
    </footer>
</body>
</html>
