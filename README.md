<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Simple</title>
    <style>
        /* Estilo del fondo blanco y el texto */
        body {
            background-color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            color: black;
        }

        /* Asegura que todos los elementos estén alineados verticalmente */
        div {
            display: flex;
            flex-direction: column;
        }

        /* Estilos para las etiquetas */
        p, ul, ol, li {
            margin: 10px 0; /* Espaciado entre los elementos */
        }

        ul, ol {
            padding-left: 20px; /* Espaciado para listas */
        }

        /* Estilo para la imagen */
        img {
            max-width: 100%; /* Hace que la imagen no sobrepase el ancho de la página */
            height: auto; /* Mantiene la proporción de la imagen */
            margin-bottom: 20px; /* Espaciado debajo de la imagen */
        }
    </style>
</head>
<body>

    <div>
        <!-- Reemplaza "ruta-de-tu-imagen.jpg" con la URL o ruta de tu imagen -->
        <img src="ruta-de-tu-imagen.jpg" alt="Imagen descriptiva">

        <p>Este es un párrafo de texto.</p>
        
        <!-- Lista con los datos que mencionaste -->
        <ul>
            <li><strong>TagNo:</strong> [Valor]</li>
            <li><strong>Tag Type:</strong> [Valor]</li>
            <li><strong>Effective Timestamp:</strong> [Valor]</li>
            <li><strong>Verification Code:</strong> [Valor]</li>
            <li><strong>Create Timestamp:</strong> [Valor]</li>
            <li><strong>End Timestamp:</strong> [Valor]</li>
            <li><strong>Status Code:</strong> [Valor]</li>
            <li><strong>VIN:</strong> [Valor]</li>
            <li><strong>Model Year:</strong> [Valor]</li>
            <li><strong>Make:</strong> [Valor]</li>
            <li><strong>Vehicle BodyType:</strong> [Valor]</li>
            <li><strong>Major Color:</strong> [Valor]</li>
            <li><strong>Dealer GDN:</strong> [Valor]</li>
            <li><strong>Dealer Name:</strong> [Valor]</li>
            <li><strong>Dealer DBA:</strong> [Valor]</li>
            <li><strong>Address:</strong> [Valor]</li>
        </ul>
    </div>

</body>
</html>
