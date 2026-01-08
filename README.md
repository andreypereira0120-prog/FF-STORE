<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FF Store — Contas Digitais</title>
  <style>
    * { box-sizing: border-box; font-family: Arial, Helvetica, sans-serif; }
    body { margin: 0; background: #0f1220; color: #eaeaf0; }
    header { background: linear-gradient(135deg,#ff7a18,#ffb347); padding: 24px; }
    header h1 { margin: 0; color:#111; }
    header p { margin: 8px 0 0; color:#222; }
    .container { max-width: 1100px; margin: 0 auto; padding: 24px; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit,minmax(260px,1fr)); gap: 16px; }
    .card { background:#171a2b; border-radius: 12px; padding: 16px; box-shadow: 0 10px 20px rgba(0,0,0,.25); }
    .card h3 { margin-top: 0; }
    .badge { display:inline-block; padding: 4px 8px; border-radius: 999px; background:#2a2f55; font-size: 12px; margin-right: 6px; }
    .price { font-size: 22px; font-weight: bold; margin: 12px 0; }
    .btn { display:inline-block; padding: 10px 14px; border-radius: 10px; background:#ff7a18; color:#111; text-decoration:none; font-weight:bold; }
    .btn.secondary { background:#2a2f55; color:#eaeaf0; }
    .features { list-style:none; padding:0; margin: 8px 0 0; }
    .features li { margin: 6px 0; font-size: 14px; }
    footer { background:#0b0e1a; padding: 16px; text-align:center; font-size: 12px; color:#b7b7c9; }
    .notice { background:#101436; border-left: 4px solid #ffb347; padding: 12px; border-radius: 8px; margin-bottom: 16px; font-size: 14px; }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>FF Store</h1>
      <p>Venda de contas digitais — entrega rápida</p>
    </div>
  </header>  <main class="container">
    <div class="notice">
      <strong>Aviso importante:</strong> a compra e venda de contas pode violar os Termos de Serviço do jogo. Este site é apenas um modelo demonstrativo para venda de <em>produtos digitais</em>. Use por sua conta e risco e informe-se sobre as regras oficiais.
    </div><h2>Contas em destaque</h2>
<div class="grid">
  <div class="card">
    <span class="badge">Rara</span><span class="badge">LVL 60</span>
    <h3>Conta FF Ouro</h3>
    <ul class="features">
      <li>Skins lendárias</li>
      <li>Diamantes: 0</li>
      <li>Servidor BR</li>
    </ul>
    <div class="price">R$ 149,90</div>
    <a class="btn" href="#pix">Comprar com Pix</a>
  </div>
  <div class="card">
    <span class="badge">Épica</span><span class="badge">LVL 70</span>
    <h3>Conta FF Diamante</h3>
    <ul class="features">
      <li>Skins raras + pets</li>
      <li>Histórico limpo</li>
      <li>Servidor BR</li>
    </ul>
    <div class="price">R$ 249,90</div>
    <a class="btn" href="#pix">Comprar com Pix</a>
  </div>
  <div class="card">
    <span class="badge">VIP</span><span class="badge">LVL 80</span>
    <h3>Conta FF Lendária</h3>
    <ul class="features">
      <li>Skins lendárias</li>
      <li>Emotes exclusivos</li>
      <li>Servidor BR</li>
    </ul>
    <div class="price">R$ 399,90</div>
    <a class="btn" href="#pix">Comprar com Pix</a>
  </div>
</div>

<h2 style="margin-top:24px">Como funciona</h2>
<div class="grid">
  <div class="card"><h3>1. Escolha</h3><p>Selecione a conta desejada.</p></div>
  <div class="card"><h3>2. Pagamento</h3><p>Pix/Cartão (integração externa).</p></div>
  <div class="card"><h3>3. Entrega</h3><p>Dados enviados após confirmação.</p></div>
</div>

<div style="margin-top:24px" class="card" id="pix">
  <h3>Pagamento via Pix</h3>
  <p><strong>Chave Pix:</strong> 92 98468-9322</p>
  <p>Tipo: Telefone</p>
  <p>Após o pagamento, envie o comprovante no WhatsApp para liberação da conta.</p>
  <img src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=PIX%3A%2092984689322" alt="QR Code Pix" />
  <br/><br/>
  <a class="btn secondary" href="#">Enviar comprovante no WhatsApp</a>
</div>

  </main>  <footer>
    © 2026 FF Store • Modelo demonstrativo
  </footer>
</body>
</html>
