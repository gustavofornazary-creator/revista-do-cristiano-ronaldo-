# revista-do-cristiano-ronaldo-
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CR7 Magazine - A Revista Oficial de Cristiano Ronaldo</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400;500&display=swap');
        
        :root {
            --gold: #FFD700;
            --red: #DA291C;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f8f8f8;
        }
        
        header {
            background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), url('https://source.unsplash.com/1600x900/?cristiano-ronaldo') center/cover no-repeat;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            position: relative;
        }
        
        .nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(0,0,0,0.95);
            padding: 15px 0;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 5%;
        }
        
        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            font-weight: 700;
            color: var(--gold);
            letter-spacing: 2px;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 30px;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-links a:hover {
            color: var(--gold);
        }
        
        .hero-content {
            max-width: 800px;
            z-index: 2;
        }
        
        .hero-content h1 {
            font-family: 'Playfair Display', serif;
            font-size: 4.5rem;
            margin-bottom: 20px;
            text-shadow: 0 4px 20px rgba(0,0,0,0.8);
        }
        
        .hero-content p {
            font-size: 1.4rem;
            margin-bottom: 30px;
        }
        
        .btn {
            display: inline-block;
            background: var(--red);
            color: white;
            padding: 14px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s;
        }
        
        .btn:hover {
            background: #c81e12;
            transform: translateY(-3px);
        }
        
        section {
            padding: 100px 5%;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        h2 {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            text-align: center;
            margin-bottom: 60px;
            color: #111;
        }
        
        .bio {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }
        
        .bio-img {
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }
        
        .stats {
            background: #111;
            color: white;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
        }
        
        .stat-card {
            background: #222;
            padding: 40px 20px;
            text-align: center;
            border-radius: 15px;
            transition: transform 0.3s;
        }
        
        .stat-card:hover {
            transform: translateY(-10px);
        }
        
        .stat-number {
            font-size: 3.5rem;
            font-weight: 700;
            color: var(--gold);
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .gallery img {
            width: 100%;
            height: 300px;
            object-fit: cover;
            border-radius: 15px;
            transition: transform 0.4s;
        }
        
        .gallery img:hover {
            transform: scale(1.05);
        }
        
        .news {
            background: #f1f1f1;
        }
        
        .news-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
        }
        
        .news-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .news-card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }
        
        footer {
            background: #111;
            color: #aaa;
            text-align: center;
            padding: 60px 20px;
        }
        
        @media (max-width: 768px) {
            .hero-content h1 {
                font-size: 3rem;
            }
            .bio {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Navegação -->
    <nav class="nav">
        <div class="logo">CR7 <span style="color:white;">MAGAZINE</span></div>
        <div class="nav-links">
            <a href="#home">Início</a>
            <a href="#bio">Biografia</a>
            <a href="#stats">Estatísticas</a>
            <a href="#gallery">Galeria</a>
            <a href="#news">Notícias</a>
        </div>
    </nav>

    <!-- Hero -->
    <header id="home">
        <div class="hero-content">
            <h1>CRISTIANO RONALDO</h1>
            <p>A maior lenda do futebol mundial • 5x Bola de Ouro</p>
            <a href="#bio" class="btn">Conheça a História</a>
        </div>
    </header>

    <!-- Biografia -->
    <section id="bio">
        <div class="container">
            <h2>Sua História</h2>
            <div class="bio">
                <div>
                    <h3>Nascido para ser o Melhor</h3>
                    <p>Cristiano Ronaldo dos Santos Aveiro nasceu em 5 de fevereiro de 1985, na ilha da Madeira, Portugal. Desde criança, mostrou talento excepcional e foi para o Sporting CP aos 12 anos.</p>
                    <p>Em 2003, transferiu-se para o Manchester United, onde explodiu mundialmente. Depois passou pelo Real Madrid (onde se tornou o maior artilheiro da história do clube), Juventus e voltou ao Manchester United. Hoje joga no Al-Nassr, na Arábia Saudita.</p>
                    <ul style="margin-top: 20px; line-height: 2;">
                        <li>⭐ 5 Bolas de Ouro</li>
                        <li>⭐ Maior artilheiro da história do futebol</li>
                        <li>⭐ Campeão da UEFA Champions League (5x)</li>
                        <li>⭐ Campeão Europeu com Portugal (2016)</li>
                    </ul>
                </div>
                <img src="https://source.unsplash.com/800x600/?cristiano-ronaldo-celebration" alt="Cristiano Ronaldo" class="bio-img">
            </div>
        </div>
    </section>

    <!-- Estatísticas -->
    <section id="stats" class="stats">
        <div class="container">
            <h2 style="color:white;">Números que Falam por Si</h2>
            <div class="stats-grid">
                <div class="stat-card">
                    <div class="stat-number">900+</div>
                    <p>Gols na Carreira</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">5</div>
                    <p>Bolas de Ouro</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">5</div>
                    <p>Champions League</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">130+</div>
                    <p>Gols pela Seleção</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Galeria -->
    <section id="gallery">
        <div class="container">
            <h2>Galeria CR7</h2>
            <div class="gallery">
                <img src="https://source.unsplash.com/600x400/?cristiano-ronaldo-goal" alt="Gol">
                <img src="https://source.unsplash.com/600x400/?cristiano-ronaldo-trophy" alt="Trofeu">
                <img src="https://source.unsplash.com/600x400/?cristiano-ronaldo-training" alt="Treino">
                <img src="https://source.unsplash.com/600x400/?cristiano-ronaldo-family" alt="Família">
            </div>
        </div>
    </section>

    <!-- Notícias -->
    <section id="news" class="news">
        <div class="container">
            <h2>Últimas Notícias</h2>
            <div class="news-grid">
                <div class="news-card">
                    <img src="https://source.unsplash.com/600x300/?cristiano-ronaldo-interview" alt="Entrevista">
                    <div style="padding: 20px;">
                        <h3>Ronaldo marca hat-trick e lidera Al-Nassr</h3>
                        <p>CR7 continua imparável na Arábia Saudita e mostra que ainda tem muito a oferecer.</p>
                        <small style="color:#666;">24 de Junho de 2026</small>
                    </div>
                </div>
                <div class="news-card">
                    <img src="https://source.unsplash.com/600x300/?cristiano-ronaldo-portugal" alt="Portugal">
                    <div style="padding: 20px;">
                        <h3>Seleção Portuguesa sonha com o hexa</h3>
                        <p>Ronaldo lidera o grupo de craques portugueses rumo à Copa do Mundo.</p>
                        <small style="color:#666;">22 de Junho de 2026</small>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 CR7 Magazine • Fan Site dedicado a Cristiano Ronaldo</p>
        <p>Feito com ❤️ para o maior de todos</p>
    </footer>

    <script>
        // Scroll suave
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Efeito no header
        window.addEventListener('scroll', () => {
            if (window.scrollY > 100) {
                document.querySelector('.nav').style.background = 'rgba(0,0,0,0.98)';
            }
        });
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CR7 Magazine - A Revista Oficial de Cristiano Ronaldo</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400;500;700&display=swap');
        
        :root {
            --gold: #FFD700;
            --red: #DA291C;
            --dark: #111;
        }
        
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f8f8f8;
        }
        
        header {
            background: linear-gradient(rgba(0,0,0,0.75), rgba(0,0,0,0.75)), url('https://source.unsplash.com/2000x1200/?cristiano-ronaldo-stadium') center/cover no-repeat;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            position: relative;
        }
        
        .nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(0,0,0,0.95);
            padding: 15px 5%;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 32px;
            font-weight: 700;
            color: var(--gold);
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 35px;
            font-weight: 500;
            transition: 0.3s;
        }
        
        .nav-links a:hover { color: var(--gold); }

        .hero-content h1 {
            font-family: 'Playfair Display', serif;
            font-size: 5.5rem;
            margin-bottom: 15px;
            text-shadow: 0 5px 25px rgba(0,0,0,0.9);
        }
        
        .hero-content p {
            font-size: 1.5rem;
            margin-bottom: 30px;
        }

        .btn {
            background: var(--red);
            color: white;
            padding: 16px 45px;
            border-radius: 50px;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: 600;
            transition: 0.4s;
        }
        .btn:hover {
            background: #c81e12;
            transform: scale(1.05);
        }

        section { padding: 110px 5%; }
        .container { max-width: 1300px; margin: 0 auto; }

        h2 {
            font-family: 'Playfair Display', serif;
            font-size: 3.2rem;
            text-align: center;
            margin-bottom: 70px;
            color: var(--dark);
        }

        /* Bio */
        .bio {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 70px;
            align-items: center;
        }
        .bio-img {
            border-radius: 20px;
            box-shadow: 0 25px 50px rgba(0,0,0,0.25);
        }

        /* Timeline */
        .timeline {
            max-width: 900px;
            margin: 0 auto;
            position: relative;
        }
        .timeline::before {
            content: '';
            position: absolute;
            width: 4px;
            background: var(--gold);
            top: 0;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
        }
        .timeline-item {
            margin: 50px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .timeline-item:nth-child(even) { flex-direction: row-reverse; }
        .timeline-content {
            width: 45%;
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        /* Stats */
        .stats {
            background: var(--dark);
            color: white;
        }
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 30px;
        }
        .stat-card {
            background: #222;
            padding: 45px 20px;
            text-align: center;
            border-radius: 18px;
        }
        .stat-number {
            font-size: 4rem;
            font-weight: 700;
            color: var(--gold);
        }

        /* Gallery */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 20px;
        }
        .gallery img {
            width: 100%;
            height: 320px;
            object-fit: cover;
            border-radius: 18px;
            transition: 0.4s;
        }
        .gallery img:hover { transform: scale(1.06); }

        /* Quotes */
        .quotes {
            background: #f1f1f1;
            text-align: center;
        }
        .quote {
            font-size: 1.4rem;
            font-style: italic;
            max-width: 800px;
            margin: 0 auto 20px;
        }

        /* News */
        .news-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(380px, 1fr));
            gap: 30px;
        }
        .news-card {
            background: white;
            border-radius: 18px;
            overflow: hidden;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
            transition: 0.3s;
        }
        .news-card:hover { transform: translateY(-10px); }

        footer {
            background: #0a0a0a;
            color: #aaa;
            text-align: center;
            padding: 80px 20px;
        }

        @media (max-width: 768px) {
            .hero-content h1 { font-size: 3.5rem; }
            .bio { grid-template-columns: 1fr; }
            .timeline::before { left: 30px; }
            .timeline-item { flex-direction: column !important; }
        }
    </style>
