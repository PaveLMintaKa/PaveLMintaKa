<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Ropa</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Bienvenido a la Tienda de Ropa</h1>
    <div class="store">
        <h2>Productos disponibles</h2>
        <div class="products">
            <div class="product">
                <h3>Camisa</h3>
                <p>Precio: $20</p>
                <button onclick="agregarAlCarrito('Camisa', 20)">Agregar al carrito</button>
            </div>
            <div class="product">
                <h3>Pantalones</h3>
                <p>Precio: $30</p>
                <button onclick="agregarAlCarrito('Pantalones', 30)">Agregar al carrito</button>
            </div>
            <div class="product">
                <h3>Zapatos</h3>
                <p>Precio: $50</p>
                <button onclick="agregarAlCarrito('Zapatos', 50)">Agregar al carrito</button>
            </div>
        </div>

        <h2>Carrito de compras</h2>
        <ul id="carrito">
            <!-- Los productos añadidos aparecerán aquí -->
        </ul>
        <p id="total">Total: $0</p>
        <button onclick="comprar()">Comprar</button>
    </div>

    <script src="script.js"></script>
</body>
</html>

<!---
PaveLMintaKa/PaveLMintaKa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
