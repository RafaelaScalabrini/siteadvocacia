<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Escritório de Advocacia Magnani & Andrade</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #1c2e4a;
      color: white;
      padding: 30px 20px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    }

    header h1 {
      font-size: 2em;
      font-weight: 600;
    }

    .container {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      text-align: center;
    }

    .container img {
      border-radius: 10px;
      margin-bottom: 20px;
    }

    h2 {
      color: #1c2e4a;
      font-size: 1.8em;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1em;
      margin-bottom: 15px;
    }

    .contact-info {
      margin-top: 30px;
    }

    .contact-info p {
      font-size: 1.1em;
      margin: 5px 0;
    }

    .whatsapp-link {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      background-color: #25D366;
      color: white;
      padding: 12px 24px;
      text-decoration: none;
      font-size: 1.1em;
      font-weight: bold;
      border-radius: 5px;
      margin-top: 15px;
      transition: background 0.3s ease;
    }

    .whatsapp-link:hover {
      background-color: #1ebe5d;
    }

    .whatsapp-link img {
      width: 24px;
      height: 24px;
      margin-right: 10px;
    }

    footer {
      background-color: #1c2e4a;
      color: white;
      text-align: center;
      padding: 15px 10px;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      .container {
        margin: 20px;
        padding: 15px;
      }

      header h1 {
        font-size: 1.5em;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Magnani & Andrade - Advocacia</h1>
  </header>

  <div class="container">
    <img src="https://via.placeholder.com/800x400" alt="Advogado loiro de olhos verdes bem vestido" />
    <h2>Especialistas em Direito Empresarial e Civil</h2>
    <p>Oferecemos atendimento personalizado com ética, compromisso e excelência.</p>
    
    <img src="https://via.placeholder.com/150" alt="Balança jurídica de bronze" />

    <div class="contact-info">
      <h3>Entre em contato:</h3>
      <p>Email: contato@magnaniadvocacia.com.br</p>
      <p>Telefone: (11) 98765-4321</p>
      <a class="whatsapp-link" href="https://wa.me/5516992523577" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp" />
        Fale conosco no WhatsApp
      </a>
    </div>
  </div>

  <footer>
    &copy; 2025 Magnani & Andrade - Todos os direitos reservados.
  </footer>
</body>
</html>
