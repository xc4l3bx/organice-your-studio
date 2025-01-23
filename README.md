<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Organiza tu Estudio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 1rem;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #4CAF50;
        }
        main {
            padding: 2rem;
            text-align: center;
        }
        .section {
            margin-bottom: 2rem;
        }
        .btn {
            padding: 0.5rem 1rem;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Organiza tu Estudio</h1>
        <p>La herramienta perfecta para organizar tus tareas y tiempo.</p>
    </header>

    <nav>
        <a href="#planificadores">Planificadores</a>
        <a href="#horarios">Generador de Horarios</a>
        <a href="#consejos">Consejos</a>
    </nav>

    <main>
        <!-- Sección de Planificadores -->
        <section id="planificadores" class="section">
            <h2>Planificadores Descargables</h2>
            <p>Descarga nuestras plantillas para organizar tus tareas y horarios.</p>
            <button class="btn">Descargar Plantillas</button>
        </section>

        <!-- Sección de Generador de Horarios -->
        <section id="horarios" class="section">
            <h2>Generador de Horarios</h2>
            <p>Elige tus materias y crea un horario personalizado.</p>
            <button class="btn">Crear mi Horario</button>
        </section>

        <!-- Sección de Consejos -->
        <section id="consejos" class="section">
            <h2>Consejos para Estudiar Mejor</h2>
            <ul>
                <li>Organiza tu tiempo usando bloques de estudio.</li>
                <li>Haz resúmenes para cada tema importante.</li>
                <li>Elimina distracciones mientras estudias.</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Organiza tu Estudio - Todos los derechos reservados</p>
    </footer>
</body>
</html>

