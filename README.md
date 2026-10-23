# proyecto-colaborativo
Proyecto colaborativo

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi página web</title>

    <!-- Bootstrap 5 -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <!-- Menú de navegación -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">

            <!-- Logo o nombre -->
            <a class="navbar-brand" href="#">Mi Web</a>

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
                        <a class="nav-link" href="#">Servicios</a>
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

  <main class="container py-5">

        <div class="row justify-content-center">

            <div class="col-12 col-md-10 col-lg-7">

                <div class="card shadow border-0 rounded-4">

                    <div class="card-body p-4 p-md-5">

                        <h1 class="text-center mb-3">
                            Formulario de Música
                        </h1>

                        <p class="text-center text-muted mb-4">
                            Cuéntanos sobre tu gusto de música
                        </p>

                        <form action="#" method="post">

                            <!-- Nombre -->
                            <div class="mb-3">
                                <label for="nombre"
                                       class="form-label">
                                    Nombre:
                                </label>

                                <input
                                    type="text"
                                    class="form-control"
                                    id="nombre"
                                    name="nombre"
                                    placeholder="Escribe tu nombre"
                                    required>
                            </div>

                            <!-- Correo electrónico -->
                            <div class="mb-3">
                                <label for="email"
                                       class="form-label">
                                    Correo electrónico:
                                </label>

                                <input
                                    type="email"
                                    class="form-control"
                                    id="email"
                                    name="email"
                                    placeholder="ejemplo@correo.com"
                                    required>
                            </div>



                            <div class="mb-3">
                               <label for="musica" class="form-label">
                                ¿Que género musical te gusta más?
                               </label>
                               
                               <select class="form-select" id="musica" name="musica">
                                <option value="">Selecciona un género</option>
                                <option value="pop">Pop</option>
                                <option value="rock">Rock</option>
                                <option value="regueton">Reguetón</option>
                                <option value="kpop">K-pop</option>
                                <option value="otros">Otros</option>
                               </select>
                            </div>

                            <div class="mb-3" id="otroMusica" style="display: none;">
                                <label for="musicaOtro" class="form-label">
                                    Especifica tu género musical:
                                </label>
                                
                                <input type="text"
                                class="form-control"
                                id="musicaOtro"
                                name="musicaOtro"
                                placeholder="Escribe tu género musical">
                            </div>

                           
                            <!-- Opinión -->
                            <div class="mb-3">
                                <label for="valoracion"
                                       class="form-label">
                                    ¿Qué opinas de las películas
                                    de Studio Ghibli?
                                </label>

                                <textarea
                                    class="form-control"
                                    id="valoracion"
                                    name="valoracion"
                                    rows="4"
                                    placeholder="Escribe aquí tu opinión..."
                                    required></textarea>
                            </div>

                            <!-- Recomendación -->
                            <div class="mb-4">
                                <label for="recomendar"
                                       class="form-label">
                                    ¿Recomendarías Studio Ghibli
                                    a otras personas?
                                </label>

                                <select
                                    class="form-select"
                                    id="recomendar"
                                    name="recomendar"
                                    required>

                                    <option value="si">Sí</option>
                                    <option value="no">No</option>
                                    <option value="talvez">Tal vez</option>

                                </select>
                            </div>

                            <!-- Botón -->
                            <div class="d-grid">
                                <button
                                    type="submit"
                                    class="btn btn-success btn-lg">
                                    Enviar formulario
                                </button>
                            </div>

                        </form>

                    </div>
                </div>

                <!-- GIF -->
                <div class="text-center mt-4">
                    <img
                        src=""
                        alt="GIF de Studio Ghibli"
                        class="img-fluid rounded-4 shadow"
                        style="max-width: 350px;">
                </div>

            </div>
        </div>
    </main>

    <!-- Pie de página -->
    <footer class="bg-success text-white text-center py-3">
        <p class="mb-0">
            Studio Ghibli - Formulario de opinión
        </p>
    </footer>






    <!-- Bootstrap JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
