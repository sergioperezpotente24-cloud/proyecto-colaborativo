<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Género Musical</title>

    <!-- Bootstrap 5 -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <!--Estilos--> 
    <link rel="stylesheet" href="estilos.css">
</head>
<body>

    <!-- Menú de navegación -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-black">
        <div class="container">

            <!-- Logo o nombre -->
            <a class="navbar-brand" href="#">Explorando la música</a>

            <!-- Botón hamburguesa -->
            <button class="navbar-toggler" type="button"
                data-bs-toggle="collapse"
                data-bs-target="#menuPrincipal"
                aria-controls="menuPrincipal"
                aria-expanded="false"
                aria-label="Abrir menú">
                <span class="navbar-toggler-icon"></span>
            </button>

            <!-- Opciones del menú -->
            <div class="collapse navbar-collapse" id="menuPrincipal">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="menu.html">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Galería</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Nosotros</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contacto</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <!--Portada-->
        <header class="portada text-center">
            <!--Imagen principal-->
            <img src="imagenes/foto_inicio.jpg" alt="imagen principal" class="imagen-principal mb-4">
            <!-- Texto  -->
            <div class="texto-inicio">
                <h1 class="display-2 fw bold">EL GÉNERO MUSICAL</h1>
                <p class="lead">
                    Explora los distintos géneros musicales
                </p>
                <p>
                    La música es una forma de expresión capaz de transmitir emociones, contar historias y conectar a personas de todo el mundo. Desde los sonidos más suaves hasta los ritmos más agresivos, cada género tiene su propia identidad, historia y manera de entender la música.
                    Explora diferentes estilos, descubre sus características y encuentra el sonido que mejor encaja contigo.
                </p>
                 <!-- Enlace a la galería -->
                <a href="galeria.html" class="btn btn-outline-light mt-3">
                    Explorar galería
                </a>
            </div>
        </header>
        <!--Sección de géneros-->
        <section class="container py-5">
            <h2 class="text-center mb-4">Nuestros géneros más escuchados</h2>
            <div class="row g-4">
                <!-- Card 1: Reggaetón -->
                <div class="col-12 col-md-6 col-lg-3">
                    <div class="card bg-dark text-white h-100">
                        <img src="imagenes/reggaeton.jpg"
                            class="card-img-top"
                            alt="Imagen representativa de la banda">
                        <div class="card-body">
                            <h3 class="card-title h5">El reggaeton</h3>
                            <p class="card-text">
                                Descubre el reggaeton con Sergio. 
                                Un género musical urbano que combina ritmos caribeños, 
                                influencias del reggae y el dancehall con elementos del hip-hop y la música electrónica.
                            </p>
                        </div>
                    </div>
                </div>
                <!-- Card 2: Rock -->
                <div class="col-12 col-md-6 col-lg-3">
                    <div class="card bg-dark text-white h-100">
                        <img src="imagenes/rock.jpg"
                            class="card-img-top"
                            alt="Banda de rock en directo">
                        <div class="card-body">
                            <h3 class="card-title h5">El rock</h3>
                            <p class="card-text">
                                Descubre el rock con Ana.
                                Un género caracterizado por sus guitarras eléctricas,
                                baterías potentes y melodías que han marcado generaciones.
                            </p>
                        </div>
                    </div>
                </div>
                <!-- Card 3: Punk -->
                <div class="col-12 col-md-6 col-lg-3">
                    <div class="card bg-dark text-white h-100">
                        <img src="imagenes/punk.jpg"
                            class="card-img-top"
                            alt="Artista de música pop">
                        <div class="card-body">
                            <h3 class="card-title h5">El punk</h3>
                            <p class="card-text">
                                Descubre el punk con Lucía.
                                un género musical y un movimiento cultural nacido como una forma de rebelión contra las normas sociales, 
                                la industria musical convencional y las estructuras establecidas.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Card 4: Metal -->
                <div class="col-12 col-md-6 col-lg-3">
                    <div class="card bg-dark text-white h-100">
                        <img src="imagenes/metal.jpg"
                            class="card-img-top"
                            alt="DJ actuando en un festival de música electrónica">
                        <div class="card-body">
                            <h3 class="card-title h5">El metal</h3>
                            <p class="card-text">
                                Descubre el metal con Alba.
                                Un género musical caracterizado por sus guitarras eléctricas distorsionadas, 
                                baterías potentes, bajos contundentes y gran variedad de estilos vocales.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section> 
    </main>
    <!--Pie de página-->
    <footer class="bg-dark text-center py-3">
        <p class="mb-0">
            &copy; 2026 Género musical - Página web musical
        </p>
    </footer>

    <!-- Bootstrap JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
