<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>Skat — Player's Guide</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,600;0,700;1,400&family=Crimson+Pro:ital,wght@0,300;0,400;0,600;1,300;1,400&display=swap" rel="stylesheet">
<style>
  :root {
    --felt: #1a2e1f;
    --felt-light: #223628;
    --felt-mid: #1e3322;
    --gold: #c9a84c;
    --gold-light: #e2c470;
    --gold-dim: #8a6f2f;
    --cream: #f5efe0;
    --cream-dim: #c8bc9e;
    --red: #c0392b;
    --red-bright: #e74c3c;
    --black-suit: #d4c8a8;
    --border: rgba(201,168,76,0.25);
    --tab-h: 60px;
    --header-h: 52px;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: 'Crimson Pro', Georgia, serif;
    background: var(--felt);
    color: var(--cream);
    min-height: 100vh;
    font-size: 16px;
    line-height: 1.5;
    overscroll-behavior: none;
  }

  /* ─── HEADER ─── */
  header {
    position: fixed;
    top: 0; left: 0; right: 0;
    height: var(--header-h);
    background: linear-gradient(180deg, #0d1a10 0%, var(--felt) 100%);
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 100;
    gap: 10px;
  }

  header h1 {
    font-family: 'Playfair Display', serif;
    font-size: 1.4rem;
    letter-spacing: 0.12em;
    color: var(--gold);
    text-transform: uppercase;
  }

  header .suit-row {
    font-size: 1.1rem;
    color: var(--gold-dim);
    letter-spacing: 0.15em;
  }

  /* ─── TABS ─── */
  nav {
    position: fixed;
    bottom: 0; left: 0; right: 0;
    height: var(--tab-h);
    background: #0d1a10;
    border-top: 1px solid var(--border);
    display: flex;
    z-index: 100;
  }

  nav button {
    flex: 1;
    background: none;
    border: none;
    color: var(--gold-dim);
    font-family: 'Crimson Pro', serif;
    font-size: 0.65rem;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    cursor: pointer;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 3px;
    padding-bottom: 4px;
    transition: color 0.2s;
  }

  nav button .icon { font-size: 1.3rem; }

  nav button.active {
    color: var(--gold);
    background: rgba(201,168,76,0.07);
    border-top: 2px solid var(--gold);
    margin-top: -2px;
  }

  /* ─── MAIN CONTENT ─── */
  main {
    padding-top: calc(var(--header-h) + 12px);
    padding-bottom: calc(var(--tab-h) + 16px);
    padding-left: 14px;
    padding-right: 14px;
    max-width: 520px;
    margin: 0 auto;
  }

  .tab-panel { display: none; }
  .tab-panel.active { display: block; }

  /* ─── SECTION TITLES ─── */
  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: 0.65rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gold-dim);
    margin: 20px 0 8px;
    border-bottom: 1px solid var(--border);
    padding-bottom: 5px;
  }

  /* ─── CARDS ─── */
  .card {
    background: var(--felt-light);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 14px 16px;
    margin-bottom: 10px;
  }

  .card-title {
    font-family: 'Playfair Display', serif;
    font-size: 1rem;
    color: var(--gold-light);
    margin-bottom: 8px;
  }

  /* ─── RANK TABLE ─── */
  .rank-strip {
    display: flex;
    align-items: stretch;
    border: 1px solid var(--border);
    border-radius: 6px;
    overflow: hidden;
    margin-bottom: 6px;
    font-size: 0.78rem;
  }

  .rank-cell {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 6px 2px;
    border-right: 1px solid var(--border);
    gap: 2px;
  }
  .rank-cell:last-child { border-right: none; }

  .rank-cell .card-face {
    font-size: 1.05rem;
    font-weight: 600;
    line-height: 1;
  }

  .rank-cell .pts {
    font-size: 0.6rem;
    color: var(--gold);
    font-weight: 600;
  }

  .rank-cell .label {
    font-size: 0.55rem;
    color: var(--cream-dim);
    letter-spacing: 0.04em;
    text-align: center;
  }

  .rank-cell.trump-top { background: rgba(201,168,76,0.1); }
  .rank-cell.zero { opacity: 0.5; }

  .red-suit { color: #e05050; }
  .black-suit { color: var(--black-suit); }

  /* ─── TRUMP ORDER VISUAL ─── */
  .trump-order {
    display: flex;
    align-items: center;
    gap: 3px;
    flex-wrap: wrap;
    font-size: 0.8rem;
  }

  .trump-badge {
    background: rgba(201,168,76,0.15);
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 3px 7px;
    font-size: 0.75rem;
    white-space: nowrap;
  }

  .trump-badge.high { background: rgba(201,168,76,0.3); color: var(--gold-light); }
  .arrow { color: var(--gold-dim); font-size: 0.65rem; }

  /* ─── GAME VALUE CALCULATOR ─── */
  .calc-section {
    background: var(--felt-light);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 16px;
    margin-bottom: 12px;
  }

  .calc-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 14px;
    gap: 10px;
  }

  .calc-label {
    font-family: 'Playfair Display', serif;
    font-size: 0.85rem;
    color: var(--cream-dim);
    min-width: 90px;
  }

  .btn-group {
    display: flex;
    gap: 4px;
    flex-wrap: wrap;
    justify-content: flex-end;
  }

  .btn-group button {
    background: var(--felt-mid);
    border: 1px solid var(--border);
    border-radius: 5px;
    color: var(--cream-dim);
    font-family: 'Crimson Pro', serif;
    font-size: 0.8rem;
    padding: 5px 9px;
    cursor: pointer;
    transition: all 0.15s;
    white-space: nowrap;
  }

  .btn-group button.selected {
    background: var(--gold);
    color: #0d1a10;
    border-color: var(--gold);
    font-weight: 700;
  }

  .btn-group button:active { transform: scale(0.95); }

  .toggle-check {
    display: flex;
    align-items: center;
    gap: 7px;
    cursor: pointer;
    font-size: 0.8rem;
    color: var(--cream-dim);
    padding: 5px 0;
  }

  .toggle-check input[type=checkbox] {
    width: 16px; height: 16px;
    accent-color: var(--gold);
    cursor: pointer;
  }

  .toggle-check.dim { opacity: 0.4; pointer-events: none; }

  .result-box {
    background: linear-gradient(135deg, rgba(201,168,76,0.15), rgba(201,168,76,0.05));
    border: 1.5px solid var(--gold-dim);
    border-radius: 10px;
    padding: 16px;
    text-align: center;
    margin-top: 14px;
  }

  .result-value {
    font-family: 'Playfair Display', serif;
    font-size: 3rem;
    color: var(--gold-light);
    line-height: 1;
    margin-bottom: 4px;
  }

  .result-label {
    font-size: 0.7rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--gold-dim);
    margin-bottom: 8px;
  }

  .result-formula {
    font-size: 0.78rem;
    color: var(--cream-dim);
    font-style: italic;
    margin-bottom: 8px;
  }

  .result-breakdown {
    font-size: 0.73rem;
    color: var(--cream-dim);
    line-height: 1.8;
  }

  .result-breakdown span {
    color: var(--gold);
  }

  .matador-stepper {
    display: flex;
    align-items: center;
    gap: 0;
    border: 1px solid var(--border);
    border-radius: 6px;
    overflow: hidden;
  }

  .matador-stepper button {
    background: var(--felt-mid);
    border: none;
    color: var(--gold);
    font-size: 1.2rem;
    padding: 6px 14px;
    cursor: pointer;
    font-family: 'Crimson Pro', serif;
    transition: background 0.15s;
  }

  .matador-stepper button:active { background: var(--gold); color: #0d1a10; }

  .matador-stepper .mat-val {
    background: var(--felt-light);
    color: var(--cream);
    font-size: 1rem;
    font-family: 'Playfair Display', serif;
    padding: 6px 16px;
    min-width: 44px;
    text-align: center;
    border-left: 1px solid var(--border);
    border-right: 1px solid var(--border);
  }

  .with-against {
    display: flex;
    gap: 6px;
  }

  .with-against button {
    background: var(--felt-mid);
    border: 1px solid var(--border);
    border-radius: 5px;
    color: var(--cream-dim);
    font-family: 'Crimson Pro', serif;
    font-size: 0.78rem;
    padding: 5px 10px;
    cursor: pointer;
  }

  .with-against button.selected {
    background: var(--gold);
    color: #0d1a10;
    font-weight: 700;
    border-color: var(--gold);
  }

  .hint-box {
    background: rgba(201,168,76,0.06);
    border-left: 2px solid var(--gold-dim);
    border-radius: 0 5px 5px 0;
    padding: 8px 12px;
    font-size: 0.77rem;
    color: var(--cream-dim);
    font-style: italic;
    margin-top: 10px;
    line-height: 1.5;
  }

  .null-warning {
    display: none;
    background: rgba(192,57,43,0.15);
    border: 1px solid rgba(192,57,43,0.4);
    border-radius: 6px;
    padding: 10px 12px;
    font-size: 0.8rem;
    color: #e8a09a;
    text-align: center;
    margin-top: 10px;
  }

  /* ─── SCORING TABLE ─── */
  .score-table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.78rem;
  }

  .score-table th {
    font-family: 'Playfair Display', serif;
    font-size: 0.65rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--gold-dim);
    border-bottom: 1px solid var(--border);
    padding: 6px 8px;
    text-align: left;
  }

  .score-table td {
    padding: 6px 8px;
    border-bottom: 1px solid rgba(201,168,76,0.1);
    vertical-align: top;
  }

  .score-table tr:last-child td { border-bottom: none; }
  .score-table .num { font-family: 'Playfair Display', serif; color: var(--gold-light); font-size: 0.9rem; }
  .score-table .win { color: #6ec68c; }
  .score-table .lose { color: #e8a09a; }

  /* ─── STEPS ─── */
  .step {
    display: flex;
    gap: 12px;
    margin-bottom: 14px;
    align-items: flex-start;
  }

  .step-num {
    background: var(--gold);
    color: #0d1a10;
    font-family: 'Playfair Display', serif;
    font-size: 0.85rem;
    width: 26px;
    height: 26px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    margin-top: 1px;
    font-weight: 700;
  }

  .step-body { flex: 1; }
  .step-body strong { color: var(--gold-light); font-style: normal; font-weight: 600; }
  .step-body p { font-size: 0.82rem; color: var(--cream-dim); line-height: 1.55; margin-top: 2px; }

  /* ─── BASE SCORE TABLE ─── */
  .base-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 6px;
    margin-bottom: 10px;
  }

  .base-item {
    background: var(--felt-mid);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 10px 12px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .base-item .suit-name { font-size: 0.9rem; }
  .base-item .base-num {
    font-family: 'Playfair Display', serif;
    font-size: 1.3rem;
    color: var(--gold);
  }

  /* ─── MULTIPLIER LIST ─── */
  .mult-list { list-style: none; }

  .mult-list li {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 7px 0;
    border-bottom: 1px solid rgba(201,168,76,0.1);
    font-size: 0.82rem;
  }

  .mult-list li:last-child { border-bottom: none; }

  .mult-tag {
    background: rgba(201,168,76,0.2);
    color: var(--gold-light);
    font-family: 'Playfair Display', serif;
    font-size: 0.8rem;
    border-radius: 4px;
    padding: 2px 7px;
  }

  /* ─── NULL TABLE ─── */
  .null-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 6px;
  }

  .null-item {
    background: var(--felt-mid);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 10px;
    text-align: center;
  }

  .null-item .null-name { font-size: 0.75rem; color: var(--cream-dim); margin-bottom: 3px; }
  .null-item .null-val { font-family: 'Playfair Display', serif; font-size: 1.5rem; color: var(--gold-light); }

  /* ─── DIVIDER ─── */
  .divider {
    border: none;
    border-top: 1px solid var(--border);
    margin: 14px 0;
  }

  /* ─── BID TABLE ─── */
  .bid-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 4px;
    font-size: 0.75rem;
  }

  .bid-cell {
    background: var(--felt-mid);
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 5px 6px;
    text-align: center;
  }

  .bid-cell .bid-num {
    font-family: 'Playfair Display', serif;
    font-size: 1rem;
    color: var(--gold-light);
    display: block;
  }

  .bid-cell .bid-desc {
    font-size: 0.55rem;
    color: var(--cream-dim);
    letter-spacing: 0.04em;
    text-transform: uppercase;
    line-height: 1.2;
  }

  /* ─── TIPS ─── */
  .tip-item {
    display: flex;
    gap: 10px;
    margin-bottom: 12px;
    font-size: 0.82rem;
    color: var(--cream-dim);
    line-height: 1.55;
  }

  .tip-icon {
    font-size: 1.1rem;
    flex-shrink: 0;
    margin-top: 1px;
  }

  /* ─── ANIMATIONS ─── */
  .tab-panel.active {
    animation: fadeIn 0.2s ease;
  }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(6px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .result-box {
    transition: all 0.2s ease;
  }

  /* ─── SCROLLBAR ─── */
  ::-webkit-scrollbar { width: 4px; }
  ::-webkit-scrollbar-track { background: var(--felt); }
  ::-webkit-scrollbar-thumb { background: var(--gold-dim); border-radius: 2px; }

  .grand-note {
    font-size: 0.72rem;
    color: var(--cream-dim);
    font-style: italic;
    text-align: center;
    margin-top: 4px;
  }

  .pill {
    display: inline-block;
    background: rgba(201,168,76,0.18);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 1px 8px;
    font-size: 0.72rem;
    color: var(--gold-light);
    margin-right: 3px;
    white-space: nowrap;
  }

  .inline-rule {
    font-size: 0.79rem;
    color: var(--cream-dim);
    line-height: 1.6;
  }
</style>
</head>
<body>

<header>
  <span class="suit-row">♣ ♠ ♥ ♦</span>
  <h1>Skat</h1>
  <span class="suit-row">♦ ♥ ♠ ♣</span>
</header>

<main>
  <!-- ══════════════════════════════ CALCULATOR ══════════════════════════════ -->
  <div class="tab-panel active" id="panel-calc">

    <div class="section-title">Game Value Calculator</div>

    <div class="calc-section">

      <div class="calc-row">
        <div class="calc-label">Trump / Game</div>
        <div class="btn-group" id="suit-btns">
          <button data-suit="diamonds" data-base="9" class="red-suit selected">♦ 9</button>
          <button data-suit="hearts"   data-base="10" class="red-suit">♥ 10</button>
          <button data-suit="spades"   data-base="11">♠ 11</button>
          <button data-suit="clubs"    data-base="12">♣ 12</button>
          <button data-suit="grand"    data-base="24">Grand</button>
          <button data-suit="null"     data-base="0">Null</button>
        </div>
      </div>

      <div id="suit-options">
        <div class="calc-row">
          <div class="calc-label">Matadors</div>
          <div style="display:flex; align-items:center; gap:8px;">
            <div class="with-against" id="wa-btns">
              <button data-wa="with" class="selected">With</button>
              <button data-wa="against">Against</button>
            </div>
            <div class="matador-stepper">
              <button id="mat-minus">−</button>
              <div class="mat-val" id="mat-display">1</div>
              <button id="mat-plus">+</button>
            </div>
          </div>
        </div>

        <div class="calc-row" style="margin-bottom:8px;">
          <div class="calc-label">Bonuses</div>
          <div style="display:flex; flex-direction:column; gap:6px; align-items:flex-end;">
            <label class="toggle-check" id="lbl-hand">
              <input type="checkbox" id="cb-hand"> Hand (no Skat)
            </label>
            <label class="toggle-check" id="lbl-schneider">
              <input type="checkbox" id="cb-schneider"> Won Schneider (90+)
            </label>
            <label class="toggle-check" id="lbl-ann-schneider">
              <input type="checkbox" id="cb-ann-schneider"> Announced Schneider
            </label>
            <label class="toggle-check" id="lbl-schwarz">
              <input type="checkbox" id="cb-schwarz"> Won Schwarz (all tricks)
            </label>
            <label class="toggle-check" id="lbl-ann-schwarz">
              <input type="checkbox" id="cb-ann-schwarz"> Announced Schwarz
            </label>
            <label class="toggle-check" id="lbl-open">
              <input type="checkbox" id="cb-open"> Open (cards displayed)
            </label>
          </div>
        </div>
      </div>

      <!-- NULL options -->
      <div id="null-options" style="display:none;">
        <div class="calc-row">
          <div class="calc-label">Variant</div>
          <div class="btn-group" id="null-variant-btns">
            <button data-nv="closed" data-nhand="no" class="selected">Closed</button>
            <button data-nv="open" data-nhand="no">Open</button>
          </div>
        </div>
        <div class="calc-row">
          <div class="calc-label">Hand?</div>
          <div class="btn-group" id="null-hand-btns">
            <button data-nh="no" class="selected">No</button>
            <button data-nh="yes">Hand</button>
          </div>
        </div>
        <div class="null-warning" id="null-warn">No trumps. No matadors. Card rank: A K Q J 10 9 8 7. Win by losing every trick.</div>
      </div>

      <div class="result-box" id="result-box">
        <div class="result-label">Game Value</div>
        <div class="result-value" id="result-val">9</div>
        <div class="result-formula" id="result-formula">Base 9 × (1 mat + 1 game) = 9×2</div>
        <hr class="divider" style="margin:8px 0;">
        <div class="result-breakdown" id="result-breakdown">
          Matadors: <span>with 1</span><br>
          Multiplier total: <span>2</span>
        </div>
      </div>

      <div class="hint-box" id="hint-box">
        💡 <strong>Bid up to this value.</strong> If you win the bid and fall short of this game value, you lose 2× the next lower valid multiple of the base.
      </div>
    </div>

    <div class="section-title">How Matadors Work</div>
    <div class="card">
      <div class="inline-rule">
        <strong style="color:var(--gold-light)">Matadors</strong> are the number of consecutive top trumps starting from J♣ — either <em>held by you</em> or <em>held by opponents</em> (combined).<br><br>
        <span class="pill">With X</span> You hold J♣ and the next X−1 in sequence.<br>
        <span class="pill">Against X</span> Your best trump is below the top X. (e.g., highest is J♥ = against 2)<br><br>
        <em>With or against counts the same for the multiplier.</em> The Skat counts as part of your hand for matadors.
      </div>
    </div>

    <div class="section-title">Quick Matador Finder</div>
    <div class="card">
      <div style="font-size:0.78rem; color:var(--cream-dim); margin-bottom:8px;">Your highest trump →</div>
      <table class="score-table">
        <thead><tr><th>Highest trump you hold</th><th>Matadors</th></tr></thead>
        <tbody>
          <tr><td>J♣</td><td class="num">With ≥1 (keep counting down)</td></tr>
          <tr><td>J♠ (no J♣)</td><td class="num">Against 1</td></tr>
          <tr><td>J♥ (no J♣ J♠)</td><td class="num">Against 2</td></tr>
          <tr><td>J♦ (no other Jacks)</td><td class="num">Against 3</td></tr>
          <tr><td>Ace of trumps (no Jacks)</td><td class="num">Against 4</td></tr>
          <tr><td>10 of trumps (no Jacks, no A)</td><td class="num">Against 5</td></tr>
        </tbody>
      </table>
    </div>
  </div>

  <!-- ══════════════════════════════ RANKS & SCORING ══════════════════════════════ -->
  <div class="tab-panel" id="panel-cards">

    <div class="section-title">Card Points (same in all suit & grand games)</div>
    <div class="card">
      <div class="rank-strip">
        <div class="rank-cell trump-top">
          <div class="card-face black-suit">J</div>
          <div class="pts">2</div>
          <div class="label">Jack×4</div>
        </div>
        <div class="rank-cell">
          <div class="card-face">A</div>
          <div class="pts">11</div>
          <div class="label">Ace</div>
        </div>
        <div class="rank-cell">
          <div class="card-face">10</div>
          <div class="pts">10</div>
          <div class="label">Ten</div>
        </div>
        <div class="rank-cell">
          <div class="card-face">K</div>
          <div class="pts">4</div>
          <div class="label">King</div>
        </div>
        <div class="rank-cell">
          <div class="card-face">Q</div>
          <div class="pts">3</div>
          <div class="label">Queen</div>
        </div>
        <div class="rank-cell zero">
          <div class="card-face">9</div>
          <div class="pts">0</div>
          <div class="label">Nine</div>
        </div>
        <div class="rank-cell zero">
          <div class="card-face">8</div>
          <div class="pts">0</div>
          <div class="label">Eight</div>
        </div>
        <div class="rank-cell zero">
          <div class="card-face">7</div>
          <div class="pts">0</div>
          <div class="label">Seven</div>
        </div>
      </div>
      <div class="grand-note">Total: 120 card points. Win by taking 61+.</div>
    </div>

    <div class="section-title">Trump Order — Suit Game (e.g., ♥ is trump)</div>
    <div class="card">
      <div class="trump-order">
        <span class="trump-badge high black-suit">J♣</span>
        <span class="arrow">›</span>
        <span class="trump-badge high black-suit">J♠</span>
        <span class="arrow">›</span>
        <span class="trump-badge high red-suit">J♥</span>
        <span class="arrow">›</span>
        <span class="trump-badge high red-suit">J♦</span>
        <span class="arrow">›</span>
        <span class="trump-badge red-suit">A♥</span>
        <span class="arrow">›</span>
        <span class="trump-badge red-suit">10♥</span>
        <span class="arrow">›</span>
        <span class="trump-badge red-suit">K♥</span>
        <span class="arrow">›</span>
        <span class="trump-badge red-suit">Q♥</span>
        <span class="arrow">›</span>
        <span class="trump-badge red-suit">9♥ 8♥ 7♥</span>
      </div>
      <div class="hint-box" style="margin-top:10px;">Jacks always belong to the <em>trump suit</em>, not their own. If ♠ is led and you only have J♠, you must play it — but if ♠ is trump and J♠ is led, any trump (even J♦) can follow.</div>
    </div>

    <div class="section-title">Trump Order — Grand Game</div>
    <div class="card">
      <div class="trump-order">
        <span class="trump-badge high black-suit">J♣</span>
        <span class="arrow">›</span>
        <span class="trump-badge high black-suit">J♠</span>
        <span class="arrow">›</span>
        <span class="trump-badge high red-suit">J♥</span>
        <span class="arrow">›</span>
        <span class="trump-badge high red-suit">J♦</span>
        <span class="arrow">›</span>
        <span style="font-size:0.78rem; color:var(--cream-dim);">then each plain suit: A › 10 › K › Q › 9 › 8 › 7</span>
      </div>
    </div>

    <div class="section-title">Null Card Order (no trumps!)</div>
    <div class="card">
      <div class="trump-order">
        <span class="trump-badge">A</span>
        <span class="arrow">›</span>
        <span class="trump-badge">K</span>
        <span class="arrow">›</span>
        <span class="trump-badge">Q</span>
        <span class="arrow">›</span>
        <span class="trump-badge">J</span>
        <span class="arrow">›</span>
        <span class="trump-badge">10</span>
        <span class="arrow">›</span>
        <span class="trump-badge">9</span>
        <span class="arrow">›</span>
        <span class="trump-badge">8</span>
        <span class="arrow">›</span>
        <span class="trump-badge">7</span>
      </div>
      <div style="font-size:0.78rem; color:var(--cream-dim); margin-top:8px;">Jacks are NOT special. Goal: take zero tricks.</div>
    </div>

    <div class="section-title">Winning & Losing</div>
    <div class="card">
      <table class="score-table">
        <tbody>
          <tr>
            <td>Declarer wins</td>
            <td class="win">61+ card pts &amp; game value ≥ bid → add game value</td>
          </tr>
          <tr>
            <td>Declarer loses (sufficient)</td>
            <td class="lose">Game value ≥ bid but &lt;61 pts → subtract 2× game value</td>
          </tr>
          <tr>
            <td>Declarer loses (overbid)</td>
            <td class="lose">Game value &lt; bid → subtract 2× lowest valid value ≥ bid</td>
          </tr>
          <tr>
            <td>Null win</td>
            <td class="win">Lose every trick → add Null value</td>
          </tr>
          <tr>
            <td>Null lose</td>
            <td class="lose">Win a trick → subtract 2× Null value</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

  <!-- ══════════════════════════════ BASE SCORES & MULTIPLIERS ══════════════════════════════ -->
  <div class="tab-panel" id="panel-scores">

    <div class="section-title">Base Scores</div>
    <div class="base-grid">
      <div class="base-item">
        <span class="suit-name red-suit">♦ Diamonds</span>
        <span class="base-num">9</span>
      </div>
      <div class="base-item">
        <span class="suit-name red-suit">♥ Hearts</span>
        <span class="base-num">10</span>
      </div>
      <div class="base-item">
        <span class="suit-name black-suit">♠ Spades</span>
        <span class="base-num">11</span>
      </div>
      <div class="base-item">
        <span class="suit-name black-suit">♣ Clubs</span>
        <span class="base-num">12</span>
      </div>
      <div class="base-item">
        <span class="suit-name">Grand</span>
        <span class="base-num">24</span>
      </div>
    </div>

    <div class="section-title">Null Game Values (flat, no multipliers)</div>
    <div class="null-grid">
      <div class="null-item">
        <div class="null-name">Closed Null</div>
        <div class="null-val">23</div>
      </div>
      <div class="null-item">
        <div class="null-name">Null Hand</div>
        <div class="null-val">35</div>
      </div>
      <div class="null-item">
        <div class="null-name">Null Open</div>
        <div class="null-val">46</div>
      </div>
      <div class="null-item">
        <div class="null-name">Null Open Hand</div>
        <div class="null-val">59</div>
      </div>
    </div>

    <div class="section-title">Multipliers — Base × (total)</div>
    <div class="card" style="padding:12px 14px;">
      <ul class="mult-list">
        <li>
          <span>Matadors (with or against)</span>
          <span class="mult-tag">+1 each</span>
        </li>
        <li>
          <span>Game (always counted)</span>
          <span class="mult-tag">+1</span>
        </li>
        <li>
          <span>Hand (skipped Skat)</span>
          <span class="mult-tag">+1</span>
        </li>
        <li>
          <span>Schneider (won 90+ pts)</span>
          <span class="mult-tag">+1</span>
        </li>
        <li>
          <span>Announced Schneider <em style="font-size:0.7rem;">(requires Hand)</em></span>
          <span class="mult-tag">+1</span>
        </li>
        <li>
          <span>Schwarz (won all tricks)</span>
          <span class="mult-tag">+1</span>
        </li>
        <li>
          <span>Announced Schwarz <em style="font-size:0.7rem;">(requires Hand)</em></span>
          <span class="mult-tag">+1</span>
        </li>
        <li>
          <span>Open <em style="font-size:0.7rem;">(requires Hand + Ann. Schwarz)</em></span>
          <span class="mult-tag">+1</span>
        </li>
      </ul>
      <div class="hint-box" style="margin-top:10px;">
        Formula: <strong style="color:var(--gold-light)">Game Value = Base × (Matadors + 1 + other bonuses)</strong><br><br>
        Example: ♣ with 2 matadors, Hand, won Schneider →<br>
        12 × (2 mat + 1 game + 1 hand + 1 schneider) = <strong style="color:var(--gold-light)">12 × 5 = 60</strong>
      </div>
    </div>

    <div class="section-title">Common Bid Values</div>
    <div class="bid-grid">
      <div class="bid-cell"><span class="bid-num">18</span><span class="bid-desc">♦ w/1</span></div>
      <div class="bid-cell"><span class="bid-num">20</span><span class="bid-desc">♥ w/1</span></div>
      <div class="bid-cell"><span class="bid-num">22</span><span class="bid-desc">♠ w/1</span></div>
      <div class="bid-cell"><span class="bid-num">23</span><span class="bid-desc">Null</span></div>
      <div class="bid-cell"><span class="bid-num">24</span><span class="bid-desc">♣ w/1 / Grand w/1</span></div>
      <div class="bid-cell"><span class="bid-num">27</span><span class="bid-desc">♦ w/2</span></div>
      <div class="bid-cell"><span class="bid-num">30</span><span class="bid-desc">♥ w/2</span></div>
      <div class="bid-cell"><span class="bid-num">33</span><span class="bid-desc">♠ w/2</span></div>
      <div class="bid-cell"><span class="bid-num">35</span><span class="bid-desc">Null Hand</span></div>
      <div class="bid-cell"><span class="bid-num">36</span><span class="bid-desc">♣ w/2</span></div>
      <div class="bid-cell"><span class="bid-num">46</span><span class="bid-desc">Null Open</span></div>
      <div class="bid-cell"><span class="bid-num">48</span><span class="bid-desc">♣ w/3</span></div>
      <div class="bid-cell"><span class="bid-num">59</span><span class="bid-desc">Null Open Hand</span></div>
      <div class="bid-cell"><span class="bid-num">60</span><span class="bid-desc">♣ w/4</span></div>
      <div class="bid-cell"><span class="bid-num">96</span><span class="bid-desc">Grand w/3</span></div>
    </div>
  </div>

  <!-- ══════════════════════════════ HOW TO PLAY ══════════════════════════════ -->
  <div class="tab-panel" id="panel-play">

    <div class="section-title">The Five Phases</div>

    <div class="step">
      <div class="step-num">1</div>
      <div class="step-body">
        <strong>Deal</strong>
        <p>First dealer chosen at random; rotates clockwise. Deal 3 to each → 2 face-down (the Skat) → 4 to each → 3 to each. Each player gets 10 cards.</p>
      </div>
    </div>

    <div class="step">
      <div class="step-num">2</div>
      <div class="step-body">
        <strong>Bid</strong>
        <p><em>Forehand</em> is senior (left of dealer). <em>Middlehand</em> opens by calling values: 18, 20, 22… Forehand says "yes" (matches) or passes. Rearhand then challenges the survivor. Winner is <strong>Declarer</strong>.</p>
        <p style="margin-top:5px;"><span class="pill">Senior</span> only needs to equal a bid to win it. <span class="pill">Junior</span> must exceed.</p>
      </div>
    </div>

    <div class="step">
      <div class="step-num">3</div>
      <div class="step-body">
        <strong>Declarer Setup</strong>
        <p>Declarer <em>may</em> look at the Skat, take both cards, and discard any two face-down (those points count for Declarer at end). OR skip the Skat for <strong>Hand</strong> bonus (+1 multiplier).</p>
        <p style="margin-top:5px;">Then declare: <strong>Suit</strong> (name trump), <strong>Grand</strong> (jacks only), or <strong>Null</strong> (lose all tricks). Optionally announce Schneider, Schwarz, or Open.</p>
      </div>
    </div>

    <div class="step">
      <div class="step-num">4</div>
      <div class="step-body">
        <strong>Play Tricks</strong>
        <p>Forehand leads first. Play clockwise. <strong>Follow suit if you can.</strong> Jacks belong to the trump suit — not their printed suit. Highest trump wins; else highest card of suit led wins.</p>
        <p style="margin-top:5px;">Winner of each trick leads the next. Skat cards go to Declarer's count at end (even if not looked at), except in Null.</p>
      </div>
    </div>

    <div class="step">
      <div class="step-num">5</div>
      <div class="step-body">
        <strong>Calculate Score</strong>
        <p>Count Declarer's card points (61+ to win). Calculate game value. Compare to bid. Win → add value. Lose → subtract 2× value. Overbid → subtract 2× next valid multiple.</p>
      </div>
    </div>

    <div class="section-title">Key Rules to Remember</div>
    <div class="card">
      <div class="tip-item">
        <span class="tip-icon">🃏</span>
        <span>Jacks are always trump, regardless of which suit is declared. The J♠ is NOT a spade in a spade-led trick — it's a trump.</span>
      </div>
      <div class="tip-item">
        <span class="tip-icon">⚠️</span>
        <span>The Skat cards are counted by the Declarer at the end — even if they were never opened. (Null is the exception.)</span>
      </div>
      <div class="tip-item">
        <span class="tip-icon">📢</span>
        <span>Announced Schneider / Schwarz / Open all require <strong>Hand</strong> (no Skat). Announcing and failing loses you those extra multipliers too.</span>
      </div>
      <div class="tip-item">
        <span class="tip-icon">🎯</span>
        <span>Winning 90+ card points <em>automatically</em> scores Schneider even if not announced (+1 mult). Opponents taking ≤30 card points also counts as Schneider — for them.</span>
      </div>
      <div class="tip-item">
        <span class="tip-icon">🔢</span>
        <span>The minimum bid is <strong>18</strong>. If all three players pass, play Ramsch — jacks are trump, everyone plays solo, and whoever takes the most card points loses.</span>
      </div>
    </div>
  </div>

</main>

<!-- Navigation -->
<nav>
  <button class="active" data-tab="calc" onclick="switchTab('calc', this)">
    <span class="icon">🧮</span>Calculator
  </button>
  <button data-tab="cards" onclick="switchTab('cards', this)">
    <span class="icon">🃏</span>Cards
  </button>
  <button data-tab="scores" onclick="switchTab('scores', this)">
    <span class="icon">✖</span>Scores
  </button>
  <button data-tab="play" onclick="switchTab('play', this)">
    <span class="icon">▶</span>How to Play
  </button>
</nav>

<script>
  // ─── TAB SWITCHING ───
  function switchTab(id, btn) {
    document.querySelectorAll('.tab-panel').forEach(p => p.classList.remove('active'));
    document.querySelectorAll('nav button').forEach(b => b.classList.remove('active'));
    document.getElementById('panel-' + id).classList.add('active');
    btn.classList.add('active');
  }

  // ─── CALCULATOR STATE ───
  let state = {
    suit: 'diamonds',
    base: 9,
    withAgainst: 'with',
    matadors: 1,
    hand: false,
    schneider: false,
    annSchneider: false,
    schwarz: false,
    annSchwarz: false,
    open: false,
    isNull: false,
    nullVariant: 'closed',
    nullHand: 'no'
  };

  // Suit buttons
  document.querySelectorAll('#suit-btns button').forEach(btn => {
    btn.addEventListener('click', () => {
      document.querySelectorAll('#suit-btns button').forEach(b => b.classList.remove('selected'));
      btn.classList.add('selected');
      state.suit = btn.dataset.suit;
      state.base = parseInt(btn.dataset.base);
      state.isNull = (state.suit === 'null');
      document.getElementById('suit-options').style.display = state.isNull ? 'none' : 'block';
      document.getElementById('null-options').style.display = state.isNull ? 'block' : 'none';
      document.getElementById('null-warn').style.display = state.isNull ? 'block' : 'none';
      updateMaxMat();
      calculate();
    });
  });

  // With/Against
  document.querySelectorAll('#wa-btns button').forEach(btn => {
    btn.addEventListener('click', () => {
      document.querySelectorAll('#wa-btns button').forEach(b => b.classList.remove('selected'));
      btn.classList.add('selected');
      state.withAgainst = btn.dataset.wa;
      calculate();
    });
  });

  // Matador stepper
  document.getElementById('mat-minus').addEventListener('click', () => {
    if (state.matadors > 1) { state.matadors--; updateMatDisplay(); calculate(); }
  });
  document.getElementById('mat-plus').addEventListener('click', () => {
    let max = state.suit === 'grand' ? 4 : 11;
    if (state.matadors < max) { state.matadors++; updateMatDisplay(); calculate(); }
  });

  function updateMatDisplay() {
    document.getElementById('mat-display').textContent = state.matadors;
  }

  function updateMaxMat() {
    let max = state.suit === 'grand' ? 4 : 11;
    if (state.matadors > max) { state.matadors = max; updateMatDisplay(); }
  }

  // Checkboxes
  const cbs = {
    hand: 'cb-hand', schneider: 'cb-schneider', annSchneider: 'cb-ann-schneider',
    schwarz: 'cb-schwarz', annSchwarz: 'cb-ann-schwarz', open: 'cb-open'
  };

  Object.entries(cbs).forEach(([key, id]) => {
    document.getElementById(id).addEventListener('change', function() {
      state[key] = this.checked;

      // Cascading logic
      if (key === 'hand' && !this.checked) {
        // Uncheck announcements if hand removed
        state.annSchneider = false; document.getElementById('cb-ann-schneider').checked = false;
        state.annSchwarz = false; document.getElementById('cb-ann-schwarz').checked = false;
        state.open = false; document.getElementById('cb-open').checked = false;
      }
      if (key === 'annSchneider' && this.checked) {
        state.hand = true; document.getElementById('cb-hand').checked = true;
        state.schneider = true; document.getElementById('cb-schneider').checked = true;
      }
      if (key === 'annSchwarz' && this.checked) {
        state.hand = true; document.getElementById('cb-hand').checked = true;
        state.schwarz = true; document.getElementById('cb-schwarz').checked = true;
        state.schneider = true; document.getElementById('cb-schneider').checked = true;
        state.annSchneider = true; document.getElementById('cb-ann-schneider').checked = true;
      }
      if (key === 'open' && this.checked) {
        state.hand = true; document.getElementById('cb-hand').checked = true;
        state.schwarz = true; document.getElementById('cb-schwarz').checked = true;
        state.schneider = true; document.getElementById('cb-schneider').checked = true;
        state.annSchneider = true; document.getElementById('cb-ann-schneider').checked = true;
        state.annSchwarz = true; document.getElementById('cb-ann-schwarz').checked = true;
      }
      if (key === 'schwarz' && this.checked) {
        state.schneider = true; document.getElementById('cb-schneider').checked = true;
      }

      // Dim announced if no hand
      document.getElementById('lbl-ann-schneider').classList.toggle('dim', !state.hand);
      document.getElementById('lbl-ann-schwarz').classList.toggle('dim', !state.hand && !state.annSchneider);

      calculate();
    });
  });

  // Null variant buttons
  document.querySelectorAll('#null-variant-btns button').forEach(btn => {
    btn.addEventListener('click', () => {
      document.querySelectorAll('#null-variant-btns button').forEach(b => b.classList.remove('selected'));
      btn.classList.add('selected');
      state.nullVariant = btn.dataset.nv;
      calculate();
    });
  });

  document.querySelectorAll('#null-hand-btns button').forEach(btn => {
    btn.addEventListener('click', () => {
      document.querySelectorAll('#null-hand-btns button').forEach(b => b.classList.remove('selected'));
      btn.classList.add('selected');
      state.nullHand = btn.dataset.nh;
      calculate();
    });
  });

  // ─── CALCULATE ───
  function calculate() {
    let value, formula, breakdown, hint;

    if (state.isNull) {
      const map = {
        'closed-no': 23, 'closed-yes': 35,
        'open-no': 46, 'open-yes': 59
      };
      value = map[state.nullVariant + '-' + state.nullHand];
      formula = 'Null — flat value, no multipliers';
      let desc = state.nullVariant === 'open' ? 'Open' : 'Closed';
      if (state.nullHand === 'yes') desc += ' Hand';
      breakdown = 'Variant: ' + desc;
      hint = '⚠️ Take even one trick and you lose. No trumps. Jacks are NOT special — A K Q J 10 9 8 7.';
    } else {
      let bonuses = 0;
      if (state.hand) bonuses++;
      if (state.schneider) bonuses++;
      if (state.annSchneider) bonuses++;
      if (state.schwarz) bonuses++;
      if (state.annSchwarz) bonuses++;
      if (state.open) bonuses++;

      let mult = state.matadors + 1 + bonuses;
      value = state.base * mult;

      let waStr = state.withAgainst === 'with' ? 'with' : 'against';
      formula = `Base ${state.base} × (${state.matadors} mat + 1 game${bonuses ? ' + ' + bonuses + ' bonus' : ''}) = ${state.base}×${mult}`;

      let parts = [`Matadors: <span>${waStr} ${state.matadors}</span>`, `Game: <span>+1</span>`];
      if (state.hand) parts.push('Hand: <span>+1</span>');
      if (state.schneider) parts.push('Schneider: <span>+1</span>');
      if (state.annSchneider) parts.push('Ann. Schneider: <span>+1</span>');
      if (state.schwarz) parts.push('Schwarz: <span>+1</span>');
      if (state.annSchwarz) parts.push('Ann. Schwarz: <span>+1</span>');
      if (state.open) parts.push('Open: <span>+1</span>');
      parts.push(`Multiplier total: <span>${mult}</span>`);
      breakdown = parts.join('<br>');

      if (state.suit === 'grand') {
        hint = '♟ Grand: only the 4 Jacks are trump. Max matadors = 4 (with or against).';
      } else {
        let suitName = state.suit.charAt(0).toUpperCase() + state.suit.slice(1);
        hint = `🎯 Bid up to <strong style="color:var(--gold-light)">${value}</strong>. If you win the bid, you must reach at least ${value} game value when calculated — or lose double.`;
      }
    }

    document.getElementById('result-val').textContent = value;
    document.getElementById('result-formula').textContent = formula;
    document.getElementById('result-breakdown').innerHTML = breakdown;
    document.getElementById('hint-box').innerHTML = hint;
  }

  // Init
  calculate();
</script>
</body>
</html>
