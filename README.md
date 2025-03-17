# escuela-deportiva-jose-ternera.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Escuela de Formación Deportiva José Ternera</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Escuela de Formación Deportiva José Ternera</h1>
        <nav>
            <ul>
                <li><a href="#registro">Registro</a></li>
                <li><a href="#rendimiento">Rendimiento</a></li>
                <li><a href="#disciplinas">Disciplinas</a></li>
            </ul>
        </nav>
    </header>

    <!-- Registro -->
    <section id="registro">
        <h2>Registrar Deportista</h2>
        <form id="registroForm">
            <label for="nombre">Nombre del Estudiante:</label>
            <input type="text" id="nombre" placeholder="Ingresa tu nombre" required><br><br>

            <label for="disciplina">Elige tu disciplina:</label>
            <select id="disciplina" required>
                <option value="futbol">Fútbol ⚽</option>
                <option value="voley">Vóley 🏐</option>
            </select><br><br>

            <label for="usuario">Nombre de Usuario (usará su nombre):</label>
            <input type="text" id="usuario" required><br><br>

            <label for="contraseña">Contraseña:</label>
            <input type="password" id="contraseña" value="12345" readonly><br><br>

            <button type="submit">Registrar</button>
        </form>
    </section>

    <!-- Rendimiento -->
    <section id="rendimiento">
        <h2>Rendimiento del Deportista</h2>
        <form id="rendimientoForm">
            <label for="asistencia">Número de días asistidos:</label>
            <input type="number" id="asistencia" placeholder="Días asistidos" required><br><br>

            <label for="velocidad">Velocidad (km/h):</label>
            <input type="number" id="velocidad" placeholder="Velocidad" required><br><br>

            <label for="resistencia">Resistencia (minutos):</label>
            <input type="number" id="resistencia" placeholder="Resistencia" required><br><br>

            <label for="potencia">Potencia (kg):</label>
            <input type="number" id="potencia" placeholder="Potencia" required><br><br>

            <button type="submit">Registrar Rendimiento</button>
        </form>
    </section>

    <!-- Disciplinas -->
    <section id="disciplinas">
        <h2>Disciplinas</h2>
        <p>Fútbol ⚽</p>
        <p>Vóley 🏐</p>
    </section>

    <footer>
        <p>Profesores: Alejandro Ramos, José Ternera, Juan Camilo Meza, Isaías Polo, Juandavid Fragoso</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
