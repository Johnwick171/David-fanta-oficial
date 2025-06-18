<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>David Fanta Oficial</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #fff;
    }

    .profile-banner {
      position: relative;
      height: 350px;
      background-image: url('https://i.postimg.cc/MKsRMQct/FB-IMG-1749852775905.jpg');
      background-size: cover;
      background-position: center;
    }

    .overlay {
      position: absolute;
      inset: 0;
      background-color: rgba(0, 0, 0, 0.5);
    }

    .banner-text {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      z-index: 2;
    }

    .banner-text 01{
      font-size: 2.5rem;
      margin: 0;
      color: #fff;
    }

    .plans-section {
      padding: 30px 20px;
      text-align: center;
    }

    .plans-section h2 {
      margin-bottom: 20px;
      font-size: 2rem;
      color: #ff4081;
    }

    .plan-cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .plan {
      background-color: #222;
      border: 2px solid #ff4081;
      padding: 20px;
      width: 260px;
      border-radius: 12px;
      transition: transform 0.2s;
    }

    .plan:hover {
      transform: scale(1.05);
    }

    .plan h3 {
      margin-top: 0;
      font-size: 1.5rem;
    }

    .plan p {
      font-size: 1.2rem;
      color: #ccc;
    }

    .subscribe-btn {
      margin-top: 15px;
      padding: 12px 24px;
      background-color: #ff4081;
      border: none;
      border-radius: 6px;
      color: white;
      cursor: pointer;
      font-size: 1rem;
    }

    .subscribe-btn:hover {
      background-color: #e73370;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #000;
      font-size: 0.9rem;
      color: #666;
    }

    @media (max-width: 768px) {
      .plan {
        width: 90%;
      }
    }
  </style>
</head>
<body>

  <div class="profile-banner">
    <div class="overlay"></div>
    <div class="banner-text">
      <h8>🇧🇷𝕯𝖆𝖛𝖎𝖉 𝖋𝖆𝖓𝖙𝖆 𝖔𝖋𝖎𝖈𝖎𝖆𝖑𝖑🇧🇷
        
        
        𝐏𝐥𝐚𝐭𝐚𝐟𝐨𝐫𝐦𝐚 𝐦𝐚𝐢𝐬 𝐜𝐨𝐦𝐩𝐥𝐞𝐭𝐚 𝐜𝐨𝐦 𝐨𝐬 𝐦𝐞𝐥𝐡𝐨𝐫𝐞𝐬 𝐯𝐢𝐝𝐞𝐨𝐬 𝐝𝐚𝐬 𝐧𝐨𝐯𝐢𝐧𝐡𝐚𝐬 𝐦𝐚𝐢𝐬 𝐪𝐮𝐞𝐧𝐭𝐞𝐬 𝐝𝐨𝐬 𝐛𝐫𝐚𝐬𝐢𝐥 𝐞 𝐝𝐞 𝐭𝐨𝐝𝐚𝐬 𝐚𝐬 𝐢𝐝𝐚𝐝𝐞𝐬🤫
      </h8>
    </div>
  </div>

  <section class="plans-section">
    <h2>Assine e tenha acesso exclusivo aos conteúdos 🔞</h2>
    <div class="plan-cards">
      <div class="plan">
        <h3>Plano Mensal</h3>
        <p>R$ 30,00 / mês</p>
        <button class="subscribe-btn" onclick="window.location.href='https://app.pushinpay.com.br/service/pay/9F2C76DA-0BD7-4C10-AB37-1BC9500BCBE8'">Assinar agora</button>
      </div>
      <div class="plan">
        <h3>Plano Trimestral</h3>
        <p>R$ 50,00 / 3 meses</p>
        <button class="subscribe-btn" onclick="window.location.href='https://app.pushinpay.com.br/service/pay/9f2c91b7-3362-4aaa-8b59-f743ddc17bc4'">Assinar agora</button>
      </div>
      <div class="plan">
        <h3>Plano Vitalício</h3>
        <p>R$ 100,00 acesso para sempre</p>
        <button class="subscribe-btn" onclick="window.location.href='https://app.pushinpay.com.br/service/pay/9f2c9261-d046-487e-86d2-3ad330c3255a'">Assinar agora</button>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 David Fanta Oficial · Todos os direitos reservados.
  </footer>

</body>
</html
