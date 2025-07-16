
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Solo Leveling Anime Promotion</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            min-height: 100vh;
            font-family: 'Segoe UI', Arial, sans-serif;
            background: radial-gradient(circle at 50% 30%, #7209b7 0%, #1a1a2e 100%);
            overflow-x: hidden;
        }
        .pulse-bg {
            position: fixed;
            top: 0; left: 0; width: 100vw; height: 100vh;
            z-index: 0;
            pointer-events: none;
        }
        .pulse {
            position: absolute;
            left: 50%; top: 40%;
            transform: translate(-50%, -50%);
            width: 600px; height: 600px;
            background: rgba(247,37,133,0.15);
            border-radius: 50%;
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: translate(-50%, -50%) scale(1); opacity: 0.7; }
            50% { transform: translate(-50%, -50%) scale(1.15); opacity: 0.4; }
            100% { transform: translate(-50%, -50%) scale(1); opacity: 0.7; }
        }
        .promo-container {
            position: relative;
            z-index: 1;
            background: rgba(34,34,59,0.95);
            border-radius: 18px;
            padding: 48px 32px;
            max-width: 480px;
            margin: 80px auto 0 auto;
            box-shadow: 0 8px 32px rgba(0,0,0,0.5);
            animation: fadeInUp 1.2s cubic-bezier(.42,0,.58,1);
        }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(60px);}
            to   { opacity: 1; transform: translateY(0);}
        }
        .anime-img {
            width: 100%;
            border-radius: 12px;
            margin-bottom: 28px;
            box-shadow: 0 4px 24px rgba(247,37,133,0.25);
            animation: posterPop 1.5s cubic-bezier(.42,0,.58,1);
        }
        @keyframes posterPop {
            0% { opacity: 0; transform: scale(0.8);}
            60% { opacity: 1; transform: scale(1.05);}
            100% { opacity: 1; transform: scale(1);}
        }
        .promo-title {
            font-size: 2.4em;
            margin-bottom: 14px;
            color: #f72585;
            letter-spacing: 2px;
            text-shadow: 0 2px 12px #7209b7;
            animation: fadeIn 2s;
        }
        .promo-desc {
            font-size: 1.18em;
            margin-bottom: 28px;
            color: #fff;
            animation: fadeIn 2.5s;
        }
        @keyframes fadeIn {
            from { opacity: 0;}
            to   { opacity: 1;}
        }
        .watch-btn {
            background: linear-gradient(90deg, #f72585 60%, #7209b7 100%);
            color: #fff;
            padding: 16px 40px;
            border: none;
            border-radius: 10px;
            font-size: 1.15em;
            cursor: pointer;
            text-decoration: none;
            box-shadow: 0 2px 16px rgba(247,37,133,0.3);
            transition: transform 0.4s, box-shadow 0.3s, background 0.5s;
            animation: glowBtn 2s infinite alternate;
        }
        @keyframes glowBtn {
            from { box-shadow: 0 2px 16px rgba(247,37,133,0.3);}
            to   { box-shadow: 0 2px 32px rgba(247,37,133,0.7);}
        }
        .watch-btn:hover {
            transform: scale(1.15);
            background: linear-gradient(90deg, #b5179e 60%, #3a0ca3 100%);
        }
        .powered {
            margin-top: 36px;
            font-size: 1em;
            color: #a0a0b2;
            letter-spacing: 1px;
            animation: fadeIn 6s;
        }
    </style>
</head>
<body>
    <div class="pulse-bg">
        <div class="pulse"></div>
    </div>
    <div class="promo-container">
        <img src="c:\Users\dell\OneDrive\Desktop\cool_wallpaper\images.jpg" alt="Solo Leveling Poster" class="anime-img">
        <div class="promo-title">Solo Leveling</div>
        <div class="promo-desc">
            Witness Sung Jinwoo's rise from the weakest hunter to the legendary Shadow Monarch! Dive into the world of Solo Leveling, packed with action, mystery, and epic battles with other monarchs and most storengest dragon monarch.
        </div>
        <a href="https://www.crunchyroll.com/solo-leveling" class="watch-btn" target="_blank">Watch Now</a>
    </div>
    <div class="powered">Powered by Nittin Sharkotu</div>
</body>
</html>
