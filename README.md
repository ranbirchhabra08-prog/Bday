<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Happy Birthday Diksha!</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent:#ff7aa2;
      --gold:#f6c85f;
      --text:#f8fafc;
    }

    html,body{
      height:100%;
      margin:0;
      font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: radial-gradient(1200px 600px at 10% 10%, #182233 0%, transparent 15%),
                  radial-gradient(900px 500px at 90% 90%, #1a2433 0%, transparent 15%),
                  var(--bg);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      overflow:hidden;
    }

    .wrap {
      width:100%;
      height:100%;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:30px;
      box-sizing:border-box;
    }

    .card{
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.00));
      border-radius:18px;
      padding:28px;
      max-width:820px;
      width:100%;
      box-shadow: 0 10px 40px rgba(2,6,23,0.7), inset 0 1px 0 rgba(255,255,255,0.02);
      text-align:center;
      position:relative;
      overflow:visible;
    }

    h1{
      margin:8px 0 4px 0;
      font-size:48px;
      letter-spacing:0.6px;
      color:var(--accent);
      text-shadow: 0 2px 12px rgba(255,122,162,0.12);
    }

    p.subtitle{
      margin:0 0 20px 0;
      color: #cfe6ff;
      opacity:0.9;
      font-size:16px;
    }

    .cake-wrap{
      display:flex;
      align-items:center;
      justify-content:center;
      margin: 10px 0 6px 0;
    }

    /* SVG cake sizing */
    svg.cake {
      width:320px;
      height:auto;
      display:block;
      filter: drop-shadow(0 12px 28px rgba(2,6,23,0.6));
    }

    /* Underlined funny line */
    .fun-line{
      margin-top:14px;
      font-size:20px;
      color:#fff;
      display:inline-block;
      padding:6px 12px;
      border-radius:8px;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.00));
      border:1px solid rgba(255,255,255,0.03);
    }

    .fun-line u{
      text-decoration-thickness:4px;
      text-decoration-color:var(--gold);
      color: #fff;
      font-weight:600;
    }

    /* Button */
    .btns{
      margin-top:18px;
      display:flex;
      gap:12px;
      justify-content:center;
      flex-wrap:wrap;
    }
    button{
      background:linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.01));
      border:1px solid rgba(255,255,255,0.06);
      color:var(--text);
      padding:10px 14px;
      border-radius:10px;
      cursor:pointer;
      font-weight:600;
      letter-spacing:0.3px;
      transition:transform .14s ease, box-shadow .14s ease, opacity .12s;
    }
    button:active{ transform:translateY(1px) }
    button:focus{ outline:none; box-shadow:0 6px 18px rgba(0,0,0,0.5) }

    /* confetti canvas sits behind card */
    canvas#confetti {
      position:fixed;
      left:0;
      top:0;
      width:100%;
      height:100%;
      pointer-events:none;
      z-index:5;
    }

    /* small footer credit */
    .credit{
      margin-top:14px;
      font-size:12px;
      color:#9fb7d6;
      opacity:0.85;
    }

    /* candle flicker */
    .flame {
      transform-origin: center bottom;
      animation: flicker 320ms infinite;
      filter: drop-shadow(0 4px 10px rgba(255,180,70,0.25));
    }
    @keyframes flicker {
      0% { transform: scaleY(1) translateY(0); opacity:1 }
      50% { transform: scaleY(0.94) translateY(-2px); opacity:0.9 }
      100% { transform: scaleY(1) translateY(0); opacity:1 }
    }

    /* small responsive tweaks */
    @media (max-width:520px){
      h1{ font-size:34px }
      svg.cake{ width:240px }
      .fun-line{ font-size:18px }
    }
  </style>