</head>
<body>

    <nav class="nav">
        <div class="logo">CR7 <span style="color:white;">MAGAZINE</span></div>
        <div class="nav-links">
            <a href="#home">Início</a>
            <a href="#bio">Biografia</a>
            <a href="#timeline">Carreira</a>
            <a href="#stats">Estatísticas</a>
            <a href="#gallery">Galeria</a>
            <a href="#news">Notícias</a>
        </div>
    </nav>

    <!-- Hero -->
    <header id="home">
        <div class="hero-content">
            <h1>CRISTIANO RONALDO</h1>
            <p>O Maior de Todos os Tempos • Siuuuu!</p>
            <a href="#bio" class="btn">Ler a Revista Completa</a>
        </div>
    </header>

    <!-- Biografia -->
    <section id="bio">
        <div class="container">
            <h2>Sua História</h2>
            <div class="bio">
                <div>
                    <h3>De Madeira para o Mundo</h3>
                    <p>Nascido em 5 de fevereiro de 1985, na Funchal, Cristiano Ronaldo superou dificuldades financeiras e problemas de saúde na infância para se tornar o maior jogador de futebol da história.</p>
                    <p>Passou pelo Sporting, Manchester United, Real Madrid, Juventus, voltou ao United e hoje brilha no Al-Nassr, na Arábia Saudita. É pai de 5 filhos e um exemplo mundial de dedicação e profissionalismo.</p>
                </div>
                <img src="https://source.unsplash.com/800x600/?cristiano-ronaldo-portrait" alt="Cristiano Ronaldo" class="bio-img">
            </div>
        </div>
    </section>

    <!-- Timeline -->
    <section id="timeline">
        <div class="container">
            <h2>Carreira em Destaque</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-content">
                        <strong>2003</strong> — Estreia pelo Manchester United
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <strong>2008</strong> — Primeira Bola de Ouro e Champions League
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <strong>2009-2018</strong> — Era dourada no Real Madrid (450 gols em 438 jogos)
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <strong>2016</strong> — Campeão da Euro com Portugal
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <strong>2021-2025</strong> — Volta ao United e ida para o Al-Nassr
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Estatísticas -->
    <section id="stats" class="stats">
        <div class="container">
            <h2 style="color:white;">Números Imbatíveis</h2>
            <div class="stats-grid">
                <div class="stat-card">
                    <div class="stat-number">920+</div>
                    <p>Gols na Carreira</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">5</div>
                    <p>Bolas de Ouro</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">5</div>
                    <p>Champions League</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">135+</div>
                    <p>Gols pela Seleção Portuguesa</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">900+</div>
                    <p>Jogos pelo Real Madrid</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Galeria -->
    <section id="gallery">
        <div class="container">
            <h2>Galeria de Momentos Épicos</h2>
            <div class="gallery">
                <img src="https://source.unsplash.com/700x500/?cristiano-ronaldo-goal" alt="Gol">
                <img src="https://source.unsplash.com/700x500/?cristiano-ronaldo-trophy" alt="Trofeu">
                <img src="https://source.unsplash.com/700x500/?cristiano-ronaldo-celebration" alt="Celebração">
                <img src="https://source.unsplash.com/700x500/?cristiano-ronaldo-family" alt="Família">
                <img src="https://source.unsplash.com/700x500/?cristiano-ronaldo-training" alt="Treino">
                <img src="https://source.unsplash.com/700x500/?cristiano-ronaldo-interview" alt="Entrevista">
            </div>
        </div>
    </section>

    <!-- Citação -->
    <section class="quotes">
        <div class="container">
            <h2>Palavras do CR7</h2>
            <p class="quote">"Eu não sigo ninguém. Sou eu que marco o caminho."</p>
            <p class="quote">"O talento sem trabalho duro é apenas um sonho."</p>
        </div>
    </section>

    <!-- Notícias -->
    <section id="news" class="news">
        <div class="container">
            <h2>Últimas Notícias</h2>
            <div class="news-grid">
                <div class="news-card">
                    <img src="https://source.unsplash.com/700x400/?cristiano-ronaldo-2026" alt="">
                    <div style="padding: 25px;">
                        <h3>Ronaldo marca 2 gols e vence o clássico</h3>
                        <p>CR7 continua sendo decisivo aos 41 anos e lidera o Al-Nassr na liga saudita.</p>
                        <small>24 de Junho de 2026</small>
                    </div>
                </div>
                <div class="news-card">
                    <img src="https://source.unsplash.com/700x400/?portugal-national-team" alt="">
                    <div style="padding: 25px;">
                        <h3>Portugal convoca Ronaldo para amistosos</h3>
                        <p>O capitão da Seleção segue sendo peça fundamental para o técnico.</p>
                        <small>22 de Junho de 2026</small>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 CR7 Magazine • Fan Site Não Oficial</p>
        <p>Feito com paixão pelo maior jogador de todos os tempos 🔥</p>
    </footer>

    <script>
        // Scroll suave
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
