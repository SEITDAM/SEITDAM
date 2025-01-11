- 👋 Hi, I’m @SEITDAM
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
SEITDAM/SEITDAM is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ойындар жүктеу платформасы</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 10px;
            background-color: #fff;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h1, h2 {
            text-align: center;
            color: #333;
        }
        .game-list {
            list-style: none;
            padding: 0;
        }
        .game-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        .game-item:last-child {
            border-bottom: none;
        }
        .game-item h3 {
            margin: 0;
            color: #333;
        }
        .game-item button {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 8px 12px;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .game-item button:hover {
            background-color: #0056b3;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            padding: 10px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ойындар жүктеу платформасы</h1>
    </header>
    <main>
        <h2>Қолжетімді ойындар</h2>
        <ul class="game-list">
            <!-- Әр ойынның элементі -->
            <li class="game-item">
                <h3>Жылан ойыны</h3>
                <button onclick="downloadGame('')">Жүктеу</button>
            </li>
            <li class="game-item">
                <h3>Теннис ойыны</h3>
                <button onclick="downloadGame('table-tennis-game.zip')">Жүктеу</button>
            </li>
            <li class="game-item">
                <h3>Flappy Bird</h3>
                <button onclick="downloadGame('flappy-bird.zip')">Жүктеу</button>
            </li>
            <li class="game-item">
                <h3>Тик-Так-Тое</h3>
                <button onclick="downloadGame('tic-tac-toe.zip')">Жүктеу</button>
            </li>
        </ul>
    </main>
    <footer>
        <p>&copy; 2025 Ойын платформасы. Барлық құқықтар қорғалған.</p>
    </footer>
    <script>
        function downloadGame(filename) {
            // Жүктеу сілтемесін жасау
            const link = document.createElement('a');
            link.href = filename;
            link.download = filename;
            link.click();
        }
    </script>
</body>
</html>
