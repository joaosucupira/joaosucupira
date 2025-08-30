<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>README - João Sucupira</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
    body {
      font-family: 'Inter', sans-serif;
      line-height: 1.6;
      background-color: #0d1117;
      color: #c9d1d9;
      margin: 0;
      padding: 20px;
    }
    .container {
      max-width: 900px;
      margin: auto;
      background: #161b22;
      padding: 20px 40px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
    }
    h1, h2, h3, h4 {
      color: #58a6ff;
    }
    h1 {
      text-align: center;
      font-size: 2.5em;
      margin-bottom: 0.5em;
    }
    h3 {
      text-align: center;
      font-weight: 400;
      font-size: 1.2em;
    }
    hr {
      border: 0;
      height: 1px;
      background: #30363d;
      margin: 20px 0;
    }
    .section {
      margin-bottom: 30px;
    }
    .grid-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .grid-item {
      background: #242424;
      border-radius: 12px;
      padding: 15px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
      transition: transform 0.2s;
    }
    .grid-item:hover {
      transform: translateY(-5px);
    }
    .grid-item h4 {
      margin-top: 0;
      margin-bottom: 10px;
      color: #c9d1d9;
    }
    .grid-item img {
      margin: 5px;
    }
    .social-links img {
      margin: 0 10px;
      transition: transform 0.2s;
    }
    .social-links img:hover {
      transform: scale(1.1);
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    ul li {
      margin-bottom: 10px;
    }
    strong {
      color: #79c0ff;
    }
</style>

</head>
<body>
  <div class="container">
    <div align="center">
      <h1>Olá! 👋 Meu nome é João Sucupira</h1>
      <h3>Sistemas de Informação - Universidade Tecnológica Federal do Paraná (UTFPR) - Engenharia de Dados, Software e Ciência de Dados.</h3>
    </div>
    <div class="section">
      <h3>Sobre Mim</h3>
      <p>Sou um profissional sempre interessado em desenvolver soluções robustas e escaláveis, com sólida formação técnica e experiência multidisciplinar em gestão. Minha jornada combina práticas de <strong>Engenharia de Software</strong> e <strong>Arquitetura de Sistemas</strong> com um profundo foco em <strong>Machine Learning</strong>, <strong>Ciência de Dados</strong> e <strong>Engenharia de Dados</strong>. Tenho muita curiosidade em aprender e sou resiliente quando enfrento desafios extensivos. Acredito na Gestão por Processos e uso consciente de artefatos da Inteligência Artifical.</p>
    <hr>
    </div>
      <div class="section">
        <h3>Habilidades Técnicas e Atividade</h3>
        <div style="display: flex; justify-content: space-around; flex-wrap: wrap; gap: 20px;">
          <div align="center">
            <img src="https://streak-stats.demolab.com/?user=joaosucupira&theme=dark" alt="Linguagens mais usadas" />
          </div>
          <div align="center">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=joaosucupira&theme=dark" alt="Gráfico de Habilidades" width="500"/>
          </div>
        </div>
      </div>
      <br>
      <div class="grid-container">
        <div class="grid-item">
          <h4>Linguagens</h4>
          <p>
            <img src="https://skillicons.dev/icons?i=python,js,java,cpp" alt="Linguagens" />
          </p>
        </div>
        <div class="grid-item">
          <h4>Deploy e ML</h4>
          <p>
            <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,docker,kubernetes" alt="Frameworks e Bibliotecas de ML" />
          </p>
        </div>
        <div class="grid-item">
          <h4>Cloud e Banco de Dados</h4>
          <p>
            <img src="https://skillicons.dev/icons?i=aws,gcp,azure,postgres" alt="Nuvem e Bancos de Dados" />
          </p>
        </div>
        <div class="grid-item">
          <h4>Outras Ferramentas</h4>
          <p>
            <img src="https://skillicons.dev/icons?i=postman,graphql,figma,photoshop" alt="Outras Ferramentas" />
          </p>
        </div>
      </div>
      <div>
        <h3>Experiência e Projetos</h3>
        <ul>
        <li>
          <strong>Estágio em Análise de Dados (UTFPR):</strong> Desenvolvi soluções de RAG utilizando <strong>Python</strong> e <strong>LangChain</strong>, e realizei consultas <strong>SQL</strong> otimizadas. Meu trabalho é aplicar os pilares da <strong>Governança de Dados</strong> e trazer Transformação Digital para o meu setor.
        </li>
        <li>
          <strong>Projetos de Machine Learning:</strong> Experiência prática com bibliotecas essenciais como <strong>TensorFlow</strong> e <strong>PyTorch</strong>, aplicadas na construção de modelos preditivos e soluções de visão computacional.
        </li>
        <li>
          <strong>Certificações:</strong> Aprimoramento contínuo com certificações como a de <strong>Databricks data engineer</strong>, que valida minha capacidade de trabalhar com engenharia de dados em escala.
        </li>
        </ul>
      </div>
      <div class="section">
        <h3>Conecte-se Comigo</h3>
        <p class="social-links" align="center">
          <a href="https://www.linkedin.com/in/jo%C3%A3o-sucupira-746954236/" target="_blank">
            <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
          </a>
          <a href="https://instagram.com/jota_ate" target="_blank">
            <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="30" width="40" />
          </a>
        </p>
      </div>
    </div>
    <br>
    </div>
</body>
</html>
