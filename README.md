# Sena-IITIC-7
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="styles1.css">
    <title>AutoCali Compraventa</title>
</head>
<body>

    <header>
        <div class="container">
            <div class="logo">
                <img src="logo.jpg" alt="Logo de FitVida Wellness Solutions">
                <h1>AutoCali Compraventa</h1>
            </div>
            <nav class="navbar navbar-expand-lg navbar-light bg-light">
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="#presentation">Presentación</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#mission-vision">Misión y Visión</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#services-contact">Servicios y Contacto</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#gallery">Galería</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#video">Video</a>
                        </li>
                    </ul>
                </div>
            </nav>
        </div>
    </header>

    <section id="presentation" class="section presentation">
        <div class="container">
            <div class="card">
                <div class="card-body">
                    <h2 class="card-title">Nuestra Presentación</h2>
                    <p class="card-text">¡Bienvenidos a AutoCali Compraventa, la mejor opción para la compra y venta de vehículos en Cali, Colombia!</p>
                </div>
            </div>
        </div>
    </section>

    <section id="mission-vision" class="section mission-vision">
        <div class="container">
            <div class="card">
                <div class="card-body">
                    <h2 class="card-title">Nuestra Misión y Visión</h2>
                    <p class="card-text"><strong>Misión:</strong> En AutoCali Compraventa, nuestra misión es facilitar el proceso de compra y venta de vehículos en Cali, Colombia, proporcionando a nuestros clientes una experiencia transparente, segura y eficiente. Nos comprometemos a ofrecer soluciones que se adapten a las necesidades individuales de cada cliente, brindando confianza y satisfacción en cada transacción.</p>
                    <p class="card-text"><strong>Visión:</strong> Como líderes en el mercado de compraventa de vehículos en Cali, aspiramos a ser reconocidos por nuestra integridad, profesionalismo y servicio al cliente excepcional. Buscamos ser la primera opción para aquellos que buscan vender o adquirir un vehículo, estableciendo relaciones duraderas basadas en la confianza y la transparencia.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="gallery" class="section gallery">
        <div class="container">
            <h2 class="text-center">Nuestra Galería de Fotos</h2>
            <div class="card">
                <div class="card-body">
                    <div id="imageCarousel" class="carousel slide" data-ride="carousel">
                        <div class="carousel-inner">
                            <div class="carousel-item active">
                                <img src="imagen1.webp" class="d-block w-100" alt="Imagen 1">
                            </div>
                            <div class="carousel-item">
                                <img src="imagen2.webp" class="d-block w-100" alt="Imagen 2">
                            </div>
                            <div class="carousel-item">
                                <img src="imagen3.webp" class="d-block w-100" alt="Imagen 3">
                            </div>
                            <div class="carousel-item">
                                <img src="imagen4.webp" class="d-block w-100" alt="Imagen 4">
                            </div>
                        </div>
                        <a class="carousel-control-prev" href="#imageCarousel" role="button" data-slide="prev">
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="sr-only">Anterior</span>
                        </a>
                        <a class="carousel-control-next" href="#imageCarousel" role="button" data-slide="next">
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="sr-only">Siguiente</span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="video" class="section video">
        <div class="container">
            <div class="card">
                <div class="card-body">
                    <div class="video-container">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container text-center">
            <div class="card">
                <div class="card-body">
                    <h3>Contacto</h3>
                    <p>Les invitamos a visitar nuestro concesionario en [Dirección], donde nuestro amable equipo estará encantado de ayudarles a encontrar el vehículo perfecto. También pueden ponerse en contacto con nosotros a través de:</p>
                    <p><strong>Teléfono:</strong> [Número de teléfono]</p>
                    <p><strong>Correo Electrónico:</strong> <a href="mailto:info@autocali.com.co">info@autocali.com.co</a></p>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <script src="js.js"></script>

</body>
</html>
