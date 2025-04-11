<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vinicius | Desenvolvedor Front-end</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #0d1b2a;
      color: #fff;
      padding: 40px 20px;
      text-align: center;
    }
    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #fff;
    }
    header h1 {
      margin: 20px 0 10px;
      font-size: 28px;
    }
    header p {
      font-size: 16px;
      opacity: 0.8;
    }
    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }
    .projetos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .projeto {
      background-color: #fff;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .contato {
      text-align: center;
      margin-top: 40px;
    }
    .contato a {
      background-color: #198754;
      color: #fff;
      padding: 12px 24px;
      border-radius: 5px;
      text-decoration: none;
      font-size: 16px;
      transition: background-color 0.3s ease;
    }
    .contato a:hover {
      background-color: #157347;
    }
  </style>
</head>
<body>
  <header>
    <img src="foto-vinicius.jpg" alt="Vinicius">
    <h1>Vinicius</h1>
    <p>Desenvolvedor Front-end | Especialista em Sites Profissionais</p>
  </header>  <section>
    <h2>Sobre mim</h2>
    <p>Meu nome é Vinicius, sou desenvolvedor front-end focado na criação de sites profissionais para negócios que querem se destacar online. Tenho experiência com design moderno, páginas rápidas e responsivas, e também atuo com marketing digital, o que me ajuda a entender exatamente o que seu site precisa para converter mais clientes.</p>
  </section>  <section>
    <h2>Projetos</h2>
    <div class="projetos">
      <div class="projeto">
        <h3>Site para Clínica Médica</h3>
        <p>Layout moderno, responsivo e com formulário de agendamento integrado.</p>
      </div>
      <div class="projeto">
        <h3>Landing Page para Barbeiro</h3>
        <p>Página única com fotos, depoimentos e botão direto para o WhatsApp.</p>
      </div>
      <div class="projeto">
        <h3>Portfólio para Fotógrafo</h3>
        <p>Site com galeria de imagens, depoimentos e contato direto.</p>
      </div>
    </div>
  </section>  <section class="contato">
    <h2>Entre em Contato</h2>
    <a href="https://wa.me/5581994898144" target="_blank">Falar no WhatsApp</a>
  </section>
</body>
</html> 
