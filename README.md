<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AgroTec Sustentável - Agrinho 2026</title>
    
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
            background-color: #f4f9f4;
        }

        .container {
            width: 85%;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Cabeçalho */
        header {
            background-color: #2e7d32;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            height: 50px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Seção Inicial (Banner) */
        .hero {
            position: relative;
            text-align: center;
            color: white;
        }

        .banner-img {
            width: 100%;
            height: auto;
            max-height: 400px;
            object-fit: cover;
            filter: brightness(60%);
        }

        .hero-overlay {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 90%;
        }

        /* Seções */
        .section {
            padding: 60px 0;
            text-align: center;
        }

        .bg-alt {
            background-color: #e8f5e9;
        }

        .grid-2 {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            align-items: center;
            text-align: left;
        }

        .grid-2.reverse {
            flex-direction: row-reverse;
        }

        .text-block, .image-block {
            flex: 1;
            min-width: 280px;
        }

        .content-img {
            width: 100%;
            max-width: 600px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        /* Simulador */
        .simulator-card {
            background: white;
            padding: 30px;
            border-radius: 8px;
            display: inline-block;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            margin-top: 20px;
        }

        .input-group {
            margin-bottom: 15px;
        }

        input[type="number"] {
            padding: 8px;
            font-size: 16px;
            width: 80px;
            margin-left: 10px;
        }

        button {
            background-color: #2e7d32;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 4px;
        }

        button:hover {
            background-color: #1b5e20;
        }

        .result-box {
            margin-top: 20px;
            font-weight: bold;
            font-size: 18px;
            color: #2e7d32;
            text-align: center;
        }
        
        .subtitle {
            color: #555;
        }

        /* Rodapé */
        footer {
            background-color: #1b5e20;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        .sub-footer {
            font-size: 0.8rem;
            opacity: 0.8;
        }
    </style>
</head>
<body>

    <header>
        <div class="container navbar">
            <img src="img/logo.png" alt="Logo AgroTec Sustentável" class="logo">
            <nav>
                <a href="#inicio">Início</a>
                <a href="#sobre">O Projeto</a>
                <a href="#comedouro">Comedouro</a>
                <a href="#simulador">Simulador</a>
            </nav>
        </div>
    </header>

    <section id="inicio" class="hero">
        <img src="img/banner.png" alt="Banner AgroTec Sustentável" class="banner-img">
        <div class="hero-overlay">
            <h1>AgroTec Sustentável</h1>
            <p>Inovação tecnológica e respeito pelo meio ambiente no Concurso Agrinho 2026</p>
        </div>
    </section>

    <section id="sobre" class="container section">
        <h2>Sobre o Projeto</h2>
        <div class="grid-2">
            <div class="text-block">
                <p>O <strong>AgroTec Sustentável</strong> é uma iniciativa desenvolvida para transformar a rotina no campo através da tecnologia acessível. O nosso foco é otimizar o uso de recursos escassos, como a água e os alimentos, reduzindo o desperdício e aumentando a eficiência da produção agrícola e pecuária.</p>
                <p>Utilizando conceitos de automação e sustentabilidade, mostramos que é possível alinhar a produtividade com a preservação ambiental de forma prática.</p>
            </div>
            <div class="image-block">
                <img src="img/maquete-geral.png" alt="Maquete do Projeto AgroTec" class="content-img">
            </div>
        </div>
    </section>

    <section id="comedouro" class="bg-alt">
        <div class="container section">
            <h2>Comedouro Inteligente</h2>
            <div class="grid-2 reverse">
                <div class="text-block">
                    <p>O nosso protótipo de <strong>Comedouro Automatizado</strong> foi desenhado para monitorar a alimentação dos animais em tempo real. Através de sensores integrados, o sistema liberta a quantidade exata de ração necessária, evitando que o alimento fique exposto à humidade ou a pragas.</p>
                    <ul>
                        <li>Redução drástica no desperdício de ração.</li>
                        <li>Acionamento controlado por horários ou sensores de presença.</li>
                        <li>Higiene e saúde reforçadas para os animais.</li>
                    </ul>
                </div>
                <div class="image-block">
                    <img src="img/comedouro.png" alt="Protótipo do Comedouro Automatizado" class="content-img">
                </div>
            </div>
        </div>
    </section>

    <section id="simulador" class="container section">
        <h2>Simulador de Impacto Sustentável</h2>
        <p class="subtitle">Insere a quantidade de dias para estimar a poupança de recursos com a nossa tecnologia:</p>
        
        <div class="simulator-card">
            <div class="input-group">
                <label for="dias">Dias de Funcionamento:</label>
                <input type="number" id="dias" value="30" min="1" placeholder="Ex: 30">
            </div>
            <button onclick="calcularEconomia()">Calcular Poupança</button>
            
            <div id="resultado" class="result-box"></div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2026 AgroTec Sustentável | Projeto para o Concurso Agrinho</p>
            <p class="sub-footer">Desenvolvido com fins educativos utilizando GitHub Pages</p>
        </div>
    </</footer>

    <script>
        function calcularEconomia() {
            const dias = document.getElementById('dias').value;
            
            if (dias <= 0 || isNaN(dias)) {
                document.getElementById('resultado').innerHTML = "Por favor, insira um número válido de dias.";
                return;
            }

            // Cálculo sustentável
            const raçãoEconomizada = (dias * 0.5).toFixed(1); // 500g por dia
            const aguaPoupada = dias * 3; // 3 litros por dia

            document.getElementById('resultado').innerHTML = 
                `Com o sistema, em ${dias} dias você economizará aproximadamente:<br> 
                🌾 ${raçãoEconomizada} kg de ração<br> 
                💧 ${aguaPoupada} litros de água!`;
        }
    </script>
</body>
</html>
