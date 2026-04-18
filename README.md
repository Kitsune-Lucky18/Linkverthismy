<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roblox Script Hub | Official Website</title>
    <style>
        /* CSS VARIABLES - Untuk memudahkan ganti warna dasar */
        :root {
            --primary-color: #ff4757;
            --secondary-color: #00d2ff;
            --overlay-dark: rgba(0, 0, 0, 0.85); /* Kegelapan background */
            --card-bg: rgba(26, 29, 43, 0.9);
            --text-main: #ffffff;
            --text-dim: #a4b0be;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: var(--text-main);
            min-height: 100vh;
            line-height: 1.6;
            
            /* PENGATURAN BACKGROUND GAMBAR */
            /* Ganti 'background.jpg' dengan nama file gambar kamu */
            background: url('background.jpg') no-repeat center center fixed;
            background-size: cover;
        }

        /* Overlay agar teks tetap terbaca meskipun background gambar terang */
        .bg-overlay {
            background-color: var(--overlay-dark);
            min-height: 100vh;
            width: 100%;
            padding-bottom: 50px;
        }

        header {
            background: linear-gradient(to bottom, rgba(255, 71, 87, 0.9), transparent);
            padding: 60px 20px;
            text-align: center;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 20px;
        }

        /* YouTube Call to Action */
        .yt-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 2px solid var(--primary-color);
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            margin-top: -40px;
            margin-bottom: 40px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        .btn-yt {
            display: inline-block;
            background: var(--primary-color);
            color: white;
            padding: 15px 35px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.1rem;
            margin-top: 15px;
            transition: 0.3s;
            text-transform: uppercase;
        }

        .btn-yt:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px rgba(255, 71, 87, 0.6);
        }

        /* Scripts Grid */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 25px;
        }

        .card {
            background: var(--card-bg);
            border-radius: 15px;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: 0.3s;
        }

        .card:hover {
            border-color: var(--secondary-color);
            transform: translateY(-5px);
        }

        .card-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-bottom: 3px solid var(--secondary-color);
        }

        .card-body {
            padding: 20px;
        }

        .card-title {
            color: var(--secondary-color);
            margin-bottom: 10px;
            font-size: 1.4rem;
        }

        .card-desc {
            color: var(--text-dim);
            font-size: 0.95rem;
            margin-bottom: 20px;
            height: 50px;
        }

        .btn-get {
            display: block;
            text-align: center;
            background: transparent;
            color: var(--secondary-color);
            border: 2px solid var(--secondary-color);
            padding: 10px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn-get:hover {
            background: var(--secondary-color);
            color: #000;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            color: var(--text-dim);
            font-size: 0.8rem;
        }

        /* Responsif untuk HP */
        @media (max-width: 600px) {
            header h1 { font-size: 1.8rem; }
            .yt-card { padding: 20px; }
        }
    </style>
</head>
<body>

    <div class="bg-overlay">
        <header>
            <h1>🚀 MY ROBLOX SCRIPTS</h1>
            <p>Gratis, Aman, dan Selalu Update</p>
        </header>

        <div class="container">
            <!-- SEKSI YOUTUBE -->
            <div class="yt-card">
                <h2>Wajib Subscribe!</h2>
                <p>Klik tombol di bawah dan subscribe untuk mendapatkan info script terbaru setiap hari.</p>
                <!-- GANTI LINK YOUTUBE DI BAWAH INI -->
                <a href="https://youtube.com/@ChannelKamu" target="_blank" class="btn-yt">Buka YouTube Saya</a>
            </div>

            <h2 style="margin-bottom: 25px; border-left: 5px solid var(--secondary-color); padding-left: 15px;">Daftar Script</h2>

            <div class="grid">
                
                <!-- START SCRIPT CARD 1 -->
                <div class="card">
                    <!-- GANTI LINK GAMBAR DI SINI -->
                    <img src="https://via.placeholder.com/400x200" alt="Blox Fruits" class="card-img">
                    <div class="card-body">
                        <h3 class="card-title">Blox Fruits Hub</h3>
                        <p class="card-desc">Auto Farm, Auto Raid, Fruit Finder, dan banyak lagi.</p>
                        <!-- GANTI LINK LINKVERTISE DI SINI -->
                        <a href="https://linkvertise.com/xxxx/yourlink" target="_blank" class="btn-get">GET SCRIPT (ADS)</a>
                    </div>
                </div>
                <!-- END SCRIPT CARD 1 -->

                <!-- START SCRIPT CARD 2 -->
                <div class="card">
                    <img src="https://via.placeholder.com/400x200" alt="Pet Simulator" class="card-img">
                    <div class="card-body">
                        <h3 class="card-title">Pet Simulator 99</h3>
                        <p class="card-desc">Auto Hatch, Farm Diamonds, dan Anti-AFK.</p>
                        <a href="https://linkvertise.com/xxxx/yourlink" target="_blank" class="btn-get">GET SCRIPT (ADS)</a>
                    </div>
                </div>
                <!-- END SCRIPT CARD 2 -->

            </div>

            <footer>
                <p>&copy; 2024 Roblox Script Hub By [Nama Kamu]. All Rights Reserved.</p>
            </footer>
        </div>
    </div>

</body>
</html>
