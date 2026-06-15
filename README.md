<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>xGHOST · Desarrollador</title>
    <!-- Fuentes modernas -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700&display=swap" rel="stylesheet">
    <!-- Font Awesome 6 (gratis) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #0a0f1e 0%, #0c1222 100%);
            color: #eef2ff;
            line-height: 1.5;
            scroll-behavior: smooth;
        }

        /* Banner sutil con efecto parallax */
        .banner {
            width: 100%;
            height: 280px;
            object-fit: cover;
            border-radius: 0 0 32px 32px;
            box-shadow: 0 20px 35px -15px rgba(0,0,0,0.5);
            transition: all 0.3s ease;
            filter: brightness(0.95);
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 2rem 1.5rem 4rem;
        }

        /* Badges / chips */
        .chill-badge {
            display: inline-block;
            background: rgba(255,255,240,0.08);
            backdrop-filter: blur(4px);
            border-radius: 60px;
            padding: 0.35rem 1rem;
            font-size: 0.85rem;
            font-weight: 500;
            color: #cdd9ff;
            border: 1px solid rgba(255,255,255,0.1);
        }

        h1 {
            font-size: 3.2rem;
            font-weight: 700;
            background: linear-gradient(120deg, #FFFFFF, #b9c8ff);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            letter-spacing: -0.01em;
        }

        .gradient-text {
            background: linear-gradient(135deg, #ffb347, #ff6b6b);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }

        .card-project {
            background: rgba(18, 25, 45, 0.65);
            backdrop-filter: blur(12px);
            border-radius: 28px;
            border: 1px solid rgba(255,255,255,0.08);
            transition: all 0.25s ease;
            overflow: hidden;
        }

        .card-project:hover {
            transform: translateY(-4px);
            border-color: rgba(255,120,120,0.4);
            box-shadow: 0 20px 30px -15px rgba(0,0,0,0.4);
            background: rgba(25, 35, 55, 0.75);
        }

        .tech-icon {
            transition: transform 0.2s ease;
            display: inline-block;
        }
        .tech-icon:hover {
            transform: translateY(-5px);
        }

        .social-btn {
            background: rgba(30, 40, 60, 0.6);
            backdrop-filter: blur(4px);
            border-radius: 40px;
            padding: 0.7rem 1.4rem;
            margin: 0 0.4rem;
            transition: 0.2s;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            font-weight: 500;
            border: 1px solid rgba(255,255,255,0.05);
        }
        .social-btn i {
            font-size: 1.25rem;
        }
        .social-btn:hover {
            background: #2a3a5a;
            transform: scale(1.02);
            border-color: rgba(255,160,100,0.5);
        }

        hr {
            border: none;
            height: 1px;
            background: linear-gradient(90deg, transparent, #ff7b4e40, #b886ff40, transparent);
            margin: 2rem 0;
        }

        footer {
            text-align: center;
            opacity: 0.6;
            font-size: 0.8rem;
            margin-top: 3rem;
        }

        @media (max-width: 680px) {
            .container {
                padding: 1.5rem 1rem;
            }
            h1 {
                font-size: 2.3rem;
            }
            .social-btn {
                padding: 0.5rem 1rem;
                margin: 0.3rem;
            }
        }
    </style>
</head>
<body>

<!-- Banner mejorado: mismo link pero con estilo más limpio -->
<img class="banner" src="https://i.imgur.com/0ONjwXz.gif" alt="banner xGHOST" />

<div class="container">
    <!-- Presentación con vibe personal -->
    <div style="text-align: center; margin-bottom: 2rem;">
        <span class="chill-badge">
            <i class="fas fa-crown" style="margin-right: 6px;"></i> developer & creator
        </span>
        <h1 style="margin-top: 1.2rem;">👋 Hola, Soy <span class="gradient-text">xGHOST</span></h1>
        <p style="font-size: 1.3rem; font-weight: 400; color: #cbd5ff; margin-top: 0.5rem;">✦ Un tipo chill que programa cosas random ✦</p>
        <div style="max-width: 720px; margin: 1.5rem auto 0; background: rgba(0,0,0,0.25); border-radius: 48px; padding: 1rem 1.8rem;">
            <p style="font-size: 1rem; color: #e0e7ff;">
                <i class="fas fa-code" style="margin-right: 8px; color: #ff9966;"></i> 
                <strong>xGHOST</strong> — Desarrollador indie, amante de los servidores, mapas y el código con alma. 
                Lidero proyectos como <strong>Horizon Studios</strong> y <strong>Ethernal OTserver</strong>. 
                Siempre explorando nuevas tecnologías y compartiendo lo que aprendo.
            </p>
        </div>
    </div>

    <!-- Proyectos actuales (diseño moderno tipo glassmorphism) -->
    <h2 style="font-size: 1.8rem; margin: 2rem 0 1rem 0; display: flex; align-items: center; gap: 12px;">
        <i class="fas fa-rocket" style="color: #ff8c5a;"></i> Proyectos actuales
    </h2>

    <div style="display: flex; flex-wrap: wrap; gap: 1.5rem; justify-content: center;">
        <!-- Proyecto 1 -->
        <div class="card-project" style="flex: 1; min-width: 240px; padding: 1.4rem 1.2rem;">
            <div style="display: flex; justify-content: space-between; align-items: center;">
                <h3 style="font-size: 1.6rem; font-weight: 600;">🏖️ Marbella RolePlay</h3>
                <i class="fas fa-pause-circle" style="color: #ffaa66; font-size: 1.7rem;"></i>
            </div>
            <div style="margin: 0.8rem 0;">
                <span class="chill-badge"><i class="fas fa-tag"></i> v3.5</span>
                <span class="chill-badge" style="background: #5a2e2e70;"><i class="fas fa-hourglass-half"></i> En pausa</span>
            </div>
            <p style="color: #b9c3e6; font-size: 0.9rem;">Roleplay inmersivo con mecánicas personalizadas.</p>
        </div>

        <!-- Proyecto 2 -->
        <div class="card-project" style="flex: 1; min-width: 240px; padding: 1.4rem 1.2rem;">
            <div style="display: flex; justify-content: space-between;">
                <h3 style="font-size: 1.6rem; font-weight: 600;">⚡ Ethernal OTserver</h3>
                <i class="fas fa-code-branch" style="color: #66ffb0; font-size: 1.5rem;"></i>
            </div>
            <div style="margin: 0.8rem 0;">
                <span class="chill-badge"><i class="fas fa-code"></i> v15.00x</span>
                <span class="chill-badge" style="background: #1e594570;"><i class="fas fa-spinner fa-pulse"></i> En desarrollo</span>
            </div>
            <p style="color: #b9c3e6; font-size: 0.9rem;">Motor optimizado, contenido único y comunidad activa.</p>
        </div>

        <!-- Proyecto 3 con enlace directo -->
        <div class="card-project" style="flex: 1; min-width: 260px; padding: 1.4rem 1.2rem;">
            <div style="display: flex; justify-content: space-between;">
                <h3 style="font-size: 1.6rem; font-weight: 600;">🎬 Horizon Studios</h3>
                <i class="fas fa-globe" style="color: #ffaa55;"></i>
            </div>
            <div style="margin: 0.8rem 0;">
                <span class="chill-badge">🎨 Producción</span>
                <a href="https://horizon-studios.netlify.app/" target="_blank" style="text-decoration: none;">
                    <span class="chill-badge" style="background: #164e63; cursor: pointer;"><i class="fas fa-external-link-alt"></i> Público</span>
                </a>
            </div>
            <p style="color: #b9c3e6; font-size: 0.9rem;">Estudio creativo: desarrollo + motion graphics.</p>
        </div>
    </div>

    <hr>

    <!-- Tecnologías con iconos reales y badges modernos -->
    <h2 style="font-size: 1.8rem; margin-bottom: 1.2rem; display: flex; gap: 10px;">
        <i class="fas fa-laptop-code"></i> Tech Stack
    </h2>
    <div style="display: flex; flex-wrap: wrap; gap: 0.9rem; row-gap: 1rem; margin-bottom: 2rem;">
        <span class="tech-icon"><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"></span>
        <span class="tech-icon"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"></span>
        <span class="tech-icon"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JS"></span>
        <span class="tech-icon"><img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"></span>
        <span class="tech-icon"><img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"></span>
        <span class="tech-icon"><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"></span>
        <span class="tech-icon"><img src="https://img.shields.io/badge/Pawn-0082BE?style=for-the-badge&logoColor=white&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48cGF0aCBmaWxsPSJ3aGl0ZSIgZD0iTTEyIDJDOS40MyAyIDcgNC40MyA3IDdDOTAzIDMgMCAxMiIvPjwvc3ZnPg==" alt="Pawn"></span>
        <span class="tech-icon"><img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" alt="Git"></span>
        <span class="tech-icon"><img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"></span>
    </div>

    <hr>

    <!-- Redes sociales con estilo y microinteracción -->
    <h2 style="font-size: 1.8rem; margin-bottom: 1rem;"><i class="fas fa-paper-plane"></i> Conecta conmigo</h2>
    <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 0.8rem; margin: 1.5rem 0;">
        <a href="https://discord.com/users/ghostgg_" target="_blank" class="social-btn"><i class="fab fa-discord"></i> ghostgg_</a>
        <a href="https://twitter.com/_ghostgg" target="_blank" class="social-btn"><i class="fab fa-twitter"></i> @_ghostgg</a>
        <a href="https://github.com/xghostxz" target="_blank" class="social-btn"><i class="fab fa-github"></i> xghostxz</a>
        <a href="https://instagram.com/ghostggm_" target="_blank" class="social-btn"><i class="fab fa-instagram"></i> ghostggm_</a>
        <a href="https://t.me/Gaboyzk" target="_blank" class="social-btn"><i class="fab fa-telegram"></i> Gaboyzk</a>
    </div>

    <!-- frase / más en breve -->
    <div style="text-align: center; margin: 3rem 0 1rem;">
        <div style="background: linear-gradient(145deg, #191e30, #111625); border-radius: 48px; padding: 1rem 2rem; display: inline-block;">
            <span style="font-weight: 600; letter-spacing: 1px;">✨ MÁS EN BREVE... ✨</span><br>
            <span style="font-size: 0.85rem; opacity: 0.75;">nuevos proyectos, tutoriales y código abierto</span>
        </div>
    </div>

    <footer>
        <i class="fas fa-crown" style="opacity: 0.5;"></i> xGHOST · siempre construyendo cosas random pero con amor <i class="fas fa-heart" style="color: #ff6b6b;"></i>
    </footer>
</div>

</body>
</html>
