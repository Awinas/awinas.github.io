<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kak Aznor Punya Birthday</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-image: url('https://media.giphy.com/media/3ohhwF34cGDoFFhRfy/giphy.gif');
            background-position: center;
            background-size: cover;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .card {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            max-width: 600px;
            text-align: center;
            animation: zoomIn 2s ease;
        }

        @keyframes zoomIn {
            from { transform: scale(0.8); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }

        h1 {
            color: #ff6b6b;
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        p {
            font-size: 1.2em;
            color: #333;
            margin: 15px 0;
        }

        .emoji {
            font-size: 1.5em;
        }

        .cake {
            margin-top: 20px;
        }

        .footer {
            margin-top: 20px;
            color: #888;
            font-size: 0.9em;
        }

        /* Music Icon */
        .music-icon {
            width: 50px;
            height: 50px;
            margin-top: 10px;
        }

    </style>
</head>
<body>
    <!-- Background Music -->
    <audio autoplay loop>
        <source src="https://www.bensound.com/bensound-music/bensound-happyrock.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <!-- Card with Message -->
    <div class="card">
        <h1>🎉 Selamat Hari Lahir, Kak Aznor! 🎉</h1>
        <p>Kepada pensyarah, guru, dan kakak tersayang yang sentiasa membantu saya, <strong>selamat menjalani hari tua anda! Hahaha 😄</strong></p>
        <p class="emoji">Terima kasih banyak kerana selalu berada di sisi saya, terutamanya dalam saat-saat yang sukar. Tanpa bantuan dan bimbingan kakak, saya tak tahu ke mana saya akan pergi.</p>
        <p class="emoji">Saya sangat bersyukur ada kakak dalam hidup saya.</p>
        <p class="cake">🍰 Jom nanti kita makan kek lagi! 🍰</p>
        <p class="footer">Terima kasih sekali lagi, Kak Aznor. Semoga kakak terus diberkati dan bahagia selalu! ✨</p>
        <p class="footer">Daripada: <strong>Fakhrul yang hensem dan macho</strong> 😎</p>
    </div>
</body>
</html>
