<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Subir Foto y Descripción</title>
</head>
<body>

    <h1>Sube tu Foto y Añade una Descripción</h1>

    <form action="tu_script_de_procesamiento.php" method="post" enctype="multipart/form-data">
        <div>
            <label for="foto">Selecciona una foto:</label>
            <input type="file" id="foto" name="foto_usuario" accept="image/*" required>
        </div>
        <br>
        <div>
            <label for="descripcion">Descripción:</label>
            <textarea id="descripcion" name="descripcion_usuario" rows="4" cols="50" required></textarea>
        </div>
        <br>
        <div>
            <input type="submit" value="Subir">
        </div>
    </form>

</body>
</html>
