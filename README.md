<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dragonborn of Data | Portafolio</title>
    <link href="https://fonts.googleapis.com/css2?family=MedievalSharp&family=Cinzel&display=swap" rel="stylesheet">
    <style>
        :root {
            --parchment: #F0EAD6;
            --dragon-red: #8B0000;
            --steel: #708090;
            --ancient-gold: #D4AF37;
        }

        body {
            font-family: 'Cinzel', serif;
            background: url('https://i.imgur.com/3tQqZ9x.jpg') fixed;
            color: #2F4F4F;
            margin: 0;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            padding: 50px 0;
            background: rgba(0, 0, 0, 0.7);
            border-bottom: 5px solid var(--dragon-red);
        }

        h1 {
            font-family: 'MedievalSharp', cursive;
            font-size: 3.5em;
            color: var(--ancient-gold);
            text-shadow: 3px 3px 2px #000;
            margin: 0;
        }

        .section {
            background: rgba(240, 234, 214, 0.9);
            padding: 30px;
            margin: 30px 0;
            border: 3px double var(--steel);
            border-radius: 10px;
            box-shadow: 5px 5px 15px rgba(0,0,0,0.3);
        }

        .skill-shout {
            background: var(--parchment);
            border: 2px solid var(--dragon-red);
            padding: 20px;
            margin: 15px 0;
            position: relative;
        }

        .skill-shout:before {
            content: '🗡️';
            position: absolute;
            left: -30px;
            top: -15px;
            font-size: 2em;
        }

        .dragon-font {
            font-family: 'MedievalSharp', cursive;
            color: var(--dragon-red);
        }

        .stone-table {
            background: linear-gradient(to right, #808080, #A9A9A9);
            padding: 15px;
            border-radius: 5px;
            color: white;
            margin: 20px 0;
        }

        .quest-log {
            border-left: 5px solid var(--dragon-red);
            padding-left: 20px;
            margin: 25px 0;
        }

        a {
            color: var(--dragon-red);
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-shadow: 0 0 5px var(--ancient-gold);
        }

        .shield-icon {
            font-size: 1.5em;
            margin-right: 10px;
        }

        footer {
            background: rgba(0, 0, 0, 0.8);
            color: var(--parchment);
            text-align: center;
            padding: 30px;
            margin-top: 50px;
            border-top: 3px solid var(--ancient-gold);
        }
    </style>
</head>
<body>
    <header>
        <h1>🐉 The Data Dragonborn</h1>
        <p style="color: var(--parchment); font-size: 1.2em;">"Fus Roh DATA!" - Desbloqueando el poder de la información</p>
    </header>

    <div class="container">
        <section class="section">
            <h2 class="dragon-font">📜 Sobre este Caballero de los Datos</h2>
            <div class="stone-table">
                <p>🛡️ <strong>Nivel:</strong> Ingeniero Informático</p>
                <p>⚔️ <strong>Habilidad especial:</strong> Limpieza de datos con Python</p>
                <p>🔮 <strong>Poderes mágicos:</strong> DAX, Power Query, SQL Avanzado</p>
            </div>
            <p>Viajero autodidacta que ha dominado las artes del análisis de datos a través de múltiples quests (proyectos personales). Equipado con:</p>
        </section>

        <section class="section">
            <h2 class="dragon-font">🎯 Habilidades de Guilda</h2>
            <div class="skill-shout">
                <h3>🐍 Python Shout (Pandas/Numpy/Matplotlib)</h3>
                <p>"Yol Toor Shul" - Fuego de dragón para transformar datos caóticos</p>
                <div class="stone-table">
                    <span class="shield-icon">🛡️</span>Efecto: +50% eficiencia en limpieza de datos
                </div>
            </div>

            <div class="skill-shout">
                <h3>📊 Power BI Thu'um</h3>
                <p>"Lok Vah Koor" - Despejar el cielo de datos para revelar insights</p>
                <div class="quest-log">
                    <p>⚔️ DAX Mastery: Cálculos temporales y medidas avanzadas</p>
                    <p>🔧 Power Query Forge: Transformación de metales (datos) en bruto</p>
                </div>
            </div>
        </section>

        <section class="section">
            <h2 class="dragon-font">⚔️ Quests Completadas</h2>
            
            <div class="quest-log">
                <h3>🏰 Proyecto: La Fortaleza de los Datos</h3>
                <p>⚗️ Poción usada: Python + SQL Server</p>
                <ul>
                    <li>🧹 Limpié establos de datos (300k+ registros)</li>
                    <li>🏹 Optimicé consultas de ballesta (tiempos de ejecución -40%)</li>
                    <li>📜 Creé pergaminos de vista (5 vistas estratégicas)</li>
                </ul>
                <a href="#">🔍 Ver mapa del calabozo (GitHub)</a>
            </div>

            <div class="quest-log">
                <h3>🐲 Proyecto: El Dragón de los Dashboards</h3>
                <p>🔭 Telescopio mágico: Power BI</p>
                <ul>
                    <li>📈 Construí altar de visualizaciones (15+ gráficos interactivos)</li>
                    <li>⚡ Automatización del aliento de fuego (ETL diario)</li>
                    <li>🎯 Descubrí punto débil del dragón (insight clave)</li>
                </ul>
                <a href="#">🏆 Ver trofeo de caza (Demo)</a>
            </div>
        </section>

        <section class="section">
            <h2 class="dragon-font">🗺️ Encuéntrame en Tamriel</h2>
            <div class="stone-table" style="text-align: center;">
                <p>🕊️ Palomar: <a href="mailto:tucorreo@ejemplo.com">tucorreo@ejemplo.com</a></p>
                <p>📜 Pergamino de contacto: <a href="#">LinkedIn</a></p>
                <p>💎 Tesoro de código: <a href="#">GitHub</a></p>
            </div>
        </section>
    </div>

    <footer>
        <p>"Lo que el dragón nace para hacer... es analizar datos" - Paarthurnax (versión 2.0)</p>
        <p>⚔️ Creado con el Elder Scrolls de HTML5 y CSS3 ⚔️</p>
    </footer>
</body>
</html>
