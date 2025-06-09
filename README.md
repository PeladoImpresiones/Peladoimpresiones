## Hi there 👋

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/c212f74d9d.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="./css/estilos.css">
    <title>Pelado Impresiones</title>
</head>
<body>
    <!--Menu navegacion-->
    <nav>
        <ul>
                 <li><a href="#sobremi">Sobre mi</a></li>
                 <li><a href="#impresiones">Impresiones</a></li>
                 <li id="logo"><img src="./imagenes/logo_sin_fondo.png" alt="Logo_de_pelado.impresiones" ></li>
                 <li><a href="#contactar">Contactar</a></li>
        </ul>

    </nav>
    <article>
        <!--Bloque Inicio-->
                <section id="inicio">
                    <h2 class="titulo">PELADO IMPRESIONES</h2>
                    <h2 class="hastag">#Diseñador</h2>
                    <h2 class="hastag">#Programador</h2>

                    <ul id="redes_sociales">

                    <li><a href="https://www.tiktok.com/@peladoimpresiones" target="_blank"><i class="fa-brands fa-tiktok"></i></a></li>
                    <li><a href="https://www.facebook.com/profile.php?id=61575361329473" target="_blank"><i class="fa-brands fa-facebook"></i></a></li>
                    <li><a href="https://www.instagram.com/peladoimpresiones/" target="_blank"><i class="fa-brands fa-square-instagram"></i></a></li>

                    </ul>
                               
                            
                </section>
                <!--Fin Bloque Inicio-->

                <!--Bloque Sobre Mi-->
                <section id="sobremi">
                    <h2>Sobre mi:</h2>
                    <img src="./imagenes/peladoPuentes.png" alt="foto de Pelado Puentes" height="200">
                    <h3>Soy <strong> diseñador y programador</strong> <span> de escasa cabellera, adicto a videojuegos y </span> con un empredimiento de impresiones 3D </h3>
                    <h3>Me defino como una persona creativa y enamorado de lo que hago, donde mi maxima es <cite>"solo si lo intentas vas a poder lograrlo". </cite> </h3>
                </section> 

                <!--Fin Bloque Sobre Mi-->

                <!--Bloque Sobre Impresiones-->
                <section id="impresiones">
                <h2>Impresiones</h2>
                <h3>Algunas de las cosas que hacemos:</h3>
                <div class="filaportfolio">
                    <div class="card">
                        <img src="./imagenes/porta_joystick_Bulbasour200x154.png" alt="impresiones1">
                        <h3>Porta Joystick</h3>
                        <h4>Bulbasour</h4>
                        <div class="sep"></div>
                        <p>Bulbasour por Joystick</p>
                        <div class="masinfo"><button type="button">MAS INFO</button></div>
                    </div>
                    <div class="card">
                        <img src="./imagenes/llavero_capibara200x154.png" alt="impresiones2">
                        <h3>llavero</h3>
                        <h4>Capibara</h4>
                        <div class="sep"></div>
                        <p>LLlavero Capibara</p>
                        <div class="masinfo"><button type="button">MAS INFO</button></div>
                    </div>
                    <div class="card">
                        <img src="./imagenes/bobsponja_porta_esponja200x154.png" alt="impresiones3">
                        <h3>Porta Esponja</h3>
                        <h4>Bob esponaja</h4>
                        <div class="sep"></div>
                        <p>Bob sponja porta espoja</p>
                        <div class="masinfo"><button type="button">MAS INFO</button></div>
                    </div>
                    <div class="card">
                        <img src="./imagenes/hongo_con_rosca200x154.jpg" alt="impresiones4">
                        <h3>Caja</h3>
                        <h4>Hongo</h4>
                        <div class="sep"></div>
                        <p>Hongo de Mario con rosca para guardad lo que se te cante</p>
                        <div class="masinfo"><button type="button">MAS INFO</button></div>
                    </div>
                    <div class="card">
                        <iframe width="250" src="https://www.youtube.com/embed/Rw4uQECnnOI?si=dNl74rpLJRRQU90u" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                        <h3>Yotube</h3>
                        <h4>Apex leyends</h4>
                        <div class="sep"></div>
                        <p>Torne de Apex leyends con .Caida</p>
                        <div class="masinfo"><button type="button">MAS INFO</button></div>
                    </div>
                </div>
            </section>
                <!--Fin Bloque Sobre Impresiones-->

                <!--Bloque Contactar-->
            <section id="contactar">
                <h2>Contacto</h2>
                <h3>Envíame tus dudas</h3>
                <form action="#">
                    <div class="itemform">
                        <label for="nombre">Nombre</label>
                        <input type="text" id="nombre" name="nombre" minlength="2" maxlength="64" size="32" required>
                    </div>
                    <div class="itemform">
                        <label for="empresa">Empresa</label>
                        <input type="text" id="empresa" name="empresa" minlength="2" maxlength="128" size="32">
                    </div>
                    <div class="itemform">
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" minlength="10" maxlength="128" size="32" required>
                    </div>
                    <div class="itemform">
                        <label for="mensaje">Mensaje</label>
                        <textarea name="mensaje" id="mensaje" cols="33" rows="5"></textarea>
                    </div>
                    <div class="itemform">
                        <input type="submit" name="boton" value="CONTACTAR">
                    </div>
                </form>
            </section>
            <!--FIN Bloque Contactar-->
    </article>
    
        <!-- Footer -->
        <footer>
            <ul>
                <li class="logo_footer"><a href="#inicio"><img src="./imagenes/logo_sin_fondo.png" alt=""></a></li>
                <li>Pelado Puentes todos los derechos reservados, doblado en Palmera Records</li>
            </ul>
        </footer>
</body>
</html>

