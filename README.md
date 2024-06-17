# redzone
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Header Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #1a1a1a;
            width: 100%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .logo {
            display: flex;
            align-items: center;
            color: #ffffff;
        }
        .red-zone {
            font-size: 2em;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .red-zone .red {
            color: #ff3333;
        }
        .masa-aparte {
            font-size: 4em;
            margin-left: 20px;
            font-weight: bold;
            color: #ff3333;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .nav {
            display: flex;
            gap: 20px;
        }
        .nav a {
            text-decoration: none;
            color: #ffffff;
            font-size: 1em;
            font-weight: bold;
            transition: color 0.3s;
        }
        .nav a:hover {
            color: #ff3333;
        }
        .logos {
            display: flex;
            gap: 10px;
        }
        .logos img {
            width: 40px; /* Adjust the size as needed */
            height: auto;
            filter: drop-shadow(2px 2px 4px rgba(0, 0, 0, 0.5));
        }
        .content {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            width: 100%;
            padding: 20px;
            box-sizing: border-box;
        }
        .main-content {
            flex: 1;
            margin-right: 20px;
        }
        .history-box, .video-box {
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
        .history-box h2, .video-box h2 {
            color: #1a1a1a;
        }
        .history-box p {
            color: #333333;
            line-height: 1.6;
        }
        .video-box iframe {
            width: 100%;
            height: 315px; /* Standard YouTube video height */
        }
        .sidebar {
            width: 300px;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .sidebar img {
            width: 100%;
            height: auto;
        }
        .sidebar h2 {
            text-align: center;
            color: #1a1a1a;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="logo">
            <span class="red-zone">RED <span class="red">ZONE</span></span>

        </div>
        <div class="nav">
            <a href="">INICIO</a>
            <a href="posiciones.html">POSICIONES</a>
            <a href="resumenes.html">RESUMENES</a>
            <a href="Partido.html">PARTIDOS</a>
        </div>
        <div class="logos">
            <img src="mig/mexicah udc.png" alt="Logo 1">
            <img src="mig/Halcones-uver.webp" alt="Logo 2">
            <img src="mig/zorros.jfif" alt="Logo 3">
        </div>
    </div>
    <div class="content">
        <div class="main-content">
            <div class="history-box">
                <h2>Historia de Xalapa en el Fútbol Americano</h2>
                <p>
                    <!-- Aquí puedes escribir la historia de Xalapa en el fútbol americano -->
                    Xalapa ha sido un lugar importante para el desarrollo del fútbol americano en México. Con una rica tradición de equipos y jugadores talentosos, la ciudad ha visto crecer este deporte desde sus inicios en la región. Equipos locales han competido en diversas ligas y han formado a jugadores que han destacado a nivel nacional e internacional.
                </p>
            </div>
            <div class="video-box">
                <h2>Video del Partido</h2>
            <iframe width="315" src="https://www.youtube.com/embed/legMB0nZ3b8?si=noMc3xEf61uaTO2l" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></iframe>
            </div>
        </div>
        <div class="sidebar">
            <h2>Mejor Jugador</h2>
            <img src="mig/WhatsApp Image 2024-06-04 at 2.00.14 PM.jpeg" alt="Mejor Jugador">
        </div>
        </div>
    </div>
    <div class="social-media">
        <a href="https://facebook.com" target="_blank"><img src="path_to_facebook_icon.png" alt="Facebook"></a>
        <a href="https://twitter.com" target="_blank"><img src="path_to_twitter_icon.png" alt="Twitter"></a>
        <a href="https://instagram.com" target="_blank"><img src="path_to_instagram_icon.png" alt="Instagram"></a>
</body>
</html>
