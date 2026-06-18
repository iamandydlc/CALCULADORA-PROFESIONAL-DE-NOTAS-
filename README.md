<img src="1781661864344.png" alt="Logo oficial ADEX Escuela de Especialización" class="max-w-[230px] md:max-w-[260px] mx-auto block anim-flotar drop-shadow-[0_4px_10px_rgba(0,0,0,0.28)]">

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Unidad Didáctica: Creatividad e Innovación | ADEX • Grupo 3</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            adex: {
              azulOscuro: '#002B80',
              azulMedio: '#003399',
              azulCorporativo: '#0047B3',
              azulClaro: '#0055CC',
              azulDestacado: '#1A75FF',
              grisTexto: '#1E293B',
              grisSuave: '#334155',
              negroRecurso: '#1A1A1A',
              azulEvalGrupal: '#003377',
              marronEvalIndiv: '#704214',
              violetaCE: '#7A20B0',
            },
          },
          fontFamily: {
            sans: ['Inter', 'Segoe UI', 'Roboto', 'Arial', 'sans-serif'],
          },
          boxShadow: {
            'institucional': '0 10px 30px rgba(0, 43, 128, 0.22)',
            'profundo': '0 16px 45px rgba(0, 43, 128, 0.30)',
          }
        }
      }
    }
  </script>
  <style type="text/tailwindcss">
    @layer utilities {
      @keyframes entradaSuave {
        from { opacity: 0; transform: translateY(-20px); }
        to { opacity: 1; transform: translateY(0); }
      }
      @keyframes escalaSutil {
        from { opacity: 0; transform: scale(0.96); }
        to { opacity: 1; transform: scale(1); }
      }
      @keyframes flotacionLigera {
        0%, 100% { transform: translateY(0px); }
        50% { transform: translateY(-4px); }
      }
      @keyframes recorridoBrillo {
        0% { background-position: -250% center; }
        100% { background-position: 250% center; }
      }

      .anim-entrada { animation: entradaSuave 1.1s ease forwards; }
      .anim-escala { animation: escalaSutil 1.3s ease forwards; }
      .anim-flotar { animation: flotacionLigera 5s ease-in-out infinite; }
      .retraso-1 { animation-delay: 0.25s; opacity: 0; }
      .retraso-2 { animation-delay: 0.45s; opacity: 0; }
      .retraso-3 { animation-delay: 0.65s; opacity: 0; }
      .retraso-4 { animation-delay: 0.85s; opacity: 0; }

      .bordeIluminado { position: relative; overflow: hidden; }
      .bordeIluminado::after {
        content: ''; position: absolute; top: 0; left: 0; width: 100%; height: 100%;
        background: linear-gradient(90deg, transparent, rgba(255,255,255,0.18), transparent);
        background-size: 250% auto;
        animation: recorridoBrillo 4s linear infinite;
        pointer-events: none;
      }

      .tabla-academica { @apply w-full border-collapse rounded-xl overflow-hidden; }
      .tabla-academica th { @apply bg-adex-azulOscuro text-white font-semibold py-3.5 px-3.5 text-center text-sm md:text-base tracking-wide; }
      .tabla-academica td { @apply border border-adex-azulClaro/20 py-3 px-3 text-sm md:text-base text-adex-grisTexto transition-all hover:bg-adex-azulClaro/8; }
    }
  </style>
