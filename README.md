<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diemsi Caps</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #f5f5f5;
        }

        header {
            background: black;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 28px;
            font-weight: bold;
        }

        nav {
            background: #222;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1515377905703-c4788e51af15') center/cover;
            height: 350px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 40px;
            font-weight: bold;
            text-shadow: 0px 0px 10px black;
        }

        .section {
            padding: 40px;
            text-align: center;
        }

        .section h2 {
            font-size: 32px;
            margin-bottom: 20px;
        }

        .catalogo {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 25px;
        }

        .item {
            background: white;
            width: 260px;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgb(0 0 0 / 20%);
        }

        .item img {
            width: 100%;
            border-radius: 10px;
        }

        .item h3 {
            margin: 10px 0 5px;
        }

        .ubi {
            font-size: 22px;
            line-height: 35px;
        }

        footer {
            background: black;
            color: white;
            padding: 20px;
            text-align: center;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>DIEMSI CAPS</header>

<nav>
    <a href="#catalogo">Catálogo</a>
    <a href="#ubicacion">Ubicación</a>
    <a href="#contacto">Contacto</a>
</nav>

<div class="hero">
    Gorras Exclusivas DMSi
</div>

<section class="section" id="catalogo">
    <h2>Catálogo</h2>

    <div class="catalogo">

        <div class="item">
            <img src="https://www.facebook.com/share/1ER8c5hWuD/?mibextid=wwXIfr" alt="Gorra 1">
            <h3>Gorra Premium Negra</h3>
            <p>$45 USD</p>
        </div>

        <div class="item">
            <img src="https://www.facebook.com/share/14WW7hn8uXt/?mibextid=wwXIfr" alt="Gorra 2">
            <h3>Gorra Blanca Logo DIEMSI</h3>
            <p>$45 USD</p>
        </div>

        <div class="item">
            <img src="https://www.facebook.com/share/1ER8c5hWuD/?mibextid=wwXIfr" alt="Gorra 3">
            <h3>Edición Especial</h3>
            <p>$65 USD</p>
        </div>

    </div>
</section>

<section class="section" id="ubicacion">
    <h2>Ubicación</h2>
    <p class="ubi">
        📍 Frente a **Tacos Charly**<br>
        📍 Calle Lamar, Austin, Texas<br>
        🧢 Ven por tu gorra DIEMSI
    </p>
</section>

<section class="section" id="contacto">
    <h2>Contacto</h2>
    <p>📱 WhatsApp: <b>+1 512-806-37-19</b></p>
    <p>📸 Instagram: <b>@diemsi_caps</b></p>
</section>

<footer>
    © 2025 DMSiCaps – Todos los derechos reservados
</footer>

</body>
</html>
