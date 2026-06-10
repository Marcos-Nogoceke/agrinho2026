<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Água no Campo: Equilíbrio para o Futuro - Agrinho 2026</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Agro Forte, Futuro Sustentável</h1>
        <h2>Uso Consciente da Água na Agricultura</h2>
    </header>

    <main>
        <section class="introducao">
            <h2>Introdução</h2>
            <p>A água é essencial para a produção de alimentos, mas seu uso excessivo e ineficiente ameaça nossa segurança hídrica. A agricultura é responsável por cerca de 70% do consumo de água doce no mundo. Por isso, o uso consciente da água é fundamental para manter uma produção forte e um meio ambiente preservado.</p>
        </section>

        <section class="problema">
            <h2>O Problema</h2>
            <p>Irrigação ineficiente, desperdício, contaminação de rios e lençóis freáticos e mudanças climáticas estão reduzindo a disponibilidade de água para o campo e para as cidades.</p>
        </section>

        <section class="solucao">
            <h2>Soluções Sustentáveis</h2>
            <ul>
                <li>Irrigação por gotejamento e pivô central</li>
                <li>Monitoramento do solo com sensores</li>
                <li>Captação e reuso de água da chuva</li>
                <li>Plantio em horários adequados</li>
                <li>Educação e boas práticas no campo</li>
            </ul>
        </section>

        <section class="interatividade">
            <h2>Calculadora de Economia de Água</h2>
            <p>Descubra quanto você pode economizar adotando práticas sustentáveis:</p>
            <div class="calculadora">
                <label>Área irrigada (em hectares):</label>
                <input type="number" id="area" value="10" min="1">
                
                <label>Tipo de irrigação:</label>
                <select id="irrigacao">
                    <option value="1.0">Convencional (Aspersão)</option>
                    <option value="0.6">Gotejamento</option>
                    <option value="0.4">Gotejamento + Sensores</option>
                </select>
                
                <button onclick="calcularEconomia()">Calcular Economia</button>
                <p id="resultado" class="resultado"></p>
            </div>
        </section>

        <section class="conclusao">
            <h2>Conclusão</h2>
            <p>Adotar o uso consciente da água não é apenas uma escolha ambiental, mas uma necessidade para garantir a produtividade agrícola e o futuro das próximas gerações.</p>
        </section>

        <section class="referencias">
            <h2>Referências</h2>
            <p>FAO - Organização das Nações Unidas para a Alimentação e Agricultura<br>
            Embrapa - Empresa Brasileira de Pesquisa Agropecuária<br>
            Ministério do Meio Ambiente</p>
        </section>
    </main>

    <footer>
        <p>Projeto desenvolvido para o Concurso Agrinho 2026</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
