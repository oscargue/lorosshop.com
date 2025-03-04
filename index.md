<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LorosShop - Gorras de Caballos</title>
    <meta name="description" content="Compra las mejores gorras con diseños de caballos para hombres, mujeres y niños. Ofertas exclusivas y envíos rápidos.">
    <meta name="keywords" content="gorras de caballos, moda ecuestre, accesorios ecuestres, gorras para hombre, gorras para mujer, tienda en línea">
    <style>
        body {
            background: #e6ddf0;(180deg, #d6bef3, #C5A3E2);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            color: #333;
        }
        .header {
            padding: 15px;
            background: #600d6f;
            border-radius: 20px;
            box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.2);
        }
        .logo {
            width: 55%;
            max-width: 140px;
            height: auto;
            border-radius: 10px;
        }
        .video-container {
            margin: 15px auto;
            width: 90%;
            max-width: 600px;
        }
        .video-container video {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .photo-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            padding: 15px;
        }
        .photo-item {
            background: white;
            width: 95%;
            max-width: 230px;
            padding: 8px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
            color: black;
        }
        .photo-item:hover {
            transform: scale(1.05);
        }
        .photo-item img {
            width: 100%;
            border-radius: 10px;
        }
        .buy-button {
            display: block;
            margin: 8px auto;
            padding: 8px;
            background: green;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: 0.3s;
        }
        .buy-button:hover {
            background: darkgreen;
        }
        .flash-sale {
            background: #f9b100;
            color: #000000;
            padding: 12px;
            font-size: 20px;
            cursor: pointer;
            margin: 15px;
            border-radius: 10px;
        }
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.6);
        }
        .modal-content {
            background-color: white;
            margin: 10% auto;
            padding: 15px;
            border-radius: 10px;
            width: 90%;
            max-width: 350px;
            text-align: center;
            color: black;
        }
        .close {
            color: red;
            font-size: 22px;
            float: right;
            cursor: pointer;
        }
        @media (max-width: 600px) {
            .photo-item {
                width: 100%;
            }
            .modal-content {
                width: 95%;
            }
            .logo {
                width: 55%;
                max-width: 130px;
            }
            .video-container {
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <img src="C:\Users\oscar\OneDrive\Documentos\loroshop morado\a1.jpg" alt="Logo de LorosShop" class="logo">
    </header>
<link rel="icon" href="img/favicon.ico" type="image/x-icon">
    <div class="video-container">
        <video controls>
            <source src="\Users\oscar\OneDrive\Documentos\loroshop morado/mi video.mp4" type="video/mp4">
            Tu navegador no soporta la etiqueta de video.
        </video>
    </div>

    <div class="flash-sale" onclick="openSaleModal()">¡Oferta Relámpago! 🔥</div>

    <div id="sale-modal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeSaleModal()">&times;</span>
            <h2>¡Descuentos Especiales!</h2>
            <p>Aprovecha nuestras ofertas exclusivas por tiempo limitado.</p>
            <div class="product">
                <img src="img/producto1.jpg" alt="Producto en Oferta">
                <p><strong>Producto 1 - $12.99</strong></p>
                <a href="https://wa.me/3044605939?text=Quiero%20comprar%20Producto%201%20por%20$12.99" class="buy-button">Comprar Ahora</a>
            </div>
        </div>
    </div>

    <div class="photo-gallery">
        <div class="photo-item">
            <img src="img/foto1.jpg" alt="Gorra Modelo 1">
            <p><strong>Gorra Modelo 1</strong></p>
            <p>Estilo deportivo y cómodo</p>
            <p><strong>Precio: $14.00</strong></p>
            <a href="https://wa.me/3044605939?text=Hola,%20quiero%20comprar%20la%20Gorra%20Modelo%201" class="buy-button">Comprar Ahora</a>
        </div>
        <!-- 10 nuevas imágenes agregadas -->
        <div class="photo-item"><img src="img/foto2.jpg" alt="Gorra Modelo 2"><p><strong>Gorra Modelo 2</strong></p><p>Diseño casual y elegante</p><p><strong>Precio: $16.00</strong></p><a href="#" class="buy-button">Comprar Ahora</a></div>
        <div class="photo-item"><img src="img/foto3.jpg" alt="Gorra Modelo 3"><p><strong>Gorra Modelo 3</strong></p><p>Estilo moderno</p><p><strong>Precio: $18.00</strong></p><a href="#" class="buy-button">Comprar Ahora</a></div>
        <div class="photo-item"><img src="img/foto4.jpg" alt="Gorra Modelo 4"><p><strong>Gorra Modelo 4</strong></p><p>Diseño único</p><p><strong>Precio: $20.00</strong></p><a href="#" class="buy-button">Comprar Ahora</a></div>
        <div class="photo-item"><img src="img/foto5.jpg" alt="Gorra Modelo 5"><p><strong>Gorra Modelo 5</strong></p><p>Comodidad premium</p><p><strong>Precio: $22.00</strong></p><a href="#" class="buy-button">Comprar Ahora</a></div>
        <div class="photo-item"><img src="img/foto6.jpg" alt="Gorra Modelo 6"><p><strong>Gorra Modelo 6</strong></p><p>Diseño elegante</p><p><strong>Precio: $24.00</strong></p><a href="#" class="buy-button">Comprar Ahora</a></div>
        <div class="photo-item"><img src="img/foto7.jpg" alt="Gorra Modelo 7"><p><strong>Gorra Modelo 7</strong></p><p>Edición especial</p><p><strong>Precio: $26.00</strong></p><a href="#" class="buy-button">Comprar Ahora</a></div>
        <div class="photo-item"><img src="img/foto8.jpg" alt="Gorra Modelo 8"><p><strong>Gorra Modelo 8</strong></p><p>Clásico y versátil</p><p><strong>Precio: $28.00</strong></p><a href="#" class="buy-button">Comprar Ahora</a></div>
        <div class="photo-item"><img src="img/foto9.jpg" alt="Gorra Modelo 9"><p><strong>Gorra Modelo 9</strong></p><p>Toque sofisticado</p><p><strong>Precio: $30.00</strong></p><a href="#" class="buy-button">Comprar Ahora</a></div>
        <div class="photo-item"><img src="img/foto10.jpg" alt="Gorra Modelo 10"><p><strong>Gorra Modelo 10</strong></p><p>Deportivo y resistente</p><p><strong>Precio: $32.00</strong></p><a href="#" class="buy-button">Comprar Ahora</a></div>
    </div>
</body>
</html>

    <script>
        function openSaleModal() {
            document.getElementById("sale-modal").style.display = "block";
        }
        function closeSaleModal() {
            document.getElementById("sale-modal").style.display = "none";
        }
    </script>
</body>
</html>
