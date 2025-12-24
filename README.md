
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Docerola Studio</title>
  <!-- Tailwind CDN (rápido para demo). Para producción conviene compilar Tailwind o usar CSS propio -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="min-h-screen bg-slate-900 text-white">
  <div id="root"></div>

  <!-- Si tu build ya exporta el bundle (p. ej. DocerolaStudio.min.js) y monta la app en #root -->
  <script src="DocerolaStudio.min.js"></script>

  <!-- Alternativa: si trabajas con módulos / desarrollo local, incluye Tone.js y midiwriter-js en index.html
       o usa import dinámico desde el componente (el componente en src/ contiene la lógica). -->
  <!-- Ejemplo de inclusión CDN (opcional para demos): -->
  <!--
  <script src="https://cdn.jsdelivr.net/npm/tone@14.7.77/build/Tone.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/midiwriter-js@2.1.0/build/index.umd.js"></script>
  -->

</body>
</html>