<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Testes Laboratoriais Rápidos</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f4f6f8;
            margin: 0;
            padding: 0;
            line-height: 1.8;
        }
        header {
            background-color: #2a7f62;
            color: white;
            padding: 30px;
            text-align: center;
        }
        nav {
            background-color: #1f5f4a;
            padding: 10px;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            margin: 6px 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav ul li a:hover {
            text-decoration: underline;
        }
        section {
            background-color: white;
            margin: 15px;
            padding: 30px;
            border-radius: 8px;
            scroll-margin-top: 95px;
        }
        h2 {
            color: #2a7f62;
        }
        .imagens {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 15px;
        }
        .imagens div {
            text-align: center;
            max-width: 250px;
        }
        .imagens img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 6px;
            border: 1px solid #ccc;
        }
        footer {
            background-color: #2a7f62;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

<header>
    <h1>Testes Laboratoriais Rápidos</h1>
    <p><strong>Disciplina:</strong> Imunologia Básica</p>
    <p><strong>Instituição:</strong> UNIFECAF – Unidade RD</p>
    <p><strong>Curso:</strong> Graduação em Farmácia</p>
</header>

<nav>
    <ul>
        <li><a href="#introducao">Introdução</a></li>
        <li><a href="#fundamentos">Fundamentos</a></li>
        <li><a href="#principio">Princípio</a></li>
        <li><a href="#procedimento">Procedimento</a></li>
        <li><a href="#exemplos">Testes</a></li>
        <li><a href="#interpretacao">Interpretação</a></li>
        <li><a href="#vantagens">Vantagens</a></li>
        <li><a href="#profissionais">Profissionais</a></li>
        <li><a href="#pacientes">Pacientes</a></li>
        <li><a href="#biosseguranca">Biossegurança</a></li>
        <li><a href="#alunos">Alunos</a></li>
    </ul>
</nav>

<section id="introducao">
    <h2>Introdução</h2>
    <p>Testes rápidos são métodos imunodiagnósticos utilizados para detecção qualitativa de antígenos ou anticorpos específicos em amostras biológicas. Resultados rápidos, geralmente em 10-30 minutos, são amplamente usados em triagens clínicas, saúde pública e atendimento emergencial.</p>
</section>

<section id="fundamentos">
    <h2>Fundamentos imunológicos</h2>
    <p>Baseiam-se na resposta imunológica adaptativa, interações específicas entre antígenos e anticorpos:</p>
    <ul>
        <li><strong>IgM:</strong> Indica infecção recente ou fase aguda</li>
        <li><strong>IgG:</strong> Indica infecção passada ou imunidade adquirida</li>
    </ul>
</section>

<section id="principio">
    <h2>Princípio analítico</h2>
    <p>A maioria dos testes rápidos utiliza imunocromatografia de fluxo lateral. A amostra migra por capilaridade e reage com anticorpos ou antígenos marcados com partículas coradas, como ouro coloidal. A formação de complexos resulta em bandas visuais interpretáveis sem equipamentos complexos.</p>
</section>

<section id="procedimento">
    <h2>Procedimento técnico</h2>
    <ul>
        <li><strong>Coleta:</strong> sangue capilar, soro, plasma, saliva ou secreções respiratórias</li>
        <li><strong>Preparação:</strong> dispositivo em temperatura ambiente e dentro do prazo de validade</li>
        <li><strong>Aplicação:</strong> deposição da amostra no cassete e adição de solução tampão</li>
        <li><strong>Desenvolvimento:</strong> ligação antígeno-anticorpo formando linhas visíveis de teste e controle</li>
    </ul>
</section>

<section id="exemplos">
    <h2>Exemplos de Testes Rápidos</h2>
    <div class="imagens">
        <div><img src="imagens/hiv.jpg" alt="Teste HIV"><p><strong>HIV:</strong> Anticorpos IgG/IgM</p></div>
        <div><img src="imagens/covid.jpg" alt="Teste COVID"><p><strong>COVID-19:</strong> Antígeno viral</p></div>
        <div><img src="imagens/hepatite.jpg" alt="Teste Hepatite"><p><strong>Hepatite B:</strong> HBsAg</p></div>
        <div><img src="imagens/dengue.jpg" alt="Teste Dengue"><p><strong>Dengue:</strong> Antígeno NS1/IgM/IgG</p></div>
        <div><img src="imagens/sifilis.jpg" alt="Teste Sífilis"><p><strong>Sífilis:</strong> Anticorpos treponêmicos</p></div>
        <div><img src="imagens/influenza.jpg" alt="Teste Influenza"><p><strong>Influenza:</strong> Antígeno viral</p></div>
        <div><img src="imagens/malaria.jpg" alt="Teste Malária"><p><strong>Malária:</strong> Antígenos Plasmodium</p></div>
    </div>
</section>

<section id="interpretacao">
    <h2>Interpretação</h2>
    <ul>
        <li>Linha controle (C): confirma a validade do teste</li>
        <li>Linha teste (T): indica resultado reagente</li>
        <li>Apenas linha controle: resultado não reagente</li>
        <li>Sem linha controle: teste inválido</li>
    </ul>
</section>

<section id="vantagens">
    <h2>Vantagens e Limitações</h2>
    <p><strong>Vantagens:</strong> Rapidez, baixo custo, fácil execução, aplicabilidade em locais com poucos recursos.</p>
    <p><strong>Limitações:</strong> Menor sensibilidade inicial, risco de falso-positivo/negativo, necessidade de confirmação laboratorial.</p>
</section>

<section id="profissionais">
    <h2>Profissionais habilitados</h2>
    <ul>
        <li>Farmacêuticos</li>
        <li>Médicos</li>
        <li>Biomédicos</li>
        <li>Enfermeiros</li>
        <li>Técnicos sob supervisão</li>
    </ul>
</section>

<section id="pacientes">
    <h2>Pacientes indicados</h2>
    <p>Sintomáticos, triagens populacionais, gestantes, indivíduos expostos a riscos biológicos e monitoramento epidemiológico.</p>
</section>

<section id="biosseguranca">
    <h2>Biossegurança</h2>
    <p>Uso de EPI (luvas, jaleco, máscara), higienização das mãos, descarte correto de resíduos e cumprimento das normas sanitárias.</p>
</section>

<section id="alunos">
    <h2>Alunos</h2>
    <ul>
        <li>Thalia Soares Dantas – RA: 119979</li>
        <li>Luann Reis da Silva – RA: 125643</li>
        <li>Debora Andreza dos Santos – RA: 120704</li>
        <li>Lorrayne Sthephane da Silva Oliveira – RA: 120439</li>
        <li>Gersica Santos Silva – RA: 122269</li>
        <li>Girlane Coelho Pinheiro – RA: 120909</li>
    </ul>
</section>

<footer>
    <p>UNIFECAF – Graduação em Farmácia | Imunologia Básica</p>
</footer>

</body>
</html>
