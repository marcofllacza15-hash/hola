<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo Mineralógico</title>

    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Catálogo Mineralógico</h1>
    <p>Colección de minerales y gemas</p>

    <input
        type="text"
        id="search"
        placeholder="Buscar mineral..."
    >
</header>

<main>
    <div id="minerales-container"></div>
</main>

<div class="modal" id="modal">
    <div class="modal-content">

        <span class="close">&times;</span>

        <div id="detalle-mineral"></div>

    </div>
</div>

<script src="script.js"></script>

</body>
</html>