</head>
<body class="bg-gradient-to-br from-adex-azulOscuro via-adex-azulMedio to-adex-azulClaro min-h-screen font-sans text-white overflow-x-hidden">

  <div class="fixed -z-0 w-full h-full opacity-5">
    <div class="absolute w-80 h-80 rounded-full bg-white blur-3xl top-12 -left-16"></div>
    <div class="absolute w-[28rem] h-[28rem] rounded-full bg-white blur-3xl bottom-12 -right-16"></div>
  </div>

  <main class="relative z-10 max-w-4xl mx-auto px-4 py-10 md:py-16">

    <div class="anim-entrada mb-8">
      <img src="1781661864344.png" alt="Logo oficial ADEX Escuela de Especialización" class="max-w-[230px] md:max-w-[260px] mx-auto block anim-flotar drop-shadow-[0_4px_10px_rgba(0,0,0,0.28)]">
    </div>

    <section class="anim-escala retraso-1 bg-white/10 backdrop-blur-md border border-white/25 rounded-xl px-6 py-4 mb-10 max-w-lg mx-auto text-center shadow-institucional">
      <h3 class="text-lg md:text-xl font-bold uppercase tracking-[0.15em] mb-3 text-white">Grupo 3</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-x-6 gap-y-1.5 text-sm md:text-[0.98rem] text-white/95 font-light">
        <p>• Jhon Dayron Zárate</p>
        <p>• Joel Hualpa</p>
        <p>• Luis Yaranga</p>
        <p>• Orlando Zacarías</p>
        <p>• Matías Martinez</p>
        <p>• Andi De la Cruz</p>
        <p>• Fatima</p>
      </div>
    </section>

    <header class="anim-escala retraso-2 text-center mb-14 md:mb-20">
      <div class="inline-block px-6 py-2 rounded-full bg-white/10 backdrop-blur-md border border-white/25 mb-5">
        <span class="text-sm font-medium tracking-widest uppercase">Material Académico Oficial</span>
      </div>
      <h1 class="text-[clamp(2rem,5vw,3.4rem)] font-extrabold tracking-tight mb-5 drop-shadow-md">Creatividad e Innovación</h1>
      <p class="text-[clamp(1.1rem,2.5vw,1.4rem)] text-white/90 max-w-2xl mx-auto font-light leading-relaxed">Unidad Didáctica • ADEX Escuela de Especialización</p>
      <div class="w-32 h-1 bg-white/60 mx-auto mt-9 rounded-full shadow-lg"></div>
    </header>

    <section class="anim-escala retraso-3 bg-white/97 backdrop-blur-lg text-adex-grisTexto rounded-2xl md:rounded-3xl p-6 md:p-10 shadow-profundo bordeIluminado transition-all duration-500 hover:scale-[1.01] hover:shadow-profundo mb-10">
      <div class="flex items-center gap-3 mb-7 border-b border-adex-azulClaro/20 pb-4">
        <i class="fa fa-list-alt text-adex-azulDestacado text-2xl"></i>
        <h2 class="text-xl md:text-2xl font-bold text-adex-azulOscuro">Estructura de la Unidad Didáctica</h2>
      </div>
      <div class="grid md:grid-cols-4 gap-6 items-start">
        <div class="md:col-span-3 overflow-x-auto">
          <table class="tabla-academica bg-white">
            <thead><tr><th colspan="2" class="bg-adex-azulCorporativo">Planificación: 14 Semanas Académicas</th></tr></thead>
            <tbody>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 1</td><td>Sesión 1 • Foro participativo — Evaluación diagnóstica</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 2</td><td>Sesión 2 • Desarrollo y participación activa</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 3</td><td>Sesión 3 • Desarrollo y participación activa</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 4</td><td>Sesión 4 • Desarrollo y participación activa</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 5</td><td>Sesión 5 • Cuestionario de verificación</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 6</td><td>Sesión 6 • Actividad CE — Evidencia evaluativa N°1</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 7</td><td>Sesión 7 • Foro participativo</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 8</td><td>Sesión 8 • Desarrollo y participación activa</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 9</td><td>Sesión 9 • Cuestionario de verificación</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 10</td><td>Sesión 10 • Actividad CE — Evidencia evaluativa N°2</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 11</td><td>Sesión 11 • Foro participativo</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 12</td><td>Sesión 12 • Desarrollo y participación activa</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 13</td><td>Sesión 13 • Cuestionario + Actividad complementaria CE</td></tr>
              <tr><td class="font-medium bg-adex-azulClaro/10">Semana 14</td><td>Sesión 14 • Cierre — Evidencia evaluativa final N°3</td></tr>
            </tbody>
          </table>
        </div>
        <div class="bg-adex-azulOscuro/6 p-4 rounded-xl border border-adex-azulClaro/20">
          <h3 class="font-bold text-adex-azulOscuro mb-3 text-center text-base">📘 LEYENDA</h3>
          <div class="space-y-3 text-sm">
            <div class="flex items-center gap-2"><span class="w-5 h-5 bg-adex-negroRecurso rounded-sm"></span><span class="text-adex-grisSuave">Recursos para desarrollo</span></div>
            <div class="flex items-center gap-2"><span class="w-5 h-5 bg-adex-azulEvalGrupal rounded-sm"></span><span class="text-adex-grisSuave">Evaluaciones grupales</span></div>
            <div class="flex items-center gap-2"><span class="w-5 h-5 bg-adex-marronEvalIndiv rounded-sm"></span><span class="text-adex-grisSuave">Evaluaciones individuales</span></div>
            <div class="flex items-center gap-2"><span class="w-5 h-5 bg-adex-violetaCE rounded-sm"></span><span class="text-adex-grisSuave">Actividades CE — Empleabilidad</span></div>
          </div>
        </div>
      </div>
    </section>

    <section class="anim-escala retraso-4 bg-white/97 backdrop-blur-lg text-adex-grisTexto rounded-2xl md:rounded-3xl p-6 md:p-10 shadow-profundo bordeIluminado transition-all duration-500 hover:scale-[1.01] hover:shadow-profundo mb-10">
      <div class="flex items-center gap-3 mb-7 border-b border-adex-azulClaro/20 pb-4">
        <i class="fa fa-balance-scale text-adex-azulDestacado text-2xl"></i>
        <h2 class="text-xl md:text-2xl font-bold text-adex-azulOscuro">Sistema de Evaluación Continua</h2>
      </div>
      <div class="space-y-8">
        <div class="overflow-x-auto">
          <table class="tabla-academica bg-white max-w-md mx-auto">
            <thead><tr><th>SESIÓN</th><th>EVALUACIÓN</th><th>PESO TOTAL</th></tr></thead>
            <tbody>
              <tr class="bg-adex-azulClaro/12"><td class="text-center font-medium">6</td><td class="text-center">EC1</td><td class="text-center font-bold text-adex-azulOscuro">20 %</td></tr>
              <tr class="bg-adex-azulClaro/12"><td class="text-center font-medium">10</td><td class="text-center">EC2</td><td class="text-center font-bold text-adex-azulOscuro">35 %</td></tr>
              <tr class="bg-adex-azulClaro/12"><td class="text-center font-medium">14</td><td class="text-center">EC3</td><td class="text-center font-bold text-adex-azulOscuro">45 %</td></tr>
            </tbody>
          </table>
        </div>
        <div class="flex flex-col md:flex-row items-center justify-center gap-6 text-center">
          <div class="font-semibold text-adex-azulOscuro">EVALUACIÓN CONTINUA</div>
          <i class="fa fa-long-arrow-down text-adex-azulDestacado text-xl rotate-90 md:rotate-0"></i>
          <div class="bg-adex-azulClaro/10 p-5 rounded-xl border border-adex-azulClaro/30 max-w-sm">
            <h4 class="font-bold text-adex-azulOscuro mb-3 text-sm">Desglose por actividad:</h4>
            <table class="tabla-academica bg-white text-sm">
              <thead><tr><th>Actividad</th><th>Peso</th></tr></thead>
              <tbody>
                <tr><td>1 Foro • Coevaluación</td><td class="text-center font-medium">10 %</td></tr>
                <tr><td>1 Participación activa • Heteroevaluación</td><td class="text-center font-medium">20 %</td></tr>
                <tr><td>1 Cuestionario • Calificación automática</td><td class="text-center font-medium">20 %</td></tr>
                <tr><td>1 Evidencia evaluativa • Heteroevaluación</td><td class="text-center font-bold">50 %</td></tr>
              </tbody>
            </table>
          </div>
        </div>
        <div class="bg-adex-azulOscuro/95 text-white p-4 rounded-xl mt-3 text-sm italic shadow-institucional">
          <i class="fa fa-info-circle mr-2"></i> Estas actividades serán definidas y comunicadas previamente por el docente, considerando intervenciones orales, trabajo colaborativo, responsabilidad y comunicación efectiva.
        </div>
      </div>
    </section>

    <section class="anim-escala retraso-4 bg-white/97 backdrop-blur-lg text-adex-grisTexto rounded-2xl md:rounded-3xl p-6 md:p-10 shadow-profundo bordeIluminado transition-all duration-500 hover:scale-[1.01] hover:shadow-profundo">
      <div class="flex items-center gap-3 mb-6 border-b border-adex-azulClaro/20 pb-4">
        <i class="fa fa-book-open text-adex-azulDestacado text-2xl"></i>
        <h2 class="text-xl md:text-2xl font-bold text-adex-azulOscuro">Desarrollo del Contenido</h2>
      </div>
      <div class="leading-relaxed text-base md:text-lg">
        <p class="text-adex-grisSuave">✅ <strong>Espacio listo:</strong> Aquí insertas todo el desarrollo teórico, definiciones, conceptos y actividades correspondientes a cada sesión. Todo mantendrá la identidad oficial y formato académico.</p>
      </div>
    </section>

    <footer class="anim-escala retraso-4 mt-14 text-center text-white/80 text-sm backdrop-blur-sm py-4 border-t border-white/15">
      <p><i class="fa fa-university mr-2"></i> ADEX Escuela de Especialización • Unidad Didáctica: Creatividad e Innovación — Grupo 3</p>
    </footer>

  </main>
</body>
</html>
