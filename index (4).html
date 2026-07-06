<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>S2 Test 3 · Revision Hub</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Zilla+Slab:wght@500;700&family=Inter:wght@400;500;600;700&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet">
<style>
  :root{
    --paper:#F2F6EE; --paper-line:#DDE7D3; --ink:#22301F;
    --amber:#C97F1E; --teal:#2F6E64; --rose:#AE4267;
    --card:#FDFEFA; --ok:#3C7A4F; --bad:#B24444;
  }
  *{box-sizing:border-box;}
  html,body{margin:0;padding:0;}
  body{
    font-family:'Inter',sans-serif;
    background:
      linear-gradient(var(--paper-line) 1px, transparent 1px) 0 0/100% 32px,
      var(--paper);
    color:var(--ink);
    padding:28px 20px 60px;
    min-height:100vh;
  }
  .wrap{max-width:1000px;margin:0 auto;}
  a{color:inherit;}

  .s2-header{ display:flex; align-items:flex-start; justify-content:space-between; gap:24px; margin-bottom:22px; flex-wrap:wrap; }
  .s2-eyebrow{ font-family:'Space Mono',monospace; font-size:11px; letter-spacing:.14em; text-transform:uppercase; color:var(--rose); margin:0 0 6px; }
  .s2-title{ font-family:'Zilla Slab',serif; font-weight:700; font-size:clamp(24px,4vw,34px); margin:0; line-height:1.15; }
  .s2-sub{ font-size:14px; color:#556352; margin-top:8px; max-width:520px;}
  .back-link{ display:inline-block; margin-bottom:18px; font-family:'Space Mono',monospace; font-size:12px; color:var(--teal); text-decoration:none; border:1px solid #c7d6bc; padding:7px 12px; border-radius:20px; background:var(--card);}
  .back-link:hover{ background:var(--teal); color:#fff; }

  .cell-wrap{ width:110px; flex-shrink:0; display:flex; flex-direction:column; align-items:center; }
  .cell-label{ font-family:'Space Mono',monospace; font-size:10px; color:#556352; margin-bottom:6px; text-align:center;}
  .cell-svg{ width:100px; height:100px; }
  .cell-wall{ fill:#fdfef9; stroke:#a9c19c; stroke-width:2; transition:stroke-dasharray .6s ease, stroke .6s ease; }
  .cell-vacuole{ fill:var(--teal); opacity:.55; transition:r .8s cubic-bezier(.34,1.4,.64,1), fill .6s ease; }
  .cell-status{ font-family:'Space Mono',monospace; font-size:11px; margin-top:6px; color:var(--teal); font-weight:700; text-align:center;}

  .s2-tabs{ display:flex; gap:8px; flex-wrap:wrap; margin-bottom:18px; }
  .s2-tab{ font-family:'Space Mono',monospace; font-size:12px; letter-spacing:.03em; padding:9px 14px; border-radius:20px; border:1px solid #c7d6bc; background:var(--card); cursor:pointer; color:var(--ink); transition:all .2s ease; }
  .s2-tab.active{ background:var(--ink); color:var(--paper); border-color:var(--ink); }
  .s2-tab .dot{ display:inline-block; width:6px; height:6px; border-radius:50%; margin-right:6px; background:#c7d6bc;}
  .s2-tab.done .dot{ background:var(--ok); }

  .panel{ display:none; animation:fade .35s ease; }
  .panel.active{ display:block; }
  @keyframes fade{ from{opacity:0; transform:translateY(4px);} to{opacity:1; transform:translateY(0);} }

  .section-card{ background:var(--card); border:1px solid #dbe7d1; border-radius:12px; padding:20px; margin-bottom:16px; }
  .section-title{ font-family:'Zilla Slab',serif; font-weight:700; font-size:19px; margin:0 0 12px; color:var(--teal);}

  .cards-grid{ display:grid; grid-template-columns:repeat(auto-fill,minmax(170px,1fr)); gap:12px; }
  /* --- FLIP CARD FIX: taller cards + scrollable back so text never gets cut --- */
  .flip{ perspective:1000px; height:170px; cursor:pointer; }
  .flip-inner{ position:relative; width:100%; height:100%; transition:transform .5s; transform-style:preserve-3d; }
  .flip.flipped .flip-inner{ transform:rotateY(180deg); }
  .flip-face{ position:absolute; inset:0; backface-visibility:hidden; border-radius:10px; display:flex; padding:12px; }
  .flip-front{ align-items:center; justify-content:center; text-align:center; background:#fbf6e8; border:1px dashed var(--amber); font-family:'Zilla Slab',serif; font-weight:700; font-size:15px; color:var(--amber);}
  .flip-back{ transform:rotateY(180deg); background:var(--teal); color:#fff; font-weight:500; font-size:12.5px; line-height:1.4; align-items:flex-start; justify-content:flex-start; text-align:left; overflow-y:auto; }
  .flip-back::-webkit-scrollbar{ width:6px; } .flip-back::-webkit-scrollbar-thumb{ background:rgba(255,255,255,.4); border-radius:3px; }

  .factor-grid{ display:grid; grid-template-columns:repeat(auto-fill,minmax(230px,1fr)); gap:14px; }
  .factor-card{ background:#fbf6e8; border:1px solid #e6d9b0; border-radius:10px; padding:14px; }
  .factor-name{ font-weight:700; margin-bottom:8px; font-size:14px; }
  .factor-btns{ display:flex; gap:8px; }
  .factor-btn{ flex:1; padding:8px 6px; border-radius:8px; border:1px solid #d8cfb8; background:#fffef9; cursor:pointer; font-size:12px; font-family:'Space Mono',monospace; }
  .factor-btn.correct{ background:#e5f2e8; border-color:var(--ok); color:var(--ok); font-weight:700;}
  .factor-btn.wrong{ background:#f6e5e5; border-color:var(--bad); color:var(--bad);}

  .quiz-q{ font-weight:600; margin-bottom:10px; }
  .quiz-opts{ display:flex; flex-direction:column; gap:8px; }
  .quiz-opt{ text-align:left; padding:10px 14px; border-radius:8px; border:1px solid #c7d6bc; background:#fffef9; cursor:pointer; font-size:14px; }
  .quiz-opt.correct{ background:#e5f2e8; border-color:var(--ok); color:var(--ok); font-weight:600;}
  .quiz-opt.wrong{ background:#f6e5e5; border-color:var(--bad); color:var(--bad);}
  .quiz-fb{ margin-top:10px; font-size:13px; color:#556352; min-height:18px;}

  .mark-btn{ margin-top:12px; font-family:'Space Mono',monospace; font-size:11px; padding:7px 12px; border-radius:8px; border:1px solid var(--teal); background:#fff; color:var(--teal); cursor:pointer; }
  .mark-btn.done{ background:var(--teal); color:#fff; }
  .scenario{ background:#fbf6e8; border-left:3px solid var(--amber); padding:10px 12px; border-radius:6px; font-size:14px; margin-bottom:10px;}

  .acc{ border:1px solid #dbe7d1; border-radius:10px; overflow:hidden; margin-bottom:10px; }
  .acc-head{ display:flex; justify-content:space-between; align-items:center; gap:10px; padding:13px 16px; background:#fbf6e8; cursor:pointer; font-weight:700; font-size:14px; }
  .acc-head .arrow{ transition:transform .3s ease; font-family:'Space Mono',monospace; color:var(--teal); }
  .acc.open .acc-head .arrow{ transform:rotate(180deg); }
  .acc-body{ max-height:0; overflow:hidden; transition:max-height .4s ease; background:#fffef9; }
  .acc.open .acc-body{ max-height:1400px; }
  .acc-body-inner{ padding:4px 16px 16px; font-size:14px; line-height:1.55; }
  .acc-body-inner .ex{ background:#f2f6ee; border-left:3px solid var(--teal); padding:9px 12px; border-radius:6px; margin-top:8px; font-size:13.5px;}
  .acc-body-inner table{ width:100%; border-collapse:collapse; margin-top:8px; font-size:13px;}
  .acc-body-inner td, .acc-body-inner th{ border:1px solid #dbe7d1; padding:6px 8px; text-align:left; }
  .acc-body-inner th{ background:#eef4e7; }

  .exam-q{ border:1px solid #e6d9b0; background:#fdfaf1; border-radius:10px; padding:14px 16px; margin-bottom:12px; }
  .exam-tag{ font-family:'Space Mono',monospace; font-size:10px; color:var(--amber); letter-spacing:.06em; text-transform:uppercase; margin-bottom:6px; }
  .exam-body{ font-size:14px; line-height:1.5; margin-bottom:10px; }
  .exam-reveal{ font-family:'Space Mono',monospace; font-size:11px; padding:7px 12px; border-radius:8px; border:1px solid var(--amber); background:#fff; color:var(--amber); cursor:pointer; }
  .exam-answer{ display:none; margin-top:10px; background:#fff; border-left:3px solid var(--ok); padding:10px 12px; border-radius:6px; font-size:13.5px; }
  .exam-answer.shown{ display:block; }

  /* ---- index page ---- */
  .idx-grid{ display:grid; grid-template-columns:repeat(auto-fill,minmax(260px,1fr)); gap:16px; }
  .idx-card{ display:block; text-decoration:none; background:var(--card); border:1px solid #dbe7d1; border-radius:14px; padding:20px; transition:transform .2s ease, box-shadow .2s ease, border-color .2s ease; }
  .idx-card:hover{ transform:translateY(-3px); box-shadow:0 8px 20px rgba(47,110,100,.14); border-color:var(--teal); }
  .idx-code{ font-family:'Space Mono',monospace; font-size:11px; color:var(--rose); letter-spacing:.08em; }
  .idx-name{ font-family:'Zilla Slab',serif; font-weight:700; font-size:20px; margin:6px 0 8px; color:var(--ink); }
  .idx-desc{ font-size:13px; color:#556352; line-height:1.5; }
  .idx-tag{ display:inline-block; margin-top:12px; font-family:'Space Mono',monospace; font-size:10px; color:var(--teal); border:1px solid #c7d6bc; padding:4px 9px; border-radius:20px;}
  .idx-badge{ display:inline-block; font-family:'Space Mono',monospace; font-size:10px; padding:2px 8px; border-radius:10px; background:#eef4e7; color:var(--teal); margin-left:6px;}
</style>

</head>
<body>
<div class="wrap">
  <div class="s2-header">
    <div>
      <p class="s2-eyebrow">IGCSE Coordinated Science · Bimester 2 Week 9</p>
      <h1 class="s2-title">S2 · Test 3 Revision Hub</h1>
      <p class="s2-sub">Pick a topic to revise. Each page has flip-card key terms, deeper explanations with everyday examples, quick quizzes, and exam-style questions with mark schemes. Good luck! 🌱</p>
    </div>
  </div>
  <div class="idx-grid">
    <a class="idx-card" href="diffusion-osmosis.html">
      <span class="idx-code">C1.2 · B3.1 · B3.2</span>
      <div class="idx-name">Diffusion & Osmosis</div>
      <div class="idx-desc">Kinetic particle theory, factors affecting diffusion, water potential, and the effect on plant cells (turgid, flaccid, plasmolysis).</div>
      <span class="idx-tag">4 sections</span>
    </a>
    <a class="idx-card" href="active-transport.html">
      <span class="idx-code">B3.3</span>
      <div class="idx-name">Active Transport</div>
      <div class="idx-desc">Moving particles against the gradient using energy from respiration — root hair ion uptake, digestion and salt glands.</div>
      <span class="idx-tag">3 sections</span>
    </a>
    <a class="idx-card" href="ionic-bonding.html">
      <span class="idx-code">C2.4</span>
      <div class="idx-name">Ionic Bonding</div>
      <div class="idx-desc">Cations & anions, dot-and-cross diagrams, the giant ionic lattice, and why ionic compounds behave the way they do.</div>
      <span class="idx-tag">3 sections</span>
    </a>
    <a class="idx-card" href="acids-bases-salts.html">
      <span class="idx-code">C7.1</span>
      <div class="idx-name">Acids, Bases & Salts</div>
      <div class="idx-desc">Reactions of acids and bases, indicator colours, the pH scale and neutralisation.</div>
      <span class="idx-tag">4 sections</span>
    </a>
    <a class="idx-card" href="exothermic-endothermic.html">
      <span class="idx-code">C5.1</span>
      <div class="idx-name">Exothermic & Endothermic</div>
      <div class="idx-desc">Energy transfer to/from the surroundings, spotting each in experiments, reaction pathways, ΔH, activation energy and bonds.</div>
      <span class="idx-tag">3 sections</span>
    </a>
  </div>
  <p style="margin-top:26px;font-size:12px;color:#556352;font-family:'Space Mono',monospace;">
    Covers: Diffusion (C1.2 · B3.1) · Osmosis (B3.2) · Active Transport (B3.3) · Ionic Bonding (C2.4) · Acids, Bases &amp; Salts (C7.1) · Exothermic &amp; Endothermic (C5.1)
  </p>
</div>
</body>
</html>
