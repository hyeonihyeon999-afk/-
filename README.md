SCORE: 0
HIGH: 0
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

<script async src="https://www.googletagmanager.com/gtag/js?id=G-46HKQC2GFC"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-46HKQC2GFC');
</script>
