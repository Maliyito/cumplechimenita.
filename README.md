# felizc cumple chimenita.
-Mali
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>¡Feliz Cumpleaños, Chimenita!</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Dancing+Script&display=swap');
  body {
    margin: 0; padding: 0; background: #1c1f26;
    color: #dcdde1; font-family: 'Montserrat', sans-serif;
    overflow-x: hidden; 
  }
  .heart {
    position: fixed; font-size: 2rem; color: #f08a5d;
    pointer-events: none; animation: float 6s ease-in infinite;
  }
  @keyframes float {
    0% { transform: translateY(100vh) scale(0); }
    50% { opacity: 1; }
    100% { transform: translateY(-10vh) scale(1); }
  }
  /* Secciones */
  section { padding: 60px 20px; position: relative; z-index: 1; }
  #intro { text-align: center; }
  #intro h1 {
    font-family: 'Dancing Script', cursive;
    font-size: 3.5em; color: #f8a5c2;
    opacity: 0; animation: fadeIn 2s forwards;
  }
  @keyframes fadeIn { to { opacity: 1; } }
  #intro h2 { font-size: 1.4em; color: #7f8fa6; margin-top: -10px; }
  .container { max-width: 700px; margin: auto;
    background: #2f3640; border-radius: 15px;
    padding: 30px; box-shadow: 0 0 25px #3a3f47;
  }
  .phrase { font-style: italic; margin: 20px 0;
    border-left: 4px solid #f8a5c2; padding-left: 15px;
  }
  .message {
    line-height: 1.6; margin: 25px 0;
  }
  .btn { background: #f08a5d; color: #fff;
    padding: 12px 20px; border: none; border-radius: 8px;
    font-size: 1.1em; cursor: pointer;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  }
  .stickers { display: flex; flex-wrap: wrap;
    justify-content: center; gap: 20px;
  }
  .stickers img { width: 100px; border-radius: 12px;
    transition: transform 0.3s;
  }
  .stickers img:hover { transform: scale(1.1); }
  iframe { border: none; border-radius: 12px; }
  #surprise { display: none; text-align: center; margin-top: 30px; }
  #surprise p { font-size: 1.3em; color: #f8a5c2; }
</style>
</head>
<body>

<!-- Corazones flotando -->
<script>
  for (let i=0;i<20;i++){
    const h = document.createElement('div');
    h.textContent = '❤️';
    h.className='heart';
    h.style.left = Math.random()*100+'vw';
    h.style.fontSize = (1+Math.random()*2)+'rem';
    h.style.animationDelay = Math.random()*6+'s';
    h.style.animationDuration = (4+Math.random()*4)+'s';
    document.body.appendChild(h);
  }
</script>

<section id="intro">
  <h1>¡Feliz Cumpleaños, Chimenita!</h1>
  <h2>🎂✨</h2>
</section>

<section id="carta">
  <div class="container">
    <h3 style="text-align:center; font-family:'Dancing Script',cursive; font-size:2em; color:#f8a5c2">Carta para ti</h3>
    <p class="message">
      No sabes cuánto valoro tenerte en mi vida. Eres mi apoyo, mi risa en los días difíciles y la persona con quien puedo ser totalmente yo.<br><br>
      Gracias por estar siempre aunque no pueda verte, por las pláticas diarias que tanto amo, y por hacerme sentir que ninguna distancia me impediría amarte tanto ni hacerme sentir amada.<br><br>
      Te amo muchísimo Chimenita, pero te amo con el alma porque el corazón deja de latir, y el alma nunca muere. Espero que nuestra amistad dure toda la vida.
    </p>
  </div>
</section>

<section id="frases">
  <div class="container">
    <h3 style="text-align:center; font-family:'Dancing Script',cursive; font-size:2em; color:#f8a5c2">Frases</h3>
    <p class="phrase">"Always forever"</p>
    <p class="phrase">"You’re my best friend, you’re my one and only."</p>
    <p class="phrase">"Gracias por ser mi compañera de risas, secretos y sueños sin límites."</p>
    <p class="phrase">"A tu lado aprendí que la verdadera amistad no tiene tiempo ni distancia."</p>
    <p class="phrase">"Aunque estemos lejos, nuestra amistad siempre nos mantiene cerca del corazón."</p>
    <p class="phrase">"QUE TE PASA LUPITAA"</p>
  </div>
</section>

<section id="galeria">
  <div class="container">
    <h3 style="text-align:center; font-family:'Dancing Script',cursive; font-size:2em; color:#f8a5c2">Galería</h3>
    <div class="stickers">
      <img src="https://mx.pinterest.com/pin/1196337404438267/" alt=https://mx.pinterest.com/pin/1196337404438267/  
      <img src="[https://mx.pinterest.com/pin/119556565103763056/)">" alt="[https://mx.pinterest.com/pin/119556565103763056/)">
      <img src="https://mx.pinterest.com/pin/1114359501530093361/">" alt="https://mx.pinterest.com/pin/1114359501530093361/">
      <img src="https://mx.pinterest.com/pin/381539399709831795/">" alt="https://mx.pinterest.com/pin/381539399709831795/">
    </div>
  </div>
</section>

<section id="playlist">
  <div class="container">
    <h3 style="text-align:center; font-family:'Dancing Script',cursive; font-size:2em; color:#f8a5c2">Playlist para ti</h3>
    <iframe src="https://open.spotify.com/embed/playlist/4aiD8DLNXpkf8yeitFgCwV" width="100%" height="380" allow="encrypted-media"></iframe>
  </div>
</section>

<section id="musica">
  <div class="container">
    <h3 style="text-align:center; font-family:'Dancing Script',cursive; font-size:2em; color:#f08a5d">Música de fondo</h3>
    <iframe width="100%" height="200" src="https://www.youtube.com/embed/c3aN6Tv4WLA?autoplay=1&loop=1&playlist=c3aN6Tv4WLA" allow="autoplay" ></iframe>
  </div>
</section>

<section id="sorpresa">
  <div class="container" style="text-align:center;">
    <button class="btn" onclick="reveal()">Haz clic aquí ❤️</button>
    <div id="surprise">
      <p> Gracias por ser parte de mi vida. Felices 15 añitos mi chimenita linda, esperó seguir siendo parte de tu vida muchos años más.</p>
    </div>
  </div>
</section>

<script>
  function reveal(){
    document.getElementById('surprise').style.display='block';
  }
</script>

<footer style="text-align:center; padding:30px; color:#7f8fa6">
  Hecho con 💖 por Mayito para Chimenita
</footer>
</body>
</html>
