<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page Innovadora</title>
    <style>
        :root {
            --primary-color: #ff6f61;
            --secondary-color: #4a90e2;
            --text-light: #ffffff;
            --text-dark: #333333;
        }

        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ff6f61, #4a90e2);
            color: var(--text-light);
            overflow-x: hidden;
        }

        /* Gradiente de fondo animado */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.1), transparent);
            animation: pulse 6s infinite;
            z-index: -1;
        }

        @keyframes pulse {
            0%, 100% {
                opacity: 0.4;
                transform: scale(1);
            }
            50% {
                opacity: 0.8;
                transform: scale(1.1);
            }
        }

        header {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.6);
            clip-path: polygon(0 0, 100% 0, 100% 90%, 0 100%);
        }

        header h1 {
            font-size: 3rem;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.2rem;
            margin: 20px 0;
        }

        .btn {
            padding: 15px 30px;
            background: var(--primary-color);
            color: var(--text-light);
            font-size: 1rem;
            text-transform: uppercase;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.4);
        }

        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 50px 20px;
            background: #ffffff;
            color: var(--text-dark);
        }

        .card {
            background: linear-gradient(145deg, var(--primary-color), var(--secondary-color));
            color: var(--text-light);
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
            width: 300px;
            margin: 20px;
            overflow: hidden;
            transition: transform 0.4s ease;
        }

        .card:hover {
            transform: scale(1.05);
        }

        .card img {
            width: 100%;
            border-bottom: 5px solid var(--text-light);
        }

        .card-content {
            padding: 20px;
            text-align: center;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: var(--secondary-color);
            color: var(--text-light);
        }

        /* Responsividad */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5rem;
            }

            .card {
                width: 90%;
            }
        }

        @media (max-width: 480px) {
            header h1 {
                font-size: 2rem;
            }

            header p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a la Innovación</h1>
        <p>Explora un diseño moderno, interactivo y atractivo.</p>
        <button class="btn">Descubre Más</button>
    </header>

    <section>
        <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Ejemplo">
            <div class="card-content">
                <h3>Título Atractivo</h3>
                <p>Descripción breve sobre este tema.</p>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Ejemplo">
            <div class="card-content">
                <h3>Título Atractivo</h3>
                <p>Descripción breve sobre este tema.</p>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Ejemplo">
            <div class="card-content">
                <h3>Título Atractivo</h3>
                <p>Descripción breve sobre este tema.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Innovación Web. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
