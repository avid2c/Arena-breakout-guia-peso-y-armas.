<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Guía Hacker: Movilidad & Peso en Arena Breakout Mobile - avid2</title>

  <!-- SEO Meta Tags -->
  <meta name="description" content="Guía hacker para mejorar tu movilidad y peso en Arena Breakout Mobile, con análisis y recomendaciones para optimizar tu juego." />
  <meta name="keywords" content="Arena Breakout, movilidad, peso, penalización velocidad, guía, avid2" />
  <meta name="author" content="avid2" />
  <meta name="robots" content="index, follow" />

  <style>
    /* (Aquí va todo tu CSS tal cual está en el código anterior mejorado, para no repetirlo copia el CSS que te di antes) */
    /* Por ejemplo: */
    * { box-sizing: border-box; }
    body {
      margin: 0;
      background-color: #0f0f0f;
      color: #00ff00;
      font-family: 'Courier New', monospace;
      line-height: 1.6;
      padding: 20px 20px 20px 250px;
      transition: background-color 0.3s ease;
    }
    /* ... resto del CSS ... */
  </style>
</head>
<body>
  <nav aria-label="Navegación principal">
    <h2>Contenido</h2>
    <a href="#introduccion">Introducción</a>
    <a href="#peso-base">Peso base y efectos</a>
    <a href="#penalizacion-arma">Penalización por arma</a>
    <a href="#mods">Efectos de Mods</a>
    <a href="#no-influye">Lo que NO influye</a>
    <a href="#conclusiones">Conclusiones</a>
    <a href="#creditos">Créditos</a>
  </nav>

  <main>
    <h1>Guía Hacker: Velocidad de Movimiento & Peso en Arena Breakout Mobile</h1>
    <p><strong>Autor:</strong> <span class="highlight">avid2</span></p>

    <section id="introduccion" class="section" tabindex="0">
      <h2>📌 Introducción</h2>
      <p>¿Cómo afecta el peso al rendimiento de tu operador? ¿Qué tan ocultas están las penalizaciones en la velocidad de movimiento (VM)? Esta guía se basa en análisis <strong>empíricos, comparativos y deducciones directas</strong> realizadas por <strong>avid2</strong>, para que tú no tengas que romperte la cabeza.</p>
    </section>

    <!-- Resto de secciones idénticas al código anterior -->

    <section id="conclusiones" class="section" tabindex="0">
      <h2>🧠 Conclusiones & Recomendaciones</h2>
      <ul>
        <li>No cruces los <code>30 kg</code> si quieres mantener la resistencia óptima.</li>
        <li>Evita pasar los <code>45 kg</code> a toda costa: perderás 15% de VM instantáneamente.</li>
        <li>Explora mods de cañón que <strong>mejoren la VM sin afectar demasiado el retroceso</strong>.</li>
        <li>Los valores de penalización por tipo de arma son fijos y ocultos. Testea en la práctica.</li>
      </ul>
      <button class="copy-btn" aria-label="Copiar conclusiones y recomendaciones" onclick="copyConclusions()">Copiar recomendaciones</button>
    </section>

    <section id="creditos" class="section" tabindex="0">
      <h2>📢 Créditos</h2>
      <p>Esta guía fue creada por <span class="highlight">avid2</span>, mediante pruebas directas en <strong>Arena Breakout Mobile</strong>. Comparte esta info, mejora tus builds y motiva a otros a investigar.</p>
    </section>
  </main>

  <footer>
    <p>© 2025 avid2 - Guía no oficial para Arena Breakout Mobile.</p>
  </footer>

  <script>
    function copyConclusions() {
      const textToCopy = `Conclusiones & Recomendaciones:
- No cruces los 30 kg si quieres mantener la resistencia óptima.
- Evita pasar los 45 kg a toda costa: perderás 15% de VM instantáneamente.
- Explora mods de cañón que mejoren la VM sin afectar demasiado el retroceso.
- Los valores de penalización por tipo de arma son fijos y ocultos. Testea en la práctica.`;
      
      navigator.clipboard.writeText(textToCopy).then(() => {
        alert('Recomendaciones copiadas al portapapeles 👍');
      }, () => {
        alert('Error al copiar, intenta manualmente.');
      });
    }
  </script>
</body>
</html>
