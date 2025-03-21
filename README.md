# Presta-SyA
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Presta SyA - Préstamos Rápidos y Seguros</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* Estilos Base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #f8f9fa;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: white;
            padding: 1rem;
            text-align: center;
        }

        .logo {
            font-size: 2rem;
            font-weight: bold;
        }

        /* Hero Section */
        .hero {
            padding: 4rem 2rem;
            text-align: center;
            background: url('https://images.unsplash.com/photo-1580519542036-c47de6196ba5?ixlib=rb-1.2.1&auto=format&fit=crop&w=1351&q=80') no-repeat center/cover;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .cta-button {
            background-color: #ff6b6b;
            color: white;
            padding: 1rem 2rem;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            margin-top: 1rem;
            transition: transform 0.3s;
        }

        .cta-button:hover {
            transform: scale(1.05);
        }

        /* Características */
        .features {
            padding: 3rem 2rem;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            background-color: white;
        }

        .feature-card {
            text-align: center;
            padding: 1.5rem;
        }

        .feature-card i {
            font-size: 2.5rem;
            color: #1e3c72;
            margin-bottom: 1rem;
        }

        /* Cómo Funciona */
        .how-it-works {
            padding: 3rem 2rem;
            background-color: #f8f9fa;
        }

        .steps {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 2rem;
            margin-top: 2rem;
        }

        .step {
            width: 200px;
            text-align: center;
        }

        .step-number {
            background-color: #1e3c72;
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 1rem;
        }

        /* Formulario de Contacto */
        .contact {
            padding: 3rem 2rem;
            background-color: white;
        }

        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }

        .form-group {
            margin-bottom: 1rem;
        }

        input, textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        /* Footer */
        footer {
            background-color: #1e3c72;
            color: white;
            padding: 2rem;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Presta SyA</div>
    </header>

    <section class="hero">
        <h2>Obtén tu préstamo en 24 horas</h2>
        <p>Desde $1,000 hasta $50,000 MXN con tasas competitivas</p>
        <a href="#contact" class="cta-button">¡Solicitar Ahora!</a>
    </section>

    <section class="features">
        <div class="feature-card">
            <i class="fas fa-clock"></i>
            <h3>Rápido</h3>
            <p>Aprobación en menos de 24 horas</p>
        </div>
        <div class="feature-card">
            <i class="fas fa-shield-alt"></i>
            <h3>Seguro</h3>
            <p>Proceso 100% confiable y transparente</p>
        </div>
        <div class="feature-card">
            <i class="fas fa-percent"></i>
            <h3>Tasas Bajas</h3>
            <p>Intereses desde el 1.5% mensual</p>
        </div>
    </section>

    <section class="how-it-works">
        <h2 style="text-align: center;">¿Cómo funciona?</h2>
        <div class="steps">
            <div class="step">
                <div class="step-number">1</div>
                <h3>Solicitud Online</h3>
                <p>Completa el formulario en 5 minutos</p>
            </div>
            <div class="step">
                <div class="step-number">2</div>
                <h3>Revisión</h3>
                <p>Validamos tu información</p>
            </div>
            <div class="step">
                <div class="step-number">3</div>
                <h3>Desembolso</h3>
                <p>Recibe tu dinero en 24h</p>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2 style="text-align: center;">Solicita tu préstamo</h2>
        <form class="contact-form">
            <div class="form-group">
                <input type="text" placeholder="Nombre completo" required>
            </div>
            <div class="form-group">
                <input type="email" placeholder="Correo electrónico" required>
            </div>
            <div class="form-group">
                <input type="tel" placeholder="Teléfono" required>
            </div>
            <div class="form-group">
                <input type="number" placeholder="Monto solicitado (MXN)" required>
            </div>
            <div class="form-group">
                <textarea rows="4" placeholder="Mensaje adicional"></textarea>
            </div>
            <button type="submit" class="cta-button">Enviar Solicitud</button>
        </form>
    </section>

    <footer>
        <p>© 2023 Presta SyA - Todos los derechos reservados</p>
        <div style="margin-top: 1rem;">
            <a href="#" style="color: white; margin: 0 1rem;"><i class="fab fa-facebook"></i></a>
            <a href="#" style="color: white; margin: 0 1rem;"><i class="fab fa-whatsapp"></i></a>
            <a href="#" style="color: white; margin: 0 1rem;"><i class="fas fa-envelope"></i></a>
        </div>
    </footer>
</body>
</html>
