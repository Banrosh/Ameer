<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تهنئة خاصة من Baron</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #0a0a0a; /* أسود أعمق */
            color: #fff;
            font-family: 'Segoe UI', Tahoma, sans-serif;
            overflow: hidden;
            position: relative;
        }

        /* تأثير النجوم المتساقطة */
        .star {
            position: absolute;
            background: #f1c40f;
            border-radius: 50%;
            opacity: 0.5;
            animation: fall linear infinite;
        }

        @keyframes fall {
            to { transform: translateY(100vh); }
        }

        .container {
            text-align: center;
            padding: 40px;
            border-radius: 20px;
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(15px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 0 30px rgba(243, 156, 18, 0.2);
            z-index: 10;
        }

        h1 {
            font-size: 3.5rem;
            background: linear-gradient(45deg, #f39c12, #d35400);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin: 0;
        }

        p {
            font-size: 1.4rem;
            color: #bdc3c7;
            margin-top: 15px;
        }

        .footer {
            margin-top: 30px;
            font-weight: bold;
            letter-spacing: 3px;
            color: #f39c12;
            text-shadow: 0 0 10px #f39c12;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>كـل عـام وأنـت بـخـيـر ✨</h1>
        <p>أتمنى لك سنة مليئة بالنجاح والرزق</p>
        <div class="footer">S A I N T</div>
    </div>

    <script>
        // كود بسيط لصنع نجوم متساقطة تلقائياً
        function createStar() {
            const star = document.createElement('div');
            star.classList.add('star');
            star.style.left = Math.random() * 100 + 'vw';
            star.style.width = Math.random() * 3 + 'px';
            star.style.height = star.style.width;
            star.style.animationDuration = Math.random() * 2 + 3 + 's';
            document.body.appendChild(star);
            setTimeout(() => star.remove(), 5000);
        }
        setInterval(createStar, 100);
    </script>

</body>
</html>
# Ameer
.
