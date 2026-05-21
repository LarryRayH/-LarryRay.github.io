<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Larry Ray Haziel Flores Pachauri | Portafolio</title>
    <style>
        /* ==========================================================================
           Estilos Globales y Reset
           ========================================================================== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background-color: #f8fafc;
            color: #1e293b;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* ==========================================================================
           Sección Hero (Encabezado principal)
           ========================================================================== */
        .hero {
            background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 100%);
            color: #ffffff;
            padding: 80px 0;
            text-align: center;
        }

        .hero h1 {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 15px;
            letter-spacing: -0.5px;
        }

        .hero .subtitle {
            font-size: 1.25rem;
            color: #93c5fd;
            font-weight: 300;
        }

        /* ==========================================================================
           Secciones de Contenido
           ========================================================================== */
        section {
            padding: 50px 0;
        }

        h2 {
            font-size: 1.8rem;
            color: #0f172a;
            margin-bottom: 25px;
            position: relative;
            padding-bottom: 8px;
        }

        h2::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50px;
            height: 4px;
            background-color: #3b82f6;
            border-radius: 2px;
        }

        /* Sobre mí */
        .about-section p {
            font-size: 1.15rem;
            color: #475569;
        }

        /* ==========================================================================
           Cuadrícula de Habilidades (Cards)
           ========================================================================== */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .skill-card {
            background-color: #ffffff;
            padding: 25px;
            border-radius: 8px;
            border: 1px solid #e2e8f0;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
        }

        .skill-number {
            display: block;
            font-size: 1.5rem;
            font-weight: bold;
            color: #3b82f6;
            margin-bottom: 10px;
        }

        .skill-card p {
            font-size: 0.95rem;
            color: #334155;
        }

        /* ==========================================================================
           Pie de Página
           ========================================================================== */
        footer {
            text-align: center;
            padding: 30px 0;
            background-color: #0f172a;
            color: #64748b;
            font-size: 0.9rem;
            margin-top: 40px;
        }

        /* Responsive - Pantallas pequeñas (Celulares) */
        @media (max-width: 600px) {
            .hero h1 {
                font-size: 1.8rem;
            }
            .hero .subtitle {
                font-size: 1rem;
            }
            .skills-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <header class="hero">
        <div class="container">
            <h1>Soy Larry Ray Haziel Flores Pachauri</h1>
            <p class="subtitle">Soy estudiante de Ciencias de la Computación de la UCSP</p>
        </div>
    </header>

    <main class="container">
        
        <section class="about-section">
            <h2>Sobre mí</h2>
            <p>Estoy en la etapa perfecta para absorber conocimientos, colaborar en proyectos desafiantes y aportar una perspectiva innovadora.</p>
        </section>

        <section class="skills-section">
            <h2>Habilidades</h2>
            <div class="skills-grid">
                
                <div class="skill-card">
                    <span class="skill-number">01</span>
                    <p>Equilibro entregas y proyectos manteniendo los plazos bajo control.</p>
                </div>

                <div class="skill-card">
                    <span class="skill-number">02</span>
                    <p>Me apasiona estructurar ideas y resolver problemas complejos paso a paso.</p>
                </div>

                <div class="skill-card">
                    <span class="skill-number">03</span>
                    <p>Me entusiasma trabajar con gente nueva, escuchar ideas y sumar al grupo.</p>
                </div>

                <div class="skill-card">
                    <span class="skill-number">04</span>
                    <p>Me acoplo sin problemas a nuevos ritmos de trabajo, metodologías y entornos.</p>
                </div>

            </div>
        </section>
    </main>

    <footer>
        <p>© 2026 Larry Ray Haziel Flores Pachauri | Desarrollado con HTML y CSS</p>
    </footer>

</body>
</html>
