
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Contacto</title>
    <style>
        /* Estilos para el contenedor del formulario */
        .contenedor-formulario {
            width: 50%;
            margin: 0 auto;
            padding: 30px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            font-family: Arial, sans-serif;
        }

        /* Estilo para los encabezados y texto del formulario */
        h1 {
            text-align: center;
            color: #333;
        }

        p {
            text-align: center;
            color: #555;
        }

        /* Estilos generales para los campos del formulario */
        label {
            display: block;
            margin: 10px 0 5px;
            font-size: 16px;
            color: #333;
        }

        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
            box-sizing: border-box;
        }

        /* Estilo para el botón de envío */
        button {
            background-color: #ff0000;
            color: white;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            width: 100%;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #45a049;
        }

        /* Estilos responsivos para pantallas pequeñas */
        @media (max-width: 768px) {
            .contenedor-formulario {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <div class="contenedor-formulario">
        <h1>Formulario de Contacto</h1>
        <p>Por favor, complete el siguiente formulario para ponerse en contacto con nosotros.</p>
        
        <form action="#" method="post">
            <!-- Campo para el nombre -->
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <!-- Campo para el correo electrónico -->
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>

            <!-- Campo para el teléfono -->
            <label for="telefono">Teléfono:</label>
            <input type="tel" id="telefono" name="telefono" required>

            <!-- Lista desplegable para elegir el país -->
            <label for="pais">País:</label>
            <select id="pais" name="pais" required>
                <option value="">Selecciona un país</option>
                <option value="mexico">México</option>
                <option value="spain">España</option>
                <option value="argentina">Argentina</option>
                <option value="colombia">Colombia</option>
                <option value="peru">Perú</option>
            </select>

            <!-- Área de texto para comentarios -->
            <label for="comentarios">Comentarios:</label>
            <textarea id="comentarios" name="comentarios" rows="5" required></textarea>

            <!-- Botón de envío -->
            <button type="submit">Enviar</button>
        </form>
    </div>

</body>
</html>
