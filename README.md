<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KUBRAJUEX - Game Hub</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; text-align: center; background: #121212; color: white; padding: 20px; }
        .container { max-width: 600px; margin: auto; }
        .game-card { background: #1e1e1e; margin: 15px; padding: 20px; border-radius: 15px; border: 1px solid #333; transition: 0.3s; }
        .game-card:hover { border-color: #00ff88; transform: translateY(-5px); }
        a { color: #00ff88; text-decoration: none; font-weight: bold; font-size: 22px; display: block; }
        .emoji { font-size: 50px; margin-bottom: 10px; }
        h1 { color: #00ff88; text-shadow: 2px 2px 10px rgba(0,255,136,0.3); }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎮 KUBRAJUEX HUB</h1>
        <p>Choose a game to play instantly!</p>

        <div class="game-card">
            <div class="emoji">🐍</div>
            <a href="snake.html">Snake Game</a>
        </div>

        <div class="game-card">
            <div class="emoji">❌⭕</div>
            <a href="tictactoe.html">Tic Tac Toe</a>
        </div>

        <div class="game-card">
            <div class="emoji">🧠</div>
            <a href="memory.html">Memory Game</a>
        </div>

        <p style="margin-top: 50px; color: #666;">Created by Sheikh Abdulla</p>
    </div>
</body>
</html>
