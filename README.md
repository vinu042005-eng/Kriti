<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Happy Teddy Day Kriti 🧸</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(to bottom right, #ff9a9e, #fad0c4);
            color: #4b1e1e;
            text-align: center;
        }

        .container {
            padding: 50px 20px;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        h2 {
            font-weight: normal;
            margin-bottom: 30px;
        }

        .teddy {
            font-size: 120px;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-20px); }
            60% { transform: translateY(-10px); }
        }

        .message {
            max-width: 600px;
            margin: auto;
            font-size: 1.2em;
            background: rgba(255, 255, 255, 0.6);
            padding: 25px;
            border-radius: 20px;
        }

        .heart {
            color: red;
            font-size: 30px;
        }

        footer {
            margin-top: 40px;
            font-size: 0.9em;
            opacity: 0.8;
        }

        button {
            margin-top: 25px;
            padding: 12px 25px;
            border: none;
            border-radius: 30px;
            background: #ff4d6d;
            color: white;
            font-size: 1em;
            cursor: pointer;
            transition: transform 0.2s, background 0.2s;
        }

        button:hover {
            background: #e63950;
            transform: scale(1.05);
        }
    </style>
</head>
<body>

<div class="container">
    <div class="teddy">🧸</div>

    <h1>Happy Teddy Day, Kriti!</h1>
    <h2>You’re cuter than any teddy in the world</h2>

    <div class="message">
        <p>
            Dear <strong>Kriti</strong>,<br><br>
            On this Teddy Day, I just want you to know that  
            if I were a teddy, I’d never leave your arms.  
            I’d listen to all your stories, keep your secrets,  
            and hug you whenever you need comfort.  
        </p>

        <p>
            You make my world warmer, happier,  
            and full of smiles every single day.  
        </p>

        <p class="heart">❤️ ❤️ ❤️</p>
    </div>

    <button onclick="alert('I love Kriti 🧸❤️')">
        Click for a Surprise
    </button>

    <footer>
        Made specially for Kriti 💕
    </footer>
</div>

</body>
</html>
