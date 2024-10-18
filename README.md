<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Ropa</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Tienda de Ropa</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Productos</a></li>
                <li><a href="#">Carrito</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="products">
            <h2>Nuestros Productos</h2>
            <div class="product-list">
                <div class="product">
                    <img src="https://via.placeholder.com/150" alt="Camisa">
                    <h3>Camisa Azul</h3>
                    <p>Precio: $25</p>
                    <button onclick="agregarAlCarrito('Camisa Azul', 25)">Agregar al carrito</button>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/150" alt="Pantalones">
                    <h3>Pantalones Blancos</h3>
                    <p>Precio: $40</p>
                    <button onclick="agregarAlCarrito('Pantalones Blancos', 40)">Agregar al carrito</button>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/150" alt="Zapatos">
                    <h3>Zapatos Negros</h3>
                    <p>Precio: $60</p>
                    <button onclick="agregarAlCarrito('Zapatos Negros', 60)">Agregar al carrito</button>
                </div>
            </div>
        </section>

        <section class="cart">
            <h2>Carrito de Compras</h2>
            <ul id="carrito">
                <!-- Productos agregados aparecerán aquí -->
            </ul>
            <p id="total">Total: $0</p>
            <button class="checkout" onclick="comprar()">Finalizar Compra</button>
        </section>
    </main>

    <footer>
        <p>© 2024 Tienda de Ropa. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

