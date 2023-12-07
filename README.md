# Pagina_HTML
 CAROL
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
    <title>Título de la Página</title>
</head>
<body>
    <div class="container">
        <header>
            <img src="LOGO BISU.png" alt="Logo" class="logo">
            <h1>Bienvenidos a Mi Empresa</h1>
            <nav>
                <ul>
                    <li><a href="#">Inicio</a></li>
                    <li><a href="#">Acerca de</a></li>
                    <li><a href="#">Contacto</a></li>
                </ul>
            </nav>
        </header>

        <main>
            <!-- Nuevo carousel con imágenes -->
            <div id="imageCarousel" class="carousel slide" data-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="imagen1.jpg" alt="Imagen 1" class="d-block w-100">
                    </div>
                    <div class="carousel-item">
                        <img src="imagen2.jpg" alt="Imagen 2" class="d-block w-100">
                    </div>
                    <div class="carousel-item">
                        <img src="imagen3.jpg" alt="Imagen 3" class="d-block w-100">
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

            <!-- Sección de visión y misión -->
            <section class="inicio">
                <div class="vision-mision">
                    <div class="vision">
                        <h2>Visión</h2>
                        <p>Ser reconocidos como la marca líder mundial en bisutería, ofreciendo una amplia gama de productos que reflejen la diversidad de estilos y personalidades. Nos esforzamos por ser pioneros en innovación, sostenibilidad y compromiso con la satisfacción total del cliente.</p>
                    </div>
                    <div class="mision">
                        <h2>Misión</h2>
                        <p>En Bisuteria, nos dedicamos a crear experiencias únicas a través de nuestra amplia colección de bisutería, que abarca desde piezas clásicas hasta las últimas tendencias. Nos comprometemos a brindar calidad excepcional, diseño exclusivo y servicio al cliente sobresaliente. Nuestra misión incluye fomentar la responsabilidad social y ambiental en cada paso de nuestra cadena de suministro.</p>
                    </div>
                </div>
            </section>

            <section>
                <h2>Valores</h2>
                <p>- Diversidad: Celebramos la individualidad y la diversidad en cada pieza, reflejando la belleza única de cada persona.</p>
                <p>- Innovación: Buscamos constantemente nuevas ideas y tecnologías para ofrecer productos vanguardistas y emocionantes.</p>

                <p>- Calidad: Nos comprometemos con la excelencia en la artesanía, utilizando materiales de alta calidad para garantizar la durabilidad y el valor de cada joya.</p>   
                <p>- Sostenibilidad: Adoptamos prácticas responsables y sostenibles en todo nuestro proceso, desde la obtención de materiales hasta la fabricación y empaquetado.</p>
            </section>
        </main>

        <footer>
            <p>&copy; BISUTERIA CARO.</p>
        </footer>
    </div>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <!-- Script adicional para el carousel de imágenes -->
    <script>
        $(document).ready(function(){
            $('#imageCarousel').carousel();
        });
    </script>
</body>
</html>
