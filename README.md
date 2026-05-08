<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Podcast: Dominando Mendeley - UCV</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --ucv-blue: #003366;
            --ucv-red: #cc0000;
            --light-bg: #f4f7f6;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--light-bg);
            margin: 0;
            color: #333;
        }
        header {
            background: var(--ucv-blue);
            color: white;
            padding: 2rem;
            text-align: center;
            border-bottom: 5px solid var(--ucv-red);
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        .section {
            margin-bottom: 30px;
            padding: 20px;
            border-left: 5px solid var(--ucv-blue);
            background: #fafafa;
        }
        /* Reproductor de Audio */
        .audio-player {
            background: #eef2f3;
            padding: 20px;
            border-radius: 50px;
            text-align: center;
            margin: 20px 0;
        }
        /* Galería de PPT */
        .ppt-viewer {
            display: flex;
            overflow-x: auto;
            gap: 15px;
            padding: 10px;
            scroll-snap-type: x mandatory;
        }
        .ppt-slide {
            min-width: 100%;
            scroll-snap-align: start;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .btn {
            display: inline-block;
            padding: 12px 25px;
            background: var(--ucv-red);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: 0.3s;
            margin: 5px;
        }
        .btn:hover { background: #990000; }
        footer { text-align: center; padding: 20px; font-size: 0.9rem; color: #666; }
    </style>
</head>
<body>

<header>
    <h1>Podcast: Dominando Mendeley</h1>
    <p>Gestión de Contenidos Digitales y del Conocimiento</p>
</header>

<div class="container">
    
    <div class="section">
        <h2><i class="fas fa-info-circle"></i> Presentación</h2>
        <p>Bienvenido a esta experiencia interactiva. Aquí aprenderás a instalar y utilizar <strong>Mendeley</strong> para potenciar tu producción científica[cite: 161, 162].</p>
    </div>

    <div class="section">
        <h2><i class="fas fa-microphone-lines"></i> Escuchar Podcast</h2>
        <div class="audio-player">
            <audio controls style="width: 100%;">
                <source src="8_may_9.05_am.aac" type="audio/aac">
                Tu navegador no soporta el audio.
            </audio>
            <p><small>Locución: Khunji Marilyn Alarcón Jimenez[cite: 160].</small></p>
        </div>
    </div>

    <div class="section">
        <h2><i class="fas fa-chalkboard-teacher"></i> Guía Visual (PPT)</h2>
        <div class="ppt-viewer">
            <img src="slide1.jpg" alt="Paso 1" class="ppt-slide">
            <img src="slide2.jpg" alt="Paso 2" class="ppt-slide">
            <img src="slide3.jpg" alt="Paso 3" class="ppt-slide">
        </div>
        <p style="text-align:center;"><small>← Desliza para ver las diapositivas →</small></p>
    </div>

    <div class="section" style="text-align: center;">
        <h2>Recursos Directos</h2>
        <a href="https://www.mendeley.com/download-desktop-new/" target="_blank" class="btn">
            <i class="fas fa-download"></i> Descargar Mendeley
        </a>
        <a href="https://apastyle.apa.org/" target="_blank" class="btn">
            <i class="fas fa-book"></i> Manual APA 7ma
        </a>
    </div>

    <div class="section">
        <h2><i class="fas fa-users-cog"></i> Evidencias de Gestión</h2>
        <p>Trabajo elaborado de forma individual utilizando herramientas de <strong>Google Workspace</strong> para la planificación y almacenamiento[cite: 308, 309].</p>
    </div>

</div>

<footer>
    <p>&copy; 2026 Universidad César Vallejo | Hans Peter Cerrón Lliempe [cite: 9, 16]</p>
</footer>

</body>
</html>
