<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Seguridad Digital Integral</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    /* ====== Base ====== */
    *,*::before,*::after{box-sizing:border-box}
    body{margin:0;background:#f5f7fb;color:#212529;font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif}
    .container{width:min(1200px,92%);margin:0 auto;padding:30px 0}

    header{background:linear-gradient(135deg,#1e3c72,#2a5298);color:#fff;padding:30px 0;text-align:center;box-shadow:0 4px 12px rgba(0,0,0,.1);position:relative}
    .logo{font-size:2.2rem;font-weight:800;margin-bottom:8px}
    .logo span{color:#4adede}
    .tagline{opacity:.9}

    /* ====== Dropdown Nosotros ====== */
    .about-dropdown{position:absolute;top:18px;left:18px;z-index:10}
    .dropdown-btn{background:rgba(255,255,255,.2);color:#fff;border:0;padding:8px 14px;border-radius:999px;cursor:pointer;font-weight:700;display:flex;align-items:center;gap:6px}
    .dropdown-btn:hover{background:rgba(255,255,255,.3)}
    .dropdown-content{position:absolute;top:calc(100% + 8px);left:0;background:#fff;border-radius:10px;box-shadow:0 10px 28px rgba(0,0,0,.18);width:min(92vw,320px);opacity:0;visibility:hidden;transform:translateY(8px);transition:.2s}
    .about-dropdown:hover .dropdown-content{opacity:1;visibility:visible;transform:translateY(0)}
    .mission-vision{padding:14px;color:#333}
    .mission-vision h3{margin:6px 0 8px;color:#2a5298;font-size:1rem}
    .mission-vision p{margin:0 0 10px;font-size:.95rem;line-height:1.5}
    .mission-vision div{padding:10px;background:#f8f9fa;border-radius:8px;margin-bottom:8px}

    h2{margin:6px 0 18px;text-align:center;color:#2c3e50;font-size:2rem;position:relative;padding-bottom:14px}
    h2::after{content:"";position:absolute;bottom:0;left:50%;transform:translateX(-50%);width:80px;height:3px;background:#3498db;border-radius:2px}

    /* ====== Nuevo diseño tipo tarjeta (como la imagen) ====== */
    .products{display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:26px;margin-top:16px}
    .card{background:#fff;border-radius:16px;box-shadow:0 10px 24px rgba(0,0,0,.08);overflow:hidden;display:flex;flex-direction:column}
    .card-header{padding:24px 20px;display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:160px;color:#fff;position:relative}
    .badge{position:absolute;right:14px;top:14px;background:#e74c3c;color:#fff;font-weight:800;border-radius:999px;padding:4px 10px;font-size:.8rem}
    .brand{font-size:.9rem;letter-spacing:2px;font-weight:800;margin-bottom:10px;opacity:.92;text-transform:uppercase}
    .title{font-size:1.5rem;margin:6px 0 0;font-weight:800;text-align:center}

    .card-body{background:#fff;padding:20px}
    .features{list-style:none;margin:0 0 14px;padding:0}
    .features li{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid #eef0f4}
    .features li:before{content:"✓";color:#2ecc71;font-weight:900}

    .price{font-size:1.9rem;font-weight:900;color:#e74c3c;text-align:center;margin:14px 0 18px}
    .price span{font-size:1rem;color:#7f8c8d;font-weight:600}

    .btn{display:block;width:100%;background:linear-gradient(90deg,#2f86e6,#243b55);color:#fff;text-align:center;padding:12px 18px;border:0;border-radius:999px;font-weight:800;cursor:pointer;transition:transform .15s, box-shadow .15s}
    .btn:hover{transform:translateY(-1px);box-shadow:0 10px 16px rgba(36,59,85,.25)}

    /* Colores por marca (como en el original) */
    .avast{background:linear-gradient(135deg,#ff7800,#fa5b0f)}
    .kaspersky{background:linear-gradient(135deg,#00a8e8,#0077cc)}
    .eset{background:linear-gradient(135deg,#d62d20,#a31c1c)}
    .norton{background:linear-gradient(135deg,#ffb800,#ff8c00)}
    .mcafee{background:linear-gradient(135deg,#c00,#a00)}

    /* ====== Modal (del primer código) ====== */
    .checkout-overlay{position:fixed;inset:0;background:rgba(0,0,0,.7);display:none;justify-content:center;align-items:center;z-index:1000;overflow-y:auto;padding:20px}
    .checkout-form{background:#fff;width:min(600px,92vw);border-radius:12px;padding:26px;box-shadow:0 18px 36px rgba(0,0,0,.28);position:relative}
    .close-btn{position:absolute;top:10px;right:12px;font-size:1.5rem;cursor:pointer;color:#7f8c8d;border:0;background:transparent}
    .form-group{margin-bottom:16px}
    .form-group label{display:block;margin-bottom:6px;font-weight:700;color:#2c3e50}
    .form-control{width:100%;padding:12px 14px;border:1px solid #ddd;border-radius:8px;font-size:1rem}
    .form-row{display:flex;gap:12px}
    .form-row .form-group{flex:1}
    .payment-methods{display:flex;gap:12px;margin:16px 0}
    .payment-method{flex:1;padding:14px;border:2px solid #ddd;border-radius:10px;text-align:center;cursor:pointer}
    .payment-method.selected{border-color:#3498db;background:#f8fafc}
    .payment-icon{font-size:1.6rem;color:#3498db;margin-bottom:6px}
    .selected-product{background:#f8f9fa;padding:12px;border-radius:10px;margin-bottom:16px;text-align:center}
    .selected-product h4{margin:0 0 4px}
    .selected-product .price{margin:0;font-size:1.25rem;color:#e74c3c;font-weight:800}

    footer{background:#2c3e50;color:#fff;text-align:center;padding:28px 0;margin-top:46px}
  </style>
</head>
<body>
  <header>
    <div class="about-dropdown">
      <button class="dropdown-btn"><i class="fas fa-info-circle"></i> Nosotros</button>
      <div class="dropdown-content">
        <div class="mission-vision">
          <div>
            <h3>Misión</h3>
            <p>Proteger a los usuarios y empresas del municipio de Amatitlán y sus alrededores contra amenazas cibernéticas, ofreciendo soluciones de seguridad digital accesibles y de calidad.</p>
          </div>
          <div>
            <h3>Visión</h3>
            <p>Ser la página líder en venta y asesoría de antivirus en Amatitlán, reconocida por su compromiso con la ciberseguridad accesible y la innovación tecnológica.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="logo">Seguridad <span>Digital Integral</span></div>
      <p class="tagline">Protección premium para tus dispositivos</p>
    </div>
  </header>

  <main class="container">
    <section id="productos">
      <h2>Antivirus Premium</h2>
      <p style="text-align:center;margin-bottom:22px">Selecciona la mejor protección para tus dispositivos</p>

      <div class="products">
        <!-- AVAST -->
        <article class="card">
          <header class="card-header avast">
            <span class="badge">Más vendido</span>
            <div class="brand">AVAST</div>
            <h3 class="title">Premium Security</h3>
          </header>
          <div class="card-body">
            <ul class="features">
              <li>Protección contra ransomware</li>
              <li>VPN incluida</li>
              <li>Cortafuegos inteligente</li>
              <li>Protección de webcam</li>
              <li>Para 10 dispositivos</li>
            </ul>
            <div class="price">Q120.00 <span>/año</span></div>
            <button class="btn buy-btn" data-brand="AVAST" data-product="Premium Security" data-price="120.00">Comprar Ahora</button>
          </div>
        </article>

        <!-- KASPERSKY -->
        <article class="card">
          <header class="card-header kaspersky">
            <div class="brand">KASPERSKY</div>
            <h3 class="title">Total Security</h3>
          </header>
          <div class="card-body">
            <ul class="features">
              <li>Protección multicapa</li>
              <li>Pago seguro</li>
              <li>Control parental</li>
              <li>Protección para Mac</li>
              <li>Para 5 dispositivos</li>
            </ul>
            <div class="price">Q110.00 <span>/año</span></div>
            <button class="btn buy-btn" data-brand="KASPERSKY" data-product="Total Security" data-price="110.00">Comprar Ahora</button>
          </div>
        </article>

        <!-- ESET -->
        <article class="card">
          <header class="card-header eset">
            <span class="badge">Recomendado</span>
            <div class="brand">ESET</div>
            <h3 class="title">Smart Security</h3>
          </header>
          <div class="card-body">
            <ul class="features">
              <li>Antivirus de última generación</li>
              <li>Protección bancaria</li>
              <li>Anti‑phishing</li>
              <li>Bajo consumo de recursos</li>
              <li>Para 3 dispositivos</li>
            </ul>
            <div class="price">Q100.00 <span>/año</span></div>
            <button class="btn buy-btn" data-brand="ESET" data-product="Smart Security" data-price="100.00">Comprar Ahora</button>
          </div>
        </article>

        <!-- NORTON -->
        <article class="card">
          <header class="card-header norton">
            <div class="brand">NORTON</div>
            <h3 class="title">360 Deluxe</h3>
          </header>
          <div class="card-body">
            <ul class="features">
              <li>Protección en tiempo real</li>
              <li>VPN ilimitada</li>
              <li>Backup en la nube</li>
              <li>Control parental</li>
              <li>Para 5 dispositivos</li>
            </ul>
            <div class="price">Q200.00 <span>/año</span></div>
            <button class="btn buy-btn" data-brand="NORTON" data-product="360 Deluxe" data-price="200.00">Comprar Ahora</button>
          </div>
        </article>

        <!-- MCAFEE -->
        <article class="card">
          <header class="card-header mcafee">
            <span class="badge">Mejor valorado</span>
            <div class="brand">MCAFEE</div>
            <h3 class="title">Total Protection</h3>
          </header>
          <div class="card-body">
            <ul class="features">
              <li>Protección antivirus</li>
              <li>Seguridad en redes WiFi</li>
              <li>Optimizador de rendimiento</li>
              <li>Protección de identidad</li>
              <li>Para 10 dispositivos</li>
            </ul>
            <div class="price">Q300.00 <span>/año</span></div>
            <button class="btn buy-btn" data-brand="MCAFEE" data-product="Total Protection" data-price="300.00">Comprar Ahora</button>
          </div>
        </article>
      </div>
    </section>
  </main>

  <!-- ====== Modal de compra (como el primer código) ====== -->
  <div class="checkout-overlay" id="checkout-overlay">
    <div class="checkout-form">
      <button class="close-btn" id="close-btn" aria-label="Cerrar">&times;</button>
      <h2>Finalizar Compra</h2>

      <div class="selected-product">
        <h4 id="selected-product-name"></h4>
        <p class="price" id="selected-product-price"></p>
      </div>

      <form id="payment-form">
        <div class="form-group">
          <label for="full-name">Nombre Completo</label>
          <input type="text" id="full-name" class="form-control" required>
        </div>
        <div class="form-group">
          <label for="email">Correo Electrónico</label>
          <input type="email" id="email" class="form-control" required>
        </div>

        <h3>Método de Pago</h3>
        <div class="payment-methods">
          <div class="payment-method selected" data-method="credit">
            <i class="far fa-credit-card payment-icon"></i>
            <div>Tarjeta de Crédito</div>
          </div>
          <div class="payment-method" data-method="debit">
            <i class="fas fa-credit-card payment-icon"></i>
            <div>Tarjeta de Débito</div>
          </div>
        </div>

        <div class="form-group">
          <label for="card-number">Número de Tarjeta</label>
          <input type="text" id="card-number" class="form-control" placeholder="1234 5678 9012 3456" required>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label for="card-expiry">Fecha de Expiración</label>
            <input type="text" id="card-expiry" class="form-control" placeholder="MM/AA" required>
          </div>
          <div class="form-group">
            <label for="card-cvc">Código CVC</label>
            <input type="text" id="card-cvc" class="form-control" placeholder="123" required>
          </div>
        </div>

        <button type="submit" class="btn">Confirmar Pago</button>
      </form>
    </div>
  </div>

  <footer>
    <div class="container">
      <p>&copy; 2025 Seguridad Digital Integral. Todos los derechos reservados.</p>
      <p><strong>Fundadores:</strong> Diego de León y Evelyn Aguilar</p>
    </div>
  </footer>

  <script>
    // Abrir modal con la info del producto
    document.querySelectorAll('.buy-btn').forEach(btn=>{
      btn.addEventListener('click', function(){
        const brand=this.getAttribute('data-brand');
        const product=this.getAttribute('data-product');
        const price=this.getAttribute('data-price');
        document.getElementById('selected-product-name').textContent=`${brand} ${product}`;
        document.getElementById('selected-product-price').textContent=`Q${price}/año`;
        document.getElementById('checkout-overlay').style.display='flex';
        document.querySelector('.checkout-form').scrollTo(0,0);
      });
    });

    // Cerrar modal
    document.getElementById('close-btn').addEventListener('click',()=>{
      document.getElementById('checkout-overlay').style.display='none';
    });
    document.getElementById('checkout-overlay').addEventListener('click',function(e){ if(e.target===this){ this.style.display='none'; }});

    // Seleccionar método de pago
    document.querySelectorAll('.payment-method').forEach(m=>{
      m.addEventListener('click', function(){
        document.querySelectorAll('.payment-method').forEach(x=>x.classList.remove('selected'));
        this.classList.add('selected');
      });
    });

    // Simular envío del formulario
    document.getElementById('payment-form').addEventListener('submit', function(e){
      e.preventDefault();
      alert('¡Compra realizada con éxito!\n\n(Esta es una simulación para fines educativos)');
      document.getElementById('checkout-overlay').style.display='none';
      this.reset();
    });
  </script>
</body>
</html>
