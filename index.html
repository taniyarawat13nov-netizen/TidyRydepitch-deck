<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>TidyRyde – Laila Pitch Deck</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=Inter:wght@300;400;500;600&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet"/>
<style>
*{margin:0;padding:0;box-sizing:border-box;}
:root{
  --bg:#070a0f; --surface:#0d1119; --card:#111827; --border:#1e2d40;
  --blue:#38bdf8; --teal:#2dd4bf; --lime:#a3e635; --orange:#fb923c; --pink:#f472b6;
  --text:#e2e8f0; --muted:#64748b; --white:#fff;
  --fh:'Syne',sans-serif; --fb:'Inter',sans-serif; --fm:'Space Mono',monospace;
}
html,body{height:100%;background:var(--bg);color:var(--text);font-family:var(--fb);}
body{overflow:hidden;}
body.edit [contenteditable]{outline:1px dashed rgba(56,189,248,.4);cursor:text;border-radius:3px;padding:1px 3px;}
body.edit [contenteditable]:focus{outline:1px solid var(--blue);background:rgba(56,189,248,.05);}

/* BAR */
#bar{position:fixed;top:0;left:0;height:2px;background:linear-gradient(90deg,var(--blue),var(--teal),var(--lime));transition:width .4s;z-index:300;}

/* TOOLBAR */
#toolbar{position:fixed;top:14px;right:14px;z-index:200;display:flex;gap:7px;align-items:center;}
#toolbar button{background:var(--card);border:1px solid var(--border);color:var(--text);font-family:var(--fm);font-size:10px;padding:7px 13px;border-radius:6px;cursor:pointer;transition:all .2s;}
#toolbar button:hover{border-color:var(--blue);color:var(--blue);}
#toolbar button.on{background:rgba(56,189,248,.12);border-color:var(--blue);color:var(--blue);}
#slbl{font-family:var(--fm);font-size:10px;color:var(--muted);padding:7px 13px;background:var(--card);border:1px solid var(--border);border-radius:6px;}

/* NAV */
#nav{position:fixed;bottom:22px;left:50%;transform:translateX(-50%);z-index:200;display:flex;align-items:center;gap:5px;background:rgba(13,17,25,.96);border:1px solid var(--border);border-radius:50px;padding:8px 16px;}
#nav button{background:none;border:none;color:var(--muted);cursor:pointer;font-size:20px;padding:3px 9px;line-height:1;transition:color .2s;}
#nav button:hover{color:var(--blue);}
#ctr{font-family:var(--fm);font-size:11px;color:var(--muted);min-width:38px;text-align:center;}
.dots{display:flex;gap:4px;align-items:center;}
.dot{width:5px;height:5px;background:var(--border);border-radius:50%;cursor:pointer;transition:all .2s;flex-shrink:0;}
.dot.on{background:var(--blue);width:14px;border-radius:3px;}

/* SLIDES */
.deck{width:100vw;height:100vh;position:relative;}
.slide{position:absolute;inset:0;display:flex;flex-direction:column;justify-content:center;align-items:center;padding:54px 76px;opacity:0;pointer-events:none;transition:opacity .4s;}
.slide.active{opacity:1;pointer-events:all;}
.inner{width:100%;max-width:1080px;position:relative;z-index:2;}
.slide::before{content:'';position:absolute;inset:0;background-image:linear-gradient(rgba(56,189,248,.025) 1px,transparent 1px),linear-gradient(90deg,rgba(56,189,248,.025) 1px,transparent 1px);background-size:48px 48px;pointer-events:none;}

/* TYPE */
.eye{font-family:var(--fm);font-size:10px;letter-spacing:.18em;text-transform:uppercase;color:var(--blue);border:1px solid rgba(56,189,248,.25);border-radius:20px;padding:4px 14px;display:inline-block;margin-bottom:16px;}
.h1{font-family:var(--fh);font-size:clamp(44px,6vw,92px);font-weight:800;line-height:.95;color:var(--white);}
.h2{font-family:var(--fh);font-size:clamp(32px,4.2vw,60px);font-weight:800;line-height:1;color:var(--white);}
.sub{font-size:clamp(13px,1.5vw,17px);color:var(--muted);line-height:1.7;margin-top:12px;font-weight:300;max-width:620px;}
.blue{color:var(--blue);} .teal{color:var(--teal);} .lime{color:var(--lime);} .org{color:var(--orange);} .pink{color:var(--pink);}

/* CARDS */
.card{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:22px;}
.cb{border-color:rgba(56,189,248,.35);background:rgba(56,189,248,.05);}
.ct{border-color:rgba(45,212,191,.35);background:rgba(45,212,191,.05);}
.cl{border-color:rgba(163,230,53,.3);background:rgba(163,230,53,.04);}
.co{border-color:rgba(251,146,60,.3);background:rgba(251,146,60,.04);}
.cp{border-color:rgba(244,114,182,.3);background:rgba(244,114,182,.04);}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:16px;}
.g3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:14px;}
.g4{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;}
.card h4{font-family:var(--fh);font-size:19px;font-weight:700;color:var(--white);margin-bottom:7px;}
.card p{font-size:13px;color:var(--muted);line-height:1.7;}
.hr{height:1px;background:var(--border);margin:14px 0;}
ul.li{list-style:none;}
ul.li li{font-size:13.5px;color:var(--text);padding:8px 0;border-bottom:1px solid rgba(30,45,64,.5);display:flex;gap:9px;align-items:flex-start;}
ul.li li:last-child{border-bottom:none;}
.d{width:5px;height:5px;background:var(--blue);border-radius:50%;margin-top:8px;flex-shrink:0;}
.dt{background:var(--teal);} .dl{background:var(--lime);} .do{background:var(--orange);} .dp{background:var(--pink);}
.pill{display:inline-block;font-family:var(--fm);font-size:10px;padding:3px 10px;border-radius:20px;margin:3px;}
.pb{background:rgba(56,189,248,.12);color:var(--blue);border:1px solid rgba(56,189,248,.25);}
.pt{background:rgba(45,212,191,.1);color:var(--teal);border:1px solid rgba(45,212,191,.25);}
.pl{background:rgba(163,230,53,.08);color:var(--lime);border:1px solid rgba(163,230,53,.2);}
.po{background:rgba(251,146,60,.1);color:var(--orange);border:1px solid rgba(251,146,60,.25);}
.pp{background:rgba(244,114,182,.1);color:var(--pink);border:1px solid rgba(244,114,182,.25);}
.bignum{font-family:var(--fh);font-size:clamp(36px,4.5vw,64px);font-weight:800;}
.lbl{font-size:11px;color:var(--muted);margin-top:3px;}

/* TLINE */
.tl{display:flex;}
.tls{flex:1;padding:16px;border:1px solid var(--border);}
.tls:first-child{border-radius:10px 0 0 10px;} .tls:last-child{border-radius:0 10px 10px 0;}
.tls.on{background:rgba(56,189,248,.05);border-color:rgba(56,189,248,.4);}
.tls .n{font-family:var(--fh);font-size:30px;font-weight:800;color:var(--blue);opacity:.3;}
.tls h5{font-size:13px;font-weight:600;color:var(--white);margin:3px 0;}
.tls p{font-size:11px;color:var(--muted);}

/* ANIMATIONS */
@keyframes blink{0%,100%{opacity:1;}50%{opacity:.2;}}
@keyframes beam{0%,100%{opacity:.25;}50%{opacity:.9;}}
@keyframes scanline{0%{top:-2px;}100%{top:102%;}}
@keyframes gz-stripe{0%{top:0%;}100%{top:100%;}}
@keyframes pulse-ring{0%{transform:translate(-50%,-50%) scale(1);opacity:.5;}100%{transform:translate(-50%,-50%) scale(1.15);opacity:0;}}

/* ======= SLIDE 1 TITLE ======= */
#s1{background:radial-gradient(ellipse at 25% 55%,rgba(14,165,233,.16) 0%,transparent 55%),radial-gradient(ellipse at 80% 20%,rgba(45,212,191,.06) 0%,transparent 50%),var(--bg);}
.logomain{font-family:var(--fh);font-weight:800;font-size:clamp(68px,10.5vw,144px);line-height:.9;letter-spacing:-.02em;}
.tagmain{font-family:var(--fm);font-size:clamp(10px,1.2vw,14px);letter-spacing:.3em;color:var(--teal);margin-top:8px;text-transform:uppercase;}

/* ======= SLIDE 3 STORY ======= */
#s3{background:radial-gradient(ellipse at 70% 50%,rgba(244,114,182,.07) 0%,transparent 60%),var(--bg);}

