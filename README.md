<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page Moderna</title>
    <style>
        /* Reset Básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background: #f9f9f9;
        }

        section {
            padding: 60px 20px;
            text-align: center;
            position: relative;
        }

        section h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #333;
        }

        section p {
            max-width: 600px;
            margin: 0 auto 20px;
            color: #666;
            line-height: 1.8;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: #007bff;
            color: #fff;
            text-decoration: none;
            border-radius: 25px;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background: #0056b3;
        }

        /* Camada 1 */
        .layer1 {
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: #fff;
        }

        /* Camada 2 */
        .layer2 {
            background: #f9f9f9;
            color: #333;
        }

        /* Divisor */
        .divider {
            height: 100px;
            overflow: hidden;
        }

        .divider svg {
            position: relative;
            display: block;
            width: calc(100% + 1.3px);
            height: 100px;
        }

        .divider .wave {
            fill: #fff;
        }

        /* Camada 3 */
        .layer3 {
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            color: #fff;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            section h2 {
                font-size: 1.5rem;
            }

            .btn {
                padding: 8px 16px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <!-- Camada 1 -->
    <section class="layer1">
        <h2>Bem-vindo à Sua Solução Digital</h2>
        <p>Descubra como transformar visitantes em clientes com nossas estratégias inovadoras de marketing.</p>
        <a href="#servicos" class="btn">Saiba Mais</a>
    </section>

    <!-- Divisor -->
    <div class="divider">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
            <path class="wave" fill="#f9f9f9" d="M0,288L48,288C96,288,192,288,288,272C384,256,480,224,576,192C672,160,768,128,864,106.7C960,85,1056,75,1152,74.7C1248,75,1344,85,1392,90.7L1440,96L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path>
        </svg>
    </div>

    <!-- Camada 2 -->
    <section class="layer2" id="servicos">
        <h2>Nossos Serviços</h2>
        <p>Oferecemos estratégias personalizadas para negócios locais, garantindo resultados mensuráveis e impactantes.</p>
        <a href="#contato" class="btn">Entre em Contato</a>
    </section>

    <!-- Divisor -->
    <div class="divider">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
            <path class="wave" fill="#ff758c" d="M0,160L48,160C96,160,192,160,288,165.3C384,171,480,181,576,192C672,203,768,213,864,192C960,171,1056,117,1152,117.3C1248,117,1344,171,1392,197.3L1440,224L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path>
        </svg>
    </div>

    <!-- Camada 3 -->
    <section class="layer3" id="contato">
        <h2>Contato</h2>
        <p>Entre em contato conosco para descobrir como podemos ajudar seu negócio a crescer.</p>
        <a href="#top" class="btn">Voltar ao Topo</a>
    </section>
</body>
</html>
