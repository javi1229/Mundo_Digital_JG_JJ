<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mundo Digital</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f7fa;
      color: #333;
    }

    header {
      background-image: url('wrike-1024x513.jpg.webp');
      background-size: cover;
      background-position: center;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      position: relative;
    }

    header::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.6); /* Overlay oscurecido */
    }

    header h1 {
      font-size: 3.5rem;
      margin: 0;
      z-index: 2;
    }

    header p {
      font-size: 1.5rem;
      margin: 15px 0 30px;
      z-index: 2;
    }

    nav {
      background-color: #333;
      padding: 10px 0;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 3;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    nav ul li {
      margin: 0 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1rem;
      padding: 10px 20px;
      transition: background-color 0.3s ease;
    }

    nav ul li a:hover {
      background-color: #555;
      border-radius: 5px;
    }

    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: 0 auto;
      text-align: center;
    }

    section h2 {
      color: #333;
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    section p {
      font-size: 1.2rem;
      line-height: 1.8;
      margin-bottom: 30px;
      color: #666;
    }

    .gallery img {
      width: 100%;
      max-width: 100%;
      border-radius: 10px;
      margin-bottom: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 40px 20px;
      margin-top: 40px;
      position: relative;
      z-index: 1;
    }

    footer p {
      margin: 0;
    }

    /* Responsividad */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2.5rem;
      }

      header p {
        font-size: 1.2rem;
      }

      nav ul li {
        margin: 0 10px;
      }
    }

    @media (max-width: 480px) {
      header h1 {
        font-size: 2rem;
      }

      header p {
        font-size: 1rem;
      }

      nav ul {
        flex-direction: column;
        background-color: #444;
        position: absolute;
        top: 50px;
        left: 0;
        width: 100%;
        display: none;
      }

      nav ul.active {
        display: flex;
      }

      nav ul li {
        margin: 10px 0;
      }

      .menu-toggle {
        background-color: #333;
        color: white;
        font-size: 2rem;
        cursor: pointer;
        border: none;
        position: absolute;
        right: 20px;
        top: 10px;
        z-index: 4;
      }

      nav ul li a {
        display: block;
        text-align: center;
        padding: 15px 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Miles de personas ya confían en Mundo Digital</h1>
    <p>Explora el mundo de la tecnología con nosotros</p>
  </header>

  <nav>
    <button class="menu-toggle">☰</button>
    <ul id="navMenu">
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#sociedad-digital">Sociedad Digital</a></li>
      <li><a href="#codigo-ascii">Código ASCII</a></li>
      <li><a href="#digital-vs-analogico">Digital vs Analógico</a></li>
      <li><a href="#hardware">Hardware</a></li>
      <li><a href="#internet">Internet</a></li>
      <li><a href="#software">Software</a></li>
      <li><a href="#redes-de-computadoras">Redes de Computadoras</a></li>
    </ul>
  </nav>

  <section id="inicio">
    <h2>Bienvenido a Mundo Digital</h2>
    <div class="gallery">
      <img src="https://blog.interfell.com/hubfs/Qu%C3%A9%20est%C3%A1%20pasando%20en%20la%20industria%20de%20la%20tecnolog%C3%ADa.jpg" alt="Industria de la tecnología">
      <p>Nuestro sitio está dedicado a compartir descripciones extensas de las funciones básicas y complejas de la tecnología actual en nuestro mundo.</p>
    </div>
  </section>

  <section id="sociedad-digital">
    <h2>Sociedad digital</h2>
    <div>
      <h3>Amazon, Instagram</h3>
      <img src="https://static.wixstatic.com/media/d2252d_4c1a1bda6a774bd68f789c0770fd16e5~mv2.png" width="500" alt="Amazon">
      <img src="https://static.vecteezy.com/system/resources/previews/023/986/514/original/instagram-logo-instagram-logo-transparent-instagram-icon-transparent-free-free-png.png" width="500" alt="Instagram">
      <p>Definición:</strong> La sociedad digital es un entorno social en el que las tecnologías digitales desempeñan un papel central en la vida diaria , afectando profundamente las formas de comunicación, interacción, trabajo, educación, comercio y entretenimiento. En una sociedad digital, las tecnologías de la información y la comunicación (TIC), como internet, dispositivos móviles, redes sociales y aplicaciones, se integran en casi todos los aspectos de la vida, facilitando el acceso a la información, la conectividad global y la automatización de procesos.

Estas sociedades se caracterizan por la digitalización de datos, la interconectividad de personas y sistemas a través de redes digitales, y la influencia creciente de la inteligencia artificial, la nube y la computación en la nube en la toma de decisiones, la producción de bienes y servicios, y la forma en que las personas se relacionan entre sí y con el entorno. La sociedad digital también plantea nuevos desafíos en términos de privacidad, seguridad, desigualdad y ética. </p>
  <section id="codigo-ascii">
    <h2>Código ASCII</h2>
    <p>El código ASCII (American Standard Code for Information Interchange) es un sistema de codificación de caracteres que asigna un valor numérico a cada símbolo, letra y número utilizado en el alfabeto inglés y en los sistemas informáticos. Desarrollado en la década de 1960, ASCII utiliza un conjunto de 255 códigos, donde cada carácter se representa por un número entero entre 0 y 255.</p>

<p>Por ejemplo:

    El carácter "A" tiene un valor ASCII de 65.
    El carácter "a" tiene un valor ASCII de 97.
  El número "0" tiene un valor ASCII de 48.</p>

Los primeros 32 códigos (0-31) están reservados para caracteres de control, como el salto de línea y el retorno de carro, que no son visibles pero controlan la forma en que los datos son transmitidos o procesados. ASCII es fundamental para la comunicación entre dispositivos electrónicos y la representación de texto en computadoras.</p>
    <div class="ascii">
      <img src="https://www.nobbot.com/wp-content/uploads/2020/08/Ascii.jpg" width="700" alt="Tabla ASCII">
    </div>
  </section>

  <section id="digital-vs-analogico">
    <h2>Digital vs Analógico</h2>
    <p>La tecnología digital convierte la información en bits, lo que permite una mayor precisión y versatilidad en su manipulación. Por otro lado, la tecnología analógica utiliza señales continuas que pueden ser más vulnerables a la distorsión. Ambas tienen sus ventajas dependiendo de la aplicación, pero la tecnología digital ha ganado terreno en la era moderna debido a su eficiencia y capacidad para procesar grandes volúmenes de datos.</p>
    <img src="https://hardzone.es/app/uploads-hardzone.es/2021/04/analogico-vs-digital.jpg" width="700" alt=500"">
  </section>

  <section id="hardware">
    <h2>Hardware</h2>
    <p>Se refiere a todos los componentes físicos de un sistema informático. Esto incluye cualquier parte tangible de una computadora u otro dispositivo electrónico que se pueda ver y tocar. El hardware abarca una amplia gama de dispositivos y componentes, como:</p>
    <ul>
      <li><strong>Procesador (CPU)</strong>:El cerebro de la computadora, responsable de ejecutar instrucciones y realizar cálculos.</li>
      <li><strong>Memoria RAM</strong>: Almacena temporalmente los datos y programas que la CPU necesita acceder rápidamente.</li>
      <li><strong>Disco duro o SSD</strong>:Dispositivos de almacenamiento donde se guardan datos de manera permanente, como el sistema operativo, aplicaciones y archivos personales.</li>
      <li><strong>Placa base</strong>:  La tarjeta principal que conecta todos los componentes del hardware entre sí.</li>
      <li><strong>Tarjetas de expansión</strong>:  Incluyen tarjetas gráficas, de sonido, de red, entre otras, que añaden funcionalidades adicionales al sistema.</li>
      <li><strong>Periféricos</strong>:  Dispositivos externos como el teclado, ratón, monitor, impresora y altavoces que permiten la interacción con la computadora.</li>
    </ul>
    <img src="https://cdn.educba.com/academy/wp-content/uploads/2019/12/Types-of-Computer-Hardware-1-1.jpg" width="700" alt="Tipos de hardware">
  </section>

  <section id="internet">
    <h2>Internet</h2>
    <p>Internet es una red global de computadoras interconectadas que permite la comunicación y el intercambio de información a través de protocolos estándar, principalmente el Protocolo de Internet (IP). Se compone de millones de redes privadas, públicas, académicas, comerciales y gubernamentales conectadas entre sí, permitiendo el acceso a servicios y recursos como la World Wide Web (WWW), el correo electrónico, redes sociales, transmisión de datos, videojuegos en línea y más.</p>

<p>Internet funciona mediante el uso de una infraestructura física (como cables de fibra óptica, satélites, routers y servidores) que transporta la información en forma de paquetes de datos. Estos paquetes son transmitidos de un punto a otro a través de rutas que dependen de la topología de la red.</p>

      Las principales características de Internet incluyen:</p>
    <strong> Acceso global</strong> : Permite a las personas conectarse y comunicarse desde cualquier parte del mundo.
    <strong> Interoperabilidad</strong>: Sistemas y dispositivos de diferentes tipos pueden comunicarse entre sí utilizando estándares comunes.
    <strong>Descentralización</strong>: No existe una entidad única que controle todo Internet; es una red distribuida.</p>
    <img src="https://www.gaceta.unam.mx/wp-content/uploads/2019/03/internet002.png" width="700" alt="Infraestructura de Internet">
  </section>

  <section id="software">
    <h2>Software</h2>
    <p>El software es el conjunto de programas que permiten a los dispositivos electrónicos realizar tareas. Se divide en tres categorías principales: software de sistema (como los sistemas operativos), software de aplicación (como navegadores y procesadores de texto) y software de desarrollo (herramientas para programadores).</p>
    <img src="https://miro.medium.com/v2/resize:fit:1000/1*Y2W4-N-hAfNg-86-jgY0lg.jpeg" width="700" alt="Tipos de software">
  </section>

  <section id="redes-de-computadoras">
    <h2>Redes de computadoras</h2>
    <p>Una red de computadoras es un conjunto de dispositivos interconectados que comparten recursos e información entre sí mediante el uso de canales de comunicación, como cables, fibra óptica o conexiones inalámbricas. Estas redes permiten que computadoras, servidores, impresoras, y otros dispositivos, llamados nodos, se comuniquen y colaboren, facilitando la transferencia de datos y la ejecución de tareas compartidas.</p>

      <p>Según su tamaño y alcance:

    LAN (Local Area Network): Una red de área local que conecta dispositivos en un área geográfica pequeña, como una oficina o un hogar.
     WAN (Wide Area Network) : Una red de área amplia que cubre grandes distancias geográficas, como una ciudad, un país o incluso el mundo (como es el caso de Internet).
    MAN (Metropolitan Area Network): Una red que abarca un área más grande que una LAN, pero más pequeña que una WAN, como una ciudad o campus universitario.</p>

    Según su topología:

   Red en estrella : Los nodos están conectados a un dispositivo central, como un switch o un router.
    Red en bus: Todos los nodos están conectados a un solo cable o línea de comunicación.
    Red en anillo: Los nodos forman un círculo y cada uno está conectado a sus vecinos inmediatos.

   Software de aplicación: Son los programas diseñados para realizar tareas específicas, como procesadores de texto (Microsoft Word), navegadores web (Google Chrome), programas de edición gráfica (Photoshop), y aplicaciones móviles.

    Software de desarrollo: Herramientas utilizadas por programadores para crear nuevos programas y aplicaciones, como los entornos de desarrollo (IDEs) y lenguajes de programación (Java, Python).</p>

      Las principales características de Internet incluyen:</p>
    Acceso global: Permite a las personas conectarse y comunicarse desde cualquier parte del mundo.</p>
    Interoperabilidad: Sistemas y dispositivos de diferentes tipos pueden comunicarse entre sí utilizando estándares comunes.</p>
    Descentralización: No existe una entidad única que controle todo Internet; es una red distribuida.</p></p>
    <img src="https://3.bp.blogspot.com/-eBvKmR8giYE/Vfpv7VcFNZI/AAAAAAAAEOk/VhLxb85OofM/s1600/red2.png" width="700" alt="Topologías de red">
  </section>
  
<footer>
    <p>&copy; 2024 Mundo Digital. Todos los derechos reservados.</p>
  </footer>

  <script>
    const menuToggle = document.querySelector('.menu-toggle');
    const navMenu = document.querySelector('#navMenu');

    menuToggle.addEventListener('click', () => {
      navMenu.classList.toggle('active');
    });
  </script>

</body>
</html>

/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

/* Body */
body {
  font-family: 'Poppins', sans-serif;
  background-color: #f0f4f8;
  color: #333;
  line-height: 1.8;
  transition: background-color 0.5s ease, color 0.5s ease;
}

body.dark-mode {
  background-color: #181818;
  color: #f0f0f0;
}

/* Header */
header {
  background: linear-gradient(120deg, #84fab0, #8fd3f4);
  color: white;
  text-align: center;
  padding: 120px 20px;
  border-bottom-left-radius: 60% 10%;
  border-bottom-right-radius: 60% 10%;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
  position: relative;
  overflow: hidden;
}

header::before {
  content: '';
  position: absolute;
  top: 0;
  left: -50%;
  width: 200%;
  height: 100%;
  background: radial-gradient(circle, rgba(255,255,255,0.2) 30%, transparent 70%);
  animation: pulse 10s infinite;
}

@keyframes pulse {
  0% { transform: translateX(0); }
  100% { transform: translateX(50%); }
}

header h1 {
  font-size: 4em;
  letter-spacing: 4px;
  text-transform: uppercase;
  margin-bottom: 20px;
  animation: bounceIn 1s ease-in-out;
}

header p {
  font-size: 1.6em;
  font-weight: 300;
  letter-spacing: 2px;
  margin-bottom: 15px;
  animation: fadeInUp 1s ease-in-out;
}

/* Navigation */
nav {
  background-color: rgba(255, 255, 255, 0.9);
  padding: 20px 0;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
  position: sticky;
  top: 0;
  z-index: 1000;
  backdrop-filter: blur(10px);
  transition: background-color 0.5s ease;
}

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
}

nav ul li {
  margin: 0 25px;
}

nav ul li a {
  color: #333;
  font-size: 1.2em;
  text-decoration: none;
  padding: 12px 28px;
  border-radius: 50px;
  transition: all 0.3s ease;
}

nav ul li a:hover {
  background-color: #8fd3f4;
  color: #fff;
  box-shadow: 0 10px 30px rgba(143, 211, 244, 0.4);
  transform: translateY(-4px);
}

/* Main Sections */
section {
  background-color: #fff;
  margin: 60px auto;
  padding: 80px;
  max-width: 1100px;
  border-radius: 30px;
  box-shadow: 0 12px 40px rgba(0, 0, 0, 0.15);
  transition: transform 0.4s ease, box-shadow 0.4s ease;
}

section:hover {
  transform: translateY(-12px);
  box-shadow: 0 18px 50px rgba(0, 0, 0, 0.25);
}

section.dark-mode {
  background-color: #2a2a2a;
}

h2 {
  font-size: 3em;
  color: #333;
  margin-bottom: 30px;
  font-weight: bold;
  position: relative;
}

h2::after {
  content: '';
  position: absolute;
  width: 100px;
  height: 5px;
  background-color: #8fd3f4;
  bottom: -15px;
  left: 0;
}

h2.dark-mode {
  color: #f0f0f0;
}

p {
  font-size: 1.4em;
  color: #666;
  line-height: 1.8;
  margin-bottom: 35px;
}

p.dark-mode {
  color: #bbb;
}

/* Cards */
.card {
  background: linear-gradient(145deg, #f5f5f5, #e2e2e2);
  border-radius: 20px;
  box-shadow: 10px 10px 30px rgba(0, 0, 0, 0.1), -10px -10px 30px rgba(255, 255, 255, 0.6);
  padding: 30px;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 15px 50px rgba(0, 0, 0, 0.15);
}

.card.dark-mode {
  background: linear-gradient(145deg, #343434, #2c2c2c);
}

/* Images */
img {
  display: block;
  max-width: 100%;
  border-radius: 25px;
  transition: transform 0.5s ease, box-shadow 0.5s ease;
}

img:hover {
  transform: scale(1.08);
  box-shadow: 0 15px 50px rgba(0, 0, 0, 0.25);
}

/* Footer */
footer {
  background-color: #1a1a1a;
  color: white;
  text-align: center;
  padding: 60px 20px;
  margin-top: 80px;
  box-shadow: 0 -8px 25px rgba(0, 0, 0, 0.3);
  font-size: 1.2em;
}

footer p {
  margin-bottom: 0;
  letter-spacing: 1.8px;
  opacity: 0.85;
}

footer a {
  color: #8fd3f4;
  text-decoration: none;
  transition: color 0.3s ease;
}

footer a:hover {
  color: #84fab0;
}

/* Animations */
@keyframes bounceIn {
  0% {
    opacity: 0;
    transform: scale(0.7);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}

@keyframes fadeInUp {
  0% {
    opacity: 0;
    transform: translateY(40px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Dark Mode Toggle */
.dark-mode-toggle {
  position: fixed;
  bottom: 25px;
  right: 25px;
  background-color: #1a1a1a;
  color: white;
  padding: 15px 25px;
  border-radius: 50px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.dark-mode-toggle:hover {
  background-color: #333;
}

/* Responsive Design */
@media (max-width: 768px) {
  header h1 {
    font-size: 3.5em;
  }

  nav ul li a {
    font-size: 1.1em;
    padding: 10px 22px;
  }

  section {
    margin: 30px;
    padding: 50px;
  }

  h2 {
    font-size: 2.6em;
  }

  .card {
    padding: 20px;
  }
}

@media (max-width: 480px) {
  header h1 {
    font-size: 2.8em;
  }

  nav ul li {
    margin: 0 12px;
  }

  section {
    margin: 20px;
    padding: 40px;
  }

  h2 {
    font-size: 2.4em;
  }
}
