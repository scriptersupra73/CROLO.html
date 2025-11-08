<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CROLO MM - Middleman Services</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            cursor: none !important;
        }

        body {
            font-family: 'Arial', sans-serif;
            overflow-x: hidden;
            background: #000;
            color: #fff;
        }

        /* Custom Cursor */
        #custom-cursor {
            position: fixed;
            width: 30px;
            height: 30px;
            border: 2px solid #00ffff;
            border-radius: 50%;
            pointer-events: none;
            z-index: 10000;
            transition: all 0.1s ease;
            mix-blend-mode: difference;
        }

        #cursor-trail {
            position: fixed;
            width: 10px;
            height: 10px;
            background: #ff00ff;
            border-radius: 50%;
            pointer-events: none;
            z-index: 9999;
            opacity: 0.6;
        }

        /* Video Background */
        #bg-video {
            position: fixed;
            top: 50%;
            left: 50%;
            min-width: 100%;
            min-height: 100%;
            width: auto;
            height: auto;
            transform: translate(-50%, -50%);
            z-index: -1;
            filter: brightness(0.3) blur(2px);
        }

        /* Parallax Container */
        .parallax-container {
            position: relative;
            height: 100vh;
            overflow: hidden;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: relative;
            perspective: 1000px;
        }

        .hero h1 {
            font-size: 8rem;
            font-weight: 900;
            background: linear-gradient(45deg, #00ffff, #ff00ff, #ffff00, #00ff00);
            background-size: 300% 300%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: gradient 3s ease infinite, float 3s ease-in-out infinite;
            text-shadow: 0 0 50px rgba(0, 255, 255, 0.5);
            transform-style: preserve-3d;
        }

        .hero p {
            font-size: 2rem;
            margin-top: 20px;
            opacity: 0;
            animation: fadeInUp 1s ease 0.5s forwards;
            text-transform: uppercase;
            letter-spacing: 5px;
        }

        @keyframes gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotateX(0deg); }
            50% { transform: translateY(-20px) rotateX(5deg); }
        }

        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
            from {
                opacity: 0;
                transform: translateY(30px);
            }
        }

        /* Particle System */
        .particle {
            position: fixed;
            width: 3px;
            height: 3px;
            background: #00ffff;
            pointer-events: none;
            z-index: 1;
            border-radius: 50%;
            opacity: 0.8;
        }

        /* Discord Button */
        .discord-btn {
            position: fixed;
            bottom: 40px;
            right: 40px;
            padding: 20px 40px;
            background: linear-gradient(45deg, #5865F2, #7289da);
            border: none;
            border-radius: 50px;
            font-size: 1.2rem;
            font-weight: bold;
            color: #fff;
            z-index: 1000;
            transition: all 0.3s ease;
            box-shadow: 0 10px 40px rgba(88, 101, 242, 0.5);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .discord-btn:hover {
            transform: scale(1.1) translateY(-5px);
            box-shadow: 0 15px 60px rgba(88, 101, 242, 0.8);
        }

        /* Glitch Effect */
        .glitch {
            position: relative;
            animation: glitch 1s infinite;
        }

        @keyframes glitch {
            0% { transform: translate(0); }
            20% { transform: translate(-2px, 2px); }
            40% { transform: translate(-2px, -2px); }
            60% { transform: translate(2px, 2px); }
            80% { transform: translate(2px, -2px); }
            100% { transform: translate(0); }
        }

        /* Features Section */
        .features {
            padding: 100px 50px;
            position: relative;
            z-index: 10;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }

        .feature-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
            transform-style: preserve-3d;
        }

        .feature-card:hover {
            transform: translateY(-10px) rotateX(5deg);
            background: rgba(255, 255, 255, 0.1);
            box-shadow: 0 20px 60px rgba(0, 255, 255, 0.3);
        }

        .feature-card h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: #00ffff;
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .feature-card img {
            width: 48px;
            height: 48px;
            filter: drop-shadow(0 0 10px rgba(0, 255, 255, 0.5));
        }

        /* Matrix Rain Effect */
        #matrix-canvas {
            position: fixed;
            top: 0;
            left: 0;
            z-index: 0;
            opacity: 0.1;
        }

        /* Scroll Indicator */
        .scroll-indicator {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateX(-50%) translateY(0); }
            40% { transform: translateX(-50%) translateY(-20px); }
            60% { transform: translateX(-50%) translateY(-10px); }
        }

        /* Hidden Secret */
        .secret-message {
            position: fixed;
            top: 10px;
            left: 10px;
            opacity: 0;
            font-size: 0.8rem;
            color: #00ffff;
            z-index: 10001;
            transition: opacity 0.3s;
        }

        /* Ripple Effect */
        .ripple {
            position: fixed;
            border-radius: 50%;
            background: rgba(0, 255, 255, 0.3);
            pointer-events: none;
            animation: ripple-animation 1s ease-out;
            z-index: 9998;
        }

        @keyframes ripple-animation {
            to {
                transform: scale(4);
                opacity: 0;
            }
        }

        /* Hologram Effect */
        .hologram {
            position: relative;
            animation: hologram-scan 2s infinite;
        }

        @keyframes hologram-scan {
            0%, 100% { filter: hue-rotate(0deg); }
            50% { filter: hue-rotate(180deg); }
        }

        /* Tilt Effect Container */
        .tilt-container {
            transform-style: preserve-3d;
            transition: transform 0.1s;
        }

        /* Neon Glow */
        .neon-glow {
            text-shadow: 0 0 10px #00ffff, 0 0 20px #00ffff, 0 0 30px #00ffff;
            animation: neon-pulse 1.5s infinite;
        }

        @keyframes neon-pulse {
            0%, 100% { text-shadow: 0 0 10px #00ffff, 0 0 20px #00ffff, 0 0 30px #00ffff; }
            50% { text-shadow: 0 0 20px #00ffff, 0 0 40px #00ffff, 0 0 60px #00ffff; }
        }

        /* Scan Line Effect */
        .scanline {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to bottom, transparent 50%, rgba(0, 255, 255, 0.1) 50%);
            background-size: 100% 4px;
            z-index: 9997;
            pointer-events: none;
            animation: scanline-move 8s linear infinite;
        }

        @keyframes scanline-move {
            0% { transform: translateY(0); }
            100% { transform: translateY(4px); }
        }

        /* Color Shift */
        .color-shift {
            animation: color-shift 5s infinite;
        }

        @keyframes color-shift {
            0% { filter: hue-rotate(0deg); }
            100% { filter: hue-rotate(360deg); }
        }

        /* Shake on Click */
        .shake {
            animation: shake 0.5s;
        }

        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            10%, 30%, 50%, 70%, 90% { transform: translateX(-10px); }
            20%, 40%, 60%, 80% { transform: translateX(10px); }
        }

        /* Konami Code Easter Egg */
        .konami-active {
            animation: rainbow-bg 2s infinite;
        }

        @keyframes rainbow-bg {
            0% { background: #ff0000; }
            16% { background: #ff7f00; }
            33% { background: #ffff00; }
            50% { background: #00ff00; }
            66% { background: #0000ff; }
            83% { background: #8b00ff; }
            100% { background: #ff0000; }
        }

        /* Double Click Easter Egg */
        .explode {
            animation: explode 1s ease-out;
        }

        @keyframes explode {
            0% { transform: scale(1); opacity: 1; }
            100% { transform: scale(10); opacity: 0; }
        }
    </style>
</head>
<body>
    <!-- Background Video -->
    <video id="bg-video" autoplay loop muted playsinline>
        <source src="https://files.catbox.moe/7sa7o6.mp4" type="video/mp4">
    </video>

    <!-- Matrix Canvas -->
    <canvas id="matrix-canvas"></canvas>

    <!-- Scanline Effect -->
    <div class="scanline"></div>

    <!-- Custom Cursor -->
    <div id="custom-cursor"></div>
    <div id="cursor-trail"></div>

    <!-- Secret Message -->
    <div class="secret-message" id="secret-msg">You found the secret! Press CTRL+SHIFT+K for more...</div>

    <!-- Hero Section -->
    <div class="parallax-container">
        <div class="hero" id="hero">
            <h1 class="glitch hologram neon-glow" id="main-title">CROLO MM</h1>
            <p class="color-shift">#1 MIDDLEMAN FOR ALL TYPES OF SELLERS</p>
            <div class="scroll-indicator">
                <svg width="30" height="50" viewBox="0 0 30 50">
                    <rect x="5" y="5" width="20" height="40" rx="10" fill="none" stroke="#00ffff" stroke-width="2"/>
                    <circle cx="15" cy="15" r="3" fill="#00ffff">
                        <animate attributeName="cy" from="15" to="35" dur="1.5s" repeatCount="indefinite"/>
                    </circle>
                </svg>
            </div>
        </div>
    </div>

    <!-- Features Section -->
    <div class="features">
        <h2 style="text-align: center; font-size: 3rem; margin-bottom: 50px;" class="neon-glow">OUR FEATURES</h2>
        <div class="feature-grid">
            <div class="feature-card tilt-container">
                <h3><img src="https://cdn3.emoji.gg/emojis/1962-secure-connection.png" alt="Secure"> Secure Transactions</h3>
                <p>Security for all your trades.</p>
            </div>
            <div class="feature-card tilt-container">
                <h3><img src="https://cdn3.emoji.gg/emojis/65023-lightning.gif" alt="Lightning"> Lightning Fast</h3>
                <p>Instant verification</p>
            </div>
            <div class="feature-card tilt-container">
                <h3><img src="https://cdn3.emoji.gg/emojis/18024-market.png" alt="Market"> All Markets</h3>
                <p>Limiteds to crypto easily with CROLO</p>
            </div>
            <div class="feature-card tilt-container">
                <h3><img src="https://cdn3.emoji.gg/emojis/819847-diamond.png" alt="Diamond"> Premium Support</h3>
                <p>24/7 assistance</p>
            </div>
            <div class="feature-card tilt-container">
                <h3><img src="https://cdn3.emoji.gg/emojis/828044-shield.png" alt="Shield"> Buyer Protection</h3>
                <p>Full refund guarantee if anything goes wrong.</p>
            </div>
            <div class="feature-card tilt-container">
                <h3><img src="https://cdn3.emoji.gg/emojis/574809-rocket.png" alt="Rocket"> Instant Transactions</h3>
                <p>Get your money immediately after transaction completion.</p>
            </div>
        </div>
    </div>

    <!-- Discord Button -->
    <a href="https://discord.gg/MWtwZTD4fh" class="discord-btn" id="discord-link" target="_blank">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
            <path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515a.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0a12.64 12.64 0 0 0-.617-1.25a.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057a.082.082 0 0 0 .031.057a19.9 19.9 0 0 0 5.993 3.03a.078.078 0 0 0 .084-.028a14.09 14.09 0 0 0 1.226-1.994a.076.076 0 0 0-.041-.106a13.107 13.107 0 0 1-1.872-.892a.077.077 0 0 1-.008-.128a10.2 10.2 0 0 0 .372-.292a.074.074 0 0 1 .077-.01c3.928 1.793 8.18 1.793 12.062 0a.074.074 0 0 1 .078.01c.12.098.246.198.373.292a.077.077 0 0 1-.006.127a12.299 12.299 0 0 1-1.873.892a.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028a19.839 19.839 0 0 0 6.002-3.03a.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03zM8.02 15.33c-1.183 0-2.157-1.085-2.157-2.419c0-1.333.956-2.419 2.157-2.419c1.21 0 2.176 1.096 2.157 2.42c0 1.333-.956 2.418-2.157 2.418zm7.975 0c-1.183 0-2.157-1.085-2.157-2.419c0-1.333.955-2.419 2.157-2.419c1.21 0 2.176 1.096 2.157 2.42c0 1.333-.946 2.418-2.157 2.418z"/>
        </svg>
        JOIN DISCORD
    </a>

    <script>
        // Custom Cursor
        const cursor = document.getElementById('custom-cursor');
        const cursorTrail = document.getElementById('cursor-trail');
        let mouseX = 0, mouseY = 0;
        let trailX = 0, trailY = 0;

        document.addEventListener('mousemove', (e) => {
            mouseX = e.clientX;
            mouseY = e.clientY;
        });

        function animateCursor() {
            cursor.style.left = mouseX + 'px';
            cursor.style.top = mouseY + 'px';
            
            trailX += (mouseX - trailX) * 0.1;
            trailY += (mouseY - trailY) * 0.1;
            cursorTrail.style.left = trailX + 'px';
            cursorTrail.style.top = trailY + 'px';
            
            requestAnimationFrame(animateCursor);
        }
        animateCursor();

        // Cursor size change on click
        document.addEventListener('mousedown', () => {
            cursor.style.transform = 'scale(0.8)';
        });
        document.addEventListener('mouseup', () => {
            cursor.style.transform = 'scale(1)';
        });

        // Particle System
        function createParticle(x, y) {
            const particle = document.createElement('div');
            particle.className = 'particle';
            particle.style.left = x + 'px';
            particle.style.top = y + 'px';
            document.body.appendChild(particle);
            
            const angle = Math.random() * Math.PI * 2;
            const velocity = Math.random() * 5 + 2;
            let life = 100;
            
            function animate() {
                life--;
                particle.style.left = parseFloat(particle.style.left) + Math.cos(angle) * velocity + 'px';
                particle.style.top = parseFloat(particle.style.top) + Math.sin(angle) * velocity + 'px';
                particle.style.opacity = life / 100;
                
                if (life > 0) requestAnimationFrame(animate);
                else particle.remove();
            }
            animate();
        }

        document.addEventListener('click', (e) => {
            for (let i = 0; i < 20; i++) {
                createParticle(e.clientX, e.clientY);
            }
        });

        // Parallax Effect
        document.addEventListener('mousemove', (e) => {
            const hero = document.querySelector('.hero h1');
            const xAxis = (window.innerWidth / 2 - e.clientX) / 25;
            const yAxis = (window.innerHeight / 2 - e.clientY) / 25;
            hero.style.transform = `translateY(-20px) rotateY(${xAxis}deg) rotateX(${yAxis}deg)`;
        });

        // Matrix Rain Effect
        const canvas = document.getElementById('matrix-canvas');
        const ctx = canvas.getContext('2d');
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;

        const matrix = 'CROLOABCDEFGHIJKLMNOPQRSTUVWXYZ123456789@#$%^&*()';
        const fontSize = 16;
        const columns = canvas.width / fontSize;
        const drops = Array(Math.floor(columns)).fill(1);

        function drawMatrix() {
            ctx.fillStyle = 'rgba(0, 0, 0, 0.04)';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            ctx.fillStyle = '#00ffff';
            ctx.font = fontSize + 'px monospace';

            for (let i = 0; i < drops.length; i++) {
                const text = matrix[Math.floor(Math.random() * matrix.length)];
                ctx.fillText(text, i * fontSize, drops[i] * fontSize);
                
                if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
                    drops[i] = 0;
                }
                drops[i]++;
            }
        }
        setInterval(drawMatrix, 35);

        // Ripple Effect on Click
        document.addEventListener('click', (e) => {
            const ripple = document.createElement('div');
            ripple.className = 'ripple';
            ripple.style.left = e.clientX - 25 + 'px';
            ripple.style.top = e.clientY - 25 + 'px';
            ripple.style.width = '50px';
            ripple.style.height = '50px';
            document.body.appendChild(ripple);
            setTimeout(() => ripple.remove(), 1000);
        });

        // Tilt Effect on Cards
        document.querySelectorAll('.tilt-container').forEach(card => {
            card.addEventListener('mousemove', (e) => {
                const rect = card.getBoundingClientRect();
                const x = e.clientX - rect.left;
                const y = e.clientY - rect.top;
                const centerX = rect.width / 2;
                const centerY = rect.height / 2;
                const rotateX = (y - centerY) / 10;
                const rotateY = (centerX - x) / 10;
                card.style.transform = `perspective(1000px) rotateX(${rotateX}deg) rotateY(${rotateY}deg) translateY(-10px)`;
            });
            card.addEventListener('mouseleave', () => {
                card.style.transform = 'perspective(1000px) rotateX(0) rotateY(0)';
            });
        });

        // Secret Message on Hover Corner
        let cornerTimer;
        document.addEventListener('mousemove', (e) => {
            if (e.clientX < 50 && e.clientY < 50) {
                clearTimeout(cornerTimer);
                document.getElementById('secret-msg').style.opacity = '1';
            } else {
                cornerTimer = setTimeout(() => {
                    document.getElementById('secret-msg').style.opacity = '0';
                }, 500);
            }
        });

        // Konami Code Easter Egg (↑↑↓↓←→←→BA)
        let konamiCode = [];
        const konamiSequence = ['ArrowUp', 'ArrowUp', 'ArrowDown', 'ArrowDown', 'ArrowLeft', 'ArrowRight', 'ArrowLeft', 'ArrowRight', 'b', 'a'];
        document.addEventListener('keydown', (e) => {
            konamiCode.push(e.key);
            konamiCode = konamiCode.slice(-10);
            if (konamiCode.join(',') === konamiSequence.join(',')) {
                document.body.classList.add('konami-active');
                alert('🎮 KONAMI CODE ACTIVATED! You are a true gamer!');
                setTimeout(() => document.body.classList.remove('konami-active'), 5000);
            }
        });

        // CTRL+SHIFT+K Easter Egg
        document.addEventListener('keydown', (e) => {
            if (e.ctrlKey && e.shiftKey && e.key === 'K') {
                e.preventDefault();
                alert('🔥 ULTRA SECRET UNLOCKED! You found the developer mode!');
                document.querySelectorAll('.feature-card').forEach(card => {
                    card.style.background = 'linear-gradient(45deg, #ff00ff, #00ffff)';
                });
            }
        });

        // Double Click Title for Explosion
        let clickCount = 0;
        document.getElementById('main-title').addEventListener('click', () => {
            clickCount++;
            if (clickCount === 2) {
                document.getElementById('main-title').classList.add('explode');
                setTimeout(() => {
                    document.getElementById('main-title').classList.remove('explode');
                    clickCount = 0;
                }, 1000);
            }
            setTimeout(() => clickCount = 0, 500);
        });

        // Shake on Discord Button Hover
        const discordBtn = document.getElementById('discord-link');
        discordBtn.addEventListener('mouseenter', () => {
            discordBtn.classList.add('shake');
            setTimeout(() => discordBtn.classList.remove('shake'), 500);
        });

        // Random color cursor trail
        setInterval(() => {
            const colors = ['#ff00ff', '#00ffff', '#ffff00', '#00ff00', '#ff0000'];
            cursorTrail.style.background = colors[Math.floor(Math.random() * colors.length)];
        }, 200);

        // Auto-scroll animation
        let scrollPos = 0;
        window.addEventListener('scroll', () => {
            scrollPos = window.scrollY;
            document.querySelector('.hero').style.transform = `translateY(${scrollPos * 0.5}px)`;
        });

        // Type writer effect on description
        const desc = document.querySelector('.hero p');
        const originalText = desc.textContent;
        desc.textContent = '';
        let i = 0;
        function typeWriter() {
            if (i < originalText.length) {
                desc.textContent += originalText.charAt(i);
                i++;
                setTimeout(typeWriter, 100);
            }
        }
        setTimeout(typeWriter, 1000);

        // Random glitch effect
        setInterval(() => {
            const title = document.getElementById('main-title');
            title.style.transform = `translate(${Math.random() * 4 - 2}px, ${Math.random() * 4 - 2}px)`;
            setTimeout(() => title.style.transform = '', 50);
        }, 3000);

        // Hover glow on features
        document.querySelectorAll('.feature-card').forEach(card => {
            card.addEventListener('mouseenter', () => {
                card.style.boxShadow = `0 0 50px ${['#00ffff', '#ff00ff', '#ffff00'][Math.floor(Math.random() * 3)]}`;
            });
        });

        // Window resize handler
        window.addEventListener('resize', () => {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        });

        // Easter egg: Type "crolo" anywhere
        let typedWord = '';
        document.addEventListener('keypress', (e) => {
            typedWord += e.key;
            typedWord = typedWord.slice(-5);
            if (typedWord === 'crolo') {
                alert('🎉 SECRET WORD FOUND! Welcome to the inner circle!');
                document.body.style.animation = 'rainbow-bg 2s infinite';
            }
        });
    </script>
</body>
</html>
