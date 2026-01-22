<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MixInstrumental</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family: Arial, sans-serif;
}

body{
  background: linear-gradient(135deg,#141e30,#243b55);
  color:white;
}

/* MENÚ */
nav{
  position:fixed;
  top:0;
  width:100%;
  background:rgba(0,0,0,0.85);
  padding:15px;
  display:flex;
  justify-content:center;
  gap:30px;
  z-index:1000;
}

nav a{
  color:white;
  text-decoration:none;
  font-weight:bold;
}

nav a:hover{
  color:#00ffd5;
}

/* SECCIONES */
section{
  min-height:100vh;
  padding:100px 20px 50px;
  text-align:center;
}

/* INICIO */
#inicio h1{
  font-size:3em;
}

#inicio p{
  max-width:900px;
  margin:15px auto;
  font-size:1.2em;
  line-height:1.7;
}

/* COLLAGE */
.collage{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:15px;
  max-width:850px;
  margin:30px auto 0;
}

.collage img{
  width:100%;
  height:140px;
  object-fit:cover;
  border-radius:12px;
}

/* ACERCA */
#acerca{
  background:rgba(255,255,255,0.05);
}

#acerca p{
  max-width:950px;
  margin:15px auto;
  font-size:1.1em;
  line-height:1.7;
}

/* INSTRUMENTOS */
.instrumentos{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:30px;
  max-width:1200px;
  margin:auto;
}

.card{
  background:rgba(255,255,255,0.12);
  border-radius:15px;
  padding:20px;
}

.card img{
  width:100%;
  height:200px;
  object-fit:cover;
  border-radius:10px;
}

.card h3{
  margin:15px 0 10px;
}

.card p{
  font-size:0.95em;
  line-height:1.6;
}

/* CONTACTO */
#contacto{
  background:rgba(0,0,0,0.5);
}

#contacto p{
  font-size:1.1em;
  margin:10px 0;
}

footer{
  background:black;
  padding:15px;
  text-align:center;
  font-size:0.9em;
}
</style>
</head>

<body>

<nav>
  <a href="#inicio">Inicio</a>
  <a href="#acerca">Acerca de</a>
  <a href="#instrumentos">Instrumentos</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="inicio">
  <h1>MIXINSTRUMENTAL</h1>
  <p>
    MixInstrumental es una página creada para aprender sobre algunos de los
    instrumentos musicales más conocidos. Esta página busca explicar de una
    forma sencilla qué instrumentos existen, cómo se usan y qué tipo de sonido
    producen.
  </p>
  <p>
    El objetivo de MixInstrumental es ayudar a estudiantes y personas
    interesadas en la música a conocer mejor los instrumentos sin que sea
    complicado. Aquí encontrarás información clara, imágenes y explicaciones
    fáciles de entender.
  </p>
  <p>
    La música está presente en nuestra vida diaria y conocer los instrumentos
    nos permite entender mejor cómo se crean las canciones que escuchamos.
  </p>

  <div class="collage">
    <img src="https://images.unsplash.com/photo-1513883049090-d0b7439799bf" alt="Piano">
    <img src="https://images.unsplash.com/photo-1511379938547-c1f69419868d" alt="Guitarra">
    <img src="https://images.unsplash.com/photo-1507838153414-b4b713384a76" alt="Flauta">
    <img src="http://googleusercontent.com/image_collection/image_retrieval/7743947030537144015_0" alt="Violín">
  </div>
</section>

<section id="acerca">
  <h2>Acerca de</h2>
  <p>
    MixInstrumental fue creada como un proyecto educativo para aprender sobre
    la música y los instrumentos musicales. La idea de esta página es mostrar
    información de manera simple, sin palabras complicadas.
  </p>
  <p>
    Muchas veces escuchamos música sin saber qué instrumentos se usan o cómo
    funcionan. Por eso, esta página explica para qué sirve cada instrumento,
    cómo se toca y qué tipo de sonido produce.
  </p>
  <p>
    Conocer los instrumentos ayuda a valorar más la música y a entender el
    trabajo que hay detrás de cada canción. MixInstrumental busca despertar
    curiosidad e interés por el mundo musical.
  </p>
</section>

<section id="instrumentos">
  <h2>Instrumentos Musicales</h2>

  <div class="instrumentos">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1513883049090-d0b7439799bf" alt="Piano">
      <h3>Piano</h3>
      <p>
        El piano es un instrumento de teclado que produce sonido al golpear
        cuerdas internas. Se usa en muchos estilos musicales y puede sonar
        suave o muy fuerte dependiendo de cómo se toque.
      </p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1511379938547-c1f69419868d" alt="Guitarra">
      <h3>Guitarra</h3>
      <p>
        La guitarra es un instrumento de cuerdas pulsadas. Es muy popular en
        géneros como el rock, pop y música latina. Su sonido cambia según la
        técnica que se use.
      </p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1507838153414-b4b713384a76" alt="Flauta">
      <h3>Flauta</h3>
      <p>
        La flauta es un instrumento de viento que produce un sonido agudo y
        suave al soplar aire. Es común en música clásica y folklórica.
      </p>
    </div>

    <div class="card">
      <img src="http://googleusercontent.com/image_collection/image_retrieval/7743947030537144015_0" alt="Violín">
      <h3>Violín</h3>
      <p>
        El violín es un instrumento de cuerdas que se toca con un arco.
        Produce un sonido expresivo y emotivo, y es muy importante en la
        música clásica.
      </p>
    </div>

  </div>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <p>📞 +593 989 35 8015</p>
  <p>📧 mixinstrumental@email.com</p>
</section>

<footer>
  © 2026 MixInstrumental
</footer>

</body>
</html>
