# RK-Ajmera-vlogs-
public reactions to superbikes: Superbike reactions ❤️😍 by Morin Lifestyle features public reactions to superbikes. PUBLIC REACTION 😲 ON MARKET 🥰 by Rohitsoni1111b shows public reactions iMom Reacts To My First Motorcycle by Tristan Clausen offers a personal take on motorcycle reactions.#motovlog #bikersofinstagram #[BikeModel] #roadtrip #hindi.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your YouTube Channel - Official Website</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: #333;
            overflow-x: hidden;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            text-decoration: none;
            color: white;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: opacity 0.3s;
        }

        .nav-links a:hover {
            opacity: 0.8;
        }

        .hamburger {
            display: none;
            flex-direction: column;
            cursor: pointer;
        }

        .hamburger span {
            width: 25px;
            height: 3px;
            background: white;
            margin: 3px 0;
            transition: 0.3s;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 600"><rect fill="%23667eea" width="1200" height="600"/><circle fill="%23764ba2" opacity="0.3" cx="200" cy="200" r="150"/><circle fill="%23f093fb" opacity="0.4" cx="800" cy="300" r="120"/><circle fill="%23f5576c" opacity="0.3" cx="1000" cy="150" r="80"/></svg>');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            margin-top: 70px;
        }

        .hero-content h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            animation: fadeInUp 1s ease;
        }

        .hero-content p {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            max-width: 600px;
            animation: fadeInUp 1s ease 0.2s both;
        }

        .cta-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
            animation: fadeInUp 1s ease 0.4s both;
        }

        .btn {
            padding: 15px 30px;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.3s;
            cursor: pointer;
        }

        .btn-primary {
            background: #ff0000;
            color: white;
        }

        .btn-primary:hover {
            background: #cc0000;
            transform: translateY(-3px);
        }

        .btn-secondary {
            background: transparent;
            color: white;
            border: 2px solid white;
        }

        .btn-secondary:hover {
            background: white;
            color: #333;
        }

        /* Stats Section */
        .stats {
            padding: 4rem 2rem;
            background: #f8f9fa;
            text-align: center;
        }

        .stats-container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
        }

        .stat-item {
            padding: 2rem;
        }

        .stat-number {
            font-size: 3rem;
            font-weight: 700;
            background: linear-gradient(135deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        /* Videos Section */
        .videos {
            padding: 5rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #333;
        }

        .videos-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }

        .video-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: all 0.3s;
        }

        .video-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }

        .video-thumbnail {
            width: 100%;
            height: 200px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            color: white;
        }

        .video-info {
            padding: 1.5rem;
        }

        .video-title {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
            color: #333;
        }

        .video-meta {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 0.9rem;
            color: #666;
        }

        /* About Section */
        .about {
            padding: 5rem 2rem;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-align: center;
        }

        .about-content {
            max-width: 800px;
            margin: 0 auto;
        }

        /* Footer */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 3rem 2rem 1rem;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-bottom: 2rem;
        }

        .social-links a {
            width: 50px;
            height: 50px;
            background: #ff0000;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 50%;
            text-decoration: none;
            transition: all 0.3s;
        }

        .social-links a:hover {
            background: #cc0000;
            transform: translateY(-3px);
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive */
        @media (max-width: 768px) {
            .hamburger {
                display: flex;
            }

            .nav-links {
                display: none;
            }

            .hero-content h1 {
                font-size: 2.5rem;
            }

            .cta-buttons {
                flex-direction: column;
                align-items: center;
            }

            .btn {
                width: 100%;
                max-width: 300px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <a href="#" class="logo">YourChannel</a>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#videos">Videos</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to YourChannel</h1>
            <p>Discover amazing content, tutorials, and entertainment. Subscribe for weekly uploads!</p>
            <div class="cta-buttons">
                <a href="https://youtube.com/@yourchannel" target="_blank" class="btn btn-primary">
                    <i class="fab fa-youtube"></i> Subscribe
                </a>
                <a href="#videos" class="btn btn-secondary">Watch Latest</a>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="stats">
        <div class="stats-container">
            <div class="stat-item">
                <div class="stat-number" data-target="150">0</div>
                <div>Subscribers</div>
            </div>
            <div class="stat-item">
                <div class="stat-number" data-target="500">0</div>
                <div>Videos</div>
            </div>
            <div class="stat-item">
                <div class="stat-number" data-target="1M">0</div>
                <div>Total Views</div>
            </div>
            <div class="stat-item">
                <div class="stat-number" data-target="50K">0</div>
                <div>Monthly Views</div>
            </div>
        </div>
    </section>

    <!-- Videos Section -->
    <section id="videos" class="videos">
        <h2 class="section-title">Latest Videos</h2>
        <div class="videos-grid">
            <div class="video-card">
                <div class="video-thumbnail">
                    <i class="fas fa-play"></i>
                </div>
                <div class="video-info">
                    <div class="video-title">Amazing Tutorial #1</div>
                    <div class="video-meta">
                        <span>2 days ago</span>
                        <span>25K views</span>
                    </div>
                </div>
            </div>
            <div class="video-card">
                <div class="video-thumbnail">
                    <i class="fas fa-play"></i>
                </div>
                <div class="video-info">
                    <div class="video-title">Best Gaming Moments</div>
                    <div class="video-meta">
                        <span>5 days ago</span>
                        <span>45K views</span>
                    </div>
                </div>
            </div>
            <div class="video-card">
                <div class="video-thumbnail">
                    <i class="fas fa-play"></i>
                </div>
                <div class="video-info">
                    <div class="video-title">Life Hacks You Need</div>
                    <div class="video-meta">
                        <span>1 week ago</span>
                        <span>67K views</span>
                    </div>
                </div>
            </div>
            <div class="video-card">
                <div class="video-thumbnail">
                    <i class="fas fa-play"></i>
                </div>
                <div class="video-info">
                    <div class="video-title">Q&A Session</div>
                    <div class="video-meta">
                        <span>2 weeks ago</span>
                        <span>33K views</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="about-content">
            <h2>About YourChannel</h2>
            <p>Welcome to YourChannel! We're passionate about creating high-quality content that entertains, educates, and inspires. Join our growing community of amazing viewers from around the world!</p>
            <div style="margin-top: 2rem;">
                <a href="https://youtube.com/@yourchannel" target="_blank" class="btn btn-primary" style="font-size: 1.2rem; padding: 18px 40px;">
                    Join the Community
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact">
        <div class="social-links">
            <a href="https://youtube.com/@yourchannel" target="_blank"><i class="fab fa-youtube"></i></a>
            <a href="https://instagram.com/yourchannel" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="https://twitter.com/yourchannel" target="_blank"><i class="fab fa-twitter"></i></a>
            <a href="https://discord.gg/yourchannel" target="_blank"><i class="fab fa-discord"></i></a>
        </div>
        <p>&copy; 2024 YourChannel. All rights reserved. | Made with ❤️ for YouTube creators</p>
    </footer>

    <script>
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Animate stats counter
        function animateCounters() {
            const counters = document.querySelectorAll('.stat-number');
            counters.forEach(counter => {
                const target = +counter.getAttribute('data-target');
                const increment = target / 100;
                let current = 0;
                
                const updateCounter = () => {
                    if (current < target) {
                        current += increment;
                        counter.textContent = Math.ceil(current).toLocaleString();
                        setTimeout(updateCounter, 20);
                    } else {
                        counter.textContent = target.toLocaleString();
                    }
                };
                updateCounter();
            });
        }

        // Trigger animation when stats section is visible
        const statsObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    animateCounters();
                    statsObserver.unobserve(entry.target);
                }
            });
        });

        statsObserver.observe(document.querySelector('.stats'));

        // Mobile menu toggle
        const hamburger = document.querySelector('.hamburger');
        const navLinks = document.querySelector('.nav-links');
        
        hamburger.addEventListener('click', () => {
            hamburger.classList.toggle('active');
            navLinks.classList.toggle('active');
        });
    </script>
</body>
</html>
