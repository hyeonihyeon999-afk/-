<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Neon Snake</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="game-container">
        <div class="header">
            <div class="score-board">
                <div class="score-item">SCORE: <span id="score">0</span></div>
                <div class="score-item">HIGH: <span id="high-score">0</span></div>
            </div>
        </div>

        <div class="canvas-wrapper">
            <canvas id="gameCanvas"></canvas>
            
            <div id="start-screen" class="overlay">
                <h1>NEON SNAKE</h1>
                <button id="start-button">START GAME</button>
                <p class="hint">Use Arrow Keys or WASD</p>
            </div>

            <div id="game-over-screen" class="overlay hidden">
                <h1>GAME OVER</h1>
                <p>Your Score: <span id="final-score">0</span></p>
                <button id="restart-button">RETRY</button>
            </div>
        </div>

        <div class="controls">
            <div class="control-row">
                <button class="ctrl-btn" id="ctrl-up">▲</button>
            </div>
            <div class="control-row">
                <button class="ctrl-btn" id="ctrl-left">◀</button>
                <button class="ctrl-btn" id="ctrl-down">▼</button>
                <button class="ctrl-btn" id="ctrl-right">▶</button>
            </div>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
