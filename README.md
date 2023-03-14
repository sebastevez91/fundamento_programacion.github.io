# fundamento_programacion.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css\styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Permanent+Marker&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css" integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="icon" type="image/x-icon" href="./img/icono-de-cv.png">
    <title>Proyecto Final CV</title>
</head>
<body>
    <!--Navegador-->
    <div class="caja-header">
        <header>
            <div class="logo">
                <h1>Proyecto final de CV</h1>
            </div>
                    <nav id="nav" class="nav">
                        <ul>
                            <li><a href="#inicio" onclick="seleccion()">Inicio</a></li>
                            <li><a href="#info-personal" onclick="seleccion()">Acerca de mi</a></li>
                            <li><a href="#skill" onclick="seleccion()">Skill</a></li>
                            <li><a href="#cv" onclick="seleccion()">Experiencia y Educación</a></li>
                            <li><a href="#habilidades" onclick="seleccion()">Habilidades</a></li>
                            <li><a href="#contacto" onclick="seleccion()">Contactos</a></li>
                        </ul>
                    </nav>
                    <div class="nav-responsive" onclick="mostrarMenu()">
                        <i class="fa-solid fa-bars"></i>
                    </div>
        </header>
    </div>
    <!----Inicio---->
    <section id="inicio" class="inicio">
        <div class="caja-inicio">
            <div class="caja-img">
                <img src="img/hero-bg.jpg" alt="Viltor huln" >
            </div>
        <h2>Soy Victor Huln</h2>
        <h3>Programador de Sistemas</h3>
        <h3>Programador de Web</h3>
        </div>
    </section>   
    <!----Acerca de mi y datos pesonales---->
    <section id="info-personal" class="info-personal">
        <div class="caja-personal">
            <h2>Acerca de mi</h2>
            <p> Soy un programador de sistemas con años de experiencia mejorando el
                funcionamiento de las organizaciones con soluciones de sistemas de
                información. Reconocido por recomendar nuevas tecnologías para
                mejorar los sistemas existentes e introducir nuevos programas.</p>
        </div>
        <div class="fila">
            <div class="col">
                <h3>Datos Personales</h3>
                <ul>
                    <li>
                        <strong>Fecha de Nacimiento</strong>
                        2/06/1993
                    </li>
                    <li>
                        <strong>Telefono</strong>
                        (825)4386357
                    </li>
                    <li>
                        <strong>Dirección</strong>
                        1145 Locut Rd, Argentina
                    </li>
                    <li>
                        <strong>E-mail</strong>
                        victor.huln@example.com
                    </li>
                    <li>
                        <strong>Cargo</strong>
                        Desarrollador
                    </li>
                </ul>
            </div>
            <div class="col">
                <h3>Intereses</h3>
                <div class="caja-interes">
                    <div class="interes">
                        <i class="fa-brands fa-avianex"></i>
                        <span>Viajes</span>
                    </div>
                    <div class="interes">
                        <i class="fa-solid fa-person-running"></i>
                        <span>Running</span>
                    </div>
                    <div class="interes">
                        <i class="fa-solid fa-book"></i>
                        <span>Lectura</span>
                    </div>
                    <div class="interes">
                        <i class="fa-solid fa-car"></i>
                        <span>Autos</span>
                    </div>
                    <div class="interes">
                        <i class="fa-solid fa-desktop"></i>
                        <span>Computación</span>
                    </div>
                </div>
            </div>
        </div>
    </section> 
    <!-----Skills-----> 
    <section class="skill" id="skill">
        <div class="caja-skill">   
                <h2>Software</h2>
                <button type="button"onclick="mostrarCerrar(true,'lenguaje')">Mostrar información
                <span class="overlay"></span></button>
                <button type="button" onclick="mostrarCerrar(false,'lenguaje')">Cerrar información
                <span class="overlay"></span></button>
                <div class="fila" id="lenguaje" >
                  <div class="col">
                        <h3>Technical Skill</h3>
                        <div class="skill-dt">
                            <span>HTML</span> <div class="barra-skill">
                                <div class="progress">
                                    <span>85%</span>
                                </div>
                                </div> 
                                <span>CSS</span> <div class="barra-skill">
                                    <div class="progress">
                                        <span>75%</span>
                                    </div>
                                    </div>   
                                 <span>PHP</span> <div class="barra-skill">
                                    <div class="progress">
                                        <span>50%</span>
                                    </div>
                                    </div>  
                                <span>JAVASCRIPT</span> <div class="barra-skill">
                                    <div class="progress">
                                        <span>90%</span>
                                    </div>
                                    </div> 
                                <span>PYTHON</span> <div class="barra-skill">
                                    <div class="progress">
                                        <span>75%</span>
                                    </div>
                                    </div> 
                        </div>
                  </div>
                  <div class="col">
                    <h3>Professional Skill</h3>
                    <div class="skill-dt" id="skill">
                        <span>TRABAJO EN EQUIPO</span> <div class="barra-skill">
                            <div class="progress">
                                <span>75%</span>
                            </div>
                            </div> 
                            <span>COMUNICACIÖN</span> <div class="barra-skill">
                                <div class="progress">
                                    <span>55%</span>
                                </div>
                                </div>   
                             <span>DEDICACIÖN</span> <div class="barra-skill">
                                <div class="progress">
                                    <span>90%</span>
                                </div>
                                </div>  
                            <span>CREATIVIDAD</span> <div class="barra-skill">
                                <div class="progress">
                                    <span>81%</span>
                                </div>
                                </div> 
                    </div>
                </div>
        </div>
    </section>
    <!---Experiencia Laboral-->
    <section id="cv" class="cv">
        <div class="caja-cv">
            <h2>Experiencia y Educación</h2>
            <div class="fila">
                <div class="col izquierda">
                    <h3>Experiencia Laboral</h3>
                    <div class="item izq">
                        <h4>Segula Technologies</h4>
                        <span class="cargo">Programador de sistemas</span>
                        <span class="fecha">02/2018 - 11/2020</span>
                        <p>Experiencia revisando códigos, hojas de ruta de proyectos y
                        requisitos cambiantes durante el transcurso de cada proyecto.
                        Supervisó la instalación de programas de software y sistemas de
                        hardware para cumplir los requisitos de cada equipo.
                        Capacidad para realizar mejoras en los sistemas informáticos de la
                        empresa</p>
                    </div>
                    <div class="item izq">
                        <h4>Netboss Comunicaciones</h4>
                        <span class="cargo">Programador de sistemas</span>
                        <span class="fecha">12/2012 - 01/2018</span>
                        <p>Logró un 87 % de éxito en la automatización del software, analizando
                        las operaciones de reclamaciones, los datos y las incidencias.
                        Creó diseños conceptuales a partir de objetivos de negocio para
                        desarrollar aplicaciones de acuerdo con la estrategia de la empresa.
                        Proporcionó una formación detallada a los usuarios para proteger los
                        datos y minimizar errores</p>
                    </div>
                    <div class="item izq">
                        <h4>Silver Storm Solutions</h4>
                        <span class="cargo">Programador de Web</span>
                        <span class="fecha">10/2011 - 09/2012</span>
                        <p>Apoyo técnico al ciclo completo del proyecto, desde el briefing
                        inicial, pasando por wireframes, diseño web, maquetación,
                        desarrollo, programación y la publicación final.
                        Participación en proyectos de software libre.
                        Experiencia demostrable en el desarrollo de aplicaciones adaptadas a
                        eCommerce y CMS.</p>
                    </div>
                </div>
                <div class="col derecha">
                    <h3>Formacion Académica</h3>
                    <div class="item der">
                        <h4>Select Business School</h4>
                        <span class="cargo">Máster en Programación de Sistemas Informáticos </span>
                        <span class="fecha">06/2011</span>
                        <p>Modalidad online</p>
                    </div>
                    <div class="item der">
                        <h4>Universidad de Valladolid, Valladolid </h4>
                        <span class="cargo">Ingeniería Informática</span>
                        <span class="fecha">06/2010</span>
                        <p>Modalidad Presencial</p>
                    </div>

                </div>
            </div>
        </div>
    </section>
           
    <!-----Habilidades------>            
    <section class="habilidades" id="habilidades">           
        <div class="caja-habilidades">
            <h2>Habilidades</h2>
                
                <div class="fila">
                    <div class="col izquierda">
                        <h3>Aptitudes</h3>
                        <button type="button" onclick="mostrarCerrar(true,'aptitudes')">Mostrar información
                            <span class="overlay"></span></button>
                        <button type="button" onclick="mostrarCerrar(false,'aptitudes')">Cerrar información
                            <span class="overlay"></span></button>
                        <ul id="aptitudes">
                            <li>Recopilación y análisis de datos</li>
                            <li>Análisis técnico</li>
                            <li>Habilidades de diagnóstico de problemas</li>
                            <li>Generación de informes</li>
                            <li>Gestión de la implementación</li>
                            <li>Herramientas de automatización</li>
                        </ul>
                    </div>
                    <div class="col derecha">
                            <h3>Idiomas</h3>
                            <button type="button" onclick="mostrarCerrar(true,'idioma')">Mostrar información
                                <span class="overlay"></span></button>
                            <button type="button" onclick="mostrarCerrar(false,'idioma')">Cerrar información
                                <span class="overlay"></span></button>
                            <ul id="idioma">
                                <li>Español: nivel nativo</li>
                                <li>Inglés: nivel intermedio (B2)</li>
                            </ul>
                    </div>
                </div>
        </div>  
    </section>     
    <!------Contacto------>
    <section id="contacto" class="contacto">
        <div class="caja-contacto">
            <h2>Contactos</h2>
                <div class="fila">
                    <div class="col">
                        <form action="" method="post">
                            <label>Nombre </label>
                            <input type="text" name="nombre" placeholder="Ingrese su Nombre" required><br>
                            <label>Apellido </label>
                            <input type="text" name="apellido" placeholder="Ingrese su Apellido" required><br>
                            <label>E-mail </label>
                            <input type="email" name="Email" placeholder="Ingrese su E-mail"><br>
                            <label>Comentario </label>
                            <textarea name="comentario" id="comentario" cols="30" rows="10" placeholder="Deje su mensaje" ></textarea><br>
                            <button>Enviar<i class="fa-solid fa-file-import"></i>
                            <span class="overlay"></span></button>
                        </form>
                    </div>
                    <div class="col">
                        <div class="info">
                            <ul>
                                <li><i class="fa-solid fa-envelope"></i>
                                    Victor.hul@example.com </li>
                                <li><i class="fa-solid fa-phone"></i>
                                    (825) 4386357 </li>
                                <li><i class="fa-solid fa-location-dot"></i>
                                    Locut RD, 1145</li>
                             </ul>
                             <div class="container">
                                <div class="social">
                                    <ul>
                                        <li><a href="#"><img src="PNG/facebook2.png" alt="facebook"></a></li>
                                        <li><a href="#"><img src="PNG/twitter.png" alt="twitter"></a></li>
                                        <li><a href="#"><img src="PNG/instagram.png" alt="instagram"></a></li>
                                        <li><a href="#"><img src="PNG/linkedin.png" alt="linkedin"></a></li>
                                    </ul>   
                                </div>
                            </div>
                        </div>     
                    </div>
             </div>
        </div>
    </section>     
    <script src="js/main.js"></script>
    <footer>
        <a href="#inicio" class="arriba">
            <i class="fa-solid fa-arrow-up"></i></a>
        <h4>Proyecto Final</h4>    
    </footer>
</body>
</html>
