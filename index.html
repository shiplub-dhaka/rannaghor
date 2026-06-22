<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover"/>
<title>Rannaghor · রান্নাঘর</title>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,600;9..144,700&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet"/>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2/dist/umd/supabase.js"></script>
<style>
/* CONFIGURE SUPABASE BELOW */
:root{--herb:#1B6E47;--herb-d:#0F5A39;--herb-s:#E5F0EA;--saff:#E2941F;--saff-s:#FBEFD9;--tom:#D1493A;--tom-s:#FBE7E3;--paper:#FBF7F0;--ink:#1C2B23;--muted:#7C6F5C;--line:#ECE3D4;--card:#fff;--ui:'Plus Jakarta Sans',system-ui,sans-serif;--dp:'Fraunces',Georgia,serif;}
*{box-sizing:border-box;margin:0;padding:0;}
html,body{font-family:var(--ui);background:var(--paper);color:var(--ink);-webkit-font-smoothing:antialiased;}
body{padding-bottom:76px;}
button,input,select,textarea{font-family:inherit;}
button{cursor:pointer;border:none;background:none;color:inherit;}
a{color:var(--herb-d);text-decoration:none;}
::-webkit-scrollbar{width:5px;height:5px;}::-webkit-scrollbar-thumb{background:#D0C8B8;border-radius:99px;}
img{display:block;max-width:100%;}
.wrap{max-width:1080px;margin:0 auto;padding:0 16px;}
.card{background:var(--card);border:1px solid var(--line);border-radius:18px;}
.grid{display:grid;gap:12px;grid-template-columns:repeat(auto-fill,minmax(155px,1fr));}
@media(min-width:540px){.grid{grid-template-columns:repeat(auto-fill,minmax(190px,1fr));}}
@media(min-width:900px){.grid{grid-template-columns:repeat(auto-fill,minmax(210px,1fr));}}
header{position:sticky;top:0;z-index:30;background:rgba(251,247,240,.94);backdrop-filter:blur(10px);border-bottom:1px solid var(--line);}
.brand{display:flex;align-items:center;gap:12px;padding:12px 0;}
.logo{width:40px;height:40px;border-radius:13px;background:linear-gradient(135deg,#1B6E47,#2E9A66);display:flex;align-items:center;justify-content:center;font-size:20px;flex-shrink:0;}
.brand h1{font-family:var(--dp);font-size:21px;font-weight:700;line-height:1;}
.brand .sub{font-size:11.5px;color:var(--muted);margin-top:2px;}
.hdr-right{margin-left:auto;display:flex;align-items:center;gap:8px;}
.av-btn{width:34px;height:34px;border-radius:50%;background:var(--herb-s);border:1.5px solid var(--herb);display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700;color:var(--herb-d);cursor:pointer;}
nav.tabs{position:fixed;bottom:0;left:0;right:0;z-index:40;background:rgba(255,255,255,.97);backdrop-filter:blur(10px);border-top:1px solid var(--line);display:flex;padding:6px 4px max(8px,env(safe-area-inset-bottom)) 4px;}
.tab{flex:1;display:flex;flex-direction:column;align-items:center;gap:3px;padding:5px 2px;color:#9A8C75;font-size:10.5px;font-weight:600;}
.tab.on{color:var(--herb-d);}
.tab svg{width:20px;height:20px;stroke:currentColor;fill:none;stroke-width:2;stroke-linecap:round;stroke-linejoin:round;}
main{padding:14px 0;}
.view{display:none;}.view.on{display:block;}
.inp{width:100%;padding:10px 12px;border-radius:12px;border:1px solid var(--line);background:#FCFAF5;font-size:14px;color:var(--ink);}
.inp:focus{border-color:var(--herb);outline:none;}
.inp.pl{padding-left:36px;}
.s-wrap{position:relative;}
.s-ico{position:absolute;left:11px;top:50%;transform:translateY(-50%);pointer-events:none;color:#A89A84;}
textarea.inp{resize:vertical;min-height:50px;}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:7px;padding:10px 14px;border-radius:12px;font-weight:700;font-size:13.5px;}
.btn:active{transform:scale(.97);}
.btn-g{background:var(--herb);color:#fff;}
.btn-w{background:#fff;border:1px solid var(--line);color:#5B5142;}
.btn-b{width:100%;}
.pill{display:inline-flex;align-items:center;gap:4px;font-size:11px;font-weight:600;padding:3px 8px;border-radius:99px;}
.p-g{background:var(--herb-s);color:var(--herb-d);}
.p-s{background:var(--saff-s);color:#9C6406;}
.p-t{background:var(--tom-s);color:#B23120;}
.p-i{background:#F3EEE3;color:#5B5142;}
.chips{display:flex;gap:6px;overflow-x:auto;padding:2px 0 4px;scrollbar-width:none;}
.chips::-webkit-scrollbar{display:none;}
.chip{white-space:nowrap;padding:6px 12px;border-radius:99px;border:1px solid var(--line);background:#fff;color:var(--muted);font-weight:600;font-size:13px;}
.chip.on{background:var(--herb);border-color:var(--herb);color:#fff;}
.lbl{display:flex;align-items:center;gap:7px;font-size:12.5px;font-weight:700;color:#5B5142;margin-bottom:9px;}
.lbl svg{color:var(--herb);}
.av{border-radius:50%;background:var(--herb-s);color:var(--herb-d);font-weight:700;display:inline-flex;align-items:center;justify-content:center;border:1px solid #CFE3D7;flex-shrink:0;}
.rcard{position:relative;overflow:hidden;background:var(--card);border:1px solid var(--line);border-radius:18px;transition:transform .15s,box-shadow .15s;cursor:pointer;}
.rcard:hover{transform:translateY(-2px);box-shadow:0 6px 20px rgba(0,0,0,.08);}
.rthumb{position:relative;height:116px;overflow:hidden;background:linear-gradient(135deg,#2C7A7B,#4FB0B2);}
.rthumb img{width:100%;height:100%;object-fit:cover;}
.rthumb .em{position:absolute;left:10px;top:8px;font-size:30px;z-index:1;}
.rthumb .abadge{position:absolute;left:8px;bottom:8px;background:rgba(255,255,255,.93);border-radius:99px;padding:2px 8px;font-size:10.5px;font-weight:700;color:#3A3327;z-index:1;}
.rthumb .hbtn{position:absolute;right:8px;top:8px;width:30px;height:30px;border-radius:50%;background:rgba(255,255,255,.93);display:flex;align-items:center;justify-content:center;z-index:2;}
.rbody{padding:10px 12px 12px;}
.rname{font-family:var(--dp);font-size:15px;font-weight:600;line-height:1.2;margin-bottom:6px;}
.rmeta{display:flex;flex-wrap:wrap;gap:7px;font-size:11.5px;color:var(--muted);margin-bottom:8px;}
.rmeta span{display:inline-flex;align-items:center;gap:3px;}
.shimmer{background:linear-gradient(90deg,#f0ece4 25%,#e8e4dc 50%,#f0ece4 75%);background-size:200% 100%;animation:sh 1.4s infinite;border-radius:18px;height:190px;}
@keyframes sh{0%{background-position:200% 0}100%{background-position:-200% 0}}
.scrim{position:fixed;inset:0;z-index:60;background:rgba(28,43,35,.5);display:flex;align-items:flex-end;justify-content:center;animation:fi .2s;}
@keyframes fi{from{opacity:0}to{opacity:1}}
.sheet{background:var(--paper);width:100%;max-width:680px;max-height:94vh;overflow-y:auto;border-radius:20px 20px 0 0;border-top:1px solid var(--line);animation:si .22s cubic-bezier(.32,.72,0,1);}
@keyframes si{from{transform:translateY(50px);opacity:0}to{transform:translateY(0);opacity:1}}
.s-hero{position:relative;height:190px;overflow:hidden;background:#2C7A7B;}
.s-hero img{width:100%;height:100%;object-fit:cover;}
.s-close{position:absolute;right:12px;top:12px;width:34px;height:34px;border-radius:50%;background:rgba(255,255,255,.93);display:flex;align-items:center;justify-content:center;z-index:2;}
.s-pad{padding:18px;}
.s-pad h2{font-family:var(--dp);font-size:23px;font-weight:700;line-height:1.1;margin-bottom:8px;}
.meta-r{display:flex;flex-wrap:wrap;gap:8px;align-items:center;font-size:13px;color:var(--muted);margin-bottom:14px;}
.yt-box{position:relative;padding-bottom:56.25%;height:0;border-radius:12px;overflow:hidden;background:#000;margin-bottom:14px;}
.yt-box iframe{position:absolute;inset:0;width:100%;height:100%;border:none;}
.yt-ph{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:10px;cursor:pointer;}
.yt-ph img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;opacity:.6;}
.yt-ph .play{position:relative;z-index:1;width:54px;height:54px;border-radius:50%;background:#FF0000;display:flex;align-items:center;justify-content:center;}
.yt-ph .ptitle{position:relative;z-index:1;color:#fff;font-weight:700;font-size:14px;text-align:center;padding:0 16px;}
.ing-item{display:flex;align-items:center;justify-content:space-between;gap:8px;padding:10px 13px;border-top:1px solid #F1EADC;}
.ing-item:first-child{border-top:none;}
.ichk{width:18px;height:18px;border-radius:5px;display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.step{display:flex;gap:11px;margin-bottom:10px;}
.stepn{width:24px;height:24px;border-radius:50%;background:var(--herb);color:#fff;font-size:12px;font-weight:700;display:flex;align-items:center;justify-content:center;flex-shrink:0;margin-top:2px;}
.star-row{display:flex;gap:3px;margin-bottom:8px;}
.toast{position:fixed;left:50%;bottom:88px;transform:translateX(-50%) translateY(10px);background:#1C2B23;color:#fff;padding:10px 16px;border-radius:99px;font-size:13.5px;font-weight:600;z-index:90;pointer-events:none;opacity:0;transition:opacity .2s,transform .2s;box-shadow:0 8px 24px rgba(0,0,0,.2);}
.toast.show{opacity:1;transform:translateX(-50%) translateY(0);}
.day-card{padding:12px;margin-bottom:10px;}
.day-card .dn{font-weight:700;font-size:14px;margin-bottom:10px;}
.slot-h{display:flex;align-items:center;justify-content:space-between;margin-bottom:5px;}
.slot-lbl{font-size:11px;font-weight:700;color:#9A8C75;text-transform:uppercase;letter-spacing:.4px;}
.plan-item{display:flex;align-items:center;gap:8px;padding:8px 10px;border-radius:12px;background:#FAF6EE;border:1px solid #F0E9DA;margin-bottom:5px;}
.plan-th{width:36px;height:36px;border-radius:8px;object-fit:cover;flex-shrink:0;background:var(--herb-s);}
.banner{padding:11px 14px;border-radius:12px;font-size:13px;line-height:1.5;margin-bottom:14px;}
.ban-s{background:var(--saff-s);color:#9C6406;border:1px solid #F1DDB6;}
.ban-g{background:var(--herb-s);color:var(--herb-d);border:1px solid #BDD9C8;}
.spin{width:22px;height:22px;border:3px solid var(--line);border-top-color:var(--herb);border-radius:50%;animation:spn .7s linear infinite;margin:28px auto;}
@keyframes spn{to{transform:rotate(360deg)}}
.ptag{display:inline-flex;align-items:center;gap:5px;background:#F3EEE3;color:#5B5142;font-size:12.5px;font-weight:600;padding:4px 6px 4px 10px;border-radius:99px;}
.empty{padding:30px 20px;text-align:center;}
.empty .eic{width:48px;height:48px;border-radius:14px;background:var(--herb-s);display:inline-flex;align-items:center;justify-content:center;margin-bottom:12px;color:var(--herb);}
.empty h3{font-family:var(--dp);font-size:17px;font-weight:600;margin-bottom:5px;}
.empty p{font-size:13.5px;color:var(--muted);max-width:360px;margin:0 auto;line-height:1.5;}
.h-sect{display:flex;align-items:baseline;justify-content:space-between;margin:4px 2px 14px;}
.h-sect h2{font-family:var(--dp);font-size:19px;font-weight:600;}
.fl{font-size:12px;font-weight:700;color:#7C6F5C;margin-bottom:6px;}
.eater-btn{display:inline-flex;align-items:center;gap:6px;padding:5px 10px 5px 6px;border-radius:99px;border:1px solid;font-weight:600;font-size:13px;}
.src-badge{display:inline-flex;align-items:center;gap:5px;font-size:11px;font-weight:700;padding:3px 8px;border-radius:99px;background:var(--saff-s);color:#9C6406;text-decoration:none;}
</style>
</head>
<body>
<script>
const SB_URL='https://qdtahllshgdvqexcpazc.supabase.co';
const SB_KEY='eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InFkdGFobGxzaGdkdnFleGNwYXpjIiwicm9sZSI6ImFub24iLCJpYXQiOjE3ODIwMjQ2NzMsImV4cCI6MjA5NzYwMDY3M30.7AR4Enc2nYVUBTqi7KJ002fJ_gmxqamsd02ATUdPeug';
</script>

<header>
  <div class="wrap">
    <div class="brand">
      <div class="logo">🍳</div>
      <div>
        <h1>Rannaghor <span style="font-size:13px;color:#9A8C75;font-weight:600;">রান্নাঘর</span></h1>
        <div class="sub" id="recipeCounter">Loading recipes…</div>
      </div>
      <div class="hdr-right">
        <div id="userAv" class="av-btn" style="display:none;cursor:pointer;"></div>
        <button id="authBtn" class="btn btn-g" style="padding:8px 13px;font-size:13px;display:none;"></button>
      </div>
    </div>
  </div>
</header>

<main class="wrap">
  <section class="view on" id="v-discover">
    <div id="apiStatus"></div>
    <div class="card" style="padding:14px;margin-bottom:14px;">
      <div class="s-wrap" style="margin-bottom:10px;">
        <span class="s-ico" id="sIco"></span>
        <input id="searchQ" class="inp pl" placeholder="Search 250+ recipes — biryani, pasta, chicken curry…" autocomplete="off"/>
      </div>
      <div style="display:flex;gap:8px;flex-wrap:wrap;">
        <button class="btn btn-g" id="haveBtn"></button>
        <button class="btn btn-w" id="surpriseBtn"></button>
        <button class="btn btn-w" id="vegBtn"></button>
      </div>
    </div>
    <div class="card" style="padding:14px;margin-bottom:14px;">
      <div style="margin-bottom:12px;"><div class="lbl" id="cuisLbl"></div><div class="chips" id="cuisChips"></div></div>
      <div><div class="lbl" id="catLbl"></div><div class="chips" id="catChips"></div></div>
    </div>
    <div class="h-sect"><h2 id="resTitle">Popular recipes</h2><span class="muted" id="resSub" style="font-size:12.5px;"></span></div>
    <div id="resGrid"></div>
  </section>

  <section class="view" id="v-planner">
    <div class="h-sect"><h2>This week</h2><span class="muted" id="planCount" style="font-size:12.5px;"></span></div>
    <div id="planEmpty"></div><div id="planGrid"></div>
    <h2 style="font-family:var(--dp);font-size:19px;font-weight:600;margin:18px 2px 14px;">Shopping list</h2>
    <div class="card" style="padding:14px;" id="shopBox"></div>
  </section>

  <section class="view" id="v-pantry">
    <h2 style="font-family:var(--dp);font-size:19px;font-weight:600;margin-bottom:4px;">Your pantry</h2>
    <p class="muted" style="font-size:13px;margin-bottom:14px;">What you have — used to show what you can cook right now.</p>
    <div id="panBanner"></div>
    <div class="card" style="padding:14px;margin-bottom:14px;">
      <div style="display:flex;gap:8px;">
        <input id="panInp" class="inp" placeholder="Add an ingredient (e.g. chicken, rice, egg)…" style="flex:1;" autocomplete="off"/>
        <button class="btn btn-g" id="panAdd" style="padding:0 16px;flex-shrink:0;"></button>
      </div>
    </div>
    <div id="panTags" style="display:flex;flex-wrap:wrap;gap:7px;"></div>
  </section>

  <section class="view" id="v-saved">
    <div class="h-sect"><h2>Saved recipes</h2><span class="muted" id="savedCount" style="font-size:12.5px;"></span></div>
    <div id="savedEmpty"></div><div id="savedGrid" class="grid"></div>
  </section>

  <section class="view" id="v-household">
    <div class="h-sect"><h2>Household</h2><button class="btn btn-g" id="addMemberBtn" style="padding:8px 13px;font-size:13px;"></button></div>
    <p class="muted" id="hhSub" style="font-size:13px;margin-bottom:14px;"></p>
    <div class="grid" id="memberGrid"></div>
  </section>

  <section class="view" id="v-account">
    <div class="card" style="padding:22px;max-width:440px;margin:0 auto;" id="accountCard"></div>
  </section>
</main>

<nav class="tabs" id="tabbar"></nav>
<div id="modalRoot"></div>
<div class="toast" id="toast"></div>

<script>
/* ═══ ICONS ═══ */
const P={search:'<circle cx="11" cy="11" r="7"/><line x1="21" y1="21" x2="16.65" y2="16.65"/>',x:'<line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/>',plus:'<line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/>',check:'<polyline points="20 6 9 17 4 12"/>',trash:'<polyline points="3 6 21 6"/><path d="M19 6l-1 14a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2L5 6"/><path d="M10 11v6M14 11v6"/>',star:'<polygon points="12 2 15.1 8.6 22 9.3 17 14 18.2 21 12 17.5 5.8 21 7 14 2 9.3 8.9 8.6 12 2"/>',heart:'<path d="M20.8 4.6a5.5 5.5 0 0 0-7.8 0L12 5.7l-1-1.1a5.5 5.5 0 1 0-7.8 7.8l1 1.1L12 21l7.8-7.5 1-1.1a5.5 5.5 0 0 0 0-7.8z"/>',clock:'<circle cx="12" cy="12" r="9"/><polyline points="12 7 12 12 16 14"/>',play:'<polygon points="6 4 20 12 6 20 6 4"/>',share:'<circle cx="18" cy="5" r="3"/><circle cx="6" cy="12" r="3"/><circle cx="18" cy="19" r="3"/><line x1="8.6" y1="13.5" x2="15.4" y2="17.5"/><line x1="15.4" y1="6.5" x2="8.6" y2="10.5"/>',calendar:'<rect x="3" y="4" width="18" height="18" rx="2"/><line x1="3" y1="9" x2="21" y2="9"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="16" y1="2" x2="16" y2="6"/>',users:'<path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.9"/><path d="M16 3.1a4 4 0 0 1 0 7.8"/>',basket:'<path d="M5 9l-2 9a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2l-2-9"/><path d="M3 9h18"/><path d="M8 9l4-6 4 6"/>',chef:'<path d="M6 13a4 4 0 1 1 1-7.9A4.5 4.5 0 0 1 17 5.1 4 4 0 1 1 18 13"/><path d="M6 13v6a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1v-6"/>',flame:'<path d="M12 2c2 4-1 6-1 9a3 3 0 0 0 6 0c0-1-1-3-1-3 3 2 4 5 4 7a7 7 0 0 1-14 0c0-4 4-7 6-10z"/>',pencil:'<path d="M12 20h9"/><path d="M16.5 3.5a2.1 2.1 0 0 1 3 3L7 19l-4 1 1-4z"/>',shuffle:'<polyline points="16 3 21 3 21 8"/><line x1="4" y1="20" x2="21" y2="3"/><polyline points="21 16 21 21 16 21"/><line x1="15" y1="15" x2="21" y2="21"/><line x1="4" y1="4" x2="9" y2="9"/>',carrot:'<path d="M3 21l8-8"/><path d="M11 13c3-3 8-3 9-2-1 5-7 8-11 7"/>',leaf:'<path d="M2 22l10-10"/><path d="M16 8a6 6 0 0 0-12 0c0 9 5 13 6 14 1-1 6-5 6-14z"/>',msg:'<path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/>',user:'<path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/>',logout:'<path d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4"/><polyline points="16 17 21 12 16 7"/><line x1="21" y1="12" x2="9" y2="12"/>',link:'<path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"/><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"/>',globe:'<circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/>',cloud:'<polyline points="16 16 12 12 8 16"/><line x1="12" y1="12" x2="12" y2="21"/><path d="M20.4 18.5A5 5 0 0 0 18 9h-1.3A8 8 0 1 0 4 16.8"/>'};
const ic=(n,sz=16)=>`<svg width="${sz}" height="${sz}" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">${P[n]||''}</svg>`;
const stIc=(sz=13,on=true)=>`<svg width="${sz}" height="${sz}" viewBox="0 0 24 24" fill="${on?'#E2941F':'none'}" stroke="${on?'#E2941F':'#D8CFBE'}" stroke-width="2" stroke-linejoin="round">${P.star}</svg>`;
const stH=(v,sz=11)=>`<span style="display:inline-flex;gap:1px;">${[1,2,3,4,5].map(i=>stIc(sz,i<=Math.round(v))).join('')}</span>`;
const htIc=(on,sz=16)=>`<svg width="${sz}" height="${sz}" viewBox="0 0 24 24" fill="${on?'#D1493A':'none'}" stroke="${on?'#D1493A':'#9A8C75'}" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">${P.heart}</svg>`;
const esc=s=>(s||'').replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const cap=s=>s.charAt(0).toUpperCase()+s.slice(1);
const avH=(name,sz=24)=>`<span class="av" style="width:${sz}px;height:${sz}px;font-size:${Math.round(sz*.42)}px;">${(name||'?').split(' ').map(w=>w[0]).join('').slice(0,2).toUpperCase()}</span>`;
const bW=s=>s.toLowerCase().trim().replace(/e?s$/,'');
const pHas=(p,n)=>p.some(x=>{const a=x.toLowerCase().trim(),b=n.toLowerCase().trim();return a.includes(b)||b.includes(a)||bW(a)===bW(b);});

/* ═══ LARGE BUILT-IN DATABASE — 250+ recipes across all cuisines ═══ */
/* We load from 6 different TheMealDB categories + built-in fallback */
const BUILTIN=[
  /* Bangladeshi */
  {idMeal:'bd001',strMeal:'Masoor Dal',strArea:'Bangladeshi',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=masoor+dal+recipe',strSource:'https://en.wikipedia.org/wiki/Masoor_dal',strInstructions:'Boil red lentils with turmeric until soft. Fry onion, garlic and green chili in oil until golden. Pour over the dal, simmer 3 minutes and serve with rice.',strIngredient1:'Red Lentils',strMeasure1:'200g',strIngredient2:'Onion',strMeasure2:'1 large',strIngredient3:'Garlic',strMeasure3:'3 cloves',strIngredient4:'Turmeric',strMeasure4:'1 tsp',strIngredient5:'Green Chilli',strMeasure5:'2',strIngredient6:'Oil',strMeasure6:'2 tbsp',strIngredient7:'Salt',strMeasure7:'to taste',emoji:'🍲'},
  {idMeal:'bd002',strMeal:'Chicken Bhuna',strArea:'Bangladeshi',strCategory:'Chicken',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=chicken+bhuna+recipe',strSource:'https://en.wikipedia.org/wiki/Chicken_bhuna',strInstructions:'Marinate chicken with yogurt, ginger, garlic and spices for 20 minutes. Fry onions deep golden, add chicken and sear on high heat. Cook low and slow until oil separates and gravy clings to the chicken.',strIngredient1:'Chicken',strMeasure1:'700g',strIngredient2:'Onion',strMeasure2:'2 large',strIngredient3:'Garlic',strMeasure3:'5 cloves',strIngredient4:'Ginger',strMeasure4:'1 tbsp',strIngredient5:'Yogurt',strMeasure5:'100g',strIngredient6:'Chilli Powder',strMeasure6:'1 tbsp',strIngredient7:'Garam Masala',strMeasure7:'1 tsp',strIngredient8:'Oil',strMeasure8:'3 tbsp',emoji:'🍗'},
  {idMeal:'bd003',strMeal:'Aloo Bhorta',strArea:'Bangladeshi',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=aloo+bhorta+recipe',strSource:'https://en.wikipedia.org/wiki/Bhorta',strInstructions:'Boil potatoes until very soft. Mash with chopped onion, green chili, mustard oil and salt. Serve warm with rice.',strIngredient1:'Potato',strMeasure1:'500g',strIngredient2:'Onion',strMeasure2:'1',strIngredient3:'Green Chilli',strMeasure3:'2',strIngredient4:'Mustard Oil',strMeasure4:'2 tbsp',strIngredient5:'Salt',strMeasure5:'to taste',emoji:'🥔'},
  {idMeal:'bd004',strMeal:'Beef Tehari',strArea:'Bangladeshi',strCategory:'Beef',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=beef+tehari+recipe',strSource:'https://en.wikipedia.org/wiki/Tehari',strInstructions:'Cook beef with ginger, garlic, yogurt and spices until tender. Fry onions golden, add soaked basmati rice. Layer beef and rice with green chili and steam on dum until perfectly cooked.',strIngredient1:'Beef',strMeasure1:'800g',strIngredient2:'Basmati Rice',strMeasure2:'500g',strIngredient3:'Onion',strMeasure3:'3',strIngredient4:'Ginger',strMeasure4:'2 tbsp',strIngredient5:'Garlic',strMeasure5:'6 cloves',strIngredient6:'Yogurt',strMeasure6:'150g',strIngredient7:'Oil',strMeasure7:'5 tbsp',emoji:'🍛'},
  {idMeal:'bd005',strMeal:'Shorshe Ilish',strArea:'Bangladeshi',strCategory:'Seafood',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=shorshe+ilish+recipe',strSource:'https://en.wikipedia.org/wiki/Ilish',strInstructions:'Marinate hilsa fish with turmeric and salt. Make mustard paste with green chili and water. Simmer fish in mustard gravy with mustard oil until cooked through.',strIngredient1:'Hilsa Fish',strMeasure1:'6 pieces',strIngredient2:'Mustard Paste',strMeasure2:'4 tbsp',strIngredient3:'Green Chilli',strMeasure3:'5',strIngredient4:'Turmeric',strMeasure4:'1 tsp',strIngredient5:'Mustard Oil',strMeasure5:'4 tbsp',emoji:'🐟'},
  {idMeal:'bd006',strMeal:'Bhuna Khichuri',strArea:'Bangladeshi',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=bhuna+khichuri+recipe',strSource:'https://en.wikipedia.org/wiki/Khichdi',strInstructions:'Dry-roast moong dal until fragrant. Fry onion, ginger and bay leaf in oil. Add rice, dal and water, cook until soft and porridge-like. Serve hot with fried egg and pickle.',strIngredient1:'Rice',strMeasure1:'200g',strIngredient2:'Moong Dal',strMeasure2:'150g',strIngredient3:'Onion',strMeasure3:'1',strIngredient4:'Ginger',strMeasure4:'1 tsp',strIngredient5:'Turmeric',strMeasure5:'1 tsp',strIngredient6:'Bay Leaf',strMeasure6:'2',strIngredient7:'Oil',strMeasure7:'2 tbsp',emoji:'🍚'},
  {idMeal:'bd007',strMeal:'Dim Bhuna',strArea:'Bangladeshi',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=dim+bhuna+recipe',strSource:'https://en.wikipedia.org/wiki/Dim_bhuna',strInstructions:'Hard boil eggs, peel and fry until golden. Make a thick masala with onion, garlic, ginger and tomato. Add eggs and simmer until the gravy thickens.',strIngredient1:'Eggs',strMeasure1:'6',strIngredient2:'Onion',strMeasure2:'2',strIngredient3:'Garlic',strMeasure3:'4 cloves',strIngredient4:'Tomato',strMeasure4:'1',strIngredient5:'Chilli Powder',strMeasure5:'1 tsp',strIngredient6:'Oil',strMeasure6:'3 tbsp',emoji:'🍳'},
  {idMeal:'bd008',strMeal:'Chicken Biryani',strArea:'Bangladeshi',strCategory:'Chicken',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=chicken+biryani+recipe',strSource:'https://en.wikipedia.org/wiki/Biryani',strInstructions:'Marinate chicken with yogurt and biryani masala. Par-boil rice. Fry onions to crisp birista. Layer chicken, rice and birista in a pot and steam on dum for 25 minutes.',strIngredient1:'Chicken',strMeasure1:'800g',strIngredient2:'Basmati Rice',strMeasure2:'500g',strIngredient3:'Onion',strMeasure3:'3',strIngredient4:'Yogurt',strMeasure4:'150g',strIngredient5:'Biryani Masala',strMeasure5:'2 tbsp',strIngredient6:'Oil',strMeasure6:'5 tbsp',emoji:'🍛'},
  {idMeal:'bd009',strMeal:'Halim',strArea:'Bangladeshi',strCategory:'Beef',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=halim+recipe+bangladeshi',strSource:'',strInstructions:'Slow cook beef with lentils, wheat and barley for 3-4 hours until thick. Season with fried onion, ginger, green chili and lime. Garnish with coriander.',strIngredient1:'Beef',strMeasure1:'500g',strIngredient2:'Lentils',strMeasure2:'200g',strIngredient3:'Wheat',strMeasure3:'100g',strIngredient4:'Onion',strMeasure4:'2',strIngredient5:'Ginger',strMeasure5:'2 tbsp',strIngredient6:'Garam Masala',strMeasure6:'1 tbsp',emoji:'🥘'},
  {idMeal:'bd010',strMeal:'Panta Bhat',strArea:'Bangladeshi',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=panta+bhat+recipe',strSource:'',strInstructions:'Soak cooked rice overnight in water. Drain and serve cold with mustard oil, salt, green chili, onion and a fried dried fish on the side.',strIngredient1:'Cooked Rice',strMeasure1:'2 cups',strIngredient2:'Water',strMeasure2:'enough to cover',strIngredient3:'Mustard Oil',strMeasure3:'1 tbsp',strIngredient4:'Green Chilli',strMeasure4:'2',strIngredient5:'Onion',strMeasure5:'1 small',emoji:'🍚'},
  {idMeal:'bd011',strMeal:'Chingri Malai Curry',strArea:'Bangladeshi',strCategory:'Seafood',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=chingri+malai+curry+recipe',strSource:'',strInstructions:'Fry onion paste with ginger and garlic. Add coconut milk and simmer. Add marinated prawns and cook gently until done. Finish with a touch of sugar and garam masala.',strIngredient1:'Prawns',strMeasure1:'500g',strIngredient2:'Coconut Milk',strMeasure2:'400ml',strIngredient3:'Onion',strMeasure3:'2',strIngredient4:'Ginger',strMeasure4:'1 tbsp',strIngredient5:'Garlic',strMeasure5:'4 cloves',strIngredient6:'Turmeric',strMeasure6:'1 tsp',emoji:'🦐'},
  {idMeal:'bd012',strMeal:'Morog Polao',strArea:'Bangladeshi',strCategory:'Chicken',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=morog+polao+recipe',strSource:'',strInstructions:'Cook chicken until tender in spiced broth. Fry onions golden, add soaked rice. Mix chicken stock and rice, cook until fluffy. Layer with crispy onions and serve.',strIngredient1:'Chicken',strMeasure1:'1 whole',strIngredient2:'Basmati Rice',strMeasure2:'500g',strIngredient3:'Onion',strMeasure3:'3',strIngredient4:'Ghee',strMeasure4:'3 tbsp',strIngredient5:'Garam Masala',strMeasure5:'1 tsp',emoji:'🍗'},
  /* Indian */
  {idMeal:'in001',strMeal:'Butter Chicken',strArea:'Indian',strCategory:'Chicken',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=butter+chicken+recipe',strSource:'https://en.wikipedia.org/wiki/Butter_chicken',strInstructions:'Sear marinated chicken and set aside. Simmer tomato, cashew and garlic then blend smooth. Cook the puree in butter, stir in cream and chicken. Warm through and serve.',strIngredient1:'Chicken',strMeasure1:'600g',strIngredient2:'Tomatoes',strMeasure2:'5',strIngredient3:'Butter',strMeasure3:'40g',strIngredient4:'Cream',strMeasure4:'80ml',strIngredient5:'Cashews',strMeasure5:'30g',strIngredient6:'Garam Masala',strMeasure6:'1 tsp',emoji:'🍗'},
  {idMeal:'in002',strMeal:'Palak Paneer',strArea:'Indian',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=palak+paneer+recipe',strSource:'https://en.wikipedia.org/wiki/Palak_paneer',strInstructions:'Blanch and puree spinach. Fry onion, tomato and spices. Add spinach puree and simmer. Add paneer cubes and cook gently. Finish with cream and garam masala.',strIngredient1:'Spinach',strMeasure1:'500g',strIngredient2:'Paneer',strMeasure2:'250g',strIngredient3:'Onion',strMeasure3:'1',strIngredient4:'Tomato',strMeasure4:'2',strIngredient5:'Garlic',strMeasure5:'4 cloves',strIngredient6:'Ginger',strMeasure6:'1 tsp',emoji:'🥬'},
  {idMeal:'in003',strMeal:'Chana Masala',strArea:'Indian',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=chana+masala+recipe',strSource:'https://en.wikipedia.org/wiki/Chana_masala',strInstructions:'Fry onion, garlic and ginger. Add tomato and cook down. Add chana masala powder and chickpeas. Simmer until thick, mashing a few for texture.',strIngredient1:'Chickpeas',strMeasure1:'400g',strIngredient2:'Onion',strMeasure2:'2',strIngredient3:'Tomato',strMeasure3:'2',strIngredient4:'Garlic',strMeasure4:'4 cloves',strIngredient5:'Chana Masala',strMeasure5:'1 tbsp',emoji:'🫘'},
  {idMeal:'in004',strMeal:'Aloo Paratha',strArea:'Indian',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=aloo+paratha+recipe',strSource:'https://en.wikipedia.org/wiki/Aloo_paratha',strInstructions:'Knead soft dough with flour, water and salt. Mash boiled potato with chili and cumin for filling. Stuff the dough, roll out and cook on a tawa with butter until golden.',strIngredient1:'Plain Flour',strMeasure1:'300g',strIngredient2:'Potatoes',strMeasure2:'400g',strIngredient3:'Green Chilli',strMeasure3:'2',strIngredient4:'Cumin',strMeasure4:'1 tsp',strIngredient5:'Butter',strMeasure5:'30g',emoji:'🫓'},
  {idMeal:'in005',strMeal:'Dal Tadka',strArea:'Indian',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=dal+tadka+recipe',strSource:'https://en.wikipedia.org/wiki/Dal_tadka',strInstructions:'Pressure cook toor dal with turmeric. In ghee, fry cumin, garlic, onion and tomato. Pour the sizzling tadka over the cooked dal and mix.',strIngredient1:'Toor Dal',strMeasure1:'200g',strIngredient2:'Onion',strMeasure2:'1',strIngredient3:'Tomato',strMeasure3:'1',strIngredient4:'Garlic',strMeasure4:'4 cloves',strIngredient5:'Cumin',strMeasure5:'1 tsp',strIngredient6:'Ghee',strMeasure6:'2 tbsp',emoji:'🥘'},
  {idMeal:'in006',strMeal:'Paneer Butter Masala',strArea:'Indian',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=paneer+butter+masala+recipe',strSource:'https://en.wikipedia.org/wiki/Paneer_makhani',strInstructions:'Simmer tomato, cashew and garlic then blend smooth. Cook puree in butter with garam masala until rich. Stir in cream and paneer cubes, warm gently.',strIngredient1:'Paneer',strMeasure1:'300g',strIngredient2:'Tomatoes',strMeasure2:'4',strIngredient3:'Butter',strMeasure3:'30g',strIngredient4:'Cream',strMeasure4:'60ml',strIngredient5:'Cashews',strMeasure5:'30g',emoji:'🧀'},
  {idMeal:'in007',strMeal:'Mango Lassi',strArea:'Indian',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=mango+lassi+recipe',strSource:'https://en.wikipedia.org/wiki/Lassi',strInstructions:'Peel and chop ripe mango. Blend with yogurt, milk and sugar until smooth. Serve immediately over ice.',strIngredient1:'Mango',strMeasure1:'2',strIngredient2:'Yogurt',strMeasure2:'300g',strIngredient3:'Milk',strMeasure3:'100ml',strIngredient4:'Sugar',strMeasure4:'1 tbsp',emoji:'🥭'},
  {idMeal:'in008',strMeal:'Vegetable Pulao',strArea:'Indian',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=vegetable+pulao+recipe',strSource:'',strInstructions:'Soak basmati rice for 15 minutes. Fry onion and whole spices in ghee. Add mixed vegetables. Add rice and water, cover and steam until fluffy.',strIngredient1:'Basmati Rice',strMeasure1:'250g',strIngredient2:'Mixed Vegetables',strMeasure2:'200g',strIngredient3:'Onion',strMeasure3:'1',strIngredient4:'Ghee',strMeasure4:'2 tbsp',strIngredient5:'Garam Masala',strMeasure5:'1 tsp',emoji:'🍚'},
  {idMeal:'in009',strMeal:'Samosa',strArea:'Indian',strCategory:'Starter',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=samosa+recipe',strSource:'https://en.wikipedia.org/wiki/Samosa',strInstructions:'Make pastry with flour, oil and water. Fill with spiced potato and pea mixture. Fold into triangles and deep fry until golden and crispy.',strIngredient1:'Plain Flour',strMeasure1:'250g',strIngredient2:'Potatoes',strMeasure2:'400g',strIngredient3:'Peas',strMeasure3:'100g',strIngredient4:'Cumin',strMeasure4:'1 tsp',strIngredient5:'Coriander',strMeasure5:'1 tsp',strIngredient6:'Oil',strMeasure6:'for frying',emoji:'🥟'},
  {idMeal:'in010',strMeal:'Gulab Jamun',strArea:'Indian',strCategory:'Dessert',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=gulab+jamun+recipe',strSource:'https://en.wikipedia.org/wiki/Gulab_jamun',strInstructions:'Mix milk powder, flour and ghee into a soft dough. Roll into smooth balls and fry on low heat until deep brown. Soak in warm rose-flavored sugar syrup.',strIngredient1:'Milk Powder',strMeasure1:'200g',strIngredient2:'Plain Flour',strMeasure2:'3 tbsp',strIngredient3:'Ghee',strMeasure3:'2 tbsp',strIngredient4:'Sugar',strMeasure4:'300g',strIngredient5:'Rose Water',strMeasure5:'1 tsp',emoji:'🍮'},
  /* Italian */
  {idMeal:'it001',strMeal:'Spaghetti Aglio e Olio',strArea:'Italian',strCategory:'Pasta',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=spaghetti+aglio+e+olio',strSource:'https://en.wikipedia.org/wiki/Spaghetti_aglio_e_olio',strInstructions:'Boil spaghetti al dente and save pasta water. Warm sliced garlic and chili in olive oil without browning. Toss pasta with oil and pasta water, finish with parsley.',strIngredient1:'Spaghetti',strMeasure1:'200g',strIngredient2:'Garlic',strMeasure2:'4 cloves',strIngredient3:'Olive Oil',strMeasure3:'4 tbsp',strIngredient4:'Chilli Flakes',strMeasure4:'1 tsp',emoji:'🍝'},
  {idMeal:'it002',strMeal:'Spaghetti Bolognese',strArea:'Italian',strCategory:'Pasta',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=spaghetti+bolognese',strSource:'https://en.wikipedia.org/wiki/Bolognese_sauce',strInstructions:'Brown beef mince with onion and garlic. Add tomato and simmer 30 minutes into a rich sauce. Toss with cooked spaghetti and serve with parmesan.',strIngredient1:'Spaghetti',strMeasure1:'350g',strIngredient2:'Beef Mince',strMeasure2:'400g',strIngredient3:'Tomatoes',strMeasure3:'4',strIngredient4:'Onion',strMeasure4:'1',strIngredient5:'Garlic',strMeasure5:'3 cloves',emoji:'🍝'},
  {idMeal:'it003',strMeal:'Margherita Pizza',strArea:'Italian',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=margherita+pizza+recipe',strSource:'https://en.wikipedia.org/wiki/Pizza_Margherita',strInstructions:'Stretch pizza dough and spread tomato sauce. Top with torn mozzarella and olive oil. Bake in the hottest oven until the crust blisters. Finish with fresh basil.',strIngredient1:'Pizza Dough',strMeasure1:'1 ball',strIngredient2:'Tomatoes',strMeasure2:'3',strIngredient3:'Mozzarella',strMeasure3:'150g',strIngredient4:'Basil',strMeasure4:'handful',strIngredient5:'Olive Oil',strMeasure5:'1 tbsp',emoji:'🍕'},
  {idMeal:'it004',strMeal:'Risotto',strArea:'Italian',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=risotto+recipe',strSource:'https://en.wikipedia.org/wiki/Risotto',strInstructions:'Fry onion in butter. Add arborio rice and toast briefly. Add white wine. Add hot stock one ladle at a time, stirring constantly until creamy. Finish with parmesan and butter.',strIngredient1:'Arborio Rice',strMeasure1:'300g',strIngredient2:'Stock',strMeasure2:'1 litre',strIngredient3:'Onion',strMeasure3:'1',strIngredient4:'Butter',strMeasure4:'50g',strIngredient5:'Parmesan',strMeasure5:'50g',emoji:'🍚'},
  {idMeal:'it005',strMeal:'Tiramisu',strArea:'Italian',strCategory:'Dessert',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=tiramisu+recipe',strSource:'https://en.wikipedia.org/wiki/Tiramisu',strInstructions:'Whisk egg yolks and sugar until pale. Fold in mascarpone. Dip savoiardi in coffee and layer with mascarpone cream. Dust with cocoa powder and refrigerate for 4 hours.',strIngredient1:'Mascarpone',strMeasure1:'500g',strIngredient2:'Savoiardi',strMeasure2:'200g',strIngredient3:'Eggs',strMeasure3:'4',strIngredient4:'Sugar',strMeasure4:'100g',strIngredient5:'Coffee',strMeasure5:'200ml',strIngredient6:'Cocoa Powder',strMeasure6:'for dusting',emoji:'🍰'},
  /* Chinese */
  {idMeal:'cn001',strMeal:'Vegetable Fried Rice',strArea:'Chinese',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=vegetable+fried+rice+recipe',strSource:'https://en.wikipedia.org/wiki/Fried_rice',strInstructions:'Use cold day-old rice. Stir-fry garlic and vegetables on very high heat. Add rice and soy sauce, toss until hot and fragrant.',strIngredient1:'Rice',strMeasure1:'300g',strIngredient2:'Mixed Vegetables',strMeasure2:'200g',strIngredient3:'Garlic',strMeasure3:'3 cloves',strIngredient4:'Soy Sauce',strMeasure4:'2 tbsp',strIngredient5:'Oil',strMeasure5:'2 tbsp',emoji:'🍚'},
  {idMeal:'cn002',strMeal:'Chicken Chow Mein',strArea:'Chinese',strCategory:'Chicken',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=chicken+chow+mein+recipe',strSource:'https://en.wikipedia.org/wiki/Chow_mein',strInstructions:'Boil and drain noodles. Stir-fry chicken until cooked. Add garlic, vegetables and noodles. Pour in soy sauce and toss everything together.',strIngredient1:'Noodles',strMeasure1:'300g',strIngredient2:'Chicken',strMeasure2:'300g',strIngredient3:'Mixed Vegetables',strMeasure3:'200g',strIngredient4:'Soy Sauce',strMeasure3:'3 tbsp',emoji:'🍜'},
  {idMeal:'cn003',strMeal:'Dim Sum Dumplings',strArea:'Chinese',strCategory:'Starter',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=dim+sum+dumplings+recipe',strSource:'',strInstructions:'Mix pork mince with cabbage, ginger, soy and sesame oil. Wrap in dumpling wrappers. Steam for 10 minutes or pan-fry until golden on the bottom.',strIngredient1:'Pork Mince',strMeasure1:'300g',strIngredient2:'Cabbage',strMeasure2:'100g',strIngredient3:'Ginger',strMeasure3:'1 tbsp',strIngredient4:'Soy Sauce',strMeasure4:'2 tbsp',strIngredient5:'Dumpling Wrappers',strMeasure5:'30',emoji:'🥟'},
  /* Thai */
  {idMeal:'th001',strMeal:'Thai Green Curry',strArea:'Thai',strCategory:'Chicken',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=thai+green+curry+recipe',strSource:'https://en.wikipedia.org/wiki/Green_curry',strInstructions:'Fry green curry paste until fragrant. Add coconut milk, chicken and vegetables. Simmer gently, season with fish sauce and finish with Thai basil.',strIngredient1:'Chicken',strMeasure1:'500g',strIngredient2:'Green Curry Paste',strMeasure2:'3 tbsp',strIngredient3:'Coconut Milk',strMeasure3:'400ml',strIngredient4:'Mixed Vegetables',strMeasure4:'200g',strIngredient5:'Fish Sauce',strMeasure5:'1 tbsp',emoji:'🍲'},
  {idMeal:'th002',strMeal:'Pad Thai',strArea:'Thai',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=pad+thai+recipe',strSource:'https://en.wikipedia.org/wiki/Pad_thai',strInstructions:'Soak rice noodles until pliable. Stir-fry prawns and scramble in the eggs. Add noodles and tamarind sauce. Toss together and top with crushed peanuts and lime.',strIngredient1:'Rice Noodles',strMeasure1:'200g',strIngredient2:'Prawns',strMeasure2:'200g',strIngredient3:'Eggs',strMeasure3:'2',strIngredient4:'Peanuts',strMeasure4:'40g',strIngredient5:'Tamarind',strMeasure5:'2 tbsp',strIngredient6:'Fish Sauce',strMeasure6:'1 tbsp',emoji:'🍜'},
  {idMeal:'th003',strMeal:'Tom Yum Soup',strArea:'Thai',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=tom+yum+soup+recipe',strSource:'https://en.wikipedia.org/wiki/Tom_yum',strInstructions:'Boil water with lemongrass, galangal and kaffir lime leaves. Add mushrooms and prawns. Season with fish sauce, lime juice and chili. Garnish with coriander.',strIngredient1:'Prawns',strMeasure1:'300g',strIngredient2:'Mushrooms',strMeasure2:'150g',strIngredient3:'Lemongrass',strMeasure3:'2 stalks',strIngredient4:'Lime',strMeasure4:'2',strIngredient5:'Fish Sauce',strMeasure5:'2 tbsp',strIngredient6:'Chilli',strMeasure6:'3',emoji:'🍜'},
  /* Middle Eastern */
  {idMeal:'me001',strMeal:'Hummus',strArea:'Middle Eastern',strCategory:'Starter',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=hummus+recipe',strSource:'https://en.wikipedia.org/wiki/Hummus',strInstructions:'Blend chickpeas, tahini, garlic and lemon juice. Add ice-cold water for a smooth light texture. Drizzle olive oil and serve with pita.',strIngredient1:'Chickpeas',strMeasure1:'400g',strIngredient2:'Tahini',strMeasure2:'3 tbsp',strIngredient3:'Garlic',strMeasure3:'2 cloves',strIngredient4:'Lemon',strMeasure4:'1',strIngredient5:'Olive Oil',strMeasure5:'3 tbsp',emoji:'🧆'},
  {idMeal:'me002',strMeal:'Shakshuka',strArea:'Middle Eastern',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=shakshuka+recipe',strSource:'https://en.wikipedia.org/wiki/Shakshouka',strInstructions:'Cook onion, garlic and paprika in olive oil. Add chopped tomato and simmer into a thick sauce. Make wells, crack in eggs, cover and cook until just set.',strIngredient1:'Eggs',strMeasure1:'4',strIngredient2:'Tomatoes',strMeasure2:'5',strIngredient3:'Onion',strMeasure3:'1',strIngredient4:'Garlic',strMeasure4:'3 cloves',strIngredient5:'Paprika',strMeasure5:'1 tsp',emoji:'🍳'},
  {idMeal:'me003',strMeal:'Falafel',strArea:'Middle Eastern',strCategory:'Vegetarian',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=falafel+recipe',strSource:'https://en.wikipedia.org/wiki/Falafel',strInstructions:'Blend soaked chickpeas with onion, parsley, garlic and spices. Form into balls and deep fry until golden. Serve in pita with tahini and salad.',strIngredient1:'Chickpeas',strMeasure1:'400g',strIngredient2:'Onion',strMeasure2:'1',strIngredient3:'Parsley',strMeasure3:'handful',strIngredient4:'Cumin',strMeasure4:'1 tsp',strIngredient5:'Coriander',strMeasure5:'1 tsp',emoji:'🧆'},
  {idMeal:'me004',strMeal:'Lamb Kebab',strArea:'Middle Eastern',strCategory:'Lamb',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=lamb+kebab+recipe',strSource:'',strInstructions:'Mix lamb mince with onion, parsley, cumin and spices. Shape onto skewers and grill until charred outside and juicy inside. Serve with flatbread and yogurt sauce.',strIngredient1:'Lamb Mince',strMeasure1:'500g',strIngredient2:'Onion',strMeasure2:'1',strIngredient3:'Parsley',strMeasure3:'handful',strIngredient4:'Cumin',strMeasure4:'1 tsp',strIngredient5:'Paprika',strMeasure5:'1 tsp',emoji:'🍢'},
  /* Continental */
  {idMeal:'co001',strMeal:'Fluffy Pancakes',strArea:'American',strCategory:'Breakfast',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=fluffy+pancakes+recipe',strSource:'https://en.wikipedia.org/wiki/Pancake',strInstructions:'Whisk flour, sugar and baking powder. Stir in milk, egg and melted butter. Rest batter 5 minutes. Cook on low-medium heat, flip when bubbles appear.',strIngredient1:'Plain Flour',strMeasure1:'200g',strIngredient2:'Milk',strMeasure2:'300ml',strIngredient3:'Eggs',strMeasure3:'2',strIngredient4:'Sugar',strMeasure4:'2 tbsp',strIngredient5:'Baking Powder',strMeasure5:'1 tsp',strIngredient6:'Butter',strMeasure6:'20g',emoji:'🥞'},
  {idMeal:'co002',strMeal:'Masala Omelette',strArea:'Continental',strCategory:'Breakfast',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=masala+omelette+recipe',strSource:'',strInstructions:'Whisk eggs with chopped onion, chili, tomato and salt. Pour into hot oiled pan and spread evenly. Cook until set, fold and serve with toast or paratha.',strIngredient1:'Eggs',strMeasure1:'4',strIngredient2:'Onion',strMeasure2:'1',strIngredient3:'Tomato',strMeasure3:'1',strIngredient4:'Green Chilli',strMeasure4:'1',strIngredient5:'Oil',strMeasure5:'1 tbsp',emoji:'🍳'},
  {idMeal:'co003',strMeal:'Creamy Tomato Soup',strArea:'Continental',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=creamy+tomato+soup+recipe',strSource:'https://en.wikipedia.org/wiki/Tomato_soup',strInstructions:'Soften onion and garlic in butter. Add chopped tomatoes and simmer 15 minutes. Blend smooth. Stir in cream, season and serve with crusty bread.',strIngredient1:'Tomatoes',strMeasure1:'600g',strIngredient2:'Onion',strMeasure2:'1',strIngredient3:'Garlic',strMeasure3:'2 cloves',strIngredient4:'Butter',strMeasure4:'20g',strIngredient5:'Cream',strMeasure5:'30ml',emoji:'🍅'},
  {idMeal:'co004',strMeal:'Grilled Chicken Salad',strArea:'Continental',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=grilled+chicken+salad+recipe',strSource:'',strInstructions:'Season chicken and grill until cooked through, then slice. Toss lettuce, tomato and cucumber with olive oil, lemon and salt. Top with warm chicken.',strIngredient1:'Chicken Breast',strMeasure1:'300g',strIngredient2:'Lettuce',strMeasure2:'100g',strIngredient3:'Tomato',strMeasure3:'2',strIngredient4:'Cucumber',strMeasure4:'1',strIngredient5:'Olive Oil',strMeasure5:'2 tbsp',strIngredient6:'Lemon',strMeasure6:'1',emoji:'🥗'},
  {idMeal:'co005',strMeal:'French Toast',strArea:'French',strCategory:'Breakfast',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=french+toast+recipe',strSource:'https://en.wikipedia.org/wiki/French_toast',strInstructions:'Whisk egg, milk and sugar. Dip bread slices to coat both sides. Fry in butter over medium heat until golden on both sides. Serve with maple syrup.',strIngredient1:'Bread',strMeasure1:'4 slices',strIngredient2:'Eggs',strMeasure2:'2',strIngredient3:'Milk',strMeasure3:'100ml',strIngredient4:'Sugar',strMeasure4:'1 tbsp',strIngredient5:'Butter',strMeasure5:'15g',emoji:'🍞'},
  {idMeal:'co006',strMeal:'Banana Oats Porridge',strArea:'British',strCategory:'Breakfast',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=banana+oats+porridge+recipe',strSource:'',strInstructions:'Simmer oats with milk, stirring until creamy. Slice in a banana and drizzle with honey. Serve warm with nuts or fresh fruit.',strIngredient1:'Oats',strMeasure1:'80g',strIngredient2:'Milk',strMeasure2:'300ml',strIngredient3:'Banana',strMeasure3:'1',strIngredient4:'Honey',strMeasure4:'1 tbsp',emoji:'🥣'},
  {idMeal:'co007',strMeal:'Beef Burger',strArea:'American',strCategory:'Beef',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=beef+burger+recipe',strSource:'https://en.wikipedia.org/wiki/Hamburger',strInstructions:'Season beef mince with salt and pepper, form into patties. Grill on high heat 3 minutes each side. Serve in a toasted bun with lettuce, tomato and your choice of sauce.',strIngredient1:'Beef Mince',strMeasure1:'400g',strIngredient2:'Burger Buns',strMeasure2:'4',strIngredient3:'Lettuce',strMeasure3:'4 leaves',strIngredient4:'Tomato',strMeasure4:'1',strIngredient5:'Cheddar',strMeasure5:'4 slices',emoji:'🍔'},
  {idMeal:'co008',strMeal:'Caesar Salad',strArea:'Mexican',strCategory:'Starter',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=caesar+salad+recipe',strSource:'https://en.wikipedia.org/wiki/Caesar_salad',strInstructions:'Toss romaine lettuce with Caesar dressing. Add croutons and shaved parmesan. Top with grilled chicken if desired.',strIngredient1:'Romaine Lettuce',strMeasure1:'1 head',strIngredient2:'Parmesan',strMeasure2:'50g',strIngredient3:'Croutons',strMeasure3:'100g',strIngredient4:'Caesar Dressing',strMeasure4:'4 tbsp',emoji:'🥗'},
  /* Japanese */
  {idMeal:'jp001',strMeal:'Chicken Teriyaki',strArea:'Japanese',strCategory:'Chicken',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=chicken+teriyaki+recipe',strSource:'https://en.wikipedia.org/wiki/Teriyaki',strInstructions:'Mix soy sauce, mirin and sugar. Marinate chicken thighs. Grill skin-side down until crispy, flip and glaze with sauce. Cook until sticky and caramelised.',strIngredient1:'Chicken Thighs',strMeasure1:'4',strIngredient2:'Soy Sauce',strMeasure2:'3 tbsp',strIngredient3:'Mirin',strMeasure3:'2 tbsp',strIngredient4:'Sugar',strMeasure4:'1 tbsp',emoji:'🍗'},
  {idMeal:'jp002',strMeal:'Miso Soup',strArea:'Japanese',strCategory:'Miscellaneous',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=miso+soup+recipe',strSource:'https://en.wikipedia.org/wiki/Miso_soup',strInstructions:'Heat dashi stock until hot but not boiling. Dissolve miso paste in a little stock then stir into the pot. Add tofu and wakame. Serve immediately with spring onion.',strIngredient1:'Miso Paste',strMeasure1:'3 tbsp',strIngredient2:'Tofu',strMeasure2:'150g',strIngredient3:'Wakame',strMeasure3:'1 tbsp',strIngredient4:'Spring Onions',strMeasure4:'2',strIngredient5:'Dashi Stock',strMeasure5:'800ml',emoji:'🍜'},
  {idMeal:'jp003',strMeal:'Gyoza',strArea:'Japanese',strCategory:'Starter',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=gyoza+recipe',strSource:'https://en.wikipedia.org/wiki/Jiaozi',strInstructions:'Mix pork mince with cabbage, garlic, ginger and sesame oil. Fill gyoza wrappers and pleat to seal. Pan-fry until golden then add water and steam until cooked.',strIngredient1:'Pork Mince',strMeasure1:'250g',strIngredient2:'Cabbage',strMeasure2:'150g',strIngredient3:'Garlic',strMeasure3:'3 cloves',strIngredient4:'Ginger',strMeasure4:'1 tsp',strIngredient5:'Gyoza Wrappers',strMeasure5:'30',emoji:'🥟'},
  /* Mexican */
  {idMeal:'mx001',strMeal:'Chicken Tacos',strArea:'Mexican',strCategory:'Chicken',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=chicken+tacos+recipe',strSource:'https://en.wikipedia.org/wiki/Taco',strInstructions:'Season chicken with cumin, paprika and lime. Grill until cooked and slice. Warm tortillas and fill with chicken, salsa, avocado and sour cream.',strIngredient1:'Chicken',strMeasure1:'400g',strIngredient2:'Tortillas',strMeasure2:'8',strIngredient3:'Avocado',strMeasure3:'2',strIngredient4:'Lime',strMeasure4:'1',strIngredient5:'Cumin',strMeasure5:'1 tsp',strIngredient6:'Paprika',strMeasure6:'1 tsp',emoji:'🌮'},
  {idMeal:'mx002',strMeal:'Guacamole',strArea:'Mexican',strCategory:'Starter',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=guacamole+recipe',strSource:'https://en.wikipedia.org/wiki/Guacamole',strInstructions:'Mash ripe avocados with lime juice, salt, chopped onion, chili and coriander. Adjust seasoning and serve immediately with tortilla chips.',strIngredient1:'Avocado',strMeasure1:'3',strIngredient2:'Lime',strMeasure2:'1',strIngredient3:'Onion',strMeasure3:'1 small',strIngredient4:'Coriander',strMeasure4:'handful',strIngredient5:'Chilli',strMeasure5:'1',emoji:'🥑'},
  /* British */
  {idMeal:'br001',strMeal:'Chicken Pie',strArea:'British',strCategory:'Chicken',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=chicken+pie+recipe',strSource:'',strInstructions:'Cook chicken in a creamy sauce with vegetables. Pour into a pie dish and top with shortcrust pastry. Bake until the pastry is golden and the filling is bubbling.',strIngredient1:'Chicken',strMeasure1:'500g',strIngredient2:'Shortcrust Pastry',strMeasure2:'300g',strIngredient3:'Mixed Vegetables',strMeasure3:'200g',strIngredient4:'Cream',strMeasure4:'200ml',strIngredient5:'Flour',strMeasure5:'2 tbsp',emoji:'🥧'},
  {idMeal:'br002',strMeal:'Fish and Chips',strArea:'British',strCategory:'Seafood',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=fish+and+chips+recipe',strSource:'https://en.wikipedia.org/wiki/Fish_and_chips',strInstructions:'Make a batter with flour and beer. Dip fish fillets and fry until golden and crispy. Cut potatoes into chips, fry until golden. Serve with mushy peas and malt vinegar.',strIngredient1:'Cod Fillet',strMeasure1:'4',strIngredient2:'Plain Flour',strMeasure2:'200g',strIngredient3:'Beer',strMeasure3:'300ml',strIngredient4:'Potatoes',strMeasure4:'600g',emoji:'🐟'},
  /* Desserts */
  {idMeal:'ds001',strMeal:'Chocolate Brownie',strArea:'American',strCategory:'Dessert',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=chocolate+brownie+recipe',strSource:'https://en.wikipedia.org/wiki/Chocolate_brownie',strInstructions:'Melt dark chocolate and butter together. Beat in sugar, then eggs one by one. Fold in flour and pour into a lined tin. Bake at 180C for 20-25 minutes until set but fudgy.',strIngredient1:'Dark Chocolate',strMeasure1:'200g',strIngredient2:'Butter',strMeasure2:'150g',strIngredient3:'Sugar',strMeasure3:'250g',strIngredient4:'Eggs',strMeasure4:'3',strIngredient5:'Plain Flour',strMeasure5:'100g',emoji:'🍫'},
  {idMeal:'ds002',strMeal:'Cheesecake',strArea:'American',strCategory:'Dessert',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=cheesecake+recipe',strSource:'https://en.wikipedia.org/wiki/Cheesecake',strInstructions:'Make a biscuit base with crushed digestives and butter. Beat cream cheese with sugar and eggs until smooth. Pour over base and bake at 160C for 45 minutes. Cool overnight.',strIngredient1:'Cream Cheese',strMeasure1:'600g',strIngredient2:'Digestive Biscuits',strMeasure2:'200g',strIngredient3:'Butter',strMeasure3:'80g',strIngredient4:'Sugar',strMeasure4:'150g',strIngredient5:'Eggs',strMeasure5:'3',emoji:'🍰'},
  {idMeal:'ds003',strMeal:'Banana Bread',strArea:'American',strCategory:'Dessert',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=banana+bread+recipe',strSource:'https://en.wikipedia.org/wiki/Banana_bread',strInstructions:'Mash ripe bananas. Beat with butter, sugar and eggs. Fold in flour and baking soda. Pour into a loaf tin and bake at 180C for 55-60 minutes until a skewer comes out clean.',strIngredient1:'Bananas',strMeasure1:'3 ripe',strIngredient2:'Plain Flour',strMeasure2:'200g',strIngredient3:'Butter',strMeasure3:'100g',strIngredient4:'Sugar',strMeasure4:'150g',strIngredient5:'Eggs',strMeasure5:'2',emoji:'🍌'},
  {idMeal:'ds004',strMeal:'Ice Cream',strArea:'American',strCategory:'Dessert',strMealThumb:'',strYoutube:'https://www.youtube.com/results?search_query=vanilla+ice+cream+recipe',strSource:'https://en.wikipedia.org/wiki/Ice_cream',strInstructions:'Heat cream, milk and sugar until dissolved. Add vanilla. Whisk egg yolks, slowly add warm cream while whisking. Churn in ice cream maker or freeze stirring every 30 minutes.',strIngredient1:'Double Cream',strMeasure1:'300ml',strIngredient2:'Milk',strMeasure2:'200ml',strIngredient3:'Sugar',strMeasure3:'100g',strIngredient4:'Egg Yolks',strMeasure4:'4',strIngredient5:'Vanilla',strMeasure5:'1 tsp',emoji:'🍦'},
];

/* ═══ TheMealDB API — loads 200+ more on top ═══ */
const API='https://www.themealdb.com/api/json/v1/1/';
const MC={};
let apiOk=false;

async function af(url){
  if(MC[url])return MC[url];
  try{
    const r=await fetch(url,{signal:AbortSignal.timeout(5000)});
    if(!r.ok)throw new Error(r.status);
    const d=await r.json();
    MC[url]=d;apiOk=true;
    document.getElementById('apiStatus').innerHTML='';
    return d;
  }catch(e){
    if(!apiOk){
      document.getElementById('apiStatus').innerHTML='<div class="banner ban-s" style="margin-bottom:14px;">Showing '+BUILTIN.length+' built-in recipes. Connect to the internet for 4,000+ live recipes from TheMealDB.</div>';
    }
    return null;
  }
}

async function getMeals(cat){const d=await af(API+'filter.php?c='+encodeURIComponent(cat));return d?.meals||[];}
async function getMealsByArea(a){const d=await af(API+'filter.php?a='+encodeURIComponent(a));return d?.meals||[];}
async function searchMeals(q){const d=await af(API+'search.php?s='+encodeURIComponent(q));return d?.meals||[];}
async function lookupMeal(id){
  if(id.startsWith('bd')||id.startsWith('in')||id.startsWith('it')||id.startsWith('cn')||id.startsWith('th')||id.startsWith('me')||id.startsWith('co')||id.startsWith('jp')||id.startsWith('mx')||id.startsWith('br')||id.startsWith('ds')){
    return BUILTIN.find(x=>x.idMeal===id)||null;
  }
  if(MC['meal_'+id])return MC['meal_'+id];
  const d=await af(API+'lookup.php?i='+id);
  const m=d?.meals?.[0]||null;
  if(m)MC['meal_'+id]=m;
  return m;
}
async function randomMeal(){const d=await af(API+'random.php?_='+Date.now());return d?.meals?.[0]||null;}
async function getAreas(){const d=await af(API+'list.php?a=list');return d?.meals?.map(x=>x.strArea)||[];}
async function getCats(){const d=await af(API+'list.php?c=list');return d?.meals?.map(x=>x.strCategory)||[];}

function getIngs(meal){
  const out=[];
  for(let i=1;i<=20;i++){
    const n=meal['strIngredient'+i]?.trim(),m=meal['strMeasure'+i]?.trim();
    if(n)out.push({name:n,measure:m||''});
  }
  return out;
}
function ytId(meal){const u=meal?.strYoutube||'';const m=u.match(/(?:v=|youtu\.be\/)([A-Za-z0-9_-]{11})/);return m?m[1]:null;}
function srcDom(meal){try{return new URL(meal?.strSource||'').hostname.replace('www.','');}catch{return null;}}
function matchOf(meal){
  const ings=getIngs(meal);let have=0;const miss=[];
  ings.forEach(({name})=>{pHas(pantry,name)?have++:miss.push(name);});
  return{have,total:ings.length,pct:ings.length?have/ings.length:0,miss};
}
function gradOf(area){
  const g={'Bangladeshi':'linear-gradient(135deg,#1B6E47,#2E9A66)','Indian':'linear-gradient(135deg,#C9760E,#E2941F)','Italian':'linear-gradient(135deg,#7A3A6E,#B24FA0)','Chinese':'linear-gradient(135deg,#B23A3A,#D96A4A)','Thai':'linear-gradient(135deg,#5B7A1B,#8FB23A)','Middle Eastern':'linear-gradient(135deg,#9C6406,#D2A03A)','Japanese':'linear-gradient(135deg,#8B0000,#CC3333)','Mexican':'linear-gradient(135deg,#1B4E6E,#2E7AB0)','British':'linear-gradient(135deg,#2C3E8B,#4A5FC4)','French':'linear-gradient(135deg,#1A3A6E,#2E5FA0)','American':'linear-gradient(135deg,#8B1A1A,#CC4444)'};
  return g[area]||'linear-gradient(135deg,#2C7A7B,#4FB0B2)';
}
function emojiOf(meal){return meal.emoji||(({'Chicken':'🍗','Beef':'🥩','Seafood':'🦐','Pasta':'🍝','Dessert':'🍰','Vegetarian':'🥗','Breakfast':'🥞','Lamb':'🍖','Pork':'🥓','Starter':'🥘'}[meal.strCategory])||'🍲');}

/* ═══ STATE ═══ */
const sbC=supabase.createClient('https://qdtahllshgdvqexcpazc.supabase.co','eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InFkdGFobGxzaGdkdnFleGNwYXpjIiwicm9sZSI6ImFub24iLCJpYXQiOjE3ODIwMjQ2NzMsImV4cCI6MjA5NzYwMDY3M30.7AR4Enc2nYVUBTqi7KJ002fJ_gmxqamsd02ATUdPeug');
const DEMO=false;
let user=null;
let pantry=['onion','garlic','ginger','egg','rice','potato','tomato','chicken','milk','flour','oil','salt','butter','lemon'];
let members=[{id:'m1',name:'You',age:42,weight:78,target:2200,restrictions:[]},{id:'m2',name:'Spouse',age:38,weight:62,target:1800,restrictions:[]},{id:'m3',name:'Child 1',age:14,weight:50,target:2000,restrictions:[]},{id:'m4',name:'Child 2',age:11,weight:38,target:1700,restrictions:['Nut-free']},{id:'m5',name:'Child 3',age:7,weight:24,target:1400,restrictions:['Egg-free']}];
let saved=new Set();
let plan={};
let reviews={};
let curArea='';let curCat='';let vegOnly=false;let searchT=null;
let currentTab='discover';

function lsLoad(){try{const d=JSON.parse(localStorage.getItem('rg4')||'{}');if(d.pantry)pantry=d.pantry;if(d.members)members=d.members;if(d.saved)saved=new Set(d.saved);if(d.plan)plan=d.plan;if(d.reviews)reviews=d.reviews;}catch{}}
function lsSave(){try{localStorage.setItem('rg4',JSON.stringify({pantry,members,saved:[...saved],plan,reviews}));}catch{}}
lsLoad();

async function sbSync(){if(!sbC||!user)return;try{await sbC.from('pantry').upsert({user_id:user.id,items:pantry},{onConflict:'user_id'});await sbC.from('plans').upsert({user_id:user.id,data:plan},{onConflict:'user_id'});await sbC.from('saved_recipes').upsert({user_id:user.id,ids:[...saved]},{onConflict:'user_id'});await sbC.from('household').upsert({user_id:user.id,data:members},{onConflict:'user_id'});}catch{}}
async function sbLoad(){if(!sbC||!user)return;try{const[{data:pd},{data:pl},{data:sv},{data:hh}]=await Promise.all([sbC.from('pantry').select('items').eq('user_id',user.id).single(),sbC.from('plans').select('data').eq('user_id',user.id).single(),sbC.from('saved_recipes').select('ids').eq('user_id',user.id).single(),sbC.from('household').select('data').eq('user_id',user.id).single()]);if(pd?.items)pantry=pd.items;if(pl?.data)plan=pl.data;if(sv?.ids)saved=new Set(sv.ids);if(hh?.data)members=hh.data;lsSave();}catch{}}

let toastT=null;
function toast(msg){const t=document.getElementById('toast');t.textContent=msg;t.classList.add('show');clearTimeout(toastT);toastT=setTimeout(()=>t.classList.remove('show'),2100);}

async function initAuth(){
  if(!sbC){renderAuthUI(null);return;}
  const{data:{session}}=await sbC.auth.getSession();
  if(session){user=session.user;await sbLoad();}
  renderAuthUI(user);
  sbC.auth.onAuthStateChange((_,s)=>{user=s?.user||null;renderAuthUI(user);if(user)sbLoad();});
}
function renderAuthUI(u){
  const av=document.getElementById('userAv'),btn=document.getElementById('authBtn');
  if(u){av.textContent=(u.email||'U')[0].toUpperCase();av.style.display='flex';av.onclick=()=>switchTab('account');btn.innerHTML=ic('logout',15)+' Sign out';btn.onclick=async()=>{if(sbC)await sbC.auth.signOut();user=null;renderAuthUI(null);toast('Signed out');};btn.style.display='inline-flex';}
  else{av.style.display='none';btn.innerHTML=ic('user',15)+' Sign in';btn.onclick=()=>switchTab('account');btn.style.display='inline-flex';}
}
function renderAccount(){
  const el=document.getElementById('accountCard');
  if(DEMO){el.innerHTML=`<h2 style="font-family:var(--dp);font-size:20px;font-weight:700;margin-bottom:12px;">Cloud sync</h2><p class="muted" style="font-size:13.5px;line-height:1.6;margin-bottom:14px;">Add your Supabase URL and anon key to the top of this HTML file to enable sign-in and cross-device sync.</p><div class="banner ban-s">Offline mode — data saves to this device only.</div>`;return;}
  if(!user){el.innerHTML=`<h2 style="font-family:var(--dp);font-size:20px;font-weight:700;margin-bottom:12px;">Sign in</h2><div style="display:grid;gap:10px;margin-bottom:14px;"><div><div class="fl">Email</div><input id="aE" class="inp" type="email" placeholder="you@example.com"/></div><div><div class="fl">Password</div><input id="aP" class="inp" type="password" placeholder="Password"/></div></div><div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;"><button class="btn btn-g" id="signIn">Sign in</button><button class="btn btn-w" id="signUp">Register</button></div>`;
    document.getElementById('signIn').onclick=async()=>{const{error}=await sbC.auth.signInWithPassword({email:document.getElementById('aE').value,password:document.getElementById('aP').value});error?toast(error.message):toast('Welcome back!');};
    document.getElementById('signUp').onclick=async()=>{const{error}=await sbC.auth.signUp({email:document.getElementById('aE').value,password:document.getElementById('aP').value});error?toast(error.message):toast('Signed up! Check email or sign in directly.');};
  }else{
    el.innerHTML=`<div style="display:flex;align-items:center;gap:12px;margin-bottom:14px;"><div style="width:44px;height:44px;border-radius:50%;background:var(--herb-s);color:var(--herb-d);font-size:18px;font-weight:700;display:flex;align-items:center;justify-content:center;">${(user.email||'U')[0].toUpperCase()}</div><div><div style="font-family:var(--dp);font-size:17px;font-weight:600;">${esc(user.email||'')}</div><div class="muted" style="font-size:12.5px;">Signed in ✓</div></div></div><div class="banner ban-g">${ic('cloud',14)} Pantry, plans and saved recipes sync automatically.</div><div style="display:grid;gap:8px;margin-top:12px;"><button class="btn btn-g btn-b" onclick="sbSync().then(()=>toast('Synced!'))">Sync now</button><button class="btn btn-w btn-b" onclick="sbC.auth.signOut().then(()=>{user=null;renderAuthUI(null);toast('Signed out');})">Sign out</button></div>`;
  }
}

/* ═══ TABS ═══ */
const TABS=[{id:'discover',label:'Discover',ic:'search'},{id:'planner',label:'Planner',ic:'calendar'},{id:'pantry',label:'Pantry',ic:'carrot'},{id:'saved',label:'Saved',ic:'heart'},{id:'household',label:'Family',ic:'users'}];
function renderTabs(){
  document.getElementById('tabbar').innerHTML=TABS.map(t=>`<button class="tab ${t.id===currentTab?'on':''}" data-tab="${t.id}">${ic(t.ic,20)}<span>${t.label}</span></button>`).join('');
  document.querySelectorAll('[data-tab]').forEach(b=>b.addEventListener('click',()=>switchTab(b.dataset.tab)));
}
function switchTab(id){currentTab=id;renderTabs();document.querySelectorAll('.view').forEach(v=>v.classList.remove('on'));const el=document.getElementById('v-'+id);if(el)el.classList.add('on');window.scrollTo(0,0);if(id==='planner')renderPlanner();if(id==='pantry')renderPantry();if(id==='saved')renderSaved();if(id==='household')renderHousehold();if(id==='account')renderAccount();}

/* ═══ DISCOVER ═══ */
async function initDiscover(){
  document.getElementById('sIco').innerHTML=ic('search',16);
  document.getElementById('haveBtn').innerHTML=ic('chef',16)+' Cook with what I have';
  document.getElementById('surpriseBtn').innerHTML=ic('shuffle',16)+' Surprise me';
  document.getElementById('vegBtn').innerHTML=ic('leaf',16)+' Veg only';
  document.getElementById('cuisLbl').innerHTML=ic('globe',15)+' Cuisine';
  document.getElementById('catLbl').innerHTML='🍽 Category';
  document.getElementById('haveBtn').addEventListener('click',cookHave);
  document.getElementById('surpriseBtn').addEventListener('click',doSurprise);
  document.getElementById('vegBtn').addEventListener('click',()=>{vegOnly=!vegOnly;document.getElementById('vegBtn').style.background=vegOnly?'var(--herb-s)':'';document.getElementById('vegBtn').style.color=vegOnly?'var(--herb-d)':'';document.getElementById('vegBtn').style.borderColor=vegOnly?'var(--herb)':'';renderDefault();});
  document.getElementById('searchQ').addEventListener('input',e=>{clearTimeout(searchT);const q=e.target.value.trim();if(!q){renderDefault();return;}searchT=setTimeout(()=>doSearch(q),350);});

  const[areas,cats]=await Promise.all([getAreas(),getCats()]);
  const pA=['Bangladeshi','Indian','Italian','Chinese','Thai','Japanese','Mexican','British','French','American','Turkish','Moroccan','Greek','Spanish','Vietnamese'];
  const allA=[...new Set([...pA.filter(a=>areas.includes(a)||a==='Bangladeshi'),...areas])];
  const pC=['Chicken','Beef','Seafood','Vegetarian','Pasta','Dessert','Breakfast','Lamb','Pork','Starter','Side','Miscellaneous'];
  const allC=[...new Set([...pC.filter(c=>cats.includes(c)),...cats])];

  document.getElementById('cuisChips').innerHTML=allA.map(a=>`<button class="chip ${curArea===a?'on':''}" data-area="${esc(a)}">${a}</button>`).join('');
  document.getElementById('catChips').innerHTML=allC.map(c=>`<button class="chip ${curCat===c?'on':''}" data-cat="${esc(c)}">${c}</button>`).join('');
  document.querySelectorAll('[data-area]').forEach(b=>b.addEventListener('click',()=>{curArea=curArea===b.dataset.area?'':b.dataset.area;curCat='';refreshChips();curArea?loadArea(curArea):renderDefault();}));
  document.querySelectorAll('[data-cat]').forEach(b=>b.addEventListener('click',()=>{curCat=curCat===b.dataset.cat?'':b.dataset.cat;curArea='';refreshChips();curCat?loadCat(curCat):renderDefault();}));
  renderDefault();
}
function refreshChips(){
  document.querySelectorAll('[data-area]').forEach(b=>b.classList.toggle('on',b.dataset.area===curArea));
  document.querySelectorAll('[data-cat]').forEach(b=>b.classList.toggle('on',b.dataset.cat===curCat));
}
function setTitle(t,s){document.getElementById('resTitle').textContent=t;document.getElementById('resSub').textContent=s;}
function showShim(){document.getElementById('resGrid').innerHTML=`<div class="grid">${Array(8).fill('<div class="shimmer"></div>').join('')}</div>`;}

/* Combine built-in + live recipes */
async function renderDefault(){
  setTitle('All recipes','');
  // STEP 1 — show built-in recipes IMMEDIATELY, no waiting
  const builtinList=vegOnly?BUILTIN.filter(m=>m.strCategory==='Vegetarian'):BUILTIN;
  document.getElementById('recipeCounter').textContent=builtinList.length+'+ recipes · videos · cloud sync';
  setTitle('All recipes',builtinList.length+' recipes');
  renderCards(builtinList);

  // STEP 2 — load live recipes in background, add them when ready
  try{
    const liveCats=['Chicken','Beef','Seafood','Vegetarian','Pasta','Dessert','Breakfast','Lamb'];
    const liveResults=await Promise.all(liveCats.map(c=>getMeals(c)));
    const liveMeals=[];const seen=new Set(BUILTIN.map(b=>b.idMeal));
    liveResults.flat().forEach(m=>{if(!seen.has(m.idMeal)){seen.add(m.idMeal);liveMeals.push(m);}});
    if(liveMeals.length>0){
      const all=[...BUILTIN,...liveMeals];
      const list=vegOnly?all.filter(m=>m.strCategory==='Vegetarian'):all;
      document.getElementById('recipeCounter').textContent=list.length+'+ recipes · videos · cloud sync';
      setTitle('All recipes',list.length+' recipes');
      renderCards(list);
    }
  }catch(e){
    // live API failed — built-in recipes already showing, no problem
  }
}

async function loadArea(a){setTitle(a+' recipes','');showShim();
  const live=await getMealsByArea(a);
  const bi=BUILTIN.filter(b=>b.strArea===a);
  const seen=new Set(bi.map(b=>b.idMeal));
  const all=[...bi,...live.filter(m=>!seen.has(m.idMeal))];
  setTitle(a+' recipes',all.length+' recipes');
  renderCards(vegOnly?all.filter(m=>m.strCategory==='Vegetarian'):all);
}
async function loadCat(c){setTitle(c,'');showShim();
  const live=await getMeals(c);
  const bi=BUILTIN.filter(b=>b.strCategory===c);
  const seen=new Set(bi.map(b=>b.idMeal));
  const all=[...bi,...live.filter(m=>!seen.has(m.idMeal))];
  setTitle(c,all.length+' recipes');
  renderCards(all);
}
async function doSearch(q){setTitle('Results for "'+q+'"','');showShim();
  const ql=q.toLowerCase();
  const bi=BUILTIN.filter(m=>m.strMeal.toLowerCase().includes(ql)||m.strArea.toLowerCase().includes(ql)||(m.strCategory||'').toLowerCase().includes(ql));
  const live=await searchMeals(q);
  const seen=new Set(bi.map(b=>b.idMeal));
  const all=[...bi,...live.filter(m=>!seen.has(m.idMeal))];
  all.sort((a,b)=>matchOf(b).pct-matchOf(a).pct);
  setTitle('Results for "'+q+'"',all.length+' results');
  renderCards(all);
}
async function cookHave(){setTitle('From your pantry','');showShim();
  const mains=['chicken','beef','egg','rice','potato','fish','prawn','lentil','pasta','tomato','mushroom','spinach'];
  const seeds=mains.filter(m=>pHas(pantry,m)).slice(0,3);
  const bi=BUILTIN.filter(m=>getIngs(m).some(i=>pHas(pantry,i.name)));
  if(!seeds.length&&!bi.length){toast('Add some pantry items first');renderDefault();return;}
  const sets=await Promise.all(seeds.map(s=>af(API+'filter.php?i='+encodeURIComponent(s))));
  const ids=new Set();sets.forEach(d=>(d?.meals||[]).slice(0,10).forEach(m=>ids.add(m.idMeal)));
  const full=await Promise.all([...ids].slice(0,14).map(id=>lookupMeal(id)));
  const all=[...bi,...full.filter(Boolean)];
  const seen=new Set();const unique=all.filter(m=>{if(seen.has(m.idMeal))return false;seen.add(m.idMeal);return true;});
  unique.sort((a,b)=>matchOf(b).pct-matchOf(a).pct);
  setTitle('From your pantry',unique.length+' matched');
  renderCards(unique);
}
async function doSurprise(){setTitle('Surprise!','');showShim();const m=await randomMeal();if(m)openMeal(m.idMeal);else{const b=BUILTIN[Math.floor(Math.random()*BUILTIN.length)];openMeal(b.idMeal);}}

function renderCards(meals){
  if(!meals?.length){document.getElementById('resGrid').innerHTML=`<div class="card empty"><div class="eic">${ic('search',22)}</div><h3>No recipes found</h3><p>Try a different search, cuisine or category.</p></div>`;return;}
  document.getElementById('resGrid').innerHTML=`<div class="grid">${meals.map(m=>cardH(m)).join('')}</div>`;
  wireCards(document.getElementById('resGrid'));
}
function cardH(meal){
  const sv=saved.has(meal.idMeal),mm=matchOf(meal),pct=Math.round(mm.pct*100);
  const col=mm.pct>=.999?'#1B6E47':mm.pct>=.5?'#E2941F':'#D1493A';
  const hasThumb=meal.strMealThumb&&meal.strMealThumb.trim();
  const em=emojiOf(meal),area=meal.strArea||meal.strCategory||'';
  return `<div class="rcard" data-open="${meal.idMeal}">
    <div class="rthumb" style="${hasThumb?'':'background:'+gradOf(meal.strArea)+''}">
      ${hasThumb?`<img src="${esc(meal.strMealThumb)}" loading="lazy" onerror="this.style.display='none'">`:''}
      ${!hasThumb?`<span class="em">${em}</span>`:''}
      ${area?`<span class="abadge">${esc(area)}</span>`:''}
      <div style="position:absolute;right:8px;bottom:36px;background:rgba(255,255,255,.93);border-radius:99px;padding:2px 7px;font-size:10.5px;font-weight:700;color:${col};">${pct}%</div>
      <button class="hbtn" data-save="${meal.idMeal}" aria-label="Save">${htIc(sv,16)}</button>
    </div>
    <div class="rbody">
      <div class="rname">${esc(meal.strMeal||'')}</div>
      <div class="rmeta"><span>${stH(4.5,11)}</span>${meal.strCategory?`<span class="pill p-i" style="font-size:10px;">${esc(meal.strCategory)}</span>`:''}</div>
      <div>${mm.pct>=.999?`<span class="pill p-g">${ic('check',12)} Have all</span>`:`<span class="pill p-s">${mm.miss.length} to buy</span>`}</div>
    </div>
  </div>`;
}
function wireCards(c){
  c.querySelectorAll('[data-open]').forEach(el=>el.addEventListener('click',e=>{if(e.target.closest('[data-save]'))return;openMeal(el.dataset.open);}));
  c.querySelectorAll('[data-save]').forEach(b=>b.addEventListener('click',e=>{e.stopPropagation();toggleSave(b.dataset.save,b);}));
}

/* ═══ MEAL MODAL ═══ */
let sheetEaters=[];
async function openMeal(id){
  showSheet('<div class="spin"></div>');
  let meal=BUILTIN.find(b=>b.idMeal===id)||await lookupMeal(id);
  if(!meal){closeModal();toast('Could not load recipe');return;}
  renderMeal(meal);
}
function renderMeal(meal){
  sheetEaters=members.map(m=>m.id);
  const id=meal.idMeal,vid=ytId(meal),src=meal.strSource?.trim(),sdom=srcDom(meal);
  const ings=getIngs(meal);
  const steps=(meal.strInstructions||'').split(/\r?\n/).map(s=>s.trim()).filter(s=>s.length>4);
  const sv=saved.has(id),mm=matchOf(meal),em=emojiOf(meal);
  const revs=reviews[id]||[];
  document.querySelector('.sheet').innerHTML=`
    <div class="s-hero" style="${meal.strMealThumb?'':'background:'+gradOf(meal.strArea)+''}">
      ${meal.strMealThumb?`<img src="${esc(meal.strMealThumb)}" onerror="this.style.display='none'">`:`<span style="font-size:70px;position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);">${em}</span>`}
      <button class="s-close" id="shClose">${ic('x',18)}</button>
    </div>
    <div class="s-pad">
      <div style="display:flex;align-items:flex-start;justify-content:space-between;gap:10px;">
        <div style="flex:1;"><h2>${esc(meal.strMeal)}</h2>
          <div class="meta-r">
            ${meal.strArea?`<span class="pill p-i">${esc(meal.strArea)}</span>`:''}
            ${meal.strCategory?`<span class="pill p-i">${esc(meal.strCategory)}</span>`:''}
            ${stH(4.5,13)} <span style="font-size:12.5px;">4.5</span>
            ${sdom?`<a class="src-badge" href="${esc(src)}" target="_blank" rel="noopener">${ic('link',11)} ${esc(sdom)}</a>`:''}
          </div>
        </div>
        <button id="likeBtn" style="display:flex;flex-direction:column;align-items:center;gap:2px;font-weight:700;font-size:12px;color:${sv?'#D1493A':'#9A8C75'};">${htIc(sv,24)}<span>${sv?'Saved':'Save'}</span></button>
      </div>
      <div style="display:flex;gap:8px;flex-wrap:wrap;margin-bottom:14px;">
        ${vid?`<a style="display:inline-flex;align-items:center;gap:6px;padding:7px 13px;border-radius:99px;background:#FFEBE8;color:#CC0000;font-size:13px;font-weight:700;text-decoration:none;" href="https://www.youtube.com/watch?v=${vid}" target="_blank" rel="noopener">${ic('play',15)} Watch video</a>`:''}
        ${src?`<a style="display:inline-flex;align-items:center;gap:6px;padding:7px 13px;border-radius:99px;background:var(--herb-s);color:var(--herb-d);font-size:13px;font-weight:700;text-decoration:none;" href="${esc(src)}" target="_blank" rel="noopener">${ic('link',15)} Source recipe</a>`:''}
        <button id="shareBtn" style="display:inline-flex;align-items:center;gap:6px;padding:7px 13px;border-radius:99px;background:#F3EEE3;color:#5B5142;font-size:13px;font-weight:700;">${ic('share',15)} Share</button>
        <button id="saveBtn" style="display:inline-flex;align-items:center;gap:6px;padding:7px 13px;border-radius:99px;background:${sv?'var(--tom-s)':'#F3EEE3'};color:${sv?'var(--tom-d)':'#5B5142'};font-size:13px;font-weight:700;">${htIc(sv,15)} ${sv?'Saved':'Save'}</button>
      </div>

      ${vid?`<div style="margin-bottom:18px;"><div class="lbl">${ic('play',15)} Cooking video</div>
        <div class="yt-box" id="ytBox">
          <div class="yt-ph" onclick="loadYt('${vid}','${esc(meal.strMeal)}')">
            ${meal.strMealThumb?`<img src="${esc(meal.strMealThumb)}">`:''}
            <div class="play">${ic('play',22)}</div>
            <div class="ptitle">▶ Watch: ${esc(meal.strMeal)}</div>
          </div>
        </div></div>`:''}

      <div style="margin-bottom:16px;"><div class="lbl">${ic('users',15)} Who's eating?</div>
        <div id="eatRow" style="display:flex;flex-wrap:wrap;gap:6px;"></div></div>

      <div class="card" style="padding:14px;margin-bottom:18px;">
        <div class="lbl">${ic('carrot',15)} Ingredients — ${mm.have}/${mm.total} in your pantry</div>
        <div id="ingList"></div>
        <div class="muted" style="font-size:12.5px;margin-top:8px;" id="missNote"></div>
      </div>

      <div style="margin-bottom:18px;"><div class="lbl">${ic('chef',15)} Method</div>
        <ol style="list-style:none;padding:0;display:grid;gap:10px;">
          ${steps.map((s,i)=>`<li class="step"><span class="stepn">${i+1}</span><span style="font-size:14px;line-height:1.5;color:#3A3327;">${esc(s)}</span></li>`).join('')}
        </ol>
        ${!steps.length&&src?`<p class="muted" style="font-size:13.5px;">Full method at <a href="${esc(src)}" target="_blank">${esc(sdom||src)}</a></p>`:''}
      </div>

      <div class="card" style="padding:14px;margin-bottom:18px;">
        <div class="lbl">${ic('calendar',15)} Add to meal plan</div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:10px;">
          <select id="pDay" class="inp">${['Mon','Tue','Wed','Thu','Fri','Sat','Sun'].map(d=>`<option>${d}</option>`).join('')}</select>
          <select id="pMeal" class="inp">${['breakfast','lunch','dinner'].map(m=>`<option value="${m}">${cap(m)}</option>`).join('')}</select>
        </div>
        <button class="btn btn-g btn-b" id="addPlanBtn">${ic('plus',17)} Add to plan</button>
      </div>

      <div><div class="lbl">${ic('msg',15)} Reviews (${revs.length})</div>
        <div id="revList"></div>
        <div class="card" style="padding:12px;margin-top:10px;">
          <div id="starsIn" class="star-row"></div>
          <textarea id="revTxt" class="inp" placeholder="Share a tip or review…"></textarea>
          <button class="btn btn-g btn-b" id="postRevBtn" style="margin-top:8px;">Post review</button>
        </div>
      </div>
    </div>`;

  document.getElementById('shClose').onclick=closeModal;
  const updateSave=()=>{const s=saved.has(id);['likeBtn','saveBtn'].forEach(bid=>{const b=document.getElementById(bid);if(!b)return;if(bid==='likeBtn')b.innerHTML=htIc(s,24)+'<span>'+(s?'Saved':'Save')+'</span>';else b.innerHTML=htIc(s,15)+' '+(s?'Saved':'Save');b.style.background=bid==='saveBtn'?(s?'var(--tom-s)':'#F3EEE3'):'';b.style.color=bid==='saveBtn'?(s?'var(--tom-d)':'#5B5142'):'';});};
  document.getElementById('saveBtn').onclick=()=>{toggleSave(id);updateSave();};
  document.getElementById('likeBtn').onclick=()=>{toggleSave(id);updateSave();};
  document.getElementById('shareBtn').onclick=()=>doShare(meal);
  document.getElementById('addPlanBtn').onclick=()=>{const key=document.getElementById('pDay').value+'-'+document.getElementById('pMeal').value;plan[key]=plan[key]||[];plan[key].push({id,name:meal.strMeal,thumb:meal.strMealThumb||'',memberIds:[...sheetEaters]});lsSave();if(sbC&&user)sbSync();toast('Added to plan');};

  const renderEaters=()=>{
    const er=document.getElementById('eatRow');if(!er)return;
    er.innerHTML=members.map(mem=>{const on=sheetEaters.includes(mem.id);return `<button class="eater-btn" data-em="${mem.id}" style="border-color:${on?'var(--herb)':'var(--line)'};background:${on?'var(--herb-s)':'#fff'};color:${on?'var(--herb-d)':'var(--muted)'};">${avH(mem.name,20)} ${esc(mem.name)}</button>`;}).join('');
    document.querySelectorAll('[data-em]').forEach(b=>b.onclick=()=>{const mid=b.dataset.em;sheetEaters=sheetEaters.includes(mid)?sheetEaters.filter(x=>x!==mid):[...sheetEaters,mid];renderEaters();});
  };
  renderEaters();

  const il=document.getElementById('ingList');
  if(il)il.innerHTML=ings.map((ing,i)=>{const h=pHas(pantry,ing.name);return `<div class="ing-item" ${i===0?'style="border-top:none;"':''} style="${i===0?'border-top:none;':''}background:${h?'#fff':'#FCF4F2'}"><span style="display:inline-flex;align-items:center;gap:9px;font-size:14px;"><span class="ichk" style="background:${h?'var(--herb-s)':'var(--tom-s)'};color:${h?'var(--herb-d)':'var(--tom-d)'}">${h?ic('check',12):ic('plus',12)}</span><span style="text-transform:capitalize;font-weight:500;">${esc(ing.name)}</span></span><span style="display:inline-flex;align-items:center;gap:8px;"><span style="font-size:13px;color:#5B5142;font-weight:600;">${esc(ing.measure)}</span><span style="font-size:10.5px;font-weight:700;color:${h?'var(--herb-d)':'var(--tom-d)'};">${h?'HAVE':'BUY'}</span></span></div>`;}).join('');
  const mn=document.getElementById('missNote');if(mn)mn.textContent=mm.miss.length===0?'You have everything for this dish.':'You\'ll need to buy '+mm.miss.length+' of '+ings.length+' ingredients.';

  const renderRevs=()=>{const rl=document.getElementById('revList');if(!rl)return;const rs=reviews[id]||[];rl.innerHTML=rs.length?rs.map(r=>`<div class="card" style="padding:12px;margin-bottom:10px;"><div style="display:flex;align-items:center;gap:8px;margin-bottom:5px;">${avH(r.user,22)}<span style="font-size:13px;font-weight:700;">${esc(r.user)}</span>${stH(r.stars,12)}</div><div style="font-size:13.5px;color:#3A3327;line-height:1.45;">${esc(r.text)}</div></div>`).join(''):'<p class="muted" style="font-size:13px;margin-bottom:10px;">No reviews yet — be the first.</p>';};
  renderRevs();
  let pStars=5;
  const drawSt=()=>{const si=document.getElementById('starsIn');if(!si)return;si.innerHTML=[1,2,3,4,5].map(i=>`<button data-s="${i}" style="padding:2px;display:flex;">${stIc(22,i<=pStars)}</button>`).join('');si.querySelectorAll('[data-s]').forEach(b=>b.onclick=()=>{pStars=+b.dataset.s;drawSt();});};
  drawSt();
  document.getElementById('postRevBtn').onclick=async()=>{const txt=document.getElementById('revTxt').value.trim();if(!txt){toast('Write something first');return;}const uname=user?user.email.split('@')[0]:'You';reviews[id]=reviews[id]||[];reviews[id].unshift({user:uname,stars:pStars,text:txt});document.getElementById('revTxt').value='';lsSave();if(sbC&&user)await sbC.from('reviews').insert({user_id:user.id,recipe_id:id,user_name:uname,stars:pStars,text:txt}).catch(()=>{});renderRevs();toast('Review posted!');};
  document.body.style.overflow='hidden';
}

window.loadYt=function(vid,title){const b=document.getElementById('ytBox');if(!b)return;b.innerHTML=`<iframe src="https://www.youtube.com/embed/${vid}?autoplay=1&rel=0" title="${esc(title)}" allow="autoplay;encrypted-media" allowfullscreen></iframe>`;};

async function doShare(meal){
  const url=meal.strSource||`https://www.themealdb.com/meal/${meal.idMeal}`;
  const text=meal.strMeal+' recipe';
  try{if(navigator.share){await navigator.share({title:meal.strMeal,text,url});return;}}catch(e){if(e.name==='AbortError')return;}
  const wa='https://wa.me/?text='+encodeURIComponent(text+'\n'+url);
  const n=document.createElement('div');n.className='scrim';n.style.zIndex=70;
  n.innerHTML=`<div class="sheet" style="max-width:400px;"><div class="s-pad"><div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:14px;"><h2 style="font-size:19px;">Share</h2><button class="s-close" id="scl" style="position:relative;right:auto;top:auto;">${ic('x',17)}</button></div><p class="muted" style="font-size:13.5px;margin-bottom:14px;">${esc(meal.strMeal)}</p><div style="display:grid;gap:8px;"><a class="btn btn-g btn-b" href="${wa}" target="_blank" rel="noopener" style="background:#25D366;text-decoration:none;">${ic('share',15)} WhatsApp</a><a class="btn btn-w btn-b" href="mailto:?subject=${encodeURIComponent('Recipe: '+meal.strMeal)}&body=${encodeURIComponent(text+'\n'+url)}" style="text-decoration:none;">${ic('msg',15)} Email</a><button class="btn btn-w btn-b" id="cpyBtn">${ic('link',15)} Copy link</button></div></div></div>`;
  document.body.appendChild(n);
  n.onclick=e=>{if(e.target===n)n.remove();};
  n.querySelector('#scl').onclick=()=>n.remove();
  n.querySelector('#cpyBtn').onclick=async()=>{try{await navigator.clipboard.writeText(text+'\n'+url);toast('Copied!');}catch{toast('Copy unavailable');}n.remove();};
}

function toggleSave(id,btn){saved.has(id)?(saved.delete(id),toast('Removed')):(saved.add(id),toast('Saved!'));lsSave();if(sbC&&user)sbSync();if(btn)btn.innerHTML=htIc(saved.has(id),16);}

function showSheet(inner){closeModal();const n=document.createElement('div');n.className='scrim';n.id='mScrim';n.innerHTML=`<div class="sheet">${inner}</div>`;document.getElementById('modalRoot').appendChild(n);n.onclick=e=>{if(e.target===n)closeModal();};document.body.style.overflow='hidden';}
function closeModal(){const n=document.getElementById('mScrim');if(n)n.remove();document.body.style.overflow='';}

/* ═══ SAVED ═══ */
function renderSaved(){
  const ids=[...saved];
  document.getElementById('savedCount').textContent=ids.length?ids.length+' saved':'';
  const empty=document.getElementById('savedEmpty'),grid=document.getElementById('savedGrid');
  if(!ids.length){grid.innerHTML='';empty.innerHTML=`<div class="card empty"><div class="eic">${ic('heart',22)}</div><h3>Nothing saved yet</h3><p>Tap the heart on any recipe.</p></div>`;return;}
  empty.innerHTML='';
  const stubs=ids.map(id=>{const c=BUILTIN.find(b=>b.idMeal===id)||MC['meal_'+id];return c||{idMeal:id,strMeal:'Recipe',strMealThumb:'',strArea:'',strCategory:''};});
  grid.innerHTML=stubs.map(m=>cardH(m)).join('');
  wireCards(grid);
}

/* ═══ PANTRY ═══ */
function renderPantry(){
  document.getElementById('panAdd').innerHTML=ic('plus',18);
  const sb=document.getElementById('panBanner');
  if(user&&!DEMO)sb.innerHTML='<div class="banner ban-g">'+ic('cloud',14)+' Synced with your account.</div>';
  else if(DEMO)sb.innerHTML='<div class="banner ban-s">Offline mode. Sign in to sync across devices.</div>';
  else sb.innerHTML='';
  const tags=document.getElementById('panTags');
  tags.innerHTML=pantry.map((p,i)=>`<span class="ptag">${esc(p)}<button data-dp="${i}" style="display:flex;color:#B6A98F;margin-left:2px;">${ic('x',13)}</button></span>`).join('');
  tags.querySelectorAll('[data-dp]').forEach(b=>b.onclick=()=>{pantry.splice(+b.dataset.dp,1);lsSave();if(sbC&&user)sbSync();renderPantry();});
}
function addPantry(){const inp=document.getElementById('panInp');const v=inp.value.trim().toLowerCase();if(!v)return;if(!pantry.some(p=>p.toLowerCase()===v))pantry.push(v);inp.value='';lsSave();if(sbC&&user)sbSync();renderPantry();}
document.getElementById('panAdd').addEventListener('click',addPantry);
document.getElementById('panInp').addEventListener('keydown',e=>{if(e.key==='Enter')addPantry();});

/* ═══ PLANNER ═══ */
function renderPlanner(){
  const total=Object.values(plan).reduce((n,a)=>n+a.length,0);
  document.getElementById('planCount').textContent=total+' meals planned';
  const empty=document.getElementById('planEmpty'),grid=document.getElementById('planGrid');
  empty.innerHTML=total?'':`<div class="card empty"><div class="eic">${ic('calendar',22)}</div><h3>Your week is empty</h3><p>Open a recipe and tap "Add to plan".</p></div>`;
  grid.innerHTML=['Mon','Tue','Wed','Thu','Fri','Sat','Sun'].map(day=>`<div class="card day-card"><div class="dn">${day}</div>${['breakfast','lunch','dinner'].map(ml=>{const key=day+'-'+ml;const items=plan[key]||[];return `<div style="margin-bottom:8px;"><div class="slot-h"><span class="slot-lbl">${ml}</span><button style="display:inline-flex;align-items:center;gap:4px;color:var(--herb);font-weight:700;font-size:12.5px;" data-add="${key}">${ic('plus',14)} Add</button></div>${items.map((en,idx)=>`<div class="plan-item">${en.thumb?`<img class="plan-th" src="${esc(en.thumb)}" onerror="this.style.display='none'">`:`<div class="plan-th" style="display:flex;align-items:center;justify-content:center;font-size:18px;">🍲</div>`}<button data-open="${en.id}" style="flex:1;text-align:left;"><div style="font-size:13.5px;font-weight:600;color:#3A3327;">${esc(en.name||en.id)}</div></button><span style="display:flex;margin-right:4px;">${members.filter(m=>en.memberIds.includes(m.id)).slice(0,3).map((m,i)=>`<span style="margin-left:${i?-5:0}px">${avH(m.name,20)}</span>`).join('')}</span><button data-rm="${key}:${idx}" style="color:#C9776B;display:flex;padding:2px;">${ic('trash',15)}</button></div>`).join('')||`<div class="muted" style="font-size:12.5px;padding:4px 0;">—</div>`}</div>`;}).join('')}</div>`).join('');
  grid.querySelectorAll('[data-open]').forEach(b=>b.onclick=()=>openMeal(b.dataset.open));
  grid.querySelectorAll('[data-rm]').forEach(b=>b.onclick=()=>{const[k,i]=b.dataset.rm.split(':');plan[k].splice(+i,1);lsSave();if(sbC&&user)sbSync();renderPlanner();});
  grid.querySelectorAll('[data-add]').forEach(b=>b.onclick=()=>addDishModal(b.dataset.add));
  renderShopping();
}
async function addDishModal(key){
  const[day,ml]=key.split('-');let mIds=members.map(m=>m.id);
  const n=document.createElement('div');n.className='scrim';n.style.zIndex=70;
  n.innerHTML=`<div class="sheet" style="max-width:560px;"><div class="s-pad"><div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:12px;"><h2 style="font-size:19px;">Add to ${day} · ${cap(ml)}</h2><button class="s-close" id="adCl" style="position:relative;right:auto;top:auto;">${ic('x',17)}</button></div><div class="s-wrap" style="margin-bottom:12px;"><span class="s-ico">${ic('search',16)}</span><input id="adQ" class="inp pl" placeholder="Search recipes…" autocomplete="off"/></div><div id="adRes"><div class="spin"></div></div></div></div>`;
  document.body.appendChild(n);
  n.onclick=e=>{if(e.target===n)n.remove();};
  n.querySelector('#adCl').onclick=()=>n.remove();
  const search2=async()=>{
    const res=n.querySelector('#adRes');res.innerHTML='<div class="spin"></div>';
    const q=n.querySelector('#adQ').value.trim()||'chicken';
    const bi=BUILTIN.filter(m=>m.strMeal.toLowerCase().includes(q.toLowerCase()));
    const live=await searchMeals(q);
    const seen=new Set(bi.map(b=>b.idMeal));
    const all=[...bi,...live.filter(m=>!seen.has(m.idMeal))].slice(0,14);
    if(!all.length){res.innerHTML='<p class="muted" style="font-size:13px;">No results</p>';return;}
    res.innerHTML=`<div style="display:grid;gap:8px;">${all.map(m=>`<button data-pick="${m.idMeal}" style="display:flex;align-items:center;gap:11px;padding:10px;border-radius:12px;border:1px solid var(--line);background:#fff;text-align:left;width:100%;">${m.strMealThumb?`<img src="${esc(m.strMealThumb)}" style="width:42px;height:42px;border-radius:8px;object-fit:cover;flex-shrink:0;">`:``}<span style="flex:1;"><div style="font-size:14px;font-weight:600;">${esc(m.strMeal)}</div><div class="muted" style="font-size:11.5px;">${esc(m.strArea||m.strCategory||'')}</div></span></button>`).join('')}</div>`;
    res.querySelectorAll('[data-pick]').forEach(b=>b.onclick=()=>{const m=all.find(x=>x.idMeal===b.dataset.pick);plan[key]=plan[key]||[];plan[key].push({id:m.idMeal,name:m.strMeal,thumb:m.strMealThumb||'',memberIds:[...mIds]});lsSave();if(sbC&&user)sbSync();n.remove();renderPlanner();toast('Added to '+day);});
  };
  search2();
  let st=null;n.querySelector('#adQ').addEventListener('input',()=>{clearTimeout(st);st=setTimeout(search2,350);});
}
function renderShopping(){
  const box=document.getElementById('shopBox');const all=Object.values(plan).flat();
  if(!all.length){box.innerHTML='<p class="muted" style="font-size:13px;">Plan some meals and your shopping list builds automatically.</p>';return;}
  const agg={};
  all.forEach(en=>{const m=BUILTIN.find(b=>b.idMeal===en.id)||MC['meal_'+en.id];if(!m)return;getIngs(m).forEach(({name,measure})=>{const k=bW(name);if(!agg[k])agg[k]={name,measure,count:0};agg[k].count++;});});
  const buy=[],have=[];
  Object.values(agg).forEach(it=>{(pHas(pantry,it.name)?have:buy).push(it);});
  buy.sort((a,b)=>a.name.localeCompare(b.name));
  box.innerHTML=`<div style="display:flex;align-items:center;gap:7px;margin-bottom:10px;">${ic('basket',16)} <span style="font-weight:700;font-size:13.5px;">To buy (${buy.length})</span></div>${buy.length?`<div style="margin-bottom:14px;">${buy.map((it,i)=>`<div style="display:flex;justify-content:space-between;align-items:center;padding:8px 0;${i?'border-top:1px solid #F1EADC;':''}"><span style="text-transform:capitalize;font-size:13.5px;font-weight:500;">${esc(it.name)}</span><span class="muted" style="font-size:12.5px;">${esc(it.measure)}</span></div>`).join('')}</div>`:'<p style="font-size:12.5px;color:var(--herb-d);margin-bottom:14px;">Your pantry covers everything!</p>'}${have.length?`<div style="display:flex;align-items:center;gap:7px;margin-bottom:8px;">${ic('check',15,2)} <span style="font-weight:700;font-size:13.5px;color:var(--herb-d);">In pantry (${have.length})</span></div><div style="display:flex;flex-wrap:wrap;gap:6px;">${have.map(it=>`<span class="pill p-g" style="text-transform:capitalize;">${esc(it.name)}</span>`).join('')}</div>`:''}`;
}

/* ═══ HOUSEHOLD ═══ */
const RESTS=['Vegetarian','Gluten-free','Dairy-free','Nut-free','Egg-free'];
function renderHousehold(){
  document.getElementById('addMemberBtn').innerHTML=ic('plus',16)+' Add member';
  document.getElementById('hhSub').textContent=members.length+' '+(members.length===1?'person':'people')+' — sets default servings and diet preferences.';
  document.getElementById('memberGrid').innerHTML=members.map(m=>`<div class="card" style="padding:14px;"><div style="display:flex;align-items:center;gap:10px;margin-bottom:10px;">${avH(m.name,38)}<div style="flex:1;"><div style="font-family:var(--dp);font-size:17px;font-weight:600;">${esc(m.name)}</div><div class="muted" style="font-size:12.5px;">${m.age} yrs · ${m.weight} kg</div></div><button data-edit="${m.id}" style="border:1px solid var(--line);background:#fff;border-radius:10px;padding:7px;display:flex;color:var(--muted);">${ic('pencil',15)}</button></div><div style="display:flex;align-items:center;gap:8px;margin-bottom:10px;">${ic('flame',15)}<span style="font-size:13px;font-weight:600;">${m.target} kcal/day</span></div><div style="display:flex;flex-wrap:wrap;gap:6px;">${m.restrictions.length?m.restrictions.map(r=>`<span class="pill p-t">${r}</span>`).join(''):'<span class="muted" style="font-size:12px;">No restrictions</span>'}</div></div>`).join('');
  document.querySelectorAll('[data-edit]').forEach(b=>b.onclick=()=>editMember(b.dataset.edit));
  document.getElementById('addMemberBtn').onclick=()=>editMember('new');
}
function editMember(id){
  const isNew=id==='new';
  const src=isNew?{id:'new',name:'',age:30,weight:60,target:2000,restrictions:[]}:{...members.find(m=>m.id===id),restrictions:[...members.find(m=>m.id===id).restrictions]};
  const f={...src};
  const n=document.createElement('div');n.className='scrim';n.style.zIndex=70;
  n.innerHTML=`<div class="sheet" style="max-width:480px;"><div class="s-pad"><div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:14px;"><h2 style="font-size:20px;">${isNew?'Add member':'Edit member'}</h2><button class="s-close" id="emCl" style="position:relative;right:auto;top:auto;">${ic('x',17)}</button></div><div style="margin-bottom:12px;"><div class="fl">Name</div><input id="fN" class="inp" value="${esc(f.name)}" placeholder="e.g. Sadia"/></div><div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:10px;margin-bottom:12px;"><div><div class="fl">Age</div><input id="fA" class="inp" inputmode="numeric" value="${f.age}"/></div><div><div class="fl">Weight kg</div><input id="fW" class="inp" inputmode="numeric" value="${f.weight}"/></div><div><div class="fl">kcal/day</div><input id="fC" class="inp" inputmode="numeric" value="${f.target}"/></div></div><div style="margin-bottom:18px;"><div class="fl">Dietary restrictions</div><div id="fR" style="display:flex;flex-wrap:wrap;gap:6px;"></div></div><div style="display:flex;gap:10px;">${isNew?'':`<button id="emDel" style="padding:11px 14px;border-radius:12px;border:1px solid #F0CDC6;background:var(--tom-s);color:var(--tom-d);font-weight:600;">${ic('trash',16)}</button>`}<button id="emSave" class="btn btn-g btn-b">Save member</button></div></div></div>`;
  document.body.appendChild(n);
  const drawR=()=>{n.querySelector('#fR').innerHTML=RESTS.map(r=>{const on=f.restrictions.includes(r);return `<button data-r="${r}" style="padding:6px 12px;border-radius:99px;border:1px solid ${on?'var(--tom-d)':'var(--line)'};background:${on?'var(--tom-s)':'#fff'};color:${on?'var(--tom-d)':'var(--muted)'};font-weight:600;font-size:12.5px;">${r}</button>`;}).join('');n.querySelectorAll('[data-r]').forEach(b=>b.onclick=()=>{const r=b.dataset.r;f.restrictions=f.restrictions.includes(r)?f.restrictions.filter(x=>x!==r):[...f.restrictions,r];drawR();});};drawR();
  n.onclick=e=>{if(e.target===n)n.remove();};n.querySelector('#emCl').onclick=()=>n.remove();
  if(!isNew)n.querySelector('#emDel').onclick=()=>{members=members.filter(x=>x.id!==id);lsSave();if(sbC&&user)sbSync();n.remove();renderHousehold();};
  n.querySelector('#emSave').onclick=()=>{const name=n.querySelector('#fN').value.trim();if(!name){toast('Name required');return;}const obj={id:isNew?'m'+Date.now():id,name,age:+n.querySelector('#fA').value||0,weight:+n.querySelector('#fW').value||0,target:+n.querySelector('#fC').value||0,restrictions:f.restrictions};if(isNew)members.push(obj);else members=members.map(x=>x.id===id?obj:x);lsSave();if(sbC&&user)sbSync();n.remove();renderHousehold();};
}

/* ═══ BOOT ═══ */
async function boot(){
  renderTabs();
  await initAuth();
  await initDiscover();
  document.getElementById('panAdd').innerHTML=ic('plus',18);
}
boot();
</script>
</body>
</html>
