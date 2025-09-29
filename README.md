[index.html](https://github.com/user-attachments/files/22607241/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Corporación Surtitodo Internacional</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #f9f9f9; color: #333; }
    header { background: #1a1a1a; color: #fff; padding: 20px 40px; display: flex; align-items: center; justify-content: flex-start; gap: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.3); }
    header img { height: 70px; width: auto; }
    header h1 { margin: 0; font-size: 2.2em; line-height: 1.2; }
    nav { background: #333; padding: 12px; text-align: center; }
    nav a { color: #fff; text-decoration: none; margin: 0 15px; font-weight: bold; font-size: 1em; }
    nav a:hover { text-decoration: underline; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    h2 { color: #1a1a1a; margin-bottom: 15px; }
    .cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { background: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
    footer { background: #1a1a1a; color: #fff; text-align: center; padding: 20px; margin-top: 30px; }
    a.catalogo { display: inline-block; margin-top: 15px; color: #1a73e8; text-decoration: none; font-weight: bold; }
    a.catalogo:hover { text-decoration: underline; }
  </style>
</head>
<body>
  <header>
    <img src="https://i.ibb.co/6M77cwG/logo.png" alt="Logo Surtitodo">
    <h1>Corporación Surtitodo Internacional</h1>
  </header>

  <nav>
    <a href="#nosotros">Quiénes somos</a>
    <a href="#sucursales">Sucursales</a>
    <a href="#envios">Envíos</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="nosotros">
    <h2>Quiénes somos</h2>
    <p>En <strong>Surtitodo</strong> ofrecemos una amplia variedad de productos a precios bajos: higiene personal, cosméticos, juguetes, carteras, peluches y mucho más. Atendemos a un público diverso, siempre con calidad y servicio al cliente.</p>
    <a href="https://linktr.ee/surtitodoint" class="catalogo" target="_blank">Ver catálogo completo</a>
  </section>

  <section id="sucursales">
    <h2>Nuestras sucursales</h2>
    <div class="cards">
      <div class="card">
        <h3>Central</h3>
        <p>📍 18 calle 3-30 zona 1, local B, Ciudad de Guatemala</p>
      </div>
      <div class="card">
        <h3>Calzada San Juan</h3>
        <p>📍 Calzada San Juan 37-10 zona 7, colonia El Rodeo</p>
      </div>
    </div>
  </section>

  <section id="envios">
    <h2>Envíos y formas de pago</h2>
    <ul>
      <li>Pago contra entrega: Q26.00</li>
      <li>Envío previo depósito: Q18.00</li>
    </ul>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>📞 3884-3742 / 3677-1008 / 3020-5190</p>
    <p>✉️ Escríbenos para más información sobre productos y pedidos al por mayor.</p>
  </section>

  <footer>
    <p>&copy; 2025 Corporación Surtitodo Internacional | Todos los derechos reservados</p>
  </footer>
</body>
</html>