</head>
<body>
  <canvas id="confetti"></canvas>
  <div class="wrap">
    <div class="card" role="main" aria-label="Birthday card for Diksha">
      <h1>🎉 Happy Birthday, Diksha! 🎉</h1>
      <p class="subtitle">Wishing you a day full of laughter, sweets and unforgettable moments.</p>

      <div class="cake-wrap" aria-hidden="false">
        <!-- SVG cake with three candles -->
        <svg class="cake" viewBox="0 0 640 480" xmlns="http://www.w3.org/2000/svg" aria-label="Birthday cake">
          <!-- plate -->
          <ellipse cx="320" cy="420" rx="220" ry="26" fill="#0b1220" opacity="0.6"/>
          <ellipse cx="320" cy="424" rx="220" ry="18" fill="#ffffff" opacity="0.03"/>

          <!-- bottom layer -->
          <rect x="120" y="240" rx="28" ry="28" width="400" height="140" fill="#ffb3c6"/>
          <!-- icing drips -->
          <path d="M120 250 q30 20 60 0 q40 -28 80 10 q40 -48 120 0 q40 -20 60 0 v40 h-420z" fill="#fff1f6" opacity="0.95"/>

          <!-- middle layer -->
          <rect x="160" y="190" rx="20" ry="20" width="320" height="70" fill="#ff7aa2"/>
          <rect x="200" y="160" rx="16" ry="16" width="240" height="50" fill="#ffd5e6"/>

          <!-- sprinkles -->
          <g>
            <rect x="210" y="200" width="6" height="18" rx="3" fill="#ffd27a" transform="rotate(15 213 209)"/>
            <rect x="260" y="210" width="6" height="16" rx="3" fill="#8fe3ff" transform="rotate(-10 263 218)"/>
            <rect x="310" y="195" width="6" height="12" rx="3" fill="#9dffb8" transform="rotate(7 313 201)"/>
            <rect x="360" y="210" width="6" height="18" rx="3" fill="#ffd27a" transform="rotate(-20 363 219)"/>
            <rect x="410" y="200" width="6" height="16" rx="3" fill="#c7b3ff" transform="rotate(10 413 208)"/>
          </g>

          <!-- candles (three) -->
          <g id="candles" transform="translate(0,0)">
            <!-- left candle -->
            <g transform="translate(235,132)">
              <rect x="-8" y="0" width="16" height="44" rx="4" fill="#ffffff"/>
              <rect x="-8" y="0" width="16" height="44" rx="4" fill="#ff8fb6" opacity="0.98"/>
              <g class="flame">
                <path d="M0 -6 C6 -18 2 -28 0 -34 C-2 -28 -6 -18 0 -6 Z" fill="#ffd56a"/>
                <path d="M0 -10 C3 -16 1 -22 0 -26 C-1 -22 -3 -16 0 -10 Z" fill="#ff9e3a"/>
              </g>
            </g>
            <!-- center candle -->
            <g transform="translate(320,108)">
              <rect x="-10" y="0" width="20" height="68" rx="5" fill="#ffffff"/>
              <rect x="-10" y="0" width="20" height="68" rx="5" fill="#8ad7ff" opacity="0.98"/>
              <g class="flame">
                <path d="M0 -8 C6 -22 2 -34 0 -40 C-2 -34 -6 -22 0 -8 Z" fill="#ffd56a"/>
                <path d="M0 -13 C3 -20 1 -26 0 -30 C-1 -26 -3 -20 0 -13 Z" fill="#ff9e3a"/>
              </g>
            </g>
            <!-- right candle -->
            <g transform="translate(405,132)">
              <rect x="-8" y="0" width="16" height="44" rx="4" fill="#ffffff"/>
              <rect x="-8" y="0" width="16" height="44" rx="4" fill="#ffd58a" opacity="0.98"/>
              <g class="flame">
                <path d="M0 -6 C6 -18 2 -28 0 -34 C-2 -28 -6 -18 0 -6 Z" fill="#ffd56a"/>
                <path d="M0 -10 C3 -16 1 -22 0 -26 C-1 -22 -3 -16 0 -10 Z" fill="#ff9e3a"/>
              </g>
            </g>
          </g>

          <!-- golden candle holders / accents -->
          <g fill="#f0c85b" opacity="0.95">
            <circle cx="235" cy="206" r="6"/>
            <circle cx="320" cy="172" r="6"/>
            <circle cx="405" cy="206" r="6"/>
          </g>
        </svg>
      </div>

      <div class="fun-line" role="note">
        <u>abh toh budhe hote jaa rhe ho pension lgwa de</u>
      </div>

      <div class="btns" aria-hidden="false">
        <button id="partyBtn">Celebrate! 🎊</button>
        <button id="toggleMusic">Play/Stop Song</button>
        <button id="download">Save as Image</button>
      </div>

      <div class="credit">Open this file locally — enjoy and feel free to edit the message!</div>
    </div>
  </div>

  <!-- optional embedded audio (encoded small beep melody) -->
  <audio id="song" loop>
    <!-- a tiny cheerful melody generated with data: audio omitted to keep file small.
         If you want a full song, replace src with a local mp3 file path. -->
  </audio>

  <script>
    // Confetti — lightweight implementation
    (function(){
      const canvas = document.getElementById('confetti');
      const ctx = canvas.getContext('2d');
      let W = canvas.width = window.innerWidth;
      let H = canvas.height = window.innerHeight;
      const colors = ['#ff7aa2','#ffd27a','#8fe3ff','#9dffb8','#c7b3ff','#ffffff'];
      let pieces = [];

      function rand(min,max){ return Math.random()*(max-min)+min }

      function Piece(){
        this.x = rand(0,W);
        this.y = rand(-H,0);
        this.w = rand(6,12);
        this.h = rand(8,18);
        this.vx = rand(-0.6,0.6);
        this.vy = rand(1,3.5);
        this.rot = rand(0,Math.PI*2);
        this.rotz = rand(-0.1,0.1);
        this.color = colors[Math.floor(rand(0,colors.length))];
      }

      function init(n=140){
        pieces = [];
        for(let i=0;i<n;i++) pieces.push(new Piece());
      }

      function resize(){
        W = canvas.width = window.innerWidth;
        H = canvas.height = window.innerHeight;
      }
      window.addEventListener('resize',resize);

      function update(){
        ctx.clearRect(0,0,W,H);
        for(let p of pieces){
          p.x += p.vx;
          p.y += p.vy;
          p.rot += p.rotz;
          ctx.save();
          ctx.translate(p.x,p.y);
          ctx.rotate(p.rot);
          ctx.fillStyle = p.color;
          ctx.fillRect(-p.w/2, -p.h/2, p.w, p.h);
          ctx.restore();
          if(p.y > H + 40) {
            Object.assign(p, new Piece());
            p.y = rand(-200, -20);
            p.x = rand(0,W);
          }
        }
        requestAnimationFrame(update);
      }

      init();
      update();

      // Simple party button: temporarily intensify confetti
      document.getElementById('partyBtn').addEventListener('click', function(){
        const old = pieces.length;
        init(300);
        setTimeout(()=> init(old), 5500);
      });

      // Download the card as image (captures card area)
      document.getElementById('download').addEventListener('click', async function(){
        try{
          // render the card element to an image using foreignObject -> svg -> blob
          const card = document.querySelector('.card');
          const rect = card.getBoundingClientRect();
          const clone = card.cloneNode(true);
          // create an outer wrapper to ensure fonts/background
          const wrapper = document.createElement('div');
          wrapper.style.width = rect.width + 'px';
          wrapper.style.height = rect.height + 'px';
          wrapper.style.background = getComputedStyle(document.body).background;
          wrapper.appendChild(clone);

          const svg = `
            <svg xmlns='http://www.w3.org/2000/svg' width='${rect.width}' height='${rect.height}'>
              <foreignObject width='100%' height='100%'>
                ${new XMLSerializer().serializeToString(wrapper).replace(/#/g, '%23')}
              </foreignObject>
            </svg>`;
          // fallback simpler approach: open a new window with the page and let user screenshot
          alert('If save fails due to browser limitations, take a screenshot of the card. (Some browsers block automatic saving.)');
          const w = window.open('', '_blank');
          w.document.write('<title>Save your card</title>');
          w.document.write(card.outerHTML);
          w.document.close();
        }catch(e){
          alert('Unable to automatically save — please screenshot the card instead.');
        }
      });

      // Simple playful beep melody using WebAudio (no external file)
      let audioCtx, osc, playing=false;
      document.getElementById('toggleMusic').addEventListener('click', function(){
        if(!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
        if(!playing){
          playing=true;
          // create a short melody sequence
          const notes = [440, 523.25, 659.25, 523.25, 440, 349.23]; // A4, C5, E5...
          let t = audioCtx.currentTime;
          for(let i=0;i<notes.length;i++){
            const o = audioCtx.createOscillator();
            const g = audioCtx.createGain();
            o.type='sine';
            o.frequency.value = notes[i];
            g.gain.value = 0.0001;
            o.connect(g); g.connect(audioCtx.destination);
            o.start(t + i*0.28);
            g.gain.setValueAtTime(0.0001, t + i*0.28);
            g.gain.exponentialRampToValueAtTime(0.08, t + i*0.28 + 0.02);
            g.gain.exponentialRampToValueAtTime(0.0001, t + i*0.28 + 0.25);
            o.stop(t + i*0.28 + 0.28);
          }
          // auto-stop flag reset
          setTimeout(()=> playing=false, notes.length*280 + 150);
        } else {
          // can't easily stop created short oscillators — just set flag and ignore
          playing=false;
        }
      });

    })();
  </script>
</body>
</html>
