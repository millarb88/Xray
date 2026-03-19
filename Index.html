<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="X-Ray">
<meta name="theme-color" content="#0a0a0f">
<title>Portfolio X-Ray</title>
<!-- Inline SVG icon as data URI for apple-touch-icon -->
<link rel="apple-touch-icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 180 180'%3E%3Crect width='180' height='180' rx='40' fill='%230a0a0f'/%3E%3Ctext x='90' y='115' font-size='90' text-anchor='middle' fill='%237c6af7'%3E✦%3C/text%3E%3C/svg%3E">
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Mono:wght@300;400;500&family=Syne:wght@400;600;700;800&display=swap');
  :root{
    --bg:#0a0a0f;--surface:#111118;--surface2:#1a1a24;--border:#2a2a3a;
    --accent:#7c6af7;--accent2:#f7c26a;--accent3:#6af7c2;
    --text:#e8e8f0;--muted:#6a6a80;--danger:#f76a6a;
    --pension:#f76ac2;--pension-dim:rgba(247,106,194,.15);--pension-border:rgba(247,106,194,.3);
    --isa:#6af7c2;--cash:#f7e06a;
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html,body{height:100%}
  body{background:var(--bg);color:var(--text);font-family:'DM Mono',monospace;min-height:100vh;
    padding-top:env(safe-area-inset-top);padding-bottom:env(safe-area-inset-bottom)}
  body::before{content:'';position:fixed;inset:0;
    background-image:linear-gradient(rgba(124,106,247,.03) 1px,transparent 1px),linear-gradient(90deg,rgba(124,106,247,.03) 1px,transparent 1px);
    background-size:40px 40px;pointer-events:none;z-index:0}
  .wrap{max-width:1100px;margin:0 auto;padding:36px 20px 60px;position:relative;z-index:1}
  h1{font-family:'Syne',sans-serif;font-size:2rem;font-weight:800;letter-spacing:-.02em}
  h1 span{color:var(--accent)}
  .subtitle{color:var(--muted);font-size:.72rem;margin-top:5px;text-transform:uppercase;letter-spacing:.05em}
  header{margin-bottom:32px}
  .card{background:var(--surface);border:1px solid var(--border);border-radius:16px;padding:22px;margin-bottom:18px}
  .card h3{font-family:'Syne',sans-serif;font-size:.82rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;margin-bottom:4px}
  .card-desc{color:var(--muted);font-size:.71rem;margin-bottom:14px;line-height:1.5}
  .hrow{display:grid;grid-template-columns:1fr 120px 76px auto;gap:7px;margin-bottom:7px;align-items:center}
  input[type=text],input[type=number],textarea,select{background:var(--surface2);border:1px solid var(--border);border-radius:8px;padding:9px 11px;color:var(--text);font-family:'DM Mono',monospace;font-size:.77rem;width:100%;transition:border-color .2s;-webkit-appearance:none}
  input:focus,textarea:focus,select:focus{outline:none;border-color:var(--accent)}
  input::placeholder,textarea::placeholder{color:var(--muted)}
  select option{background:var(--surface2)}
  textarea{resize:vertical;min-height:140px;line-height:1.6}
  .btn{background:var(--accent);color:#fff;border:none;border-radius:10px;padding:11px 20px;font-family:'Syne',sans-serif;font-weight:700;font-size:.82rem;cursor:pointer;transition:all .2s;display:inline-flex;align-items:center;gap:6px;-webkit-tap-highlight-color:transparent}
  .btn:active{filter:brightness(.9)}
  .btn-sm{background:transparent;border:1px solid var(--border);color:var(--muted);font-family:'DM Mono',monospace;font-size:.73rem;padding:7px 12px;border-radius:8px;cursor:pointer;transition:all .2s;-webkit-tap-highlight-color:transparent}
  .btn-sm:active{border-color:var(--accent);color:var(--accent)}
  .btn-pension{background:transparent;border:1px solid var(--pension-border);color:var(--pension);font-family:'DM Mono',monospace;font-size:.73rem;padding:7px 12px;border-radius:8px;cursor:pointer}
  .del{background:transparent;border:none;color:var(--muted);cursor:pointer;padding:4px 8px;font-size:.85rem;border-radius:6px;-webkit-tap-highlight-color:transparent}
  .del:active{color:var(--danger)}
  .btn-row{display:flex;gap:9px;margin-top:12px;flex-wrap:wrap;align-items:center}
  .go{width:100%;justify-content:center;padding:14px;font-size:.93rem;border-radius:12px;background:linear-gradient(135deg,var(--accent),#a06af7);box-shadow:0 4px 20px rgba(124,106,247,.3);margin-top:8px}
  .itabs{display:flex;gap:2px;background:var(--surface2);border-radius:12px;padding:4px;width:fit-content}
  .itab{padding:8px 18px;border-radius:9px;border:none;background:transparent;color:var(--muted);font-family:'DM Mono',monospace;font-size:.76rem;cursor:pointer;transition:all .2s;-webkit-tap-highlight-color:transparent}
  .itab.on{background:var(--accent);color:#fff}
  .panel{display:none}.panel.on{display:block}
  .err{background:rgba(247,106,106,.08);border:1px solid rgba(247,106,106,.25);border-radius:10px;padding:11px 14px;font-size:.72rem;color:var(--danger);margin-bottom:14px;display:none}
  .err.on{display:block}
  /* pension */
  .pension-card{background:var(--surface);border:1px solid var(--pension-border);border-radius:16px;padding:22px;margin-bottom:18px;position:relative;overflow:hidden}
  .pension-card::before{content:'PENSION';position:absolute;top:12px;right:14px;font-size:.58rem;font-family:'Syne',sans-serif;font-weight:700;letter-spacing:.1em;color:var(--pension);opacity:.4}
  .pension-card h3{font-family:'Syne',sans-serif;font-size:.82rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;margin-bottom:4px;color:var(--pension)}
  .pval-row{display:flex;gap:9px;align-items:center;margin-bottom:14px}
  .pval-row input{max-width:190px}
  .pf-edit-row{display:grid;grid-template-columns:1fr 76px 18px;gap:7px;align-items:center;margin-bottom:5px}
  .pf-edit-name{font-size:.7rem;color:var(--text);line-height:1.3}
  .pf-pct-total{font-size:.68rem;margin-top:9px;padding:5px 9px;border-radius:6px;display:inline-block}
  .pf-pct-total.ok{color:var(--accent3);background:rgba(106,247,194,.08);border:1px solid rgba(106,247,194,.2)}
  .pf-pct-total.bad{color:var(--danger);background:rgba(247,106,106,.08);border:1px solid rgba(247,106,106,.2)}
  .pf-bar-bg{height:2px;background:var(--border);border-radius:2px;margin-bottom:5px}
  .pf-bar-fill{height:100%;border-radius:2px;background:var(--pension)}
  /* results */
  #R{display:none}#R.on{display:block}
  .rtabs{display:flex;gap:2px;background:var(--surface2);border-radius:12px;padding:4px;margin-bottom:22px;width:fit-content}
  .rtab{padding:8px 18px;border-radius:9px;border:none;background:transparent;color:var(--muted);font-family:'DM Mono',monospace;font-size:.76rem;cursor:pointer;transition:all .2s}
  .rtab.on{background:var(--surface);color:var(--text);box-shadow:0 1px 6px rgba(0,0,0,.3)}
  .rpanel{display:none}.rpanel.on{display:block}
  .rtop{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:24px;flex-wrap:wrap;gap:10px}
  .rtop h2{font-family:'Syne',sans-serif;font-size:1.35rem;font-weight:800}
  .tbox .lbl{font-size:.62rem;color:var(--muted);text-transform:uppercase;letter-spacing:.06em}
  .tbox .val{font-family:'Syne',sans-serif;font-size:1.6rem;font-weight:800;color:var(--accent)}
  .rtop-breakdown{display:flex;gap:16px;align-items:center;flex-wrap:wrap;margin-top:3px}
  .rtop-sub{font-size:.66rem;color:var(--muted);display:flex;align-items:center;gap:5px}
  .dot{width:7px;height:7px;border-radius:50%;display:inline-block;flex-shrink:0}
  .igrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(158px,1fr));gap:12px;margin-bottom:22px}
  .ic{background:var(--surface);border:1px solid var(--border);border-radius:12px;padding:15px}
  .ic .ico{font-size:1.1rem;margin-bottom:6px;display:block}
  .ic .lbl{font-size:.6rem;color:var(--muted);text-transform:uppercase;letter-spacing:.07em;margin-bottom:2px}
  .ic .val{font-family:'Syne',sans-serif;font-size:1.05rem;font-weight:700}
  .ic .sub{font-size:.62rem;color:var(--muted);margin-top:2px}
  .tbl-wrap{background:var(--surface);border:1px solid var(--border);border-radius:14px;overflow:hidden;margin-bottom:20px;overflow-x:auto;-webkit-overflow-scrolling:touch}
  .tbl-wrap table{width:100%;border-collapse:collapse;white-space:nowrap}
  .tbl-wrap.clk tbody tr{cursor:pointer;-webkit-tap-highlight-color:transparent}
  th{padding:9px 11px;text-align:left;font-size:.59rem;text-transform:uppercase;letter-spacing:.07em;color:var(--muted);border-bottom:1px solid var(--border);background:var(--surface2)}
  td{padding:9px 11px;font-size:.73rem;border-bottom:1px solid rgba(42,42,58,.4)}
  tr:last-child td{border-bottom:none}
  .tbl-wrap.clk tbody tr:active td{background:rgba(124,106,247,.1)}
  .fn{font-family:'Syne',sans-serif;font-weight:600;font-size:.74rem}
  .tag{font-size:.59rem;padding:2px 6px;border-radius:10px;border:1px solid;white-space:nowrap;display:inline-block}
  .te{color:var(--accent);border-color:rgba(124,106,247,.3);background:rgba(124,106,247,.08)}
  .tf{color:var(--accent2);border-color:rgba(247,194,106,.3);background:rgba(247,194,106,.08)}
  .ts{color:var(--accent3);border-color:rgba(106,247,194,.3);background:rgba(106,247,194,.08)}
  .tp{color:var(--pension);border-color:var(--pension-border);background:var(--pension-dim)}
  .tc{color:var(--cash);border-color:rgba(247,224,106,.3);background:rgba(247,224,106,.07)}
  .cgrid3{display:grid;grid-template-columns:repeat(auto-fit,minmax(290px,1fr));gap:16px;margin-bottom:20px}
  .cc{background:var(--surface);border:1px solid var(--border);border-radius:14px;padding:18px}
  .cc h3{font-family:'Syne',sans-serif;font-size:.78rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;margin-bottom:2px}
  .cc>p{color:var(--muted);font-size:.62rem;margin-bottom:12px}
  .cw{position:relative;height:210px}
  .leg{margin-top:10px;max-height:220px;overflow-y:auto;padding-right:2px}
  .leg::-webkit-scrollbar{width:3px}
  .leg::-webkit-scrollbar-track{background:transparent}
  .leg::-webkit-scrollbar-thumb{background:var(--border);border-radius:2px}
  .li{display:flex;align-items:center;gap:6px;margin-bottom:5px;cursor:pointer;border-radius:6px;padding:3px 4px;margin-left:-4px;transition:background .15s;-webkit-tap-highlight-color:transparent}
  .li:active{background:rgba(124,106,247,.12)}
  .sw{width:7px;height:7px;border-radius:2px;flex-shrink:0}
  .bn{flex:1;font-size:.67rem;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;min-width:0}
  .lamt{font-size:.64rem;color:var(--muted);white-space:nowrap;flex-shrink:0}
  .lp{font-size:.65rem;color:var(--muted);width:34px;text-align:right;flex-shrink:0}
  .da{font-size:.56rem;color:var(--muted);flex-shrink:0}
  .sec-hdr{font-family:'Syne',sans-serif;font-size:.78rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;margin-bottom:9px;margin-top:2px}
  .sec-hdr span{font-size:.61rem;font-weight:400;color:var(--muted);text-transform:none;letter-spacing:0}
  .minibar{width:70px;height:3px;background:var(--border);border-radius:2px;display:inline-block;vertical-align:middle}
  .minibar-fill{height:100%;border-radius:2px;background:linear-gradient(90deg,var(--accent2),var(--accent))}
  .note{background:rgba(124,106,247,.06);border:1px solid rgba(124,106,247,.2);border-radius:10px;padding:12px 15px;font-size:.7rem;color:var(--muted);margin-bottom:18px;line-height:1.6}
  .note strong{color:var(--accent)}
  .pension-note{background:var(--pension-dim);border:1px solid var(--pension-border);border-radius:10px;padding:12px 15px;font-size:.7rem;color:var(--muted);margin-bottom:18px;line-height:1.6}
  .pension-note strong{color:var(--pension)}
  .split-wrap{background:var(--surface);border:1px solid var(--border);border-radius:14px;padding:18px;margin-bottom:20px}
  .split-wrap h3{font-family:'Syne',sans-serif;font-size:.78rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;margin-bottom:12px}
  .split-bar{display:flex;height:20px;border-radius:6px;overflow:hidden;gap:2px;margin-bottom:9px}
  .split-seg{transition:flex .5s ease;display:flex;align-items:center;justify-content:center;font-size:.58rem;font-family:'Syne',sans-serif;font-weight:700;min-width:0;overflow:hidden}
  .split-labels{display:flex;justify-content:space-between;font-size:.65rem;color:var(--muted)}
  /* performance chart */
  .perf-card{background:var(--surface);border:1px solid var(--border);border-radius:14px;padding:20px;margin-bottom:20px}
  .perf-card h3{font-family:'Syne',sans-serif;font-size:.78rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;margin-bottom:4px}
  .perf-card>p{color:var(--muted);font-size:.62rem;margin-bottom:14px;line-height:1.5}
  .perf-hw{position:relative;height:320px}
  .perf-stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(130px,1fr));gap:10px;margin-top:16px}
  .pstat{background:var(--surface2);border-radius:10px;padding:12px}
  .pstat .pl{font-size:.6rem;color:var(--muted);text-transform:uppercase;letter-spacing:.06em;margin-bottom:3px}
  .pstat .pv{font-family:'Syne',sans-serif;font-size:1.1rem;font-weight:700}
  .pstat .ps{font-size:.62rem;color:var(--muted);margin-top:2px}
  .pup{color:var(--accent3)}
  .pdn{color:var(--danger)}
  .range-btns{display:flex;gap:5px;margin-bottom:14px;flex-wrap:wrap}
  .rbtn{background:transparent;border:1px solid var(--border);color:var(--muted);font-family:'DM Mono',monospace;font-size:.7rem;padding:5px 10px;border-radius:7px;cursor:pointer;transition:all .2s}
  .rbtn.on{background:var(--accent);border-color:var(--accent);color:#fff}
  .perf-loading{display:flex;align-items:center;justify-content:center;height:200px;color:var(--muted);font-size:.75rem;gap:10px;flex-direction:column}
  .spinner{width:24px;height:24px;border:2px solid var(--border);border-top-color:var(--accent);border-radius:50%;animation:spin .7s linear infinite}
  @keyframes spin{to{transform:rotate(360deg)}}
  .perf-caveat{background:rgba(247,194,106,.06);border:1px solid rgba(247,194,106,.2);border-radius:9px;padding:10px 13px;font-size:.68rem;color:var(--muted);margin-bottom:14px;line-height:1.55}
  .perf-caveat strong{color:var(--accent2)}
  /* modal */
  .modal-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.78);z-index:1000;align-items:center;justify-content:center;padding:18px;backdrop-filter:blur(5px)}
  .modal-overlay.on{display:flex;animation:fadeIn .15s ease}
  @keyframes fadeIn{from{opacity:0}to{opacity:1}}
  .modal-box{background:var(--surface);border:1px solid var(--border);border-radius:18px;width:100%;max-width:520px;max-height:85vh;display:flex;flex-direction:column;box-shadow:0 24px 80px rgba(0,0,0,.6)}
  .modal-header{display:flex;justify-content:space-between;align-items:flex-start;padding:18px 20px 13px;border-bottom:1px solid var(--border);gap:10px}
  .modal-title{font-family:"Syne",sans-serif;font-size:1rem;font-weight:800}
  .modal-subtitle{font-size:.65rem;color:var(--muted);margin-top:3px;line-height:1.5}
  .modal-close{background:transparent;border:none;color:var(--muted);font-size:1.1rem;cursor:pointer;padding:4px 8px;border-radius:6px;flex-shrink:0;-webkit-tap-highlight-color:transparent}
  .modal-body{padding:16px 20px;overflow-y:auto;flex:1}
  .dr-row{display:grid;grid-template-columns:10px 1fr 64px 44px 68px;align-items:center;gap:7px;margin-bottom:11px}
  .dr-swatch{width:10px;height:10px;border-radius:2px;flex-shrink:0}
  .dr-name{font-size:.71rem;line-height:1.3;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
  .dr-bar-bg{height:4px;background:var(--border);border-radius:2px}
  .dr-bar-fill{height:100%;border-radius:2px;transition:width .5s ease}
  .dr-pct{font-size:.71rem;font-weight:600;text-align:right;white-space:nowrap}
  .dr-sub{font-size:.6rem;color:var(--muted);white-space:nowrap;text-align:right}
  .save-badge{font-size:.63rem;color:var(--accent3);background:rgba(106,247,194,.08);border:1px solid rgba(106,247,194,.2);border-radius:6px;padding:3px 9px;display:inline-flex;align-items:center;gap:4px}
  /* install prompt */
  .install-card{background:linear-gradient(135deg,rgba(124,106,247,.1),rgba(106,247,194,.05));border:1px solid var(--accent);border-radius:14px;padding:18px;margin-bottom:20px}
  .install-card h3{font-family:'Syne',sans-serif;font-size:.82rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;margin-bottom:10px;color:var(--accent)}
  .install-steps{list-style:none;padding:0}
  .install-steps li{font-size:.72rem;color:var(--muted);padding:6px 0;border-bottom:1px solid rgba(42,42,58,.4);display:flex;align-items:flex-start;gap:9px;line-height:1.5}
  .install-steps li:last-child{border-bottom:none}
  .step-n{font-family:'Syne',sans-serif;font-weight:700;color:var(--accent);font-size:.72rem;flex-shrink:0;width:16px}
  @media(max-width:600px){
    .hrow{grid-template-columns:1fr 95px 68px auto}
    .dr-row{grid-template-columns:10px 1fr 50px 38px}
    .dr-sub{display:none}
    .cgrid3{grid-template-columns:1fr}
    .perf-hw{height:250px}
  }
</style>
</head>
<body>
<div class="wrap">
  <header>
    <h1>Portfolio <span>X·Ray</span></h1>
    <div class="subtitle">Underlying exposure · historical performance · saves to this browser</div>
  </header>

  <!-- Install prompt (shown when accessed as web page, not standalone) -->

  <div class="install-card" id="installCard" style="display:none">
    <h3>📲 Install as iPhone App</h3>
    <ul class="install-steps">
      <li><span class="step-n">1</span><span>You need to host this file online first — drag it to <strong style="color:var(--text)">netlify.com/drop</strong> (free, instant). You'll get a URL like <em>random-name.netlify.app</em></span></li>
      <li><span class="step-n">2</span><span>Open that URL in <strong style="color:var(--text)">Safari</strong> on your iPhone</span></li>
      <li><span class="step-n">3</span><span>Tap the <strong style="color:var(--text)">Share button</strong> (box with arrow) at the bottom of Safari</span></li>
      <li><span class="step-n">4</span><span>Scroll down and tap <strong style="color:var(--text)">"Add to Home Screen"</strong></span></li>
      <li><span class="step-n">5</span><span>Tap <strong style="color:var(--text)">Add</strong> — the app icon will appear on your home screen. It opens full-screen, no browser bar</span></li>
    </ul>
    <button class="btn-sm" style="margin-top:10px;font-size:.68rem" onclick="document.getElementById('installCard').style.display='none'">Got it, dismiss</button>
  </div>

  <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px;flex-wrap:wrap;gap:8px">
    <div class="itabs">
      <button class="itab on" onclick="swTab('m')">Enter Holdings</button>
      <button class="itab" onclick="swTab('p')">Paste Text</button>
    </div>
    <span id="saveBadge" style="display:none" class="save-badge">💾 Saved</span>
  </div>

  <!-- Manual tab -->

  <div class="panel on" id="pm">
    <div class="card">
      <h3>ISA / GIA Holdings</h3>
      <p class="card-desc">Enter each fund or ETF name (or ticker), its current GBP value, and account type.</p>
      <div id="rows">
        <div class="hrow">
          <input type="text" placeholder="e.g. iShares Core MSCI World" class="fi" oninput="saveDraft()">
          <input type="number" placeholder="Value £" class="fv" min="0" oninput="saveDraft()">
          <select class="fa" onchange="saveDraft()"><option value="ISA">ISA</option><option value="GIA">GIA</option></select>
          <button class="del" onclick="delRow(this)">✕</button>
        </div>
      </div>
      <div class="btn-row">
        <button class="btn-sm" onclick="addRow()">+ Add holding</button>
        <button class="btn-sm" onclick="loadEx()">Load example</button>
      </div>
    </div>
    <div class="pension-card">
      <h3>🏦 Pension (LifeSight)</h3>
      <p class="card-desc" style="color:var(--muted)">Enter your total pension pot value. Edit the percentages to match your split — must total 100%.</p>
      <div class="pval-row">
        <input type="number" id="pensionVal" placeholder="Total pension value £" min="0" style="max-width:185px" oninput="saveDraft()">
      </div>
      <div id="pensionFunds"></div>
      <div id="pensionTotalEl" class="pf-pct-total ok">Total: 100.00%</div>
      <div class="btn-row" style="margin-top:9px">
        <button class="btn-pension" onclick="resetPensionPcts()">↺ Reset to LifeSight defaults</button>
      </div>
      <p style="font-size:.61rem;color:var(--muted);margin-top:11px;line-height:1.5">Geographic &amp; sector assumptions use publicly available benchmarks. Actual LifeSight allocations may differ.</p>
    </div>
    <div class="err" id="em"></div>
    <button class="btn go" onclick="goManual()">✦ Analyse My Portfolio</button>
  </div>

  <!-- Paste tab -->

  <div class="panel" id="pp">
    <div class="card">
      <h3>Paste Holdings</h3>
      <p class="card-desc">Copy your HL holdings list and paste below. One holding per line with value.<br><br>SWDA £24,200<br>VUKG £21,374</p>
      <textarea id="pt" placeholder="Paste your holdings here..." oninput="saveDraft()"></textarea>
    </div>
    <div class="pension-card">
      <h3>🏦 Pension (LifeSight)</h3>
      <p class="card-desc" style="color:var(--muted)">Optional — uses the splits from the Enter Holdings tab.</p>
      <div class="pval-row">
        <input type="number" id="pensionValP" placeholder="Total pension value £" min="0" style="max-width:185px">
      </div>
    </div>
    <div class="err" id="ep"></div>
    <button class="btn go" onclick="goPaste()">✦ Analyse My Portfolio</button>
  </div>

  <!-- Results -->

  <div id="R">
    <div class="rtop">
      <div>
        <h2>Portfolio X-Ray</h2>
        <div class="rtop-breakdown" id="rBreakdown"></div>
      </div>
      <div class="tbox"><div class="lbl">Total Value</div><div class="val" id="rTot"></div></div>
    </div>

```
<!-- Result sub-tabs -->
<div class="rtabs">
  <button class="rtab on" onclick="swRTab('xray')">X-Ray</button>
  <button class="rtab" onclick="swRTab('perf')">Performance</button>
</div>

<!-- X-Ray panel -->
<div class="rpanel on" id="rpXray">
  <div class="note" id="rNote"></div>
  <div class="pension-note" id="rPensionNote" style="display:none"></div>
  <div class="split-wrap" id="rSplitWrap" style="display:none">
    <h3>Wealth Split</h3>
    <div class="split-bar" id="rSplitBar"></div>
    <div class="split-labels" id="rSplitLabels"></div>
  </div>
  <div class="igrid" id="rIns"></div>
  <div class="cgrid3">
    <div class="cc"><h3>Country</h3><p>Geographic exposure — tap to drill down</p><div class="cw"><canvas id="cC"></canvas></div><div class="leg" id="lC"></div></div>
    <div class="cc"><h3>Region</h3><p>Grouped by region — tap to see countries</p><div class="cw"><canvas id="cR"></canvas></div><div class="leg" id="lR"></div></div>
    <div class="cc"><h3>Sector</h3><p>Industry exposure — tap to drill down</p><div class="cw"><canvas id="cS"></canvas></div><div class="leg" id="lS"></div></div>
  </div>
  <div class="sec-hdr">Top Single-Stock Concentrations <span>— tap to see funds holding it</span></div>
  <div class="tbl-wrap clk">
    <table>
      <thead><tr><th style="width:26px"></th><th>Company</th><th>Ticker</th><th>Exposure</th><th>% Port.</th><th style="color:var(--accent);font-size:.55rem">funds ▸</th></tr></thead>
      <tbody id="rUl"></tbody>
    </table>
  </div>
  <div class="sec-hdr">Fund Exposures <span>— ranked largest to smallest · tap row to see country breakdown</span></div>
  <div class="tbl-wrap clk">
    <table>
      <thead><tr><th style="width:26px"></th><th>Fund / ETF</th><th>Account</th><th>Type</th><th>Exposure</th><th>Value</th><th>% Port.</th><th style="color:var(--accent);font-size:.55rem">countries ▸</th></tr></thead>
      <tbody id="rFundExp"></tbody>
    </table>
  </div>
</div>

<!-- Performance panel -->
<div class="rpanel" id="rpPerf">
  <div class="perf-caveat">
    <strong>How this works:</strong> Uses Yahoo Finance price history for ETFs with known tickers. Assumes today's portfolio composition held unchanged throughout. Cash holdings use flat value. LifeSight pension funds have no public price data — pension value shown as a flat line at today's value. GBP prices used where available, USD otherwise (minor FX impact).
  </div>
  <div class="perf-card">
    <h3>Portfolio Value Over Time</h3>
    <p>Back-calculated using current holdings & weightings</p>
    <div class="range-btns" id="rangeBtns">
      <button class="rbtn" onclick="setRange('1Y')">1Y</button>
      <button class="rbtn" onclick="setRange('3Y')">3Y</button>
      <button class="rbtn" onclick="setRange('5Y')">5Y</button>
      <button class="rbtn on" onclick="setRange('MAX')">Max</button>
    </div>
    <div class="perf-hw" id="perfChartWrap">
      <div class="perf-loading" id="perfLoading">
        <div class="spinner"></div>
        <span>Loading price history…</span>
      </div>
      <canvas id="perfChart" style="display:none"></canvas>
    </div>
    <div class="perf-stats" id="perfStats"></div>
  </div>
</div>

<button class="btn-sm" onclick="reset()" style="margin-top:6px">← Analyse another portfolio</button>
```

  </div>
</div>

<!-- Modal -->

<div id="drillModal" class="modal-overlay" onclick="if(event.target===this)closeDrill()">
  <div class="modal-box">
    <div class="modal-header">
      <div style="min-width:0">
        <div class="modal-title" id="drillTitle"></div>
        <div class="modal-subtitle" id="drillSubtitle"></div>
      </div>
      <button class="modal-close" onclick="closeDrill()">✕</button>
    </div>
    <div class="modal-body" id="drillRows"></div>
  </div>
</div>

<script>
// ─────────────────────────────────────────────────────────────────────────────
// CONSTANTS
// ─────────────────────────────────────────────────────────────────────────────
const PAL=['#7c6af7','#f7c26a','#6af7c2','#f76a6a','#6ab4f7','#c26af7','#f7906a','#6af7a0','#f76ab0','#a0f76a','#f7e06a','#6ac6f7','#d4f76a','#80f7d0','#f76ac2'];
let _D=null, _perfChart=null, _perfRange='MAX', _rawPerfData=null;

// Map known fund names → Yahoo Finance tickers (GBP-quoted where possible)
const TICKER_MAP={
  'iShares Core MSCI World ETF':        'SWDA.L',
  'Vanguard FTSE 100 ETF':              'VUKE.L',
  'iShares MSCI India ETF':             'NDIA.L',
  'iShares Core MSCI EM IMI ETF':       'EMIM.L',
  'iShares S&P 500 GBP Hedged ETF':     'IGUS.L',
  'iShares Core MSCI Japan IMI ETF':    'IJPA.L',
  'Xtrackers Russell 2000 ETF':         'XRSG.L',
  'iShares NASDAQ 100 ETF':             'CNX1.L',
  'Invesco EURO STOXX 50 ETF':          'CSSX5E.L',
  'Vanguard FTSE 250 ETF':              'VMID.L',
  'iShares MSCI EM ex-China ETF':       'EMXC',
  'Xtrackers Stoxx Europe 600 ETF':     'XESC.L',
  'Vanguard FTSE All-World ETF':        'VWRL.L',
  'WS Amati Strategic Metals':          null,   // no liquid ticker
  'abrdn Sterling Money Market':        null,   // cash — flat
};

// Flags
const FLAGS={US:'🇺🇸',UK:'🇬🇧',JP:'🇯🇵',CN:'🇨🇳',IN:'🇮🇳',TW:'🇹🇼',KR:'🇰🇷',FR:'🇫🇷',DE:'🇩🇪',CH:'🇨🇭',NL:'🇳🇱',DK:'🇩🇰',SE:'🇸🇪',AU:'🇦🇺',CA:'🇨🇦',BR:'🇧🇷',SA:'🇸🇦',ZA:'🇿🇦',HK:'🇭🇰',BE:'🇧🇪',FI:'🇫🇮',IT:'🇮🇹',ES:'🇪🇸',NO:'🇳🇴',SG:'🇸🇬',NZ:'🇳🇿',CL:'🇨🇱',RU:'🇷🇺'};
const gf=ct=>FLAGS[ct]||'🌐';

// Region map
const REG_MAP={'United States':'North America','Canada':'North America','Mexico':'North America','United Kingdom':'Europe','France':'Europe','Germany':'Europe','Switzerland':'Europe','Netherlands':'Europe','Sweden':'Europe','Denmark':'Europe','Spain':'Europe','Italy':'Europe','Belgium':'Europe','Finland':'Europe','Norway':'Europe','Austria':'Europe','Portugal':'Europe','Ireland':'Europe','Poland':'Europe','Europe ex-UK':'Europe','Japan':'Asia Pacific','Australia':'Asia Pacific','New Zealand':'Asia Pacific','Hong Kong':'Asia Pacific','Singapore':'Asia Pacific','South Korea':'Asia Pacific','Taiwan':'Asia Pacific','China':'Emerging Markets','India':'Emerging Markets','Brazil':'Emerging Markets','Saudi Arabia':'Emerging Markets','South Africa':'Emerging Markets','Russia':'Emerging Markets','Chile':'Emerging Markets','Indonesia':'Emerging Markets','Malaysia':'Emerging Markets','Thailand':'Emerging Markets','Cash':'Cash / Bonds','Cash & Money Market':'Cash / Bonds','Fixed Income':'Cash / Bonds'};
const toReg=c=>REG_MAP[c]||'Other';

const CASH_SE=new Set(['Cash','Cash & Money Market','Fixed Income','Money Market']);
const isCash=fd=>fd.type==='Cash'||(fd.se&&fd.se.filter(([s])=>CASH_SE.has(s)).reduce((a,[,p])=>a+p,0)>=95);

// ─────────────────────────────────────────────────────────────────────────────
// LIFESIGHT DATA
// ─────────────────────────────────────────────────────────────────────────────
const LS_DEF=[{name:'LifeSight Equity',pct:34.42},{name:'Developed Market Equity (Hedged)',pct:24.19},{name:'Emerging Markets Equity',pct:22.56},{name:'Asia Pacific (ex Japan) Equity',pct:8.81},{name:'Japan Equity',pct:3.40},{name:'UK Equity',pct:3.39},{name:'Europe (ex UK) Equity',pct:3.23}];
const LS_DATA={'LifeSight Equity':{co:[['United States',62],['Japan',6],['United Kingdom',4],['China',4],['France',3],['Canada',3],['Switzerland',3],['Germany',2],['India',2],['Other',11]],se:[['Technology',22],['Financials',16],['Healthcare',12],['Consumer Discretionary',10],['Industrials',10],['Communication Services',8],['Consumer Staples',7],['Energy',5],['Materials',4],['Real Estate',3],['Utilities',3]],st:[['Apple','AAPL',4.0,'US'],['Microsoft','MSFT',3.6,'US'],['NVIDIA','NVDA',3.0,'US'],['Amazon','AMZN',2.4,'US'],['Meta','META',1.6,'US'],['Alphabet A','GOOGL',1.3,'US'],['Tesla','TSLA',0.9,'US'],['Samsung','005930',0.8,'KR'],['Eli Lilly','LLY',0.8,'US'],['TSMC','TSM',0.7,'TW']]},'Developed Market Equity (Hedged)':{co:[['United States',68],['Japan',7],['United Kingdom',4],['France',3],['Canada',3],['Switzerland',3],['Germany',3],['Australia',2],['Netherlands',2],['Other',5]],se:[['Technology',24],['Financials',15],['Healthcare',13],['Consumer Discretionary',11],['Industrials',10],['Communication Services',8],['Consumer Staples',7],['Energy',4],['Materials',4],['Real Estate',2],['Utilities',2]],st:[['Apple','AAPL',5.0,'US'],['Microsoft','MSFT',4.5,'US'],['NVIDIA','NVDA',3.8,'US'],['Amazon','AMZN',2.9,'US'],['Meta','META',2.0,'US'],['Alphabet A','GOOGL',1.6,'US'],['Broadcom','AVGO',1.3,'US'],['Tesla','TSLA',1.2,'US'],['Eli Lilly','LLY',1.1,'US'],['JPMorgan','JPM',1.0,'US']]},'Emerging Markets Equity':{co:[['China',27],['India',18],['Taiwan',14],['Brazil',7],['Saudi Arabia',5],['South Africa',4],['Other',25]],se:[['Technology',22],['Financials',20],['Consumer Discretionary',13],['Materials',8],['Energy',7],['Industrials',7],['Consumer Staples',6],['Healthcare',5],['Communication Services',5],['Other',7]],st:[['TSMC','TSM',7.2,'TW'],['Samsung','005930',4.5,'KR'],['Tencent','700',3.8,'CN'],['Alibaba','BABA',2.5,'CN'],['Reliance Industries','RELIANCE',1.9,'IN'],['HDFC Bank','HDFCBANK',1.6,'IN'],['Meituan','3690',1.4,'CN'],['Infosys','INFY',1.2,'IN'],['JD.com','JD',1.0,'CN'],['PDD Holdings','PDD',0.9,'CN']]},'Asia Pacific (ex Japan) Equity':{co:[['China',35],['India',20],['Taiwan',14],['South Korea',10],['Australia',8],['Hong Kong',7],['Other',6]],se:[['Technology',25],['Financials',22],['Consumer Discretionary',14],['Materials',9],['Energy',6],['Industrials',6],['Consumer Staples',6],['Healthcare',5],['Other',7]],st:[['TSMC','TSM',8.5,'TW'],['Samsung','005930',5.2,'KR'],['Tencent','700',4.5,'CN'],['Alibaba','BABA',3.0,'CN'],['BHP','BHP',2.5,'AU'],['HDFC Bank','HDFCBANK',2.2,'IN'],['Reliance Industries','RELIANCE',2.0,'IN'],['Meituan','3690',1.8,'CN'],['AIA Group','1299',1.5,'HK'],['ANZ Bank','ANZ',1.2,'AU']]},'Japan Equity':{co:[['Japan',100]],se:[['Industrials',22],['Consumer Discretionary',19],['Technology',15],['Financials',13],['Healthcare',8],['Materials',7],['Consumer Staples',6],['Communication Services',5],['Real Estate',3],['Energy',2]],st:[['Toyota','7203',5.5,'JP'],['Sony','6758',3.8,'JP'],['Keyence','6861',2.9,'JP'],['SoftBank','9984',2.8,'JP'],['Mitsubishi UFJ','8306',2.6,'JP'],['Recruit','6098',2.4,'JP'],['Shin-Etsu Chemical','4063',2.1,'JP'],['Daikin','6367',2.0,'JP'],['Fanuc','6954',1.9,'JP'],['Sumitomo Mitsui','8316',1.8,'JP']]},'UK Equity':{co:[['United Kingdom',100]],se:[['Financials',21],['Energy',15],['Consumer Staples',14],['Healthcare',12],['Industrials',11],['Materials',8],['Consumer Discretionary',7],['Communication Services',6],['Utilities',4],['Real Estate',2]],st:[['AstraZeneca','AZN',8.0,'UK'],['Shell','SHEL',7.5,'UK'],['HSBC','HSBA',5.8,'UK'],['Unilever','ULVR',4.6,'UK'],['BP','BP',4.4,'UK'],['Rio Tinto','RIO',3.7,'UK'],['GSK','GSK',3.4,'UK'],['Diageo','DGE',3.1,'UK'],['Lloyds','LLOY',2.8,'UK'],['BAT','BATS',2.7,'UK']]},'Europe (ex UK) Equity':{co:[['France',23],['Switzerland',18],['Germany',17],['Netherlands',10],['Sweden',7],['Denmark',6],['Spain',5],['Italy',5],['Other',9]],se:[['Healthcare',18],['Industrials',16],['Consumer Staples',14],['Financials',13],['Consumer Discretionary',11],['Technology',10],['Materials',7],['Energy',5],['Communication Services',4],['Utilities',2]],st:[['Novo Nordisk','NOVO',8.5,'DK'],['ASML','ASML',7.2,'NL'],['Nestle','NESN',6.0,'CH'],['LVMH','MC',5.5,'FR'],['Roche','ROG',4.5,'CH'],['Novartis','NOVN',4.0,'CH'],['SAP','SAP',3.8,'DE'],['Schneider Electric','SU',3.5,'FR'],['Linde','LIN',3.2,'DE'],['Sanofi','SAN',3.0,'FR']]}};

// ─────────────────────────────────────────────────────────────────────────────
// FUND DB
// ─────────────────────────────────────────────────────────────────────────────
const DB=[
{k:['abrdn sterling','sterling money market','money market class'],name:'abrdn Sterling Money Market',type:'Cash',co:[['Cash',100]],se:[['Cash & Money Market',100]],st:[]},
{k:['amati','strategic metals'],name:'WS Amati Strategic Metals',type:'Fund',co:[['Canada',28],['United Kingdom',18],['Australia',16],['United States',12],['Chile',8],['Other',18]],se:[['Materials',85],['Energy',8],['Industrials',7]],st:[['Wheaton Precious Metals','WPM',6.5,'CA'],['Sandstorm Gold','SSL',5.2,'CA'],['Hochschild Mining','HOC',4.8,'UK'],['Pan American Silver','PAAS',4.5,'CA'],['Adriatic Metals','ADT1',4.0,'UK']]},
{k:['euro stoxx 50','eurostoxx 50','invesco markets plc euro'],name:'Invesco EURO STOXX 50 ETF',type:'ETF',co:[['France',36],['Germany',26],['Netherlands',14],['Spain',10],['Italy',8],['Belgium',4],['Finland',2]],se:[['Consumer Staples',17],['Industrials',16],['Technology',15],['Financials',14],['Healthcare',11],['Consumer Discretionary',10],['Energy',7],['Materials',5],['Utilities',5]],st:[['LVMH','MC',7.2,'FR'],['ASML','ASML',6.8,'NL'],['Linde','LIN',5.5,'DE'],['TotalEnergies','TTE',5.2,'FR'],['SAP','SAP',5.1,'DE'],['Sanofi','SAN',4.8,'FR'],['Siemens','SIE',4.2,'DE'],['Air Liquide','AI',3.8,'FR'],['Schneider Electric','SU',3.5,'FR'],['Airbus','AIR',3.2,'FR']]},
{k:['msci japan imi','core msci japan','japan imi'],name:'iShares Core MSCI Japan IMI ETF',type:'ETF',co:[['Japan',100]],se:[['Industrials',22],['Consumer Discretionary',19],['Technology',15],['Financials',13],['Healthcare',8],['Materials',7],['Consumer Staples',6],['Communication Services',5],['Real Estate',3],['Energy',2]],st:[['Toyota','7203',5.5,'JP'],['Sony','6758',3.8,'JP'],['Keyence','6861',2.9,'JP'],['SoftBank','9984',2.8,'JP'],['Mitsubishi UFJ','8306',2.6,'JP'],['Recruit Holdings','6098',2.4,'JP'],['Shin-Etsu Chemical','4063',2.1,'JP'],['Daikin','6367',2.0,'JP'],['Fanuc','6954',1.9,'JP'],['Sumitomo Mitsui','8316',1.8,'JP']]},
{k:['core msci world','msci world ucits etf usd','swda'],name:'iShares Core MSCI World ETF',type:'ETF',co:[['United States',67],['Japan',6.5],['United Kingdom',4.2],['France',3.2],['Canada',3.1],['Switzerland',2.8],['Germany',2.5],['Australia',2.2],['Netherlands',1.4],['Other',7.1]],se:[['Technology',23.5],['Financials',15.2],['Healthcare',12.8],['Consumer Discretionary',10.5],['Industrials',10.2],['Communication Services',8.1],['Consumer Staples',7.0],['Energy',4.5],['Materials',4.0],['Real Estate',2.6],['Utilities',1.6]],st:[['Apple','AAPL',4.8,'US'],['Microsoft','MSFT',4.2,'US'],['NVIDIA','NVDA',3.6,'US'],['Amazon','AMZN',2.8,'US'],['Meta','META',1.9,'US'],['Alphabet A','GOOGL',1.5,'US'],['Broadcom','AVGO',1.2,'US'],['Tesla','TSLA',1.1,'US'],['Eli Lilly','LLY',1.0,'US'],['JPMorgan','JPM',0.9,'US']]},
{k:['msci india','iind'],name:'iShares MSCI India ETF',type:'ETF',co:[['India',100]],se:[['Financials',26.5],['Technology',18.2],['Consumer Discretionary',12.8],['Energy',10.5],['Materials',8.2],['Industrials',7.5],['Consumer Staples',6.8],['Healthcare',5.2],['Communication Services',4.3]],st:[['Reliance Industries','RELIANCE',10.2,'IN'],['HDFC Bank','HDFCBANK',8.5,'IN'],['ICICI Bank','ICICIBANK',6.8,'IN'],['Infosys','INFY',5.9,'IN'],['TCS','TCS',5.2,'IN'],['L&T','LT',3.8,'IN'],['Axis Bank','AXISBANK',3.2,'IN'],['HUL','HINDUNILVR',2.9,'IN'],['ITC','ITC',2.8,'IN'],['Bajaj Finance','BAJFINANCE',2.5,'IN']]},
{k:['msci emerging markets imi','core msci emerging','emerging markets imi'],name:'iShares Core MSCI EM IMI ETF',type:'ETF',co:[['China',27],['India',18],['Taiwan',16],['South Korea',12],['Brazil',5],['Saudi Arabia',4],['South Africa',3],['Other',15]],se:[['Technology',22],['Financials',20],['Consumer Discretionary',13],['Materials',8],['Energy',7],['Industrials',7],['Consumer Staples',6],['Healthcare',5],['Communication Services',5],['Other',7]],st:[['TSMC','TSM',7.2,'TW'],['Samsung','005930',4.5,'KR'],['Tencent','700',3.8,'CN'],['Alibaba','BABA',2.5,'CN'],['Reliance Industries','RELIANCE',1.9,'IN'],['HDFC Bank','HDFCBANK',1.6,'IN'],['Meituan','3690',1.4,'CN'],['Infosys','INFY',1.2,'IN'],['JD.com','JD',1.0,'CN'],['PDD Holdings','PDD',0.9,'CN']]},
{k:['s&p 500 gbp hedged','sp500 gbp','s&p 500 gbp'],name:'iShares S&P 500 GBP Hedged ETF',type:'ETF',co:[['United States',100]],se:[['Technology',29],['Financials',13],['Healthcare',13],['Consumer Discretionary',10],['Industrials',9],['Communication Services',8],['Consumer Staples',6],['Energy',4],['Materials',3],['Real Estate',3],['Utilities',2]],st:[['Apple','AAPL',7.2,'US'],['Microsoft','MSFT',6.5,'US'],['NVIDIA','NVDA',5.8,'US'],['Amazon','AMZN',4.0,'US'],['Meta','META',2.8,'US'],['Alphabet A','GOOGL',2.2,'US'],['Alphabet C','GOOG',1.9,'US'],['Berkshire Hathaway','BRK.B',1.7,'US'],['Broadcom','AVGO',1.6,'US'],['Eli Lilly','LLY',1.5,'US']]},
{k:['msci em ex china','em ex china'],name:'iShares MSCI EM ex-China ETF',type:'ETF',co:[['India',26],['Taiwan',24],['South Korea',18],['Brazil',8],['Saudi Arabia',6],['South Africa',5],['Other',13]],se:[['Technology',28],['Financials',22],['Consumer Discretionary',12],['Materials',9],['Energy',8],['Industrials',8],['Healthcare',6],['Consumer Staples',5],['Other',2]],st:[['TSMC','TSM',11.2,'TW'],['Samsung','005930',7.0,'KR'],['Reliance Industries','RELIANCE',3.2,'IN'],['HDFC Bank','HDFCBANK',2.8,'IN'],['SK Hynix','000660',2.2,'KR'],['Infosys','INFY',2.0,'IN'],['ICICI Bank','ICICIBANK',1.8,'IN'],['Vale','VALE',1.6,'BR'],['Saudi Aramco','2222',1.5,'SA'],['TCS','TCS',1.4,'IN']]},
{k:['nasdaq 100','nasdaq100'],name:'iShares NASDAQ 100 ETF',type:'ETF',co:[['United States',90],['Netherlands',2.5],['United Kingdom',1.5],['Other',6]],se:[['Technology',51],['Communication Services',16],['Consumer Discretionary',14],['Healthcare',7],['Industrials',5],['Consumer Staples',4],['Financials',2],['Other',1]],st:[['Apple','AAPL',9.0,'US'],['Microsoft','MSFT',8.5,'US'],['NVIDIA','NVDA',8.0,'US'],['Amazon','AMZN',5.5,'US'],['Meta','META',4.8,'US'],['Alphabet A','GOOGL',3.5,'US'],['Alphabet C','GOOG',3.0,'US'],['Tesla','TSLA',3.0,'US'],['Broadcom','AVGO',2.8,'US'],['Costco','COST',1.8,'US']]},
{k:['ftse 100 ucits','vanguard funds plc ftse 100','vukg'],name:'Vanguard FTSE 100 ETF',type:'ETF',co:[['United Kingdom',100]],se:[['Financials',21.5],['Energy',15.2],['Consumer Staples',13.8],['Healthcare',12.2],['Industrials',10.5],['Materials',8.2],['Consumer Discretionary',7.0],['Communication Services',5.8],['Utilities',3.5],['Real Estate',2.3]],st:[['AstraZeneca','AZN',8.2,'UK'],['Shell','SHEL',7.8,'UK'],['HSBC','HSBA',5.9,'UK'],['Unilever','ULVR',4.8,'UK'],['BP','BP',4.5,'UK'],['Rio Tinto','RIO',3.8,'UK'],['GSK','GSK',3.5,'UK'],['Diageo','DGE',3.2,'UK'],['Lloyds','LLOY',2.9,'UK'],['BAT','BATS',2.8,'UK']]},
{k:['ftse 250','vanguard funds plc ftse 250'],name:'Vanguard FTSE 250 ETF',type:'ETF',co:[['United Kingdom',100]],se:[['Financials',25],['Industrials',20],['Consumer Discretionary',16],['Real Estate',10],['Healthcare',8],['Technology',7],['Consumer Staples',6],['Materials',4],['Energy',3],['Utilities',1]],st:[['3i Group','III',2.8,'UK'],['Intermediate Capital','ICP',1.9,'UK'],['Beazley','BEZ',1.8,'UK'],['Spirent Comms','SPT',1.5,'UK'],['Watches of Switzerland','WOSG',1.4,'UK'],['Drax Group','DRX',1.3,'UK'],['Hiscox','HSX',1.2,'UK'],['Bellway','BWY',1.1,'UK'],['Rightmove','RMV',1.1,'UK'],['Hilton Food Group','HFG',1.0,'UK']]},
{k:['russell 2000','xrsg'],name:'Xtrackers Russell 2000 ETF',type:'ETF',co:[['United States',100]],se:[['Financials',17.5],['Healthcare',16.2],['Industrials',15.8],['Consumer Discretionary',12.5],['Technology',11.2],['Energy',6.5],['Materials',5.8],['Real Estate',5.5],['Consumer Staples',4.0],['Utilities',3.5],['Communication Services',1.5]],st:[['Sprouts Farmers','SFM',0.5,'US'],['Chord Energy','CHRD',0.4,'US'],['Fabrinet','FN',0.4,'US'],['Applied Industrial','AIT',0.4,'US'],['Onto Innovation','ONTO',0.3,'US']]},
{k:['stoxx europe 600','stoxx600','europe 600'],name:'Xtrackers Stoxx Europe 600 ETF',type:'ETF',co:[['United Kingdom',23],['France',17],['Switzerland',14],['Germany',13],['Netherlands',7],['Sweden',5],['Denmark',4],['Spain',4],['Italy',4],['Other',9]],se:[['Financials',17],['Industrials',15],['Healthcare',14],['Consumer Discretionary',11],['Technology',10],['Consumer Staples',10],['Energy',6],['Materials',6],['Communication Services',5],['Utilities',4],['Real Estate',2]],st:[['Novo Nordisk','NOVO',3.8,'DK'],['ASML','ASML',3.5,'NL'],['Nestle','NESN',3.2,'CH'],['LVMH','MC',2.8,'FR'],['AstraZeneca','AZN',2.6,'UK'],['Shell','SHEL',2.4,'UK'],['Roche','ROG',2.2,'CH'],['Novartis','NOVN',2.0,'CH'],['HSBC','HSBA',1.9,'UK'],['Schneider Electric','SU',1.8,'FR']]},
{k:['vwrl','ftse all-world','all world'],name:'Vanguard FTSE All-World ETF',type:'ETF',co:[['United States',62],['Japan',5.8],['United Kingdom',3.9],['China',3.5],['France',3.0],['Canada',2.9],['Switzerland',2.6],['Germany',2.3],['India',2.1],['Other',11.9]],se:[['Technology',21.5],['Financials',15.8],['Healthcare',11.5],['Consumer Discretionary',10.2],['Industrials',10.0],['Communication Services',7.8],['Consumer Staples',7.2],['Energy',5.0],['Materials',4.2],['Real Estate',2.8],['Utilities',4.0]],st:[['Apple','AAPL',4.1,'US'],['Microsoft','MSFT',3.8,'US'],['NVIDIA','NVDA',3.2,'US'],['Amazon','AMZN',2.5,'US'],['Meta','META',1.7,'US'],['Alphabet A','GOOGL',1.4,'US'],['Tesla','TSLA',1.0,'US'],['Samsung','005930',0.9,'KR'],['Eli Lilly','LLY',0.9,'US'],['TSMC','TSM',0.8,'TW']]},
];

function matchFund(name){
  const n=name.toLowerCase();
  for(const f of DB) if(f.k.some(k=>n.includes(k))) return f;
  if(n.includes('money market')||n.includes('cash fund')||(n.includes('cash')&&!n.includes('cashflow')))
    return {name,type:'Cash',co:[['Cash',100]],se:[['Cash & Money Market',100]],st:[],generic:true};
  if(n.includes('bond')||n.includes('gilt')||n.includes('fixed income'))
    return {name,type:'Fund',co:[['Cash',100]],se:[['Fixed Income',100]],st:[],generic:true};
  if(n.includes('s&p 500')||n.includes('sp500'))
    return {name,type:'ETF',co:[['United States',100]],se:[['Technology',29],['Financials',13],['Healthcare',13],['Consumer Discretionary',10],['Industrials',9],['Other',26]],st:[],generic:true};
  if(n.includes('japan')||n.includes('nikkei'))
    return {name,type:'ETF',co:[['Japan',100]],se:[['Industrials',22],['Consumer Discretionary',19],['Technology',15],['Financials',13],['Other',31]],st:[],generic:true};
  if(n.includes('china'))
    return {name,type:'ETF',co:[['China',100]],se:[['Technology',30],['Consumer Discretionary',20],['Financials',18],['Communication Services',12],['Other',20]],st:[],generic:true};
  if(n.includes('emerg')||n.includes('developing'))
    return {name,type:'ETF',co:[['China',27],['India',18],['Taiwan',14],['South Korea',12],['Other',29]],se:[['Technology',22],['Financials',20],['Consumer Discretionary',13],['Other',45]],st:[],generic:true};
  if(n.includes('uk ')||n.includes('ftse 100')||n.includes('united kingdom')||n.includes('britain'))
    return {name,type:'ETF',co:[['United Kingdom',100]],se:[['Financials',22],['Energy',15],['Consumer Staples',14],['Healthcare',12],['Industrials',10],['Other',27]],st:[],generic:true};
  if(n.includes('europe')||n.includes('european'))
    return {name,type:'ETF',co:[['United Kingdom',23],['France',18],['Germany',14],['Switzerland',13],['Netherlands',8],['Other',24]],se:[['Financials',17],['Industrials',15],['Healthcare',14],['Consumer Discretionary',11],['Other',43]],st:[],generic:true};
  return {name,type:'Fund',co:[['United States',65],['Europe ex-UK',15],['Japan',7],['United Kingdom',5],['Other',8]],se:[['Technology',22],['Financials',16],['Healthcare',13],['Consumer Discretionary',10],['Industrials',10],['Other',29]],st:[],generic:true};
}

// ─────────────────────────────────────────────────────────────────────────────
// PENSION UI
// ─────────────────────────────────────────────────────────────────────────────
let PS=LS_DEF.map(f=>({...f}));
function renderPensionUI(){
  document.getElementById('pensionFunds').innerHTML=PS.map((f,i)=>`
    <div class="pf-edit-row">
      <span class="pf-edit-name">${f.name}</span>
      <input type="number" step="0.01" min="0" max="100" value="${f.pct.toFixed(2)}" oninput="updPS(${i},this.value)" style="padding:6px 8px;font-size:.71rem;text-align:right">
      <span style="font-size:.68rem;color:var(--muted)">%</span>
    </div>
    <div class="pf-bar-bg"><div class="pf-bar-fill" style="width:${Math.min(100,f.pct/35*100)}%"></div></div>
  `).join('');
  updPSTotal();
}
function updPS(i,v){PS[i].pct=parseFloat(v)||0;updPSTotal();saveDraft();}
function updPSTotal(){
  const t=PS.reduce((s,f)=>s+f.pct,0);
  const el=document.getElementById('pensionTotalEl');
  el.textContent=`Total: ${t.toFixed(2)}%`;
  el.className='pf-pct-total '+(Math.abs(t-100)<0.05?'ok':'bad');
}
function resetPensionPcts(){PS=LS_DEF.map(f=>({...f}));renderPensionUI();saveDraft();}
function getPensionH(id){
  const v=parseFloat(document.getElementById(id)?.value)||0;
  if(!v) return [];
  const tot=PS.reduce((s,f)=>s+f.pct,0);
  return PS.map(f=>{
    const fd=LS_DATA[f.name]||{co:[['Other',100]],se:[],st:[]};
    return {name:f.name,value:+(v*f.pct/tot).toFixed(2),acct:'Pension',isPension:true,co:fd.co,se:fd.se,st:fd.st};
  });
}

// ─────────────────────────────────────────────────────────────────────────────
// AGGREGATE
// ─────────────────────────────────────────────────────────────────────────────
function agg(holdings){
  const total=holdings.reduce((s,h)=>s+h.value,0);
  const CM={},SM={},RM={},STM={},coD={},seD={},reD={},fundCo={};
  const generics=[];
  holdings.forEach(h=>{
    let fd;
    if(h.isPension){fd={name:h.name,type:'Pension',co:h.co,se:h.se,st:h.st};}
    else{fd=matchFund(h.name);h.type=fd.type;if(fd.generic)generics.push(h.name.split(' ').slice(0,4).join(' '));}
    h.fd=fd;
    const cash=isCash(fd),w=h.value/total,sn=fd.name||h.name,acct=h.acct||'ISA';
    fundCo[sn]={countries:cash?[{country:'Cash',fundPct:100,pp:+(100*w).toFixed(2)}]:fd.co.map(([c,p])=>({country:c,fundPct:p,pp:+(p*w).toFixed(2)})),acct,value:h.value,type:h.type||fd.type,cash};
    function addD(map,k,v){if(!map[k])map[k]=[];map[k].push(v);}
    function addRD(map,rg,c,contrib){if(!map[rg])map[rg]=[];const ex=map[rg].find(x=>x.country===c);if(ex)ex.contribution=+(ex.contribution+contrib).toFixed(2);else map[rg].push({country:c,contribution:+contrib.toFixed(2)});}
    if(cash){
      CM['Cash']=(CM['Cash']||0)+100*w;addD(coD,'Cash',{name:sn,contribution:+(100*w).toFixed(2),fundPct:100,acct});
      RM['Cash / Bonds']=(RM['Cash / Bonds']||0)+100*w;addRD(reD,'Cash / Bonds','Cash',100*w);
      fd.se.forEach(([s,p])=>{SM[s]=(SM[s]||0)+p*w;addD(seD,s,{name:sn,contribution:+(p*w).toFixed(2),fundPct:p,acct});});
    }else{
      fd.co.forEach(([c,p])=>{CM[c]=(CM[c]||0)+p*w;addD(coD,c,{name:sn,contribution:+(p*w).toFixed(2),fundPct:p,acct});const rg=toReg(c);RM[rg]=(RM[rg]||0)+p*w;addRD(reD,rg,c,p*w);});
      fd.se.forEach(([s,p])=>{SM[s]=(SM[s]||0)+p*w;addD(seD,s,{name:sn,contribution:+(p*w).toFixed(2),fundPct:p,acct});});
      (fd.st||[]).forEach(([n,t,p,ct])=>{if(!STM[n])STM[n]={n,t,ct,p:0,funds:[]};STM[n].p+=p*w/100;STM[n].funds.push({name:sn,contribution:+(p*w/100).toFixed(3),fundPct:p,acct});});
    }
  });
  Object.values(coD).forEach(a=>a.sort((a,b)=>b.contribution-a.contribution));
  Object.values(seD).forEach(a=>a.sort((a,b)=>b.contribution-a.contribution));
  Object.values(reD).forEach(a=>a.sort((a,b)=>b.contribution-a.contribution));
  const co=Object.entries(CM).map(([c,p])=>({c,p:+p.toFixed(1)})).sort((a,b)=>b.p-a.p);
  const se=Object.entries(SM).map(([s,p])=>({s,p:+p.toFixed(1)})).sort((a,b)=>b.p-a.p);
  const re=Object.entries(RM).map(([r,p])=>({r,p:+p.toFixed(1)})).sort((a,b)=>b.p-a.p);
  const st=Object.values(STM).map(x=>({...x,p:+(x.p*100).toFixed(2)})).sort((a,b)=>b.p-a.p).slice(0,20);
  const us=CM['United States']||0,top=holdings.slice().sort((a,b)=>b.value-a.value)[0];
  const penTotal=holdings.filter(h=>h.acct==='Pension').reduce((s,h)=>s+h.value,0);
  const isaTotal=holdings.filter(h=>h.acct!=='Pension').reduce((s,h)=>s+h.value,0);
  const note=generics.length?'Some holdings used estimated allocations: '+generics.slice(0,3).join('; ')+'. Others use known data.':'All holdings matched to known fund data.';
  return {holdings:holdings.map(h=>({name:h.name,value:h.value,type:h.type||h.fd?.type,acct:h.acct||'ISA'})),co,se,re,st,total,coD,seD,reD,fundCo,penTotal,isaTotal,ins:{us:+us.toFixed(1),topPct:+(top.value/total*100).toFixed(1),topName:top.name.length>34?top.name.slice(0,34)+'…':top.name,n:holdings.length,topSec:se[0]?.s||'—',topSecP:se[0]?.p||0},note};
}

// ─────────────────────────────────────────────────────────────────────────────
// PERFORMANCE CHART
// ─────────────────────────────────────────────────────────────────────────────
async function fetchHistory(ticker){
  // Use a public CORS proxy to reach Yahoo Finance
  const proxy='https://query1.finance.yahoo.com/v8/finance/chart/';
  const url=`${proxy}${encodeURIComponent(ticker)}?interval=1wk&range=20y`;
  try{
    const r=await fetch(url,{headers:{'Accept':'application/json'}});
    if(!r.ok) return null;
    const j=await r.json();
    const res=j?.chart?.result?.[0];
    if(!res) return null;
    const ts=res.timestamps||[];
    const closes=res.indicators?.adjclose?.[0]?.adjclose||res.indicators?.quote?.[0]?.close||[];
    const out={};
    ts.forEach((t,i)=>{if(closes[i]!=null)out[t*1000]=closes[i];});
    return out;
  }catch(e){return null;}
}

async function loadPerformance(){
  if(!_D) return;
  const perfWrap=document.getElementById('perfChartWrap');
  const loading=document.getElementById('perfLoading');
  const canvas=document.getElementById('perfChart');
  loading.style.display='flex';canvas.style.display='none';
  document.getElementById('perfStats').innerHTML='';

  // Build list of holdings with tickers
  // Match each holding name → ticker
  const jobs=_D.holdings.map(h=>{
    const fd=matchFund(h.name);
    const sn=fd.name||h.name;
    let ticker=TICKER_MAP[sn];
    // Also try direct DB lookup
    if(ticker===undefined){
      // Pension funds → no ticker
      if(h.acct==='Pension') ticker=null;
    }
    const cash=isCash(fd)||h.type==='Cash';
    return {name:h.name,sn,value:h.value,ticker,cash,isPension:h.acct==='Pension'};
  });

  // Fetch all tickers in parallel
  const results=await Promise.all(jobs.map(async j=>{
    if(j.cash||j.isPension||!j.ticker) return {job:j,hist:null};
    const hist=await fetchHistory(j.ticker);
    return {job:j,hist};
  }));

  // Find common date range (union of all available dates, fill gaps with last known)
  // Collect all timestamps
  const allTs=new Set();
  results.forEach(({hist})=>{if(hist) Object.keys(hist).forEach(t=>allTs.add(+t));});
  if(!allTs.size){
    loading.innerHTML='<span style="color:var(--muted);font-size:.72rem">⚠️ Could not load price data. Check your internet connection.</span>';
    return;
  }
  const sortedTs=[...allTs].sort((a,b)=>a-b);

  // For each holding, compute value series:
  // value(t) = currentValue * (price(t) / currentPrice)
  // We use relative returns: normalise each series so last point = current value
  const series=results.map(({job,hist})=>{
    if(!hist){
      // Cash or pension or no ticker: flat line at current value
      const flat={};sortedTs.forEach(t=>flat[t]=job.value);
      return {name:job.sn,values:flat,flat:true};
    }
    const tsArr=Object.keys(hist).map(Number).sort((a,b)=>a-b);
    if(!tsArr.length) return {name:job.sn,values:{},flat:true};
    // Get latest available price
    const latestPrice=hist[tsArr[tsArr.length-1]];
    if(!latestPrice) return {name:job.sn,values:{},flat:true};
    // Forward-fill to get value at each timestamp
    const values={};
    let lastPrice=null;
    sortedTs.forEach(t=>{
      // Find closest price at or before t
      if(hist[t]!=null) lastPrice=hist[t];
      if(lastPrice!=null) values[t]=job.value*(lastPrice/latestPrice);
    });
    return {name:job.sn,values,flat:false};
  });

  // Sum all series per timestamp
  const totalSeries=sortedTs.map(t=>{
    let sum=0;
    series.forEach(s=>{if(s.values[t]!=null)sum+=s.values[t];});
    return {t,v:sum};
  }).filter(x=>x.v>0);

  if(!totalSeries.length){
    loading.innerHTML='<span>No data available</span>';return;
  }

  _rawPerfData=totalSeries;
  renderPerfChart(_perfRange);
  loading.style.display='none';canvas.style.display='block';
}

function filterByRange(data,range){
  if(range==='MAX') return data;
  const now=data[data.length-1].t;
  const years={'1Y':1,'3Y':3,'5Y':5}[range]||5;
  const cutoff=now-years*365.25*24*3600*1000;
  return data.filter(x=>x.t>=cutoff);
}

function renderPerfChart(range){
  if(!_rawPerfData) return;
  const data=filterByRange(_rawPerfData,range);
  if(!data.length) return;

  const labels=data.map(x=>new Date(x.t).toLocaleDateString('en-GB',{month:'short',year:'2-digit'}));
  const values=data.map(x=>x.v);
  const startV=values[0],endV=values[values.length-1];
  const change=endV-startV,changePct=(change/startV)*100;
  const maxV=Math.max(...values),minV=Math.min(...values);
  const maxDrop=((minV-maxV)/maxV)*100;

  // Stats
  const up=changePct>=0;
  document.getElementById('perfStats').innerHTML=`
    <div class="pstat"><div class="pl">Current Value</div><div class="pv">£${endV.toLocaleString('en-GB',{maximumFractionDigits:0})}</div><div class="ps">Today</div></div>
    <div class="pstat"><div class="pl">Period Start</div><div class="pv">£${startV.toLocaleString('en-GB',{maximumFractionDigits:0})}</div><div class="ps">${new Date(data[0].t).toLocaleDateString('en-GB',{month:'short',year:'numeric'})}</div></div>
    <div class="pstat"><div class="pl">Total Return</div><div class="pv ${up?'pup':'pdn'}">${up?'+':''}£${Math.round(change).toLocaleString('en-GB')}</div><div class="ps ${up?'pup':'pdn'}">${up?'+':''}${changePct.toFixed(1)}%</div></div>
    <div class="pstat"><div class="pl">Max Drawdown</div><div class="pv pdn">${maxDrop.toFixed(1)}%</div><div class="ps">Peak to trough</div></div>
    <div class="pstat"><div class="pl">Data Points</div><div class="pv">${data.length}</div><div class="ps">Weekly</div></div>
  `;

  if(_perfChart) _perfChart.destroy();
  const ctx=document.getElementById('perfChart').getContext('2d');
  // Gradient fill
  const grad=ctx.createLinearGradient(0,0,0,300);
  grad.addColorStop(0,'rgba(124,106,247,.4)');
  grad.addColorStop(1,'rgba(124,106,247,0)');

  _perfChart=new Chart(ctx,{
    type:'line',
    data:{
      labels,
      datasets:[{
        data:values,
        borderColor:'#7c6af7',
        borderWidth:2,
        backgroundColor:grad,
        fill:true,
        tension:0.3,
        pointRadius:0,
        pointHoverRadius:5,
        pointHoverBackgroundColor:'#7c6af7',
        pointHoverBorderColor:'#fff',
        pointHoverBorderWidth:2,
      }]
    },
    options:{
      responsive:true,maintainAspectRatio:false,
      interaction:{mode:'index',intersect:false},
      plugins:{
        legend:{display:false},
        tooltip:{
          backgroundColor:'rgba(17,17,24,.95)',
          borderColor:'rgba(124,106,247,.3)',
          borderWidth:1,
          titleColor:'#e8e8f0',
          bodyColor:'#6a6a80',
          titleFont:{family:'Syne',size:13,weight:'700'},
          callbacks:{
            label:c=>`  £${Math.round(c.parsed.y).toLocaleString('en-GB')}`
          }
        }
      },
      scales:{
        x:{
          grid:{color:'rgba(42,42,58,.5)',drawTicks:false},
          ticks:{
            color:'#6a6a80',font:{family:'DM Mono',size:10},
            maxTicksLimit:8,maxRotation:0
          }
        },
        y:{
          grid:{color:'rgba(42,42,58,.5)',drawTicks:false},
          ticks:{
            color:'#6a6a80',font:{family:'DM Mono',size:10},
            callback:v=>'£'+Math.round(v/1000)+'k'
          }
        }
      }
    }
  });
}

function setRange(r){
  _perfRange=r;
  document.querySelectorAll('.rbtn').forEach(b=>b.classList.toggle('on',b.textContent===r));
  renderPerfChart(r);
}

// ─────────────────────────────────────────────────────────────────────────────
// PERSISTENCE
// ─────────────────────────────────────────────────────────────────────────────
let _saveT=null;
function saveDraft(){
  clearTimeout(_saveT);
  _saveT=setTimeout(()=>{
    try{
      const rows=[...document.querySelectorAll('#rows .hrow')].map(r=>({n:r.querySelector('.fi')?.value||'',v:r.querySelector('.fv')?.value||'',a:r.querySelector('.fa')?.value||'ISA'})).filter(r=>r.n);
      localStorage.setItem('pxray',JSON.stringify({rows,pv:document.getElementById('pensionVal')?.value||'',ps:PS,pt:document.getElementById('pt')?.value||''}));
      const b=document.getElementById('saveBadge');b.style.display='inline-flex';clearTimeout(b._t);b._t=setTimeout(()=>b.style.display='none',2200);
    }catch(e){}
  },600);
}
function loadDraft(){
  try{
    const raw=localStorage.getItem('pxray');
    if(!raw){renderPensionUI();return;}
    const d=JSON.parse(raw);
    if(d.ps&&d.ps.length===PS.length) PS=d.ps;
    if(d.pv) document.getElementById('pensionVal').value=d.pv;
    if(d.pt) document.getElementById('pt').value=d.pt;
    if(d.rows?.length){
      const c=document.getElementById('rows');c.innerHTML='';
      d.rows.forEach(r=>{
        const row=document.createElement('div');row.className='hrow';
        row.innerHTML=`<input type="text" class="fi" value="${sa(r.n)}" placeholder="Fund name or ticker" oninput="saveDraft()"><input type="number" class="fv" value="${r.v}" placeholder="Value £" min="0" oninput="saveDraft()"><select class="fa" onchange="saveDraft()"><option value="ISA"${r.a==='ISA'?' selected':''}>ISA</option><option value="GIA"${r.a==='GIA'?' selected':''}>GIA</option></select><button class="del" onclick="delRow(this)">✕</button>`;
        c.appendChild(row);
      });
    }
    renderPensionUI();
  }catch(e){renderPensionUI();}
}
const sa=s=>(s||'').replace(/"/g,'&quot;').replace(/</g,'&lt;');

// ─────────────────────────────────────────────────────────────────────────────
// UI HELPERS
// ─────────────────────────────────────────────────────────────────────────────
function swTab(t){
  document.querySelectorAll('.itab').forEach((b,i)=>b.classList.toggle('on',(i===0&&t==='m')||(i===1&&t==='p')));
  document.getElementById('pm').classList.toggle('on',t==='m');
  document.getElementById('pp').classList.toggle('on',t==='p');
}
function swRTab(t){
  document.querySelectorAll('.rtab').forEach(b=>b.classList.toggle('on',b.textContent.toLowerCase().includes(t==='xray'?'x-ray':'perf')));
  document.getElementById('rpXray').classList.toggle('on',t==='xray');
  document.getElementById('rpPerf').classList.toggle('on',t==='perf');
  if(t==='perf'&&!_rawPerfData) loadPerformance();
}
function addRow(){
  const r=document.createElement('div');r.className='hrow';
  r.innerHTML='<input type="text" placeholder="Fund name or ticker" class="fi" oninput="saveDraft()"><input type="number" placeholder="Value £" class="fv" min="0" oninput="saveDraft()"><select class="fa" onchange="saveDraft()"><option value="ISA">ISA</option><option value="GIA">GIA</option></select><button class="del" onclick="delRow(this)">✕</button>';
  document.getElementById('rows').appendChild(r);
}
function delRow(b){if(document.querySelectorAll('#rows .hrow').length>1){b.parentElement.remove();saveDraft();}}
function loadEx(){
  const ex=[['iShares Core MSCI World UCITS ETF USD Acc (GBP)',24385,'ISA'],['Vanguard Funds Plc FTSE 100 UCITS ETF GBP ACC',21397,'ISA'],['iShares IV plc MSCI India UCITS ETF USD Acc (GBP)',19974,'ISA'],['iShares plc Core MSCI Emerging Markets IMI UCITS ETF Acc',24817,'ISA'],['iShares V plc S&P 500 GBP Hedged UCITS ETF (Acc)',18279,'ISA'],['iShares III plc Core MSCI Japan IMI UCITS ETF Acc (GBP)',25907,'ISA'],['Xtrackers Russell 2000 UCITS ETF 1C',11820,'ISA'],['WS Amati Strategic Metals Fund Class B - Accumulation',11697,'ISA'],['abrdn Sterling Money Market Class I - Accumulation (GBP)',8506,'ISA'],['Invesco Markets plc EURO STOXX 50 UCITS ETF',14108,'ISA'],['iShares VII plc NASDAQ 100 UCITS ETF USD Acc',13938,'ISA'],['Vanguard Funds Plc FTSE 250 UCITS ETF Acc',12278,'ISA'],['iShares VII plc MSCI EM ex China UCITS ETF USD Acc',13016,'ISA'],['Xtrackers Stoxx Europe 600 UCITS ETF (DR)',6680,'ISA']];
  const c=document.getElementById('rows');c.innerHTML='';
  ex.forEach(([n,v,a])=>{const r=document.createElement('div');r.className='hrow';r.innerHTML=`<input type="text" class="fi" value="${sa(n)}" oninput="saveDraft()"><input type="number" class="fv" value="${v}" oninput="saveDraft()"><select class="fa" onchange="saveDraft()"><option value="ISA"${a==='ISA'?' selected':''}>ISA</option><option value="GIA"${a==='GIA'?' selected':''}>GIA</option></select><button class="del" onclick="delRow(this)">✕</button>`;c.appendChild(r);});
  document.getElementById('pensionVal').value=85000;
  saveDraft();
}
function getManual(){return[...document.querySelectorAll('#rows .hrow')].map(r=>({name:r.querySelector('.fi').value.trim(),value:parseFloat(r.querySelector('.fv').value)||0,acct:r.querySelector('.fa')?.value||'ISA'})).filter(h=>h.name&&h.value>0);}
function parsePaste(txt){const out=[];txt.split(/\n/).map(s=>s.trim()).filter(Boolean).forEach(ln=>{if(!/\d/.test(ln))return;const parts=ln.split(/\t/);if(parts.length>=2){const nm=parts[0].replace(/\s*\d+\s*$/,'').trim();const val=parseFloat(parts[parts.length-1].replace(/[£,\s]/g,''));if(nm&&val>0&&nm.length>2)out.push({name:nm,value:val,acct:'ISA'});return;}const m=ln.match(/([\d,]+\.\d{2})\s*$/);if(!m)return;const val=parseFloat(m[1].replace(/,/g,''));const name=ln.replace(m[0],'').replace(/\s*\d+\s*$/,'').trim();if(name&&val>0)out.push({name,value:val,acct:'ISA'});});return out;}
function hideErr(){document.querySelectorAll('.err').forEach(e=>e.classList.remove('on'));}
function showErr(id,msg){const e=document.getElementById(id);e.textContent=msg;e.classList.add('on');}
function goManual(){hideErr();const h=getManual();if(!h.length){showErr('em','Please enter at least one holding with a value.');return;}const tot=PS.reduce((s,f)=>s+f.pct,0);if(Math.abs(tot-100)>0.1){showErr('em',`Pension splits total ${tot.toFixed(2)}% — adjust to 100% first.`);return;}render(agg([...h,...getPensionH('pensionVal')]));}
function goPaste(){hideErr();const t=document.getElementById('pt').value.trim();if(!t){showErr('ep','Please paste your holdings first.');return;}const h=parsePaste(t);if(!h.length){showErr('ep','Could not read any holdings.');return;}render(agg([...h,...getPensionH('pensionValP')]));}

// ─────────────────────────────────────────────────────────────────────────────
// MODALS
// ─────────────────────────────────────────────────────────────────────────────
function openDrill(label,type){
  if(!_D)return;
  const total=_D.total;
  if(type==='region'){const countries=(_D.reD[label]||[]).slice().sort((a,b)=>b.contribution-a.contribution);const tot=countries.reduce((s,x)=>s+x.contribution,0),maxC=countries[0]?.contribution||1;showModal('🗺️ '+label,`Total: ${tot.toFixed(1)}%  •  £${Math.round(tot/100*total).toLocaleString('en-GB')}`,countries.map((x,i)=>drRow(i,x.country,x.contribution/maxC*100,x.contribution.toFixed(1)+'%','£'+Math.round(x.contribution/100*total).toLocaleString('en-GB'))).join(''));return;}
  const detail=type==='country'?_D.coD[label]:_D.seD[label];if(!detail?.length)return;
  const tot=detail.reduce((s,x)=>s+x.contribution,0),maxC=detail[0].contribution;
  showModal((type==='country'?'🌍':'🏭')+' '+label,`Total: ${tot.toFixed(1)}%  •  £${Math.round(tot/100*total).toLocaleString('en-GB')}`,detail.map((x,i)=>drRow(i,x.name+(x.acct==='Pension'?' [P]':''),x.contribution/maxC*100,x.contribution.toFixed(1)+'%','£'+Math.round(x.contribution/100*total).toLocaleString('en-GB'))).join(''));
}
function openFundDrill(fn){if(!_D)return;const fd=_D.fundCo[fn];if(!fd)return;const countries=fd.countries.slice().sort((a,b)=>b.fundPct-a.fundPct),maxP=countries[0]?.fundPct||1;const acctL=fd.acct==='Pension'?`<span style="color:var(--pension)">[Pension]</span>`:fd.acct==='GIA'?`<span style="color:var(--accent2)">[GIA]</span>`:`<span style="color:var(--isa)">[ISA]</span>`;showModal('🌍 '+fn,`${acctL} &nbsp;£${fd.value.toLocaleString('en-GB',{maximumFractionDigits:0})} &nbsp;•&nbsp; Country breakdown`,countries.map((x,i)=>drRow(i,x.country,x.fundPct/maxP*100,x.fundPct.toFixed(1)+'%','£'+Math.round(x.pp/100*_D.total).toLocaleString('en-GB'))).join(''));}
function openUnderlierDrill(sn){if(!_D)return;const s=_D.st.find(x=>x.n===sn);if(!s?.funds?.length)return;const funds=[...s.funds].sort((a,b)=>b.contribution-a.contribution),maxC=funds[0].contribution;const total=_D.total;showModal(gf(s.ct)+' '+s.n+(s.t?' ('+s.t+')':''),`Total: ${s.p.toFixed(2)}%  •  £${Math.round(s.p/100*total).toLocaleString('en-GB')}  •  ${funds.length} fund${funds.length!==1?'s':''}`,funds.map((f,i)=>drRow(i,f.name+(f.acct==='Pension'?' [P]':''),f.contribution/maxC*100,(f.contribution*100).toFixed(2)+'%','£'+Math.round(f.contribution*total).toLocaleString('en-GB'))).join(''));}
function drRow(i,name,barW,pct,sub){return `<div class="dr-row"><div class="dr-swatch" style="background:${PAL[i%PAL.length]}"></div><span class="dr-name" title="${name}">${name}</span><div class="dr-bar-bg"><div class="dr-bar-fill" style="width:${Math.min(100,barW||0)}%;background:${PAL[i%PAL.length]}"></div></div><span class="dr-pct">${pct}</span><span class="dr-sub">${sub}</span></div>`;}
function showModal(title,sub,body){document.getElementById('drillTitle').textContent=title;document.getElementById('drillSubtitle').innerHTML=sub;document.getElementById('drillRows').innerHTML=body;document.getElementById('drillModal').classList.add('on');}
function closeDrill(){document.getElementById('drillModal').classList.remove('on');}

// ─────────────────────────────────────────────────────────────────────────────
// RENDER
// ─────────────────────────────────────────────────────────────────────────────
function render(d){
  _D=d;_rawPerfData=null;_perfChart=null;
  document.getElementById('rTot').textContent='£'+d.total.toLocaleString('en-GB',{maximumFractionDigits:0});
  document.getElementById('rNote').innerHTML='<strong>Note:</strong> '+d.note;
  const pn=document.getElementById('rPensionNote');
  if(d.penTotal>0){pn.style.display='block';pn.innerHTML=`<strong>🏦 Pension:</strong> £${d.penTotal.toLocaleString('en-GB',{maximumFractionDigits:0})} (${(d.penTotal/d.total*100).toFixed(1)}% of wealth) split across ${PS.length} LifeSight sub-funds. Assumptions use public benchmarks.`;}else pn.style.display='none';
  const sw=document.getElementById('rSplitWrap');
  if(d.penTotal>0&&d.isaTotal>0){sw.style.display='block';const iP=(d.isaTotal/d.total*100).toFixed(1),pP=(d.penTotal/d.total*100).toFixed(1);document.getElementById('rSplitBar').innerHTML=`<div class="split-seg" style="flex:${iP};background:var(--isa);color:#0a0a0f">${iP>12?'ISA/GIA':''}</div><div class="split-seg" style="flex:${pP};background:var(--pension);color:#0a0a0f">${pP>8?'Pension':''}</div>`;document.getElementById('rSplitLabels').innerHTML=`<span><span class="dot" style="background:var(--isa)"></span> ISA/GIA £${d.isaTotal.toLocaleString('en-GB',{maximumFractionDigits:0})} (${iP}%)</span><span><span class="dot" style="background:var(--pension)"></span> Pension £${d.penTotal.toLocaleString('en-GB',{maximumFractionDigits:0})} (${pP}%)</span>`;}else sw.style.display='none';
  document.getElementById('rBreakdown').innerHTML=d.penTotal>0?`<span class="rtop-sub"><span class="dot" style="background:var(--isa)"></span> ISA/GIA £${d.isaTotal.toLocaleString('en-GB',{maximumFractionDigits:0})}</span><span class="rtop-sub"><span class="dot" style="background:var(--pension)"></span> Pension £${d.penTotal.toLocaleString('en-GB',{maximumFractionDigits:0})}</span>`:'';
  const i=d.ins;document.getElementById('rIns').innerHTML=ic('🇺🇸','US Exposure',i.us.toFixed(1)+'%','of portfolio')+ic('📊','Top Sector',i.topSecP.toFixed(1)+'%',i.topSec)+ic('🏆','Largest Holding',i.topPct.toFixed(1)+'%',i.topName)+ic('🔢','Holdings',i.n,'positions');
  donut('cC',d.co,'c','lC','country',d.total);donut('cR',d.re,'r','lR','region',d.total);donut('cS',d.se,'s','lS','sector',d.total);
  const ul=document.getElementById('rUl');ul.innerHTML='';
  const mp=d.st[0]?.p||1;
  if(d.st.length){d.st.forEach(s=>{const sf=s.n.replace(/\\/g,'\\\\').replace(/'/g,"\\'");ul.innerHTML+=`<tr onclick="openUnderlierDrill('${sf}')"><td style="padding:9px 4px 9px 11px;font-size:.88rem">${gf(s.ct)}</td><td><span class="fn">${s.n}</span></td><td style="font-size:.62rem;color:var(--muted)">${s.t||'—'}</td><td><div class="minibar"><div class="minibar-fill" style="width:${Math.min(100,s.p/mp*100)}%"></div></div></td><td style="font-weight:600">${s.p.toFixed(2)}%</td><td style="font-size:.58rem;color:var(--muted)">▸ ${s.funds?.length||0} fund${(s.funds?.length||0)!==1?'s':''}</td></tr>`;});}
  else ul.innerHTML='<tr><td colspan="6" style="color:var(--muted);font-size:.72rem;padding:14px 11px">No stock-level data available.</td></tr>';
  // Fund table — sorted largest to smallest
  const fe=document.getElementById('rFundExp');fe.innerHTML='';
  const sortedHoldings=[...d.holdings].sort((a,b)=>b.value-a.value);
  const maxV=sortedHoldings[0]?.value||1;
  sortedHoldings.forEach(h=>{const pct=h.value/d.total*100,bw=Math.min(100,h.value/maxV*100),pen=h.acct==='Pension',gia=h.acct==='GIA';const tc=h.type==='Cash'?'tc':pen?'tp':h.type==='ETF'?'te':'tf';const ab=pen?'<span class="tag tp">Pension</span>':gia?'<span class="tag tf">GIA</span>':'<span class="tag ts">ISA</span>';const sf=h.name.replace(/\\/g,'\\\\').replace(/'/g,"\\'");fe.innerHTML+=`<tr onclick="openFundDrill('${sf}')"${pen?' style="background:rgba(247,106,194,.03)"':''}><td style="padding:9px 4px 9px 11px">📂</td><td><span class="fn" style="font-size:.71rem">${h.name.length>40?h.name.slice(0,40)+'…':h.name}</span></td><td>${ab}</td><td><span class="tag ${tc}">${h.type||'Fund'}</span></td><td><div class="minibar"><div class="minibar-fill" style="width:${bw}%"></div></div></td><td>£${h.value.toLocaleString('en-GB',{maximumFractionDigits:0})}</td><td style="font-weight:600">${pct.toFixed(1)}%</td><td style="font-size:.58rem;color:var(--muted)">▸ countries</td></tr>`;});
  // Reset perf panel
  document.getElementById('perfLoading').style.display='flex';document.getElementById('perfLoading').innerHTML='<div class="spinner"></div><span>Loading price history…</span>';document.getElementById('perfChart').style.display='none';document.getElementById('perfStats').innerHTML='';
  // Switch to X-Ray tab
  swRTab('xray');
  document.getElementById('R').classList.add('on');
  setTimeout(()=>document.getElementById('R').scrollIntoView({behavior:'smooth',block:'start'}),80);
}
function ic(ico,lbl,val,sub){return`<div class="ic"><span class="ico">${ico}</span><div class="lbl">${lbl}</div><div class="val">${val}</div><div class="sub">${sub}</div></div>`;}
function donut(cid,items,key,lid,type,total){
  if(window['_c'+cid])window['_c'+cid].destroy();
  const labels=items.map(x=>x[key]),vals=items.map(x=>x.p),cols=PAL.slice(0,labels.length);
  window['_c'+cid]=new Chart(document.getElementById(cid),{type:'doughnut',data:{labels,datasets:[{data:vals,backgroundColor:cols,borderWidth:2,borderColor:'#111118',hoverOffset:6}]},options:{responsive:true,maintainAspectRatio:false,cutout:'65%',plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>{const amt=total?(` · £${Math.round(c.parsed/100*total).toLocaleString('en-GB')}`):'';return ` ${c.label}: ${c.parsed.toFixed(1)}%${amt}`;}}}},onClick:(e,els)=>{if(els.length)openDrill(labels[els[0].index],type);}}});
  document.getElementById(lid).innerHTML=items.map((x,i)=>`<div class="li" onclick="openDrill('${x[key].replace(/'/g,"\\'")}','${type}')" title="Tap to drill down"><div class="sw" style="background:${cols[i]}"></div><span class="bn">${x[key]}</span>${total?`<span class="lamt">£${Math.round(x.p/100*total).toLocaleString('en-GB')}</span>`:''}<span class="lp">${x.p.toFixed(1)}%</span><span class="da">▸</span></div>`).join('');
}
function reset(){_D=null;_rawPerfData=null;document.getElementById('R').classList.remove('on');window.scrollTo({top:0,behavior:'smooth'});}

// ─────────────────────────────────────────────────────────────────────────────
// INIT
// ─────────────────────────────────────────────────────────────────────────────
document.addEventListener('DOMContentLoaded',()=>{
  loadDraft();
  // Show install card only in browser (not standalone PWA)
  if(!window.navigator.standalone){
    document.getElementById('installCard').style.display='block';
  }
});
</script>

</body>
</html>
