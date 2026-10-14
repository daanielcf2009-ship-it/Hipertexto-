# Hipertexto-
Hipertexto lenguaje 
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hipertexto de textos funcionales</title>
<style>
:root{--azul:#173b63;--celeste:#e8f3ff;--azul2:#2d6da3;--blanco:#fff;--gris:#f5f7fa;--verde:#2e8b57;--amarillo:#f5b942}
*{box-sizing:border-box}
body{margin:0;font-family:Arial,Helvetica,sans-serif;background:linear-gradient(135deg,#edf6ff,#fff);color:#1f2937}
header{background:linear-gradient(135deg,#173b63,#2d6da3);color:white;padding:34px 18px;text-align:center}
header h1{margin:0 0 8px;font-size:clamp(28px,5vw,48px)}
header p{margin:5px auto;max-width:800px;font-size:17px}
nav{position:sticky;top:0;z-index:10;background:#fff;box-shadow:0 2px 12px #0002;display:flex;flex-wrap:wrap;justify-content:center;gap:8px;padding:10px}
nav a{background:#e8f3ff;color:#173b63;text-decoration:none;font-weight:bold;padding:10px 14px;border-radius:22px;transition:.2s}
nav a:hover{background:#2d6da3;color:white;transform:translateY(-2px)}
main{max-width:1100px;margin:auto;padding:25px 16px 60px}
section{background:white;border-radius:18px;padding:25px;margin:22px 0;box-shadow:0 6px 22px #173b6312;border:1px solid #dce8f3}
.view{display:none;animation:fade .25s ease}
.view.active{display:block}
@keyframes fade{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}
.home-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:16px;margin-top:22px}
.home-card{background:linear-gradient(145deg,#f8fbff,#e8f3ff);border:1px solid #cfe1f2;border-radius:18px;padding:20px;text-align:center;box-shadow:0 5px 15px #173b6312}
.home-card h3{margin:8px 0;color:#173b63}
.home-card p{min-height:42px}
.back{display:inline-block;margin-top:18px;text-decoration:none;background:#173b63;color:#fff;padding:11px 16px;border-radius:10px;font-weight:bold}
.back:hover{background:#2d6da3}
.cover{padding:34px 25px}
.cover h2{font-size:32px}
.cover-sub{font-size:18px;color:#52667a}
.rubric{background:#fff9e8;border:1px solid #f0d58a;border-radius:14px;padding:15px;margin-top:20px}
h2{color:#173b63;margin-top:0}
h3{color:#2d6da3}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:15px}
.card{background:var(--gris);border-left:5px solid #2d6da3;border-radius:12px;padding:17px}
.card strong{color:#173b63}
.type-card{display:flex;flex-direction:column;justify-content:space-between}
.btn{border:0;border-radius:10px;background:#2d6da3;color:#fff;padding:11px 15px;font-weight:bold;cursor:pointer;margin-top:10px}
.btn:hover{background:#173b63}
.example{display:none;background:#fff;border:1px dashed #2d6da3;border-radius:12px;padding:15px;margin-top:12px}
.example.show{display:block}
.example p{margin:7px 0}
.badge{display:inline-block;background:#e8f3ff;color:#173b63;padding:5px 9px;border-radius:20px;font-size:13px;font-weight:bold}
.flow{display:flex;flex-wrap:wrap;gap:10px;align-items:center;justify-content:center;margin:20px 0}
.flow span{background:#173b63;color:#fff;padding:12px 16px;border-radius:12px}
.arrow{font-size:25px;color:#2d6da3}
.quiz button{display:block;width:100%;text-align:left;background:#f5f7fa;color:#1f2937;border:1px solid #d9e1e8;padding:12px;border-radius:10px;margin:8px 0;cursor:pointer}
.quiz button:hover{background:#e8f3ff}
#result{font-weight:bold;margin-top:12px}
footer{text-align:center;background:#173b63;color:#fff;padding:22px}
.small{font-size:14px;color:#667085}
</style>
</head>
<body>
<header>
  <div class="badge">COMUNICACIÓN ORAL Y ESCRITA</div>
  <h1>Hipertexto de textos funcionales</h1>
  <p>Una manera divertida para conocer qué son, para qué sirven y cómo se utilizan los principales textos funcionales.</p>
</header>

<nav>
  <a href="#inicio">🏠 Portada</a>
  <a href="#que son">📘 ¿Qué son?</a>
  <a href="#tipos">📄 Tipos</a>
  <a href="#ejemplos">🔎 Ejemplos</a>
  <a href="#recursos">🌐 Recursos</a>
  <a href="#quiz">🎮 Juego</a>
  <a href="#conclusion">✅ Conclusión</a>
</nav>

<main>
<section id="inicio" class="view cover">
  <div class="badge">COMUNICACIÓN ORAL Y ESCRITA</div>
  <h2>📚 Hipertexto de textos funcionales</h2>
  <p class="cover-sub">Un recorrido interactivo por los textos funcionales, sus características, funciones y ejemplos.</p>
  <div class="flow">
    <span>Informar</span><b class="arrow">→</b><span>Solicitar</span><b class="arrow">→</b><span>Organizar</span><b class="arrow">→</b><span>Dejar constancia</span>
  </div>
  <h3>Explora el trabajo</h3>
  <div class="home-grid">
    <div class="home-card"><div style="font-size:34px">📘</div><h3>1. ¿Qué son?</h3><p>Definición y características de los textos funcionales.</p><a class="btn" href="#que-son">Entrar</a></div>
    <div class="home-card"><div style="font-size:34px">📄</div><h3>2. Tipos</h3><p>Oficios, actas, solicitudes, circulares, memorandos y correos.</p><a class="btn" href="#tipos">Entrar</a></div>
    <div class="home-card"><div style="font-size:34px">🔎</div><h3>3. Ejemplos</h3><p>Comparación rápida de los seis tipos y su función.</p><a class="btn" href="#ejemplos">Entrar</a></div>
    <div class="home-card"><div style="font-size:34px">🌐</div><h3>4. Recursos</h3><p>Videos y enlaces para ampliar el tema.</p><a class="btn" href="#recursos">Entrar</a></div>
    <div class="home-card"><div style="font-size:34px">🎮</div><h3>5. Juego</h3><p>Cuestionario para comprobar lo aprendido.</p><a class="btn" href="#quiz">Entrar</a></div>
    <div class="home-card"><div style="font-size:34px">✅</div><h3>6. Conclusión</h3><p>Idea final sobre la utilidad de estos textos.</p><a class="btn" href="#conclusion">Entrar</a></div>
  </div>
  <div class="rubric"><strong>⭐ Enfoque de la evaluación:</strong> información completa, ejemplos de cada tipo, presentación visual creativa, enlaces interactivos y texto claro y ordenado.</div>
  <p class="small" style="margin-top:20px">Para cambiar de apartado, primero vuelve a la Portada.</p>
</section>

<section id="que-son" class="view">
  <h2>1. ¿Qué son los textos funcionales?</h2>
  <p>Son textos escritos principalmente para cumplir una función específica en una situación real. Su objetivo es que el mensaje sea claro, ordenado y útil para el que lo recibe.</p>
  <div class="grid">
    <div class="card"><strong>🎯 Propósito claro</strong><br>Indican qué se quiere comunicar o conseguir.</div>
    <div class="card"><strong>📝 Información precisa</strong><br>Presentan los datos necesarios sin complicar el mensaje.</div>
    <div class="card"><strong>📌 Orden</strong><br>La información se organiza para facilitar su comprensión.</div>
    <div class="card"><strong>👥 Destinatario</strong><br>Se escriben pensando en una persona o grupo específico.</div>
    <div class="card"><strong>🗣️ Lenguaje adecuado</strong><br>El tono cambia según la situación y el destinatario.</div>
    <div class="card"><strong>⚙️ Utilidad</strong><br>Sirven para realizar una acción o comunicar algo importante.</div>
  </div>

  <a class="back" href="#inicio">← Volver a la portada</a>
</section>

<section id="tipos" class="view">
  <h2>2. Tipos de textos funcionales</h2>
  <p>Selecciona «Ver ejemplo» para descubrir la función y un ejemplo breve de cada tipo solicitado.</p>
  <div class="grid">

    <div class="card type-card"><div><h3>📄 Oficio</h3><p>Documento formal usado para comunicar asuntos oficiales entre instituciones, autoridades o personas.</p><p><strong>Características:</strong> formalidad, fecha, destinatario, asunto, cuerpo y firma.</p></div><button class="btn" onclick="toggle('oficio')">Ver ejemplo</button><div id="oficio" class="example"><strong>Ejemplo:</strong><p>«OFICIO No. 05-2026.</p><p>San Pedro Carchá, 12 de octubre de 2026.</p><p>Señora Directora: Por medio del presente oficio solicitamos autorización para realizar una actividad académica.»</p></div></div>

    <div class="card type-card"><div><h3>📋 Acta</h3><p>Documento que deja constancia de lo ocurrido, acordado o tratado durante una reunión.</p><p><strong>Características:</strong> fecha, lugar, participantes, asuntos tratados, acuerdos y firmas.</p></div><button class="btn" onclick="toggle('acta')">Ver ejemplo</button><div id="acta" class="example"><strong>Ejemplo:</strong><p>«ACTA No. 03</p><p>En San Pedro Carchá, siendo las 10:00 horas, se reunieron los estudiantes del grupo. Se acordó entregar el proyecto el viernes. Firman los participantes.»</p></div></div>

    <div class="card type-card"><div><h3>✉️ Solicitud</h3><p>Escrito mediante el cual una persona pide formalmente algo a una autoridad o institución.</p><p><strong>Características:</strong> petición clara, motivo, datos del solicitante, fecha y firma.</p></div><button class="btn" onclick="toggle('solicitud')">Ver ejemplo</button><div id="solicitud" class="example"><strong>Ejemplo:</strong><p>«SOLICITUD</p><p>San Pedro Carcha, 12 dde octubre de 2006</p><p>Por este medio solicito autorización para utilizar el salón de actos el día viernes para una exposición escolar.»</p></div></div>

    <div class="card type-card"><div><h3>📢 Circular</h3><p>Mensaje escrito que comunica una información a varias personas de una institución o grupo.</p><p><strong>Características:</strong> información general, destinatarios múltiples, claridad y fecha.</p></div><button class="btn" onclick="toggle('circular')">Ver ejemplo</button><div id="circular" class="example"><strong>Ejemplo:</strong><p>«CIRCULAR No. 04-2026</p><p>Se informa a todos los estudiantes que el próximo lunes las clases iniciarán a las 8:00 horas.</p><p>Atentamente:</p><p>Direccion»</p></div></div>

    <div class="card type-card"><div><h3>🗒️ Memorando</h3><p>Comunicación breve utilizada dentro de una organización para transmitir instrucciones, avisos o información.</p><p><strong>Características:</strong> breve, directo, asunto, destinatario, remitente y fecha.</p></div><button class="btn" onclick="toggle('memo')">Ver ejemplo</button><div id="memo" class="example"><strong>Ejemplo:</strong><p>«MEMORANDO. Para: Equipo de trabajo. Asunto: Entrega de materiales. Se solicita entregar los materiales antes del jueves.</p><p>Direccion»</p></div></div>

    <div class="card type-card"><div><h3>📧 Correo electrónico</h3><p>Mensaje digital que permite enviar información rápidamente a una o varias personas.</p><p><strong>Características:</strong> destinatario, asunto, saludo, mensaje, despedida y, si es necesario, archivos adjuntos.</p></div><button class="btn" onclick="toggle('correo')">Ver ejemplo</button><div id="correo" class="example"><strong>Ejemplo:</strong><p>«Asunto: Entrega del proyecto.Buenas tardes, profesora. Le envío adjunto nuestro proyecto de textos funcionales. Saludos.»</p></div></div>
  </div>

  <a class="back" href="#inicio">← Volver a la portada</a>
</section>

<section id="ejemplos" class="view">
  <h2>3. ¿Qué tienen en común?</h2>
  <div class="grid">
    <div class="card"><strong>Información:</strong><br>Presentan datos necesarios para cumplir su propósito.</div>
    <div class="card"><strong>Función:</strong><br>Cada texto responde a una necesidad específica.</div>
    <div class="card"><strong>Estructura:</strong><br>Usan una organización que ayuda a comprender el mensaje.</div>
    <div class="card"><strong>Contexto:</strong><br>Se adaptan a la situación y a las personas que participan.</div>
  </div>
  <h3>Comparación rápida</h3>
  <div style="overflow-x:auto">
  <table style="width:100%;border-collapse:collapse">
    <tr style="background:#173b63;color:white"><th style="padding:10px">Texto</th><th>Función principal</th><th>Uso común</th></tr>
    <tr><td style="padding:10px;border:1px solid #ddd">Oficio</td><td style="border:1px solid #ddd">Comunicación formal</td><td style="border:1px solid #ddd">Instituciones</td></tr>
    <tr><td style="padding:10px;border:1px solid #ddd">Acta</td><td style="border:1px solid #ddd">Dejar constancia</td><td style="border:1px solid #ddd">Reuniones</td></tr>
    <tr><td style="padding:10px;border:1px solid #ddd">Solicitud</td><td style="border:1px solid #ddd">Pedir algo</td><td style="border:1px solid #ddd">Trámites</td></tr>
    <tr><td style="padding:10px;border:1px solid #ddd">Circular</td><td style="border:1px solid #ddd">Informar a varios</td><td style="border:1px solid #ddd">Instituciones</td></tr>
    <tr><td style="padding:10px;border:1px solid #ddd">Memorando</td><td style="border:1px solid #ddd">Avisar o instruir</td><td style="border:1px solid #ddd">Trabajo</td></tr>
    <tr><td style="padding:10px;border:1px solid #ddd">Correo</td><td style="border:1px solid #ddd">Comunicar digitalmente</td><td style="border:1px solid #ddd">Estudio y trabajo</td></tr>
  </table>
  </div>

  <a class="back" href="#inicio">← Volver a la portada</a>
</section>

<section id="recursos" class="view">
  <h2>4. Recursos interactivos y enlaces</h2>
  <p>Estos recursos complementan el tema y convierten el trabajo en un hipertexto, porque permiten navegar y consultar información relacionada.</p>
  <div class="grid">
    <div class="card"><h3>🎥 Video</h3><p>Explicación complementaria sobre textos funcionales.</p><a class="btn" style="display:inline-block;text-decoration:none" target="_blank" href="https://www.youtube.com/results?search_query=textos+funcionales">Abrir videos</a></div>
    <div class="card"><h3>🌐 Consulta</h3><p>Busca más ejemplos y definiciones del tema.</p><a class="btn" style="display:inline-block;text-decoration:none" target="_blank" href="https://www.google.com/search?q=textos+funcionales+ejemplos">Investigar</a></div>
    <div class="card"><h3>🎮 Juego</h3><p>Comprueba lo aprendido en el cuestionario de esta página.</p><a class="btn" style="display:inline-block;text-decoration:none" href="#inicio">Volver a la portada</a></div>
  </div>

  <a class="back" href="#inicio">← Volver a la portada</a>
</section>

<section id="quiz" class="view" class="quiz">
  <h2>5. 🎮 Juego: ¿Cuánto aprendiste?</h2>
  <p>Responde las preguntas. Al final podrás ver tu puntuación.</p>
  <p><strong>1. ¿Cuál es la función principal de un acta?</strong></p>
  <button onclick="answer(this,false)">Pedir permiso para realizar una actividad.</button>
  <button onclick="answer(this,true)">Dejar constancia de lo ocurrido o acordado en una reunión.</button>
  <button onclick="answer(this,false)">Enviar un mensaje informal a un amigo.</button>

  <p><strong>2. ¿Cuál se usa para pedir algo formalmente?</strong></p>
  <button onclick="answer(this,true)">Solicitud.</button>
  <button onclick="answer(this,false)">Acta.</button>
  <button onclick="answer(this,false)">Circular.</button>

  <p><strong>3. ¿Cuál puede enviarse por medios digitales?</strong></p>
  <button onclick="answer(this,false)">Acta únicamente.</button>
  <button onclick="answer(this,true)">Correo electrónico.</button>
  <button onclick="answer(this,false)">Oficio únicamente.</button>

  <p><strong>4. ¿Qué característica ayuda a que un texto funcional sea fácil de comprender?</strong></p>
  <button onclick="answer(this,true)">Claridad y organización.</button>
  <button onclick="answer(this,false)">Usar palabras innecesariamente complicadas.</button>
  <button onclick="answer(this,false)">No indicar el propósito.</button>

  <p id="result">Puntuación: 0/4</p>
  <button class="btn" onclick="location.reload()">Reiniciar juego</button>

  <a class="back" href="#inicio">← Volver a la portada</a>
</section>

<section id="conclusion" class="view">
  <h2>✅ Conclusión</h2>
  <p>Los textos funcionales son útiles en la vida escolar, laboral y cotidiana porque permiten informar, solicitar, organizar y dejar constancia de diferentes situaciones. Conocer su función, características y estructura ayuda a comunicar mensajes claros y adecuados.</p>
  <p class="small">Trabajo hipertextos funcionales.</p>

  <a class="back" href="#inicio">← Volver a la portada</a>
</section>
</main>

<footer>Hipertexto de textos funcionales</footer>

<script>
let score=0, answered=0;

function toggle(id){
  document.getElementById(id).classList.toggle('show');
}

function answer(btn,correct){
  if(btn.dataset.done)return;
  btn.dataset.done="1";
  answered++;
  btn.style.background=correct ? "#dff4e7" : "#ffe3e3";
  btn.style.borderColor=correct ? "#2e8b57" : "#c94c4c";
  if(correct)score++;
  document.getElementById('result').textContent="Puntuación: "+score+"/4";
}

function showPage(){
  const id=location.hash ? location.hash.substring(1) : "inicio";
  const valid=["inicio","que-son","tipos","ejemplos","recursos","quiz","conclusion"];
  const target=valid.includes(id) ? id : "inicio";
  document.querySelectorAll(".view").forEach(v=>v.classList.remove("active"));
  document.getElementById(target).classList.add("active");
  window.scrollTo(0,0);
}

window.addEventListener("hashchange",showPage);
window.addEventListener("DOMContentLoaded",showPage);
</script>
</body>
</html>
