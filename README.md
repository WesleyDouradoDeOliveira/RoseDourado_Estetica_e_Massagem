<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rose Dourado Estética e Massagens padrão de spa</title>
    <link rel="stylesheet" href="css/styles.css">
    <style>
        /* Estilos para o tema de spa */
        body {
            background-color: #f0efe9;
            color: #6d4e42;
            font-family: Arial, sans-serif;
        }
        header {
            background-color: #c0a080;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        header img {
            width: 100px;
            height: auto;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }
        nav ul li {
            margin-right: 20px;
            cursor: pointer;
            font-weight: bold;
            color: #6d4e42;
        }
        nav ul li:hover, nav ul li.active-nav {
            color: #ffffff;
        }
        .section {
            display: none;
            padding: 30px;
            text-align: center;
        }
        .active {
            display: block;
        }
        .servicos {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
        }
        .servico-btn {
            background-color: #c0a080;
            color: #fff;
            padding: 15px 30px;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .servico-btn:hover {
            background-color: #a68a60;
        }
        .promo {
            padding: 15px;
            background-color: #fff2e0;
            margin: 15px 0;
            border-radius: 10px;
            text-align: center;
        }
        #carrinho {
            list-style-type: none;
            padding: 0;
            text-align: left;
        }
        .form-container {
            max-width: 400px;
            margin: 0 auto;
            background-color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .form-container input, .form-container select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-container button {
            background-color: #c0a080;
            color: white;
            padding: 10px;
            width: 100%;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .form-container button:hover {
            background-color: #a68a60;
        }
        .historia-container {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 10px;
            margin-top: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .historia-container h3 {
            font-size: 1.8em;
            margin-bottom: 15px;
        }
        .historia-container p {
            font-size: 1.2em;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.jpg" alt="Rose Dourado Estética e Massagens padrão de spa">
        <h1>Rose Dourado Estética e Massagens padrão de spa</h1>
        <nav>
            <ul>
                <li id="homeLink" onclick="showSection('home')">Home</li>
                <li id="massagensLink" onclick="showSection('massagens')">Massagens</li>
                <li id="faciaisLink" onclick="showSection('faciais')">Tratamentos Faciais</li>
                <li id="carrinhoLink" onclick="showSection('carrinho')">Carrinho</li>
                <li id="agendamentoLink" onclick="showSection('agendamento')">Agendamento</li>
                <li id="quemSomosLink" onclick="showSection('quemSomos')">Quem Somos</li>
            </ul>
        </nav>
    </header>

    <!-- Seção Home -->
    <section id="home" class="section active">
        <h2>Bem-vindo à Rose Dourado</h2>
        <p>Experimente o luxo e o relaxamento com nossos serviços de spa e bem-estar.</p>
        <div class="servicos">
            <button class="servico-btn" onclick="showSection('massagens')">Massagens</button>
            <button class="servico-btn" onclick="showSection('faciais')">Tratamentos Faciais</button>
        </div>
        <div class="historia-container">
            <h3>Nossa História</h3>
            <p>A Rose Dourado Estética e Massagens padrão de spa nasceu da paixão por promover bem-estar e qualidade de vida. Fundada em 2018, nossa empresa foi criada com o objetivo de oferecer um refúgio de paz e relaxamento para quem busca cuidar de si e renovar suas energias. Desde o início, nosso propósito foi unir técnicas tradicionais com as mais recentes inovações em estética e massagem, sempre com foco no conforto e satisfação dos nossos clientes.
                
                Nosso compromisso com a excelência nos levou a investir constantemente em capacitação, produtos de alta qualidade e tecnologias de ponta. Hoje, contamos com uma equipe de profissionais experientes e apaixonados pelo que fazem, prontos para oferecer um atendimento personalizado e adaptado às necessidades de cada cliente.
                
                Ao longo dos anos, nos tornamos referência em [serviço ou área de especialidade, como “massoterapia terapêutica” ou “estética facial e corporal”] na região, conquistando a confiança de nossos clientes por meio de uma experiência que vai além do serviço: é uma verdadeira jornada de cuidado e bem-estar.</p>
        </div>
    </section>

    <!-- Seção Quem Somos -->
    <section id="quemSomos" class="section">
        <h3>Quem Somos</h3>
        <p>Na Rose Dourado Estética e Massagens padrão de spa, acreditamos que cuidar do corpo é essencial para manter a mente e o espírito em harmonia. Somos uma clínica de estética e massagem dedicada a oferecer experiências de bem-estar que promovem relaxamento, saúde e autoestima. Nossa equipe é composta por profissionais altamente qualificados e apaixonados por transformar vidas por meio do cuidado pessoal.</p>
        <p>Trabalhamos com um ambiente acolhedor, técnicas avançadas e produtos de qualidade para proporcionar um atendimento que supere as expectativas de nossos clientes. Nosso compromisso é oferecer um serviço personalizado, respeitando as necessidades e preferências de cada pessoa que chega até nós.</p>
        <p>Com uma abordagem que une tradição e inovação, buscamos ser mais do que um simples serviço: queremos criar experiências que renovem o corpo, a mente e o espírito de nossos clientes.</p>
        <button onclick="showSection('home')">Voltar ao Home</button>
    </section>

    <!-- Seção Tratamentos Faciais -->
    <section id="faciais" class="section">
        <h3>Tratamentos Faciais</h3>
        <ul>
            <li>Limpeza de Pele Profunda - R$ 100,00 <button onclick="adicionarAoCarrinho('Limpeza de Pele Profunda', 100)">Adicionar ao Carrinho</button></li>
            <li>Hidratação Facial - R$ 80,00 <button onclick="adicionarAoCarrinho('Hidratação Facial', 80)">Adicionar ao Carrinho</button></li>
            <li>Peeling Facial - R$ 120,00 <button onclick="adicionarAoCarrinho('Peeling Facial', 120)">Adicionar ao Carrinho</button></li>
            <li>Máscara de Ouro - R$ 150,00 <button onclick="adicionarAoCarrinho('Máscara de Ouro', 150)">Adicionar ao Carrinho</button></li>
            <li>Tratamento Antiacne - R$ 110,00 <button onclick="adicionarAoCarrinho('Tratamento Antiacne', 110)">Adicionar ao Carrinho</button></li>
            <li>Tratamento para Rejuvenescimento - R$ 180,00 <button onclick="adicionarAoCarrinho('Tratamento para Rejuvenescimento', 180)">Adicionar ao Carrinho</button></li>
            <li>Radiofrequência Facial - R$ 200,00 <button onclick="adicionarAoCarrinho('Radiofrequência Facial', 200)">Adicionar ao Carrinho</button></li>
            <li>Microagulhamento - R$ 250,00 <button onclick="adicionarAoCarrinho('Microagulhamento', 250)">Adicionar ao Carrinho</button></li>
            <li>Peeling de Diamante - R$ 140,00 <button onclick="adicionarAoCarrinho('Peeling de Diamante', 140)">Adicionar ao Carrinho</button></li>
            <li>Tratamento para Clareamento de Manchas - R$ 160,00 <button onclick="adicionarAoCarrinho('Tratamento para Clareamento de Manchas', 160)">Adicionar ao Carrinho</button></li>
            <li>Botox Facial - R$ 300,00 <button onclick="adicionarAoCarrinho('Botox Facial', 300)">Adicionar ao Carrinho</button></li>
            <li>Hidratação com Colágeno - R$ 120,00 <button onclick="adicionarAoCarrinho('Hidratação com Colágeno', 120)">Adicionar ao Carrinho</button></li>
            <li>Peeling de Cristal - R$ 150,00 <button onclick="adicionarAoCarrinho('Peeling de Cristal', 150)">Adicionar ao Carrinho</button></li>
            <li>Máscara de Argila - R$ 90,00 <button onclick="adicionarAoCarrinho('Máscara de Argila', 90)">Adicionar ao Carrinho</button></li>
            <li>Tratamento de Lifting Facial - R$ 220,00 <button onclick="adicionarAoCarrinho('Tratamento de Lifting Facial', 220)">Adicionar ao Carrinho</button></li>
            <li>Revitalização com Vitamina C - R$ 130,00 <button onclick="adicionarAoCarrinho('Revitalização com Vitamina C', 130)">Adicionar ao Carrinho</button></li>
            <li>Tratamento Redutor de Linhas de Expressão - R$ 180,00 <button onclick="adicionarAoCarrinho('Tratamento Redutor de Linhas de Expressão', 180)">Adicionar ao Carrinho</button></li>
            
        </ul>
        <button onclick="showSection('home')">Voltar ao Home</button>
    </section>

    <!-- Seção Massagens -->
    <section id="massagens" class="section">
        <h3>Massagens</h3>
        <ul>
            <li>Massagem Relaxante - R$ 90,00 <button onclick="adicionarAoCarrinho('Massagem Relaxante', 90)">Adicionar ao Carrinho</button></li>
            <li>Massagem Terapêutica - R$ 120,00 <button onclick="adicionarAoCarrinho('Massagem Terapêutica', 120)">Adicionar ao Carrinho</button></li>
            <li>Massagem Modeladora - R$ 150,00 <button onclick="adicionarAoCarrinho('Massagem Modeladora', 150)">Adicionar ao Carrinho</button></li>
            <li>Massagem com Pedras Quentes - R$ 130,00 <button onclick="adicionarAoCarrinho('Massagem com Pedras Quentes', 130)">Adicionar ao Carrinho</button></li>
            <li>Massagem Anti-stress - R$ 110,00 <button onclick="adicionarAoCarrinho('Massagem Anti-stress', 110)">Adicionar ao Carrinho</button></li>
            <li>Massagem Relaxante com Óleos Essenciais - R$ 140,00 <button onclick="adicionarAoCarrinho('Massagem Relaxante com Óleos Essenciais', 140)">Adicionar ao Carrinho</button></li>
            <li>Massagem com Aromaterapia - R$ 160,00 <button onclick="adicionarAoCarrinho('Massagem com Aromaterapia', 160)">Adicionar ao Carrinho</button></li>
            <li>Massagem Desportiva - R$ 180,00 <button onclick="adicionarAoCarrinho('Massagem Desportiva', 180)">Adicionar ao Carrinho</button></li>
            <li>Massagem Linfática - R$ 150,00 <button onclick="adicionarAoCarrinho('Massagem Linfática', 150)">Adicionar ao Carrinho</button></li>
            <li>Massagem Craniana - R$ 110,00 <button onclick="adicionarAoCarrinho('Massagem Craniana', 110)">Adicionar ao Carrinho</button></li>
            <li>Reflexologia - R$ 120,00 <button onclick="adicionarAoCarrinho('Reflexologia', 120)">Adicionar ao Carrinho</button></li>
            <li>Massagem Ayurvédica - R$ 200,00 <button onclick="adicionarAoCarrinho('Massagem Ayurvédica', 200)">Adicionar ao Carrinho</button></li>
            <li>Massagem Tailandesa - R$ 250,00 <button onclick="adicionarAoCarrinho('Massagem Tailandesa', 250)">Adicionar ao Carrinho</button></li>
            
        </ul>
        <button onclick="showSection('home')">Voltar ao Home</button>
    </section>




<!-- Seção Carrinho -->
<section id="carrinho" class="section">
    <h3>Carrinho</h3>
    <ul id="carrinho-list"></ul>
    <p>Total: R$ <span id="total">0,00</span></p>

    <!-- Opções de Pagamento -->
    <h4>Escolha a forma de pagamento:</h4>
    <form id="pagamento-form">
        <label>
            <input type="radio" name="pagamento" value="pix" required> PIX
        </label><br>
        <label>
            <input type="radio" name="pagamento" value="boleto" required> Boleto
        </label><br>
        <label>
            <input type="radio" name="pagamento" value="cartao" required> Cartão de Crédito
        </label><br>
        
        <!-- Botão Finalizar Compra -->
        <button type="submit">Finalizar Compra</button>
    </form>
</section>







<!-- Seção Agendamento -->
<section id="agendamento" class="section">
    <h3>Agende seu Atendimento</h3>
    <div class="form-container">
        <label for="nome">Nome:</label>
        <input type="text" id="nome" placeholder="Digite seu nome" required>
        <br>
        <label for="telefone">Telefone:</label>
        <input type="tel" id="telefone" placeholder="Digite seu telefone" required>
        <br>
        <label for="dataNascimento">Data de Nascimento:</label>
        <input type="date" id="dataNascimento" required>
        <br>
        <label for="hora">Escolha a hora:</label>
        <input type="time" id="hora" required>
        <br>
        <label for="servico">Escolha o serviço:</label>
        <select id="servico" required>
            <option value="massagem">Massagem</option>
            <option value="estetica">Estética</option>
        </select>
        <br>
        <button type="submit">Agendar</button>
    </div>
    <button onclick="showSection('home')">Voltar ao Home</button>
</section>

    <script>
        // Função para alternar seções
        function showSection(section) {
            document.querySelectorAll('.section').forEach(function(sec) {
                sec.classList.remove('active');
            });
            document.getElementById(section).classList.add('active');
        }

        // Função para adicionar item ao carrinho
        let carrinho = [];
        let total = 0;

        function adicionarAoCarrinho(nome, preco) {
            carrinho.push({ nome, preco });
            total += preco;
            atualizarCarrinho();
        }

        function atualizarCarrinho() {
            const carrinhoList = document.getElementById('carrinho-list');
            const totalElement = document.getElementById('total');

            // Limpa a lista do carrinho
            carrinhoList.innerHTML = '';

            // Adiciona cada item ao carrinho
            carrinho.forEach(function(item) {
                const li = document.createElement('li');
                li.textContent = item.nome + ' - R$ ' + item.preco;
                carrinhoList.appendChild(li);
            });

            // Atualiza o total
            totalElement.textContent = total.toFixed(2);
        }

        // Impede o envio do formulário
        document.getElementById('agendamento-form').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Agendamento realizado com sucesso!');
        });
    </script>
</body>
</html>