/* ======= SLIDE 4 MACHINE CSS ART ======= */
#s4{background:radial-gradient(ellipse at 40% 50%,rgba(56,189,248,.09) 0%,transparent 60%),var(--bg);}
.mach{width:230px;height:350px;background:linear-gradient(180deg,#1a1f2e,#0d1119);border:1.5px solid #2a3a50;border-radius:10px;position:relative;overflow:hidden;display:flex;flex-direction:column;box-shadow:0 0 60px rgba(56,189,248,.14);}
.mscr{background:#050810;margin:9px 9px 0;height:64px;border-radius:5px;border:1px solid #1a2535;display:flex;flex-direction:column;align-items:center;justify-content:center;overflow:hidden;position:relative;}
.mscr-bg{position:absolute;inset:0;background:linear-gradient(135deg,rgba(56,189,248,.14),rgba(56,189,248,.02));}
.mscr-t{font-family:'Syne',sans-serif;font-size:9px;font-weight:700;color:#fff;letter-spacing:.08em;position:relative;z-index:2;text-align:center;line-height:1.35;}
.mscr-s{font-family:'Space Mono',monospace;font-size:6px;color:var(--blue);position:relative;z-index:2;letter-spacing:.15em;margin-top:2px;}
.mqr{height:22px;display:flex;align-items:center;justify-content:center;gap:5px;margin:6px 9px;}
.mqrc{width:20px;height:20px;border-radius:50%;background:#050810;border:1px solid var(--blue);display:flex;align-items:center;justify-content:center;font-family:'Space Mono',monospace;font-size:5px;color:var(--blue);}
.mql{flex:1;height:1px;background:rgba(56,189,248,.2);}
.mchm{display:flex;gap:7px;margin:0 9px;flex:1;}
.mc{flex:1;background:#080c14;border:1px solid #1a2535;border-radius:6px;display:flex;flex-direction:column;align-items:center;justify-content:center;position:relative;overflow:hidden;}
.mc::before{content:'';position:absolute;inset:0;background:radial-gradient(circle at 50% 65%,rgba(56,189,248,.18),transparent 65%);}
.mc.dp::before{background:radial-gradient(circle at 50% 65%,rgba(45,212,191,.15),transparent 65%);}
.mcl{font-family:'Space Mono',monospace;font-size:5.5px;color:var(--blue);position:absolute;bottom:4px;left:50%;transform:translateX(-50%);white-space:nowrap;letter-spacing:.1em;}
.mc.dp .mcl{color:var(--teal);}
.mbot{margin:7px 9px 9px;height:22px;background:#050810;border-radius:5px;border:1px solid #1a2535;display:flex;align-items:center;justify-content:center;gap:8px;}
.uvb{position:absolute;width:1px;background:linear-gradient(180deg,rgba(56,189,248,.7),transparent);animation:beam 2s ease-in-out infinite;top:6px;}
.uvbd{background:linear-gradient(180deg,rgba(45,212,191,.6),transparent);}
.gring{position:absolute;width:200px;height:200px;border:1px solid rgba(56,189,248,.08);border-radius:50%;left:50%;top:50%;transform:translate(-50%,-50%);pointer-events:none;}

/* ======= GENZ MACHINE ======= */
.gzm{width:210px;height:370px;background:linear-gradient(180deg,#0f172a,#060a12);border-radius:20px;border:1px solid rgba(56,189,248,.28);position:relative;overflow:hidden;box-shadow:0 0 80px rgba(56,189,248,.18);}
.gzm::after{content:'LAILA';font-family:'Syne',sans-serif;font-weight:800;font-size:10px;letter-spacing:.45em;color:rgba(56,189,248,.1);position:absolute;bottom:14px;left:50%;transform:translateX(-50%);white-space:nowrap;}
.gz-sl{position:absolute;width:100%;height:1px;background:rgba(56,189,248,.25);animation:scanline 4s linear infinite;pointer-events:none;}
.gz-stripe{position:absolute;width:100%;height:2px;background:linear-gradient(90deg,transparent,rgba(56,189,248,.5),transparent);animation:gz-stripe 3.5s ease-in-out infinite;}
.gzt{background:rgba(56,189,248,.07);border-bottom:1px solid rgba(56,189,248,.18);height:52px;display:flex;align-items:center;justify-content:space-between;padding:0 14px;}
.gztl{font-family:'Syne',sans-serif;font-weight:800;font-size:13px;color:var(--white);}
.gzst{width:7px;height:7px;background:var(--lime);border-radius:50%;box-shadow:0 0 8px var(--lime);}
.gzcw{display:flex;gap:5px;margin:10px;height:192px;}
.gzc{flex:1;border-radius:11px;border:1px solid rgba(56,189,248,.18);background:rgba(0,0,0,.35);display:flex;flex-direction:column;align-items:center;justify-content:center;position:relative;overflow:hidden;}
.gzc.dp2{border-color:rgba(45,212,191,.25);}
.gzg{position:absolute;width:100%;height:55%;bottom:0;background:radial-gradient(ellipse at 50% 100%,rgba(56,189,248,.22),transparent 70%);}
.gzc.dp2 .gzg{background:radial-gradient(ellipse at 50% 100%,rgba(45,212,191,.18),transparent 70%);}
.gzb{margin:0 10px 10px;display:flex;flex-direction:column;gap:7px;}
.gzpb{background:rgba(56,189,248,.07);border:1px solid rgba(56,189,248,.18);border-radius:8px;padding:7px 11px;display:flex;align-items:center;justify-content:space-between;}
.gzqr{display:flex;gap:5px;}
.gzqrbox{width:30px;height:30px;background:#fff;border-radius:5px;display:flex;align-items:center;justify-content:center;}
.gzsc{flex:1;background:rgba(163,230,53,.07);border:1px solid rgba(163,230,53,.18);border-radius:6px;display:flex;align-items:center;justify-content:center;font-family:'Space Mono',monospace;font-size:7px;color:var(--lime);letter-spacing:.1em;}
</style>
</head>
<body>
<div id="bar"></div>
<div id="toolbar">
  <span id="slbl">01/15</span>
  <button id="editBtn" onclick="toggleEdit()">✏ EDIT</button>
  <button onclick="dlHTML()">⬇ SAVE HTML</button>
  <button onclick="dlPDF()">📄 PRINT PDF</button>
</div>

<div class="deck">

<!-- ============================
  S1: TITLE
============================= -->
<div class="slide active" id="s1">
<div class="inner" style="display:flex;flex-direction:column;align-items:flex-start;">
  <div style="display:flex;align-items:center;gap:9px;margin-bottom:14px;">
    <div style="width:8px;height:8px;background:var(--lime);border-radius:50%;animation:blink 1.8s ease-in-out infinite;"></div>
    <span style="font-family:var(--fm);font-size:10px;color:var(--teal);letter-spacing:.15em;">PRE-LAUNCH · PILOT READY · INDIA</span>
  </div>
  <div class="logomain"><span style="color:var(--white)" contenteditable="false">TIDY</span><span class="blue" contenteditable="false">RYDE</span></div>
  <p class="tagmain" contenteditable="false">CLEAN HELMET. SAFE RIDER. EVERY TIME.</p>
  <p class="sub" style="margin-top:16px;" contenteditable="false">We built a machine that deep cleans <em>and</em> sanitizes your helmet — automatically — in 60 seconds. Meet <strong style="color:var(--pink);">Laila.</strong></p>
  <div style="display:flex;gap:22px;margin-top:36px;align-items:center;">
    <span style="font-family:var(--fm);font-size:11px;color:var(--muted);">Founder Deck · 2025</span>
    <div style="width:1px;height:14px;background:var(--border);"></div>
    <span style="font-family:var(--fm);font-size:11px;color:var(--muted);">Hardware + IoT</span>
    <div style="width:1px;height:14px;background:var(--border);"></div>
    <span style="font-family:var(--fm);font-size:11px;color:var(--muted);">Made in India 🇮🇳</span>
  </div>
  <!-- rings -->
  <div style="position:absolute;right:-10px;top:50%;transform:translateY(-50%);pointer-events:none;">
    <div style="width:270px;height:270px;border:1px solid rgba(56,189,248,.07);border-radius:50%;position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);"></div>
    <div style="width:170px;height:170px;border:1px solid rgba(56,189,248,.12);border-radius:50%;position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);animation:pulse-ring 3s ease-out infinite;"></div>
    <div style="width:85px;height:85px;border:1.5px solid rgba(56,189,248,.2);border-radius:50%;position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);display:flex;align-items:center;justify-content:center;">
      <span style="font-family:var(--fm);font-size:7.5px;color:var(--blue);letter-spacing:.15em;text-align:center;line-height:1.8;">CLEAN<br>SAFE<br>SMART</span>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S2: PROBLEM
============================= -->
<div class="slide" id="s2">
<div class="inner">
  <div class="eye">01 · The Problem</div>
  <div class="h2">Riders Share Helmets.<br><span class="blue">Nobody Cleans Them.</span></div>
  <div class="g2" style="margin-top:22px;">
    <div class="card co">
      <h4 style="color:var(--orange);">THE DIRT PROBLEM</h4>
      <div class="hr"></div>
      <ul class="li">
        <li><span class="d do"></span>Sweat, oil, dead skin cells accumulate daily inside helmets</li>
        <li><span class="d do"></span>Rental helmets touched by 8–10 riders a day — never washed</li>
        <li><span class="d do"></span>Even personal helmets cleaned less than once a month</li>
        <li><span class="d do"></span>No machine, no standard, no solution exists</li>
      </ul>
    </div>
    <div class="card cp">
      <h4 style="color:var(--pink);">THE GERM PROBLEM</h4>
      <div class="hr"></div>
      <ul class="li">
        <li><span class="d dp"></span>Shared helmets spread fungal infections, lice, skin conditions</li>
        <li><span class="d dp"></span>UV sanitization exists — but never accessible on the go</li>
        <li><span class="d dp"></span>Post-COVID hygiene awareness is at an all-time high</li>
        <li><span class="d dp"></span>Riders want clean helmets. There's just nowhere to get one.</li>
      </ul>
    </div>
  </div>
  <div class="card cb" style="margin-top:14px;padding:16px 22px;display:flex;align-items:center;gap:18px;">
    <div class="bignum blue" style="font-size:52px;flex-shrink:0;" contenteditable="false">90M+</div>
    <div>
      <div style="font-weight:600;font-size:15px;color:var(--white);" contenteditable="false">Two-wheeler riders in India. The world's largest biking nation.</div>
      <div style="font-size:13px;color:var(--muted);margin-top:3px;" contenteditable="false">Millions share helmets every day. Zero automated deep-clean + sanitize solution exists. Until now.</div>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S3: WHY LAILA
============================= -->
<div class="slide" id="s3">
<div class="inner" style="display:grid;grid-template-columns:1.1fr 1fr;gap:44px;align-items:center;">
  <div>
    <div class="eye" style="border-color:rgba(244,114,182,.3);color:var(--pink);">02 · The Name</div>
    <div class="h2" style="line-height:1.1;">Why did we call<br>our machine<br><span class="pink">"Laila"?</span></div>
    <div class="hr" style="border-color:rgba(244,114,182,.2);margin:18px 0;"></div>
    <div style="font-family:var(--fh);font-size:clamp(18px,2.4vw,30px);font-weight:700;color:var(--white);line-height:1.15;" contenteditable="false">Every rider has a <span class="pink">Laila</span> —<br>the one they can't ride without.</div>
    <p style="font-size:14.5px;color:var(--muted);margin-top:16px;line-height:1.75;" contenteditable="false">In the legend of <strong style="color:var(--white);">Laila-Majnu</strong>, Laila is the one Majnu is inseparable from. Obsessed over. Would do anything for.</p>
    <p style="font-size:14.5px;color:var(--muted);margin-top:10px;line-height:1.75;" contenteditable="false">A rider's helmet is exactly that. You wear it on your face. You trust it with your life. You breathe through it every single ride.</p>
    <p style="font-size:14.5px;line-height:1.75;margin-top:10px;" contenteditable="false"><strong style="color:var(--white);">If the helmet is a rider's Laila,</strong> <span class="pink">shouldn't she be treated with the love she deserves?</span></p>
    <div class="card cb" style="margin-top:16px;padding:13px 18px;">
      <p style="font-family:var(--fm);font-size:11px;color:var(--blue);line-height:1.6;" contenteditable="false">"Har rider ki ek Laila hoti hai — uski helmet."<br><span style="color:var(--muted);font-size:10px;">Every rider has a Laila — their helmet.</span></p>
    </div>
  </div>
  <div style="display:flex;flex-direction:column;gap:14px;">
    <div class="card cp">
      <div style="font-family:var(--fm);font-size:10px;color:var(--pink);margin-bottom:10px;letter-spacing:.1em;">THE PARALLEL</div>
      <div style="display:flex;gap:16px;align-items:center;">
        <div style="text-align:center;flex:1;">
          <div style="font-size:26px;">🏍️</div>
          <div style="font-family:var(--fh);font-size:13px;font-weight:700;color:var(--white);margin-top:5px;">RIDER</div>
          <div style="font-size:10px;color:var(--muted);">Majnu</div>
        </div>
        <div style="font-family:var(--fh);font-size:26px;color:var(--pink);">♥</div>
        <div style="text-align:center;flex:1;">
          <div style="font-size:26px;">⛑️</div>
          <div style="font-family:var(--fh);font-size:13px;font-weight:700;color:var(--white);margin-top:5px;">HELMET</div>
          <div style="font-size:10px;color:var(--muted);">Laila</div>
        </div>
      </div>
    </div>
    <div class="card">
      <div style="font-family:var(--fm);font-size:10px;color:var(--muted);margin-bottom:8px;">AND SO OUR MACHINE</div>
      <p style="font-size:13.5px;color:var(--text);line-height:1.7;" contenteditable="false">Laila the machine exists to <strong style="color:var(--white);">clean, care for, and protect</strong> the rider's most loyal companion — deeply and automatically. In 60 seconds.</p>
    </div>
    <div class="card" style="padding:16px 18px;text-align:center;">
      <div style="font-family:var(--fh);font-size:32px;font-weight:800;"><span style="color:var(--white);">TIDY</span><span class="blue">RYDE</span></div>
      <div style="font-family:var(--fm);font-size:9px;color:var(--muted);letter-spacing:.15em;margin-top:2px;">PRESENTS</div>
      <div style="font-family:var(--fh);font-size:22px;font-weight:700;color:var(--pink);margin-top:4px;">Laila</div>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S4: MEET LAILA (PRODUCT CSS ART)
============================= -->
<div class="slide" id="s4">
<div class="inner" style="display:grid;grid-template-columns:1fr 1.05fr;gap:44px;align-items:center;">
  <div>
    <div class="eye" style="border-color:rgba(244,114,182,.3);color:var(--pink);">03 · The Machine</div>
    <div class="h2">Meet <span class="pink">Laila.</span></div>
    <p class="sub" contenteditable="false">A dual-function automated kiosk — deep cleans physically, sanitizes biologically — in one 60-second cycle. No human. No mess. No compromise.</p>
    <div class="hr"></div>
    <div class="g2" style="margin-top:4px;">
      <div style="background:var(--card);border:1px solid var(--border);border-radius:8px;padding:13px;">
        <div style="font-family:var(--fh);font-size:14px;font-weight:700;color:var(--blue);">QUICK CLEAN</div>
        <p style="font-size:12px;color:var(--muted);margin-top:4px;" contenteditable="false">Air + UV + mist. 30–45 sec. <strong style="color:var(--blue);">₹49</strong></p>
      </div>
      <div style="background:var(--card);border:1px solid rgba(45,212,191,.3);border-radius:8px;padding:13px;">
        <div style="font-family:var(--fh);font-size:14px;font-weight:700;color:var(--teal);">DEEP CLEAN</div>
        <p style="font-size:12px;color:var(--muted);margin-top:4px;" contenteditable="false">Wash + UV + sanitize + dry. 90 sec. <strong style="color:var(--teal);">₹89</strong></p>
      </div>
    </div>
    <div style="margin-top:12px;display:flex;flex-wrap:wrap;gap:4px;">
      <span class="pill pb">IoT / ESP32</span>
      <span class="pill pt">QR + UPI Pay</span>
      <span class="pill pl">Water Recycling</span>
      <span class="pill po">15" Ad Display</span>
      <span class="pill pb">Portable Wheels</span>
      <span class="pill pp">Auto Fault Alert</span>
    </div>
  </div>
  <!-- CSS Machine Art -->
  <div style="display:flex;justify-content:center;align-items:center;position:relative;">
    <div class="gring"></div>
    <div class="gring" style="width:290px;height:290px;border-color:rgba(56,189,248,.05);"></div>
    <div class="mach">
      <!-- screen -->
      <div class="mscr">
        <div class="mscr-bg"></div>
        <div class="mscr-t">CLEAN HELMET<br>SAFE RIDE</div>
        <div class="mscr-s">CLEAN | SANITIZE | DRY</div>
        <div style="position:absolute;right:0;top:0;bottom:0;width:45%;background:linear-gradient(90deg,transparent,rgba(56,189,248,.07));"></div>
      </div>
      <!-- qr strip -->
      <div class="mqr">
        <div class="mql"></div>
        <div class="mqrc">QR</div>
        <div class="mql"></div>
      </div>
      <!-- chambers -->
      <div class="mchm">
        <div class="mc">
          <div class="uvb" style="left:28%;height:44%;animation-delay:.3s;"></div>
          <div class="uvb" style="left:50%;height:54%;animation-delay:.9s;"></div>
          <div class="uvb" style="left:72%;height:40%;animation-delay:.6s;"></div>
          <svg width="34" height="30" viewBox="0 0 60 50" fill="none" style="position:relative;z-index:2;">
            <ellipse cx="30" cy="28" rx="22" ry="18" fill="#1a2535"/>
            <path d="M8 28 Q8 10 30 8 Q52 10 52 28" fill="#263548"/>
            <ellipse cx="30" cy="22" rx="12" ry="8" fill="rgba(56,189,248,0.1)" stroke="rgba(56,189,248,0.3)" stroke-width="0.5"/>
          </svg>
          <div class="mcl">QUICK CLEAN</div>
        </div>
        <div class="mc dp">
          <div class="uvb uvbd" style="left:26%;height:50%;animation-delay:.5s;"></div>
          <div class="uvb uvbd" style="left:50%;height:58%;animation-delay:1s;"></div>
          <div class="uvb uvbd" style="left:74%;height:44%;animation-delay:.2s;"></div>
          <svg width="34" height="30" viewBox="0 0 60 50" fill="none" style="position:relative;z-index:2;">
            <ellipse cx="30" cy="28" rx="22" ry="18" fill="#0d2020"/>
            <path d="M8 28 Q8 10 30 8 Q52 10 52 28" fill="#0f2a28"/>
            <ellipse cx="30" cy="22" rx="12" ry="8" fill="rgba(45,212,191,0.08)" stroke="rgba(45,212,191,0.3)" stroke-width="0.5"/>
          </svg>
          <div class="mcl">DEEP CLEAN</div>
        </div>
      </div>
      <!-- bottom -->
      <div class="mbot">
        <div style="width:9px;height:9px;border:1.5px solid rgba(56,189,248,.5);border-radius:2px;"></div>
        <span style="font-family:'Space Mono',monospace;font-size:6px;color:var(--muted);letter-spacing:.18em;">CLEAN · SAFE · SMART</span>
      </div>
    </div>
    <!-- Spec callouts -->
    <div style="position:absolute;left:-140px;top:70px;font-family:var(--fm);font-size:10px;color:var(--muted);text-align:right;line-height:2.2;">
      <div style="color:var(--text);">15" LCD Display</div>
      <div style="width:70px;height:1px;background:rgba(56,189,248,.25);margin:0 0 0 auto;"></div>
      <div style="color:var(--text);margin-top:10px;">ESP32 IoT</div>
      <div style="width:55px;height:1px;background:rgba(56,189,248,.25);margin:0 0 0 auto;"></div>
      <div style="color:var(--text);margin-top:10px;">QR Panel</div>
      <div style="width:60px;height:1px;background:rgba(56,189,248,.25);margin:0 0 0 auto;"></div>
    </div>
    <div style="position:absolute;right:-145px;top:90px;font-family:var(--fm);font-size:10px;color:var(--muted);line-height:2.2;">
      <div style="color:var(--blue);">UV-C Chamber</div>
      <div style="width:55px;height:1px;background:rgba(56,189,248,.25);"></div>
      <div style="color:var(--teal);margin-top:10px;">Mist Nozzles</div>
      <div style="width:50px;height:1px;background:rgba(45,212,191,.25);"></div>
      <div style="color:var(--text);margin-top:10px;">15L Water Tank</div>
      <div style="width:65px;height:1px;background:rgba(56,189,248,.25);"></div>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S5: GENZ DESIGN
============================= -->
<div class="slide" id="s5">
<div class="inner" style="display:grid;grid-template-columns:1fr 1fr;gap:44px;align-items:center;">
  <div style="display:flex;flex-direction:column;align-items:center;position:relative;">
    <!-- GenZ Machine -->
    <div class="gzm">
      <div class="gz-sl"></div>
      <div class="gz-stripe"></div>
      <div class="gzt">
        <div><div class="gztl">LAILA</div><div style="font-family:'Space Mono',monospace;font-size:6px;color:var(--muted);letter-spacing:.15em;">BY TIDYRYDE</div></div>
        <div style="display:flex;align-items:center;gap:7px;"><div style="font-family:'Space Mono',monospace;font-size:7px;color:var(--lime);">ONLINE</div><div class="gzst"></div></div>
      </div>
      <div class="gzcw">
        <div class="gzc">
          <div class="gzg"></div>
          <div style="font-size:26px;position:relative;z-index:2;margin-bottom:5px;">⚡</div>
          <div style="font-family:'Syne',sans-serif;font-weight:800;font-size:11px;color:var(--white);position:relative;z-index:2;">QUICK</div>
          <div style="font-family:'Space Mono',monospace;font-size:7px;color:var(--blue);position:relative;z-index:2;margin-top:3px;letter-spacing:.1em;">UV+MIST·30s</div>
          <div style="position:absolute;bottom:22px;font-family:'Syne',sans-serif;font-weight:800;font-size:16px;color:var(--blue);z-index:2;" contenteditable="false">₹49</div>
        </div>
        <div class="gzc dp2">
          <div class="gzg"></div>
          <div style="font-size:26px;position:relative;z-index:2;margin-bottom:5px;">💧</div>
          <div style="font-family:'Syne',sans-serif;font-weight:800;font-size:11px;color:var(--white);position:relative;z-index:2;">DEEP</div>
          <div style="font-family:'Space Mono',monospace;font-size:7px;color:var(--teal);position:relative;z-index:2;margin-top:3px;letter-spacing:.1em;">WASH·90s</div>
          <div style="position:absolute;bottom:22px;font-family:'Syne',sans-serif;font-weight:800;font-size:16px;color:var(--teal);z-index:2;" contenteditable="false">₹89</div>
        </div>
      </div>
      <div class="gzb">
        <div class="gzpb">
          <div><div style="font-family:'Space Mono',monospace;font-size:8px;color:var(--muted);">MAIN SERVICE</div><div style="font-family:'Syne',sans-serif;font-weight:800;font-size:20px;color:var(--blue);" contenteditable="false">₹49</div></div>
          <div style="text-align:right;"><div style="font-family:'Space Mono',monospace;font-size:8px;color:var(--muted);">DEEP CLEAN</div><div style="font-family:'Syne',sans-serif;font-weight:800;font-size:20px;color:var(--teal);" contenteditable="false">₹89</div></div>
        </div>
        <div class="gzqr">
          <div class="gzqrbox">
            <svg width="22" height="22" viewBox="0 0 22 22"><rect x="1" y="1" width="4" height="4" fill="#000"/><rect x="6" y="1" width="2" height="2" fill="#000"/><rect x="9" y="1" width="4" height="4" fill="#000"/><rect x="1" y="6" width="2" height="2" fill="#000"/><rect x="9" y="6" width="2" height="2" fill="#000"/><rect x="1" y="9" width="4" height="4" fill="#000"/><rect x="6" y="13" width="4" height="4" fill="#000"/><rect x="11" y="11" width="4" height="4" fill="#000"/><rect x="16" y="6" width="4" height="4" fill="#000"/><rect x="16" y="1" width="2" height="2" fill="#000"/><rect x="13" y="16" width="4" height="4" fill="#000"/><rect x="1" y="16" width="2" height="4" fill="#000"/><rect x="6" y="18" width="4" height="2" fill="#000"/></svg>
          </div>
          <div class="gzsc">SCAN TO START →</div>
        </div>
      </div>
    </div>
    <div style="width:140px;height:16px;background:radial-gradient(ellipse,rgba(56,189,248,.28),transparent);margin-top:6px;border-radius:50%;filter:blur(6px);"></div>
  </div>
  <div>
    <div class="eye">04 · Design Vision</div>
    <div class="h2">Laila,<br><span class="blue">Reimagined</span><br>for <span class="teal">Gen-Z.</span></div>
    <p class="sub" contenteditable="false">Same dual-clean tech. Same IoT backbone. Wrapped in a design that makes riders stop and stare.</p>
    <div class="hr"></div>
    <ul class="li">
      <li><span class="d"></span><strong style="color:var(--white);">Matte black shell</strong> — edge-lit acrylic chambers glow UV-blue from 10 metres away</li>
      <li><span class="d dt"></span><strong style="color:var(--white);">Tap-to-pay / QR + UPI</strong> — zero friction, no app download needed</li>
      <li><span class="d dl"></span><strong style="color:var(--white);">Live status countdown</strong> through transparent chamber — watch Laila work</li>
      <li><span class="d dp"></span><strong style="color:var(--white);">Portable on wheels</strong> — relocate to events, colleges, petrol pumps on demand</li>
      <li><span class="d do"></span><strong style="color:var(--white);">1800mm tall</strong> — designed to be noticed. The machine is the marketing.</li>
    </ul>
  </div>
</div>
</div>

<!-- ============================
  S6: HOW IT WORKS
============================= -->
<div class="slide" id="s6">
<div class="inner">
  <div class="eye">05 · Process</div>
  <div class="h2">Clean in <span class="blue">60 Seconds</span> Flat.</div>
  <div style="margin-top:24px;display:flex;border:1px solid var(--border);border-radius:11px;overflow:hidden;">
    <div style="flex:1;padding:18px 12px;text-align:center;border-right:1px solid var(--border);"><div style="font-size:22px;margin-bottom:6px;">📱</div><div style="font-family:var(--fh);font-size:13px;font-weight:700;color:var(--blue);">SCAN QR</div><div style="font-size:11px;color:var(--muted);margin-top:3px;">Any UPI app</div></div>
    <div style="display:flex;align-items:center;padding:0 2px;color:var(--border);font-size:18px;">›</div>
    <div style="flex:1;padding:18px 12px;text-align:center;border-right:1px solid var(--border);"><div style="font-size:22px;margin-bottom:6px;">☑️</div><div style="font-family:var(--fh);font-size:13px;font-weight:700;color:var(--white);">SELECT</div><div style="font-size:11px;color:var(--muted);margin-top:3px;">Quick or Deep</div></div>
    <div style="display:flex;align-items:center;padding:0 2px;color:var(--border);font-size:18px;">›</div>
    <div style="flex:1;padding:18px 12px;text-align:center;border-right:1px solid var(--border);"><div style="font-size:22px;margin-bottom:6px;">💳</div><div style="font-family:var(--fh);font-size:13px;font-weight:700;color:var(--white);">PAY</div><div style="font-size:11px;color:var(--muted);margin-top:3px;">₹49 / ₹89</div></div>
    <div style="display:flex;align-items:center;padding:0 2px;color:var(--border);font-size:18px;">›</div>
    <div style="flex:1;padding:18px 12px;text-align:center;border-right:1px solid var(--border);background:rgba(56,189,248,.04);"><div style="font-size:22px;margin-bottom:6px;">⚡</div><div style="font-family:var(--fh);font-size:13px;font-weight:700;color:var(--blue);">CYCLE</div><div style="font-size:11px;color:var(--muted);margin-top:3px;">60–90 seconds</div></div>
    <div style="display:flex;align-items:center;padding:0 2px;color:var(--border);font-size:18px;">›</div>
    <div style="flex:1;padding:18px 12px;text-align:center;border-right:1px solid var(--border);"><div style="font-size:22px;margin-bottom:6px;">📊</div><div style="font-family:var(--fh);font-size:13px;font-weight:700;color:var(--white);">STATUS</div><div style="font-size:11px;color:var(--muted);margin-top:3px;">Live display</div></div>
    <div style="display:flex;align-items:center;padding:0 2px;color:var(--border);font-size:18px;">›</div>
    <div style="flex:1;padding:18px 12px;text-align:center;background:rgba(163,230,53,.03);border-left:1px solid rgba(163,230,53,.2);"><div style="font-size:22px;margin-bottom:6px;">✅</div><div style="font-family:var(--fh);font-size:13px;font-weight:700;color:var(--lime);">DONE</div><div style="font-size:11px;color:var(--muted);margin-top:3px;">Take helmet</div></div>
  </div>
  <div class="g3" style="margin-top:16px;">
    <div class="card" style="padding:16px;">
      <div style="font-family:var(--fm);font-size:9px;color:var(--muted);margin-bottom:8px;">QUICK CLEAN CHAMBER</div>
      <ul class="li" style="font-size:12px;"><li><span class="d"></span>Air blower clears dust & debris</li><li><span class="d"></span>UV-C light sanitizes inner surface</li><li><span class="d"></span>Antimicrobial mist spray</li></ul>
    </div>
    <div class="card ct" style="padding:16px;">
      <div style="font-family:var(--fm);font-size:9px;color:var(--teal);margin-bottom:8px;">DEEP CLEAN CHAMBER</div>
      <ul class="li" style="font-size:12px;"><li><span class="d dt"></span>Pressurised water spray nozzles</li><li><span class="d dt"></span>UV-C sanitization full cycle</li><li><span class="d dt"></span>Hot air dry — exits clean & fresh</li></ul>
    </div>
    <div class="card" style="padding:16px;">
      <div style="font-family:var(--fm);font-size:9px;color:var(--muted);margin-bottom:8px;">IOT BACKBONE</div>
      <ul class="li" style="font-size:12px;"><li><span class="d dl"></span>ESP32 — real-time data logging</li><li><span class="d dl"></span>Auto fault detection + SMS alert</li><li><span class="d dl"></span>10L closed-loop water recycling</li></ul>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S7: MACHINE BLUEPRINT + COST
============================= -->
<div class="slide" id="s7">
<div class="inner">
  <div class="eye">06 · Machine Blueprint</div>
  <div class="h2">Built In-House.<br><span class="blue">₹80K–1.2L.</span> <span class="teal">Zero Compromise.</span></div>
  <div class="g2" style="margin-top:20px;gap:18px;">
    <div>
      <div class="card cb" style="padding:18px;margin-bottom:14px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--blue);margin-bottom:12px;">COMPONENT COST BREAKDOWN</div>
        <table style="width:100%;font-size:12.5px;border-collapse:collapse;">
          <tr><td style="color:var(--muted);padding:5px 0;">Steel chassis + fabrication (Okhla/Mayapuri)</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹14K–22K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Acrylic transparent chambers (x2, 8mm)</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹8K–13K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">UV-C germicidal lights + holders (x6)</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹4K–8K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Air blower + mist nozzle system</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹4K–7K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Water pump + spray nozzles + solenoid</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹3K–6K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Water tanks (15L + 20L + 10L reuse)</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹1.5K–3K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">ESP32 + PCB + relay + SMPS + MCB</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹4K–7K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">15" LCD display (refurb, Nehru Place)</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹5K–9K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">QR display panel (3.5" LCD)</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹1K–2K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Plumbing, wiring, LED, hardware</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹5K–9K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Caster wheels + branding wrap + paint</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹4K–7K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Assembly labour + contingency (10%)</td><td style="color:var(--text);text-align:right;" contenteditable="false">₹7K–12K</td></tr>
          <tr style="border-top:2px solid var(--blue);"><td style="color:var(--blue);padding:8px 0;font-weight:600;">TOTAL PILOT MACHINE</td><td style="color:var(--blue);text-align:right;font-weight:600;" contenteditable="false">₹61K–1.05L</td></tr>
        </table>
      </div>
    </div>
    <div style="display:flex;flex-direction:column;gap:14px;">
      <div class="card cl" style="padding:18px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--lime);margin-bottom:8px;">WHY SELF-BUILD?</div>
        <ul class="li">
          <li><span class="d dl"></span>OEM machines: ₹1.5–2.5L + still need customization</li>
          <li><span class="d dl"></span>Self-build: ₹61K–1.05L — same quality, full control</li>
          <li><span class="d dl"></span>We own every component. Easy to repair, upgrade, scale.</li>
          <li><span class="d dl"></span>Delhi fabricators (Okhla, Mayapuri) for body + chambers</li>
          <li><span class="d dl"></span>IndiaMART + local vendors for all tech components</li>
        </ul>
      </div>
      <div class="card" style="padding:18px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--muted);margin-bottom:8px;">SOURCING STRATEGY</div>
        <div style="display:flex;flex-wrap:wrap;gap:5px;">
          <span class="pill pb">IndiaMART OEMs</span>
          <span class="pill pt">Okhla Fabricators</span>
          <span class="pill pl">Nehru Place (Electronics)</span>
          <span class="pill po">Mayapuri (Metal Work)</span>
          <span class="pill pb">Alibaba (Bulk UV parts)</span>
        </div>
      </div>
      <div class="card cb" style="padding:16px 18px;text-align:center;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--blue);margin-bottom:6px;">TARGET PILOT BUDGET</div>
        <div class="bignum blue" style="font-size:44px;" contenteditable="false">₹80K–1.2L</div>
        <div class="lbl">all-in, including buffer for first build iterations</div>
      </div>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S8: PROFIT ANALYSIS ₹49
============================= -->
<div class="slide" id="s8">
<div class="inner">
  <div class="eye">07 · Unit Economics — Quick Clean</div>
  <div class="h2">₹49 Per Wash.<br><span class="lime">₹39 Goes to Us.</span></div>
  <div class="g2" style="margin-top:22px;gap:18px;">
    <div>
      <div class="card cb" style="margin-bottom:14px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--blue);margin-bottom:12px;">VARIABLE COST — QUICK CLEAN (PER USE)</div>
        <table style="width:100%;font-size:13px;border-collapse:collapse;">
          <tr><td style="color:var(--muted);padding:5px 0;">Electricity (2500W × 45sec cycle)</td><td style="color:var(--text);text-align:right;">₹0.50</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Antimicrobial mist solution (5ml)</td><td style="color:var(--text);text-align:right;">₹1.00</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">UV-C bulb amortization</td><td style="color:var(--text);text-align:right;">₹0.10</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Maintenance reserve (monthly)</td><td style="color:var(--text);text-align:right;">₹1.50</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">IoT / SIM data + misc</td><td style="color:var(--text);text-align:right;">₹0.90</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--blue);padding:6px 0;font-weight:600;">Variable Cost Per Use</td><td style="color:var(--blue);text-align:right;font-weight:600;">₹4.00</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">+ Machine amortisation (₹90K ÷ 21,600 uses)</td><td style="color:var(--text);text-align:right;">₹4.17</td></tr>
          <tr style="border-top:2px solid var(--teal);"><td style="color:var(--teal);padding:7px 0;font-weight:600;">Total Fully-Loaded Cost</td><td style="color:var(--teal);text-align:right;font-weight:600;">~₹8–10</td></tr>
        </table>
      </div>
    </div>
    <div style="display:flex;flex-direction:column;gap:14px;">
      <div style="display:flex;gap:10px;">
        <div class="card cb" style="flex:1;text-align:center;padding:18px 10px;">
          <div class="bignum blue" style="font-size:42px;" contenteditable="false">₹49</div>
          <div class="lbl">price per use</div>
        </div>
        <div style="display:flex;align-items:center;font-family:var(--fh);font-size:32px;font-weight:800;color:var(--muted);">−</div>
        <div class="card co" style="flex:1;text-align:center;padding:18px 10px;">
          <div class="bignum org" style="font-size:42px;" contenteditable="false">₹10</div>
          <div class="lbl">total cost</div>
        </div>
        <div style="display:flex;align-items:center;font-family:var(--fh);font-size:32px;font-weight:800;color:var(--muted);">=</div>
        <div class="card cl" style="flex:1;text-align:center;padding:18px 10px;border-width:2px;">
          <div class="bignum lime" style="font-size:42px;" contenteditable="false">₹39</div>
          <div class="lbl">net profit</div>
        </div>
      </div>
      <div class="card cl" style="padding:18px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--lime);margin-bottom:12px;">MONTHLY PROJECTION (20 USES/DAY)</div>
        <table style="width:100%;font-size:13px;border-collapse:collapse;">
          <tr><td style="color:var(--muted);padding:5px 0;">Daily revenue (20 × ₹49)</td><td style="color:var(--text);text-align:right;">₹980</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Monthly revenue (×30)</td><td style="color:var(--text);text-align:right;">₹29,400</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Monthly operating cost</td><td style="color:var(--text);text-align:right;">₹6,000</td></tr>
          <tr style="border-top:2px solid var(--lime);"><td style="color:var(--lime);padding:7px 0;font-weight:600;">Monthly net profit</td><td style="color:var(--lime);text-align:right;font-weight:600;">~₹23,400</td></tr>
        </table>
      </div>
      <div class="card" style="padding:16px;display:flex;gap:20px;align-items:center;">
        <div style="text-align:center;flex:1;">
          <div class="bignum teal" style="font-size:36px;" contenteditable="false">80%</div>
          <div class="lbl">gross margin</div>
        </div>
        <div style="width:1px;background:var(--border);height:40px;"></div>
        <div style="text-align:center;flex:1;">
          <div class="bignum blue" style="font-size:36px;" contenteditable="false">4–5</div>
          <div class="lbl">month payback</div>
        </div>
        <div style="width:1px;background:var(--border);height:40px;"></div>
        <div style="text-align:center;flex:1;">
          <div class="bignum lime" style="font-size:36px;" contenteditable="false">~3mo</div>
          <div class="lbl">at 30 uses/day</div>
        </div>
      </div>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S9: PROFIT ANALYSIS ₹89
============================= -->
<div class="slide" id="s9">
<div class="inner">
  <div class="eye">08 · Unit Economics — Deep Clean</div>
  <div class="h2">₹89. Proof We Can<br><span class="teal">Clean the Dirtiest Helmet.</span></div>
  <p class="sub" contenteditable="false">Deep clean is not our main revenue driver — it's our proof of capability. But it's also profitable.</p>
  <div class="g2" style="margin-top:18px;">
    <div>
      <div class="card ct" style="margin-bottom:14px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--teal);margin-bottom:12px;">ADDITIONAL COST OVER QUICK CLEAN</div>
        <table style="width:100%;font-size:13px;border-collapse:collapse;">
          <tr><td style="color:var(--muted);padding:5px 0;">Quick Clean base cost</td><td style="color:var(--blue);text-align:right;">₹10.00</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Extra electricity (pump + longer cycle)</td><td style="color:var(--text);text-align:right;">₹1.50</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Water (5L per wash × ₹0.50/L)</td><td style="color:var(--text);text-align:right;">₹2.50</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Cleaning agent / shampoo (15ml)</td><td style="color:var(--text);text-align:right;">₹3.00</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Higher pump + nozzle wear reserve</td><td style="color:var(--text);text-align:right;">₹2.00</td></tr>
          <tr style="border-top:2px solid var(--teal);"><td style="color:var(--teal);padding:7px 0;font-weight:600;">Total Cost — Deep Clean</td><td style="color:var(--teal);text-align:right;font-weight:600;">~₹19–21</td></tr>
        </table>
      </div>
    </div>
    <div style="display:flex;flex-direction:column;gap:14px;">
      <div style="display:flex;gap:10px;">
        <div class="card ct" style="flex:1;text-align:center;padding:18px 10px;">
          <div class="bignum teal" style="font-size:42px;" contenteditable="false">₹89</div>
          <div class="lbl">deep clean price</div>
        </div>
        <div style="display:flex;align-items:center;font-family:var(--fh);font-size:32px;font-weight:800;color:var(--muted);">−</div>
        <div class="card co" style="flex:1;text-align:center;padding:18px 10px;">
          <div class="bignum org" style="font-size:42px;" contenteditable="false">₹20</div>
          <div class="lbl">total cost</div>
        </div>
        <div style="display:flex;align-items:center;font-family:var(--fh);font-size:32px;font-weight:800;color:var(--muted);">=</div>
        <div class="card cl" style="flex:1;text-align:center;padding:18px 10px;border-width:2px;">
          <div class="bignum lime" style="font-size:42px;" contenteditable="false">₹69</div>
          <div class="lbl">net profit</div>
        </div>
      </div>
      <div class="card cp" style="padding:18px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--pink);margin-bottom:10px;">WHY ₹89 DEEP CLEAN EXISTS</div>
        <ul class="li">
          <li><span class="d dp"></span>Demonstrates our machine can handle the dirtiest helmets</li>
          <li><span class="d dp"></span>Premium positioning — this is the "show off" feature</li>
          <li><span class="d dp"></span>78% margin — still highly profitable when used</li>
          <li><span class="d dp"></span>Revenue model does NOT depend on deep clean frequency</li>
        </ul>
      </div>
      <div class="card cb" style="padding:14px 18px;">
        <p style="font-size:13.5px;color:var(--text);" contenteditable="false"><strong style="color:var(--blue);">Our core revenue engine is ₹49 quick cleans.</strong> Deep clean at ₹89 is proof of tech depth and a high-margin bonus service.</p>
      </div>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S10: COMPETITION
============================= -->
<div class="slide" id="s10">
<div class="inner">
  <div class="eye">09 · Competition</div>
  <div class="h2">Nobody's Built<br><span class="blue">What We're Building.</span></div>
  <table style="width:100%;border-collapse:collapse;font-size:12.5px;margin-top:24px;">
    <thead><tr>
      <th style="font-family:var(--fm);font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);padding:8px 10px;text-align:left;border-bottom:1px solid var(--border);">PLAYER</th>
      <th style="font-family:var(--fm);font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);padding:8px 10px;border-bottom:1px solid var(--border);">DEEP CLEAN</th>
      <th style="font-family:var(--fm);font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);padding:8px 10px;border-bottom:1px solid var(--border);">SANITIZE</th>
      <th style="font-family:var(--fm);font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);padding:8px 10px;border-bottom:1px solid var(--border);">BOTH TOGETHER</th>
      <th style="font-family:var(--fm);font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);padding:8px 10px;border-bottom:1px solid var(--border);">IOT ENABLED</th>
      <th style="font-family:var(--fm);font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);padding:8px 10px;border-bottom:1px solid var(--border);">QR PAYMENT</th>
      <th style="font-family:var(--fm);font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);padding:8px 10px;border-bottom:1px solid var(--border);">PORTABLE</th>
    </tr></thead>
    <tbody>
      <tr style="background:rgba(56,189,248,.05);">
        <td style="padding:10px;font-weight:600;color:var(--pink);border-left:2px solid var(--blue);">LAILA by TidyRyde ★</td>
        <td style="padding:10px;text-align:center;color:var(--teal);font-size:15px;">✓</td>
        <td style="padding:10px;text-align:center;color:var(--teal);font-size:15px;">✓</td>
        <td style="padding:10px;text-align:center;color:var(--teal);font-size:15px;">✓</td>
        <td style="padding:10px;text-align:center;color:var(--teal);font-size:15px;">✓</td>
        <td style="padding:10px;text-align:center;color:var(--teal);font-size:15px;">✓</td>
        <td style="padding:10px;text-align:center;color:var(--teal);font-size:15px;">✓</td>
      </tr>
      <tr style="border-bottom:1px solid rgba(30,45,64,.4);"><td style="padding:9px 10px;color:var(--text);">HelmoTech</td><td style="padding:9px;text-align:center;color:var(--orange);">~</td><td style="padding:9px;text-align:center;color:var(--orange);">~</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td></tr>
      <tr style="border-bottom:1px solid rgba(30,45,64,.4);"><td style="padding:9px 10px;color:var(--text);">Shield X Syndicate</td><td style="padding:9px;text-align:center;color:var(--orange);">~</td><td style="padding:9px;text-align:center;color:var(--teal);">✓</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--orange);">~</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td></tr>
      <tr style="border-bottom:1px solid rgba(30,45,64,.4);"><td style="padding:9px 10px;color:var(--text);">Hygienexpro</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--teal);">✓</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td></tr>
      <tr><td style="padding:9px 10px;color:var(--text);">Manual shops</td><td style="padding:9px;text-align:center;color:var(--orange);">~</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td><td style="padding:9px;text-align:center;color:var(--border);">✗</td></tr>
    </tbody>
  </table>
  <div class="card cb" style="margin-top:16px;padding:15px 20px;">
    <p style="font-size:14.5px;color:var(--text);" contenteditable="false">The market has either cleaning or sanitization — never both, never IoT, never QR payments, never portable. <strong style="color:var(--blue);">Laila does all six.</strong></p>
  </div>
</div>
</div>

<!-- ============================
  S11: LOCATIONS
============================= -->
<div class="slide" id="s11">
<div class="inner">
  <div class="eye">10 · Pilot Locations</div>
  <div class="h2">We Go Where<br><span class="blue">Riders Are.</span></div>
  <div class="g3" style="margin-top:22px;">
    <div class="card cb" style="padding:20px;">
      <div style="font-size:22px;margin-bottom:8px;">⛽</div>
      <div style="font-family:var(--fh);font-size:18px;font-weight:700;color:var(--white);margin-bottom:6px;">Petrol Pumps</div>
      <p style="font-size:13px;color:var(--muted);" contenteditable="false">Primary target. High two-wheeler footfall. Riders idle 5–8 min during refuelling — perfect cycle time. Delhi NCR to start.</p>
      <div style="margin-top:10px;display:flex;flex-wrap:wrap;gap:4px;"><span class="pill pb">High Traffic</span><span class="pill pb">Daily Repeat</span></div>
    </div>
    <div class="card ct" style="padding:20px;">
      <div style="font-size:22px;margin-bottom:8px;">🎓</div>
      <div style="font-family:var(--fh);font-size:18px;font-weight:700;color:var(--white);margin-bottom:6px;">Colleges</div>
      <p style="font-size:13px;color:var(--muted);" contenteditable="false">70%+ of college students in India ride bikes or scooters. Captive audience. Strong peer influence — one clean helmet sparks ten.</p>
      <div style="margin-top:10px;display:flex;flex-wrap:wrap;gap:4px;"><span class="pill pt">Gen-Z Users</span><span class="pill pt">Social Buzz</span></div>
    </div>
    <div class="card cl" style="padding:20px;">
      <div style="font-size:22px;margin-bottom:8px;">🏍️</div>
      <div style="font-family:var(--fh);font-size:18px;font-weight:700;color:var(--white);margin-bottom:6px;">Bike Events</div>
      <p style="font-size:13px;color:var(--muted);" contenteditable="false">Laila is portable on wheels. Roll her to rallies, melas, motosport events. Concentrated audience of helmet-owners. High impulse, premium use.</p>
      <div style="margin-top:10px;display:flex;flex-wrap:wrap;gap:4px;"><span class="pill pl">Portable</span><span class="pill pl">Event Play</span></div>
    </div>
  </div>
  <div class="card cb" style="margin-top:14px;padding:16px 20px;display:flex;align-items:center;gap:16px;">
    <div style="font-size:22px;flex-shrink:0;">🚀</div>
    <p style="font-size:14px;color:var(--text);" contenteditable="false"><strong style="color:var(--blue);">Phase 1 target:</strong> 2–3 petrol pumps in Delhi NCR + 1 college pilot. Validate 20+ uses/day. Then replicate and expand.</p>
  </div>
</div>
</div>

<!-- ============================
  S12: TRACTION
============================= -->
<div class="slide" id="s12">
<div class="inner">
  <div class="eye">11 · Where We Are</div>
  <div class="h2">Blueprint Done.<br><span class="blue">Build Starting.</span></div>
  <div class="g2" style="margin-top:20px;">
    <div>
      <div class="card cb" style="margin-bottom:14px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--blue);margin-bottom:11px;">COMPLETED</div>
        <ul class="li">
          <li><span class="d"></span>Dual-chamber machine design fully finalized</li>
          <li><span class="d"></span>Full component BOM locked (₹61K–1.05L)</li>
          <li><span class="d"></span>IoT architecture (ESP32 + water system) designed</li>
          <li><span class="d"></span>Unit economics validated: ₹10 cost / ₹49 price = ₹39 profit</li>
          <li><span class="d"></span>Vendor shortlist: Okhla fabricators + IndiaMART OEMs</li>
          <li><span class="d"></span>Pilot location shortlist: 3 petrol pumps + 2 colleges, Delhi NCR</li>
        </ul>
      </div>
      <div class="card cl">
        <div style="font-family:var(--fm);font-size:10px;color:var(--lime);margin-bottom:11px;">NEXT STEPS</div>
        <ul class="li">
          <li><span class="d dl"></span>Procure components from shortlisted vendors</li>
          <li><span class="d dl"></span>Build Pilot Machine #1 at Delhi workshop</li>
          <li><span class="d dl"></span>Deploy + validate 20 uses/day target</li>
        </ul>
      </div>
    </div>
    <div>
      <div class="card" style="margin-bottom:14px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--muted);margin-bottom:10px;">PILOT MACHINE BUDGET</div>
        <table style="width:100%;font-size:13px;border-collapse:collapse;">
          <tr><td style="color:var(--muted);padding:5px 0;">Components + fabrication</td><td style="color:var(--text);text-align:right;">₹61K–90K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Buffer (first-build iterations)</td><td style="color:var(--text);text-align:right;">₹10K–20K</td></tr>
          <tr style="border-top:1px solid var(--border);"><td style="color:var(--muted);padding:5px 0;">Legal / registration</td><td style="color:var(--text);text-align:right;">₹5K–10K</td></tr>
          <tr style="border-top:2px solid var(--blue);"><td style="color:var(--blue);padding:7px 0;font-weight:600;">Total Pilot Budget</td><td style="color:var(--blue);text-align:right;font-weight:600;">₹80K–1.2L</td></tr>
        </table>
      </div>
      <div class="card cb" style="text-align:center;padding:20px;">
        <div style="font-family:var(--fm);font-size:10px;color:var(--blue);margin-bottom:8px;">CURRENT STAGE</div>
        <div style="display:flex;align-items:center;justify-content:center;gap:8px;margin-bottom:6px;">
          <div style="width:8px;height:8px;background:var(--lime);border-radius:50%;"></div>
          <span style="font-weight:600;font-size:14px;color:var(--white);">Pre-launch · Pilot ready</span>
        </div>
        <p style="font-size:12px;color:var(--muted);" contenteditable="false">Not raising funds. Building with our own capital. Looking for pilot locations and build partners.</p>
      </div>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S13: ROADMAP (PHASE-BASED)
============================= -->
<div class="slide" id="s13">
<div class="inner">
  <div class="eye">12 · Roadmap</div>
  <div class="h2">The Plan is<br><span class="blue">Simple. Phase by Phase.</span></div>
  <div style="margin-top:24px;display:flex;flex-direction:column;gap:11px;">
    <div style="display:flex;gap:16px;align-items:stretch;">
      <div style="width:90px;flex-shrink:0;display:flex;flex-direction:column;align-items:center;justify-content:center;">
        <div style="font-family:var(--fh);font-size:36px;font-weight:800;color:var(--blue);opacity:.35;line-height:1;">01</div>
      </div>
      <div class="card cb" style="flex:1;padding:15px 20px;">
        <div style="font-weight:600;font-size:14px;color:var(--white);margin-bottom:4px;" contenteditable="false">BUILD PILOT MACHINE #1</div>
        <p style="font-size:12.5px;color:var(--muted);" contenteditable="false">Procure all components. Fabricate first Laila unit at Delhi workshop. Test all systems. Deploy at first petrol pump in Delhi NCR.</p>
      </div>
    </div>
    <div style="display:flex;gap:16px;align-items:stretch;">
      <div style="width:90px;flex-shrink:0;display:flex;flex-direction:column;align-items:center;justify-content:center;">
        <div style="font-family:var(--fh);font-size:36px;font-weight:800;color:var(--blue);opacity:.25;line-height:1;">02</div>
      </div>
      <div class="card" style="flex:1;padding:15px 20px;">
        <div style="font-weight:600;font-size:14px;color:var(--white);margin-bottom:4px;" contenteditable="false">VALIDATE + COLLEGE ENTRY</div>
        <p style="font-size:12.5px;color:var(--muted);" contenteditable="false">Hit 20+ uses/day. Iterate on UX and pricing. Deploy at 1 college. Attend first bike event with portable Laila. Build social content.</p>
      </div>
    </div>
    <div style="display:flex;gap:16px;align-items:stretch;">
      <div style="width:90px;flex-shrink:0;display:flex;flex-direction:column;align-items:center;justify-content:center;">
        <div style="font-family:var(--fh);font-size:36px;font-weight:800;color:var(--blue);opacity:.2;line-height:1;">03</div>
      </div>
      <div class="card" style="flex:1;padding:15px 20px;">
        <div style="font-weight:600;font-size:14px;color:var(--white);margin-bottom:4px;" contenteditable="false">3–5 MACHINES · DELHI NCR</div>
        <p style="font-size:12.5px;color:var(--muted);" contenteditable="false">Scale to 5 machines across Delhi NCR. Mix of petrol pumps + colleges + events. Build IoT monitoring dashboard. First profitable month.</p>
      </div>
    </div>
    <div style="display:flex;gap:16px;align-items:stretch;">
      <div style="width:90px;flex-shrink:0;display:flex;flex-direction:column;align-items:center;justify-content:center;">
        <div style="font-family:var(--fh);font-size:36px;font-weight:800;color:var(--blue);opacity:.15;line-height:1;">04</div>
      </div>
      <div class="card" style="flex:1;padding:15px 20px;">
        <div style="font-weight:600;font-size:14px;color:var(--white);margin-bottom:4px;" contenteditable="false">15–20 MACHINES · 2 CITIES</div>
        <p style="font-size:12.5px;color:var(--muted);" contenteditable="false">Expand to Bangalore or Pune. Build Laila v2 (improved design, faster cycle). ₹3–5L/month revenue. Consider external capital.</p>
      </div>
    </div>
  </div>
</div>
</div>

<!-- ============================
  S14: VISION
============================= -->
<div class="slide" id="s14" style="background:radial-gradient(ellipse at center,rgba(56,189,248,.1) 0%,transparent 65%),var(--bg);">
<div class="inner" style="display:flex;flex-direction:column;align-items:center;text-align:center;">
  <div class="eye">13 · Vision</div>
  <div class="h1" style="font-size:clamp(34px,5.2vw,76px);margin-top:8px;max-width:880px;line-height:1.05;" contenteditable="false">
    Every petrol pump.<br>Every college gate.<br>Every bike rally.<br>
    <span class="pink">One Laila.</span>
  </div>
  <p style="font-size:15px;color:var(--muted);max-width:560px;margin-top:20px;line-height:1.75;" contenteditable="false">We're not just building a cleaning machine. We're building the default infrastructure for helmet hygiene in India. The product is simple. The opportunity is massive.</p>
  <div style="display:flex;gap:40px;margin-top:32px;flex-wrap:wrap;justify-content:center;">
    <div style="text-align:center;"><div class="bignum blue" style="font-size:52px;" contenteditable="false">100+</div><div class="lbl">machines target</div></div>
    <div style="width:1px;background:var(--border);"></div>
    <div style="text-align:center;"><div class="bignum teal" style="font-size:52px;" contenteditable="false">10</div><div class="lbl">cities · year 3</div></div>
    <div style="width:1px;background:var(--border);"></div>
    <div style="text-align:center;"><div class="bignum lime" style="font-size:52px;" contenteditable="false">₹12Cr</div><div class="lbl">revenue run rate</div></div>
  </div>
</div>
</div>

<!-- ============================
  S15: CLOSE
============================= -->
<div class="slide" id="s15" style="background:radial-gradient(ellipse at 60% 70%,rgba(45,212,191,.07) 0%,transparent 55%),var(--bg);">
<div class="inner">
  <div class="eye" style="border-color:rgba(45,212,191,.3);color:var(--teal);">14 · Let's Go</div>
  <div class="h1" style="font-size:clamp(36px,5.2vw,74px);" contenteditable="false">Not Fundraising.<br><span class="blue">Looking For</span><br><span class="pink">Pilot Locations.</span></div>
  <p class="sub" contenteditable="false">We want to deploy the first Laila at your petrol pump or college. We handle installation, maintenance, and operations. You provide the space.</p>
  <div class="g3" style="margin-top:24px;">
    <div class="card cb" style="padding:20px;text-align:center;"><div style="font-size:20px;">⛽</div><div style="font-family:var(--fh);font-size:17px;font-weight:700;color:var(--white);margin:7px 0;" contenteditable="false">Petrol Pump Owner?</div><p style="font-size:12.5px;color:var(--muted);" contenteditable="false">Let Laila sit at your station. Your customers get a service they've never had before.</p></div>
    <div class="card" style="padding:20px;text-align:center;"><div style="font-size:20px;">🎓</div><div style="font-family:var(--fh);font-size:17px;font-weight:700;color:var(--white);margin:7px 0;" contenteditable="false">College / Hostel?</div><p style="font-size:12.5px;color:var(--muted);" contenteditable="false">Students will love it. We keep it running. Zero hassle for administration.</p></div>
    <div class="card cl" style="padding:20px;text-align:center;"><div style="font-size:20px;">🏍️</div><div style="font-family:var(--fh);font-size:17px;font-weight:700;color:var(--white);margin:7px 0;" contenteditable="false">Organizing an Event?</div><p style="font-size:12.5px;color:var(--muted);" contenteditable="false">Laila is portable. We roll to your bike rally, set up, operate, and take down.</p></div>
  </div>
  <div class="card" style="margin-top:16px;padding:16px 22px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:14px;border-color:rgba(244,114,182,.28);">
    <div><div style="font-family:var(--fh);font-size:24px;font-weight:800;"><span style="color:var(--white);">TIDY</span><span class="blue">RYDE</span> <span style="font-size:15px;color:var(--muted);">/ Laila</span></div><div style="font-family:var(--fm);font-size:9px;color:var(--muted);margin-top:2px;letter-spacing:.15em;">CLEAN HELMET. SAFE RIDER. EVERY TIME.</div></div>
    <div style="text-align:right;"><div style="font-size:13.5px;color:var(--text);" contenteditable="false">Pre-launch · Pilot build in progress</div><div style="font-size:12px;color:var(--muted);margin-top:2px;" contenteditable="false">Delhi NCR · Made in India 🇮🇳</div></div>
  </div>
</div>
</div>

</div><!-- /deck -->

<!-- NAV -->
<div id="nav">
  <button onclick="go(-1)">‹</button>
  <div class="dots" id="dots"></div>
  <button onclick="go(1)">›</button>
  <span id="ctr" style="margin-left:5px;">1/15</span>
</div>

<script>
const SN=['Title','Problem','Why Laila?','Meet Laila','Design Vision','How It Works','Machine Blueprint','Economics · ₹49','Economics · ₹89','Competition','Pilot Locations','Traction','Roadmap','Vision','Close'];
const slides=document.querySelectorAll('.slide');
const N=slides.length;
let cur=0,editMode=false;

// Build dots
const dotsEl=document.getElementById('dots');
for(let i=0;i<N;i++){const d=document.createElement('div');d.className='dot';d.onclick=()=>show(i);d.title=SN[i]||'';dotsEl.appendChild(d);}

function show(n){
  slides[cur].classList.remove('active');
  cur=(n+N)%N;
  slides[cur].classList.add('active');
  document.getElementById('ctr').textContent=(cur+1)+'/'+N;
  document.getElementById('slbl').textContent=String(cur+1).padStart(2,'0')+'/'+N+' · '+(SN[cur]||'');
  document.getElementById('bar').style.width=((cur+1)/N*100)+'%';
  document.querySelectorAll('.dot').forEach((d,i)=>d.classList.toggle('on',i===cur));
}
function go(d){show(cur+d);}
document.addEventListener('keydown',e=>{
  if(e.key==='ArrowRight'||e.key==='ArrowDown')go(1);
  if(e.key==='ArrowLeft'||e.key==='ArrowUp')go(-1);
  if(e.key.toLowerCase()==='e')toggleEdit();
});
let tx=0;
document.addEventListener('touchstart',e=>tx=e.touches[0].clientX);
document.addEventListener('touchend',e=>{if(Math.abs(tx-e.changedTouches[0].clientX)>50)go(tx>e.changedTouches[0].clientX?1:-1);});

function toggleEdit(){
  editMode=!editMode;
  document.body.classList.toggle('edit',editMode);
  const b=document.getElementById('editBtn');
  b.classList.toggle('on',editMode);
  b.textContent=editMode?'✓ EDITING':'✏ EDIT';
  document.querySelectorAll('[contenteditable]').forEach(el=>el.setAttribute('contenteditable',editMode?'true':'false'));
  toast(editMode?'Edit mode ON — click any text to edit. Press E to toggle.':'Edit mode OFF.');
}

function dlHTML(){
  const blob=new Blob(['<!DOCTYPE html>'+document.documentElement.outerHTML],{type:'text/html'});
  const a=document.createElement('a');a.href=URL.createObjectURL(blob);a.download='TidyRyde_Laila_PitchDeck.html';a.click();
  toast('HTML file downloading...');
}

function dlPDF(){
  toast('Opening print dialog — select "Save as PDF" in your browser.');
  setTimeout(()=>window.print(),400);
}

function toast(msg){
  let t=document.getElementById('_toast');
  if(!t){t=document.createElement('div');t.id='_toast';Object.assign(t.style,{position:'fixed',bottom:'76px',left:'50%',transform:'translateX(-50%)',background:'#111827',border:'1px solid #1e2d40',color:'#e2e8f0',fontFamily:'Space Mono,monospace',fontSize:'11px',padding:'9px 18px',borderRadius:'6px',zIndex:'500',transition:'opacity .3s',whiteSpace:'nowrap'});document.body.appendChild(t);}
  t.textContent=msg;t.style.opacity='1';
  clearTimeout(t._t);t._t=setTimeout(()=>t.style.opacity='0',3000);
}

show(0);
</script>

<style>
@media print{
  #nav,#toolbar,#bar{display:none!important;}
  body{overflow:visible!important;}
  .deck{height:auto!important;}
  .slide{position:relative!important;opacity:1!important;pointer-events:all!important;page-break-after:always;min-height:100vh;display:flex!important;break-inside:avoid;}
  .slide::before{display:none;}
}
</style>
</body>
</html>
