<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vitamina K – Noticias que te tocan el bolsillo</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    *,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
    body{font-family:'Inter',sans-serif;background:#ffffff;color:#111;line-height:1.5}
    a{text-decoration:none;color:inherit}
    img{max-width:100%;display:block}

    header{background:#000;color:#facc15;padding:1.2rem}
    nav{display:flex;justify-content:space-between;align-items:center;gap:1.5rem;flex-wrap:wrap}
    nav ul{display:flex;list-style:none;gap:1rem}
    nav li{font-weight:600}
    nav a:hover{color:#facc15}
    .brand{font-size:1.5rem;font-weight:700;letter-spacing:.03em;color:#facc15}

    .hero{background:#fff;color:#000;padding:4rem 1.5rem;text-align:center}
    .hero h1{font-size:2rem;margin-bottom:.5rem;color:#d62828;}
    .hero p{opacity:.9;font-size:1.1rem}

    main{max-width:1080px;margin:2rem auto;padding:0 1.5rem;display:grid;gap:2rem}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:1.5rem}

    article{background:#f9f9f9;border-radius:.6rem;overflow:hidden;box-shadow:0 4px 12px rgba(0,0,0,.08);display:flex;flex-direction:column}
    article img{height:180px;object-fit:cover}
    article div{padding:1rem}
    .kicker{font-size:.75rem;text-transform:uppercase;letter-spacing:.05em;color:#facc15;margin-bottom:.4rem}
    article h2{font-size:1.2rem;margin-bottom:.5rem;color:#000}
    article p{font-size:.9rem;opacity:.85;margin-bottom:.8rem}
    .cta{margin-top:auto;font-weight:600;color:#d62828}

    footer{background:#000;color:#999;text-align:center;padding:1rem;font-size:.8rem;margin-top:3rem}
    footer a {color: #facc15; font-weight: bold;}
  </style>
</head>
<body>

<header>
  <nav>
    <span class="brand">Vitamina K</span>
    <ul>
      <li><a href="#">Inicio</a></li>
      <li><a href="#">Noticias</a></li>
      <li><a href="#">Contacto</a></li>
    </ul>
  </nav>
</header>

<section class="hero">
  <h1>No vine a caer bien. Vine a no caerme nunca.</h1>
  <p>La web de los que madrugan, se indignan y actúan. Aquí las noticias no se maquillan: se exponen.</p>
</section>

<main>
  <h2 style="color:#d62828">Últimas publicaciones</h2>
  <div class="grid">
    <!-- CARD 1 -->
    <article>
      <img src="https://via.placeholder.com/640x360?text=Calculadora+de+Impuestos" alt="">
      <div>
        <span class="kicker">HERRAMIENTA</span>
        <h2>Calculadora: ¿Cuánto te roba el Estado al año?</h2>
        <p>Introduce tus ingresos y descubre cuántos días trabajas solo para pagar impuestos.</p>
        <a href="#" class="cta">Probar ahora →</a>
      </div>
    </article>

    <!-- CARD 2 -->
    <article>
      <img src="https://via.placeholder.com/640x360?text=Corrupci%C3%B3n+al+descubierto" alt="">
      <div>
        <span class="kicker">DENUNCIA</span>
        <h2>El último escándalo del PSOE explicado en 3 pasos</h2>
        <p>Una publicación que no verás en medios subvencionados. Lo contamos claro y sin miedo.</p>
        <a href="#" class="cta">Leer más →</a>
      </div>
    </article>

    <!-- CARD 3 -->
    <article>
      <img src="https://via.placeholder.com/640x360?text=Datos+que+duelen" alt="">
      <div>
        <span class="kicker">ECONOMÍA</span>
        <h2>¿En qué país te quitan 8 meses de sueldo?</h2>
        <p>En España. Te lo explicamos con cifras y comparativas reales.</p>
        <a href="#" class="cta">Descúbrelo aquí →</a>
      </div>
    </article>
  </div>
</main>

<footer>
  © 2025 Vitamina K · Hecho con coraje y sin filtros · <a href="https://www.instagram.com/vitaminak.of" target="_blank">@vitaminak.of</a>
</footer>

</body>
</html>

