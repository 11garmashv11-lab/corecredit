<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CreditCore — Дорожная карта проекта</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
:root {
  --bg: #0a0b0f;
  --bg2: #0f1117;
  --bg3: #13151e;
  --card: #141720;
  --border: rgba(255,255,255,0.07);
  --border2: rgba(255,255,255,0.12);
  --accent: #4f8fff;
  --accent2: #7c3aff;
  --accent3: #00d4aa;
  --accent4: #ff6b35;
  --accent5: #ffd166;
  --text: #e8eaf0;
  --text2: #8892a4;
  --text3: #505870;
  --glow: rgba(79,143,255,0.15);
  --glow2: rgba(124,58,255,0.12);
}

*{margin:0;padding:0;box-sizing:border-box}

html{scroll-behavior:smooth}

body{
  background:var(--bg);
  color:var(--text);
  font-family:'Inter',sans-serif;
  font-size:15px;
  line-height:1.7;
  overflow-x:hidden;
}

/* ── NOISE TEXTURE ── */
body::before{
  content:'';
  position:fixed;
  inset:0;
  background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.03'/%3E%3C/svg%3E");
  pointer-events:none;
  z-index:0;
  opacity:.4;
}

/* ── HERO ── */
.hero{
  min-height:100vh;
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:80px 24px 60px;
  position:relative;
  overflow:hidden;
}

.hero-bg{
  position:absolute;
  inset:0;
  background:
    radial-gradient(ellipse 80% 60% at 50% 0%, rgba(79,143,255,0.1) 0%, transparent 60%),
    radial-gradient(ellipse 60% 40% at 80% 80%, rgba(124,58,255,0.08) 0%, transparent 50%),
    radial-gradient(ellipse 50% 50% at 20% 60%, rgba(0,212,170,0.06) 0%, transparent 50%);
  pointer-events:none;
}

.hero-grid{
  position:absolute;
  inset:0;
  background-image:
    linear-gradient(rgba(255,255,255,0.025) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.025) 1px, transparent 1px);
  background-size:60px 60px;
  mask-image:radial-gradient(ellipse 80% 70% at 50% 30%, black 0%, transparent 80%);
  pointer-events:none;
}

.badge{
  display:inline-flex;
  align-items:center;
  gap:8px;
  background:rgba(79,143,255,0.1);
  border:1px solid rgba(79,143,255,0.25);
  border-radius:100px;
  padding:6px 16px;
  font-size:12px;
  font-weight:500;
  color:var(--accent);
  letter-spacing:.05em;
  text-transform:uppercase;
  margin-bottom:28px;
  opacity:0;
  animation:fadeUp .6s .1s forwards;
}

.badge-dot{
  width:6px;height:6px;
  border-radius:50%;
  background:var(--accent);
  animation:pulse 2s infinite;
}

@keyframes pulse{
  0%,100%{opacity:1;transform:scale(1)}
  50%{opacity:.4;transform:scale(.7)}
}

.hero h1{
  font-family:'Syne',sans-serif;
  font-size:clamp(42px,8vw,88px);
  font-weight:800;
  line-height:1.0;
  letter-spacing:-.03em;
  margin-bottom:8px;
  opacity:0;
  animation:fadeUp .7s .2s forwards;
}

.hero h1 span{
  background:linear-gradient(135deg, var(--accent) 0%, var(--accent2) 50%, var(--accent3) 100%);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
}

.hero-sub{
  font-family:'Syne',sans-serif;
  font-size:clamp(18px,3vw,26px);
  font-weight:600;
  color:var(--text2);
  margin-bottom:20px;
  opacity:0;
  animation:fadeUp .7s .3s forwards;
}

.hero-desc{
  max-width:600px;
  color:var(--text2);
  font-size:16px;
  line-height:1.8;
  margin-bottom:48px;
  opacity:0;
  animation:fadeUp .7s .4s forwards;
}

.hero-stats{
  display:flex;
  gap:48px;
  justify-content:center;
  flex-wrap:wrap;
  margin-bottom:60px;
  opacity:0;
  animation:fadeUp .7s .5s forwards;
}

.stat{
  text-align:center;
}

.stat-val{
  font-family:'Syne',sans-serif;
  font-size:32px;
  font-weight:800;
  color:var(--text);
  display:block;
}

.stat-label{
  font-size:12px;
  color:var(--text3);
  text-transform:uppercase;
  letter-spacing:.08em;
  font-weight:500;
}

.scroll-hint{
  position:absolute;
  bottom:32px;
  left:50%;
  transform:translateX(-50%);
  display:flex;
  flex-direction:column;
  align-items:center;
  gap:8px;
  color:var(--text3);
  font-size:11px;
  letter-spacing:.1em;
  text-transform:uppercase;
  opacity:0;
  animation:fadeUp .7s 1s forwards;
}

.scroll-line{
  width:1px;height:40px;
  background:linear-gradient(var(--accent), transparent);
  animation:scrollPulse 2s infinite;
}

@keyframes scrollPulse{
  0%{transform:scaleY(0);transform-origin:top}
  50%{transform:scaleY(1);transform-origin:top}
  51%{transform:scaleY(1);transform-origin:bottom}
  100%{transform:scaleY(0);transform-origin:bottom}
}

/* ── SECTION ── */
.section{
  padding:80px 24px;
  max-width:1200px;
  margin:0 auto;
}

.section-label{
  font-size:11px;
  font-weight:600;
  letter-spacing:.15em;
  text-transform:uppercase;
  color:var(--accent);
  margin-bottom:12px;
}

.section-title{
  font-family:'Syne',sans-serif;
  font-size:clamp(28px,4vw,44px);
  font-weight:800;
  line-height:1.1;
  letter-spacing:-.02em;
  margin-bottom:16px;
}

.section-desc{
  color:var(--text2);
  max-width:560px;
  font-size:16px;
  line-height:1.8;
  margin-bottom:56px;
}

/* ── PHASE CARDS ── */
.phases{
  display:flex;
  flex-direction:column;
  gap:0;
  position:relative;
}

.phases::before{
  content:'';
  position:absolute;
  left:31px;
  top:40px;
  bottom:40px;
  width:2px;
  background:linear-gradient(var(--accent) 0%, var(--accent2) 50%, var(--accent3) 100%);
  opacity:.3;
}

.phase{
  display:grid;
  grid-template-columns:64px 1fr;
  gap:0 28px;
  padding:0 0 48px;
  opacity:0;
  transform:translateY(24px);
  transition:opacity .6s, transform .6s;
}

.phase.visible{
  opacity:1;
  transform:none;
}

.phase-num{
  display:flex;
  align-items:flex-start;
  padding-top:4px;
  flex-direction:column;
  align-items:center;
  gap:0;
}

.num-circle{
  width:64px;height:64px;
  border-radius:50%;
  display:flex;
  align-items:center;
  justify-content:center;
  font-family:'Syne',sans-serif;
  font-size:20px;
  font-weight:800;
  flex-shrink:0;
  position:relative;
  z-index:1;
}

.phase:nth-child(1) .num-circle{background:rgba(79,143,255,0.15);color:var(--accent);border:1.5px solid rgba(79,143,255,0.4)}
.phase:nth-child(2) .num-circle{background:rgba(124,58,255,0.15);color:var(--accent2);border:1.5px solid rgba(124,58,255,0.4)}
.phase:nth-child(3) .num-circle{background:rgba(0,212,170,0.12);color:var(--accent3);border:1.5px solid rgba(0,212,170,0.35)}
.phase:nth-child(4) .num-circle{background:rgba(255,107,53,0.12);color:var(--accent4);border:1.5px solid rgba(255,107,53,0.35)}
.phase:nth-child(5) .num-circle{background:rgba(255,209,102,0.12);color:var(--accent5);border:1.5px solid rgba(255,209,102,0.35)}

.phase-body{
  border:1px solid var(--border);
  border-radius:16px;
  background:var(--card);
  padding:28px 32px 32px;
  position:relative;
  overflow:hidden;
}

.phase-body::before{
  content:'';
  position:absolute;
  inset:0;
  opacity:0;
  transition:opacity .4s;
  pointer-events:none;
}

.phase:nth-child(1) .phase-body::before{background:radial-gradient(ellipse 80% 60% at 0% 0%, rgba(79,143,255,0.05), transparent)}
.phase:nth-child(2) .phase-body::before{background:radial-gradient(ellipse 80% 60% at 0% 0%, rgba(124,58,255,0.05), transparent)}
.phase:nth-child(3) .phase-body::before{background:radial-gradient(ellipse 80% 60% at 0% 0%, rgba(0,212,170,0.04), transparent)}
.phase:nth-child(4) .phase-body::before{background:radial-gradient(ellipse 80% 60% at 0% 0%, rgba(255,107,53,0.04), transparent)}
.phase:nth-child(5) .phase-body::before{background:radial-gradient(ellipse 80% 60% at 0% 0%, rgba(255,209,102,0.04), transparent)}

.phase:hover .phase-body::before{opacity:1}

.phase-header{
  display:flex;
  align-items:flex-start;
  justify-content:space-between;
  margin-bottom:20px;
  gap:16px;
  flex-wrap:wrap;
}

.phase-tag{
  font-size:11px;
  font-weight:600;
  letter-spacing:.1em;
  text-transform:uppercase;
  padding:4px 12px;
  border-radius:100px;
  white-space:nowrap;
}

.phase:nth-child(1) .phase-tag{background:rgba(79,143,255,0.12);color:var(--accent)}
.phase:nth-child(2) .phase-tag{background:rgba(124,58,255,0.12);color:var(--accent2)}
.phase:nth-child(3) .phase-tag{background:rgba(0,212,170,0.1);color:var(--accent3)}
.phase:nth-child(4) .phase-tag{background:rgba(255,107,53,0.1);color:var(--accent4)}
.phase:nth-child(5) .phase-tag{background:rgba(255,209,102,0.1);color:var(--accent5)}

.phase-title{
  font-family:'Syne',sans-serif;
  font-size:22px;
  font-weight:700;
  letter-spacing:-.01em;
  line-height:1.2;
  margin-bottom:10px;
}

.phase-desc{
  color:var(--text2);
  font-size:14px;
  line-height:1.75;
  margin-bottom:24px;
}

.tasks{
  display:grid;
  grid-template-columns:repeat(auto-fill, minmax(220px, 1fr));
  gap:10px;
}

.task{
  display:flex;
  align-items:flex-start;
  gap:10px;
  background:rgba(255,255,255,0.03);
  border:1px solid var(--border);
  border-radius:10px;
  padding:12px 14px;
  font-size:13px;
  color:var(--text2);
  line-height:1.5;
}

.task-icon{
  width:20px;height:20px;
  border-radius:6px;
  display:flex;
  align-items:center;
  justify-content:center;
  flex-shrink:0;
  font-size:11px;
  margin-top:1px;
}

.phase:nth-child(1) .task-icon{background:rgba(79,143,255,0.15);color:var(--accent)}
.phase:nth-child(2) .task-icon{background:rgba(124,58,255,0.15);color:var(--accent2)}
.phase:nth-child(3) .task-icon{background:rgba(0,212,170,0.12);color:var(--accent3)}
.phase:nth-child(4) .task-icon{background:rgba(255,107,53,0.12);color:var(--accent4)}
.phase:nth-child(5) .task-icon{background:rgba(255,209,102,0.12);color:var(--accent5)}

.task strong{color:var(--text);font-weight:500}

/* ── BUREAUS SECTION ── */
.bureaus-grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:20px;
  margin-bottom:40px;
}

.bureau-card{
  border:1px solid var(--border);
  border-radius:16px;
  background:var(--card);
  padding:28px 24px;
  position:relative;
  overflow:hidden;
  opacity:0;
  transform:translateY(20px);
  transition:all .5s;
}

.bureau-card.visible{opacity:1;transform:none}

.bureau-card:hover{
  border-color:var(--border2);
  transform:translateY(-3px);
}

.bureau-logo{
  font-family:'Syne',sans-serif;
  font-size:20px;
  font-weight:800;
  margin-bottom:12px;
}

.bureau-logo.eq{color:#2196F3}
.bureau-logo.ex{color:#FF5722}
.bureau-logo.tu{color:#4CAF50}

.bureau-desc{
  font-size:13px;
  color:var(--text2);
  line-height:1.65;
  margin-bottom:16px;
}

.bureau-link{
  font-size:12px;
  color:var(--text3);
  font-family:'Inter',monospace;
}

/* ── TECH STACK ── */
.tech-grid{
  display:grid;
  grid-template-columns:repeat(auto-fill, minmax(180px, 1fr));
  gap:14px;
}

.tech-card{
  border:1px solid var(--border);
  border-radius:12px;
  background:var(--card);
  padding:18px 20px;
  opacity:0;
  transform:translateY(16px);
  transition:all .4s;
}

.tech-card.visible{opacity:1;transform:none}

.tech-card:hover{
  border-color:rgba(79,143,255,0.3);
  background:rgba(79,143,255,0.05);
}

.tech-category{
  font-size:10px;
  letter-spacing:.12em;
  text-transform:uppercase;
  color:var(--text3);
  font-weight:600;
  margin-bottom:8px;
}

.tech-name{
  font-family:'Syne',sans-serif;
  font-size:16px;
  font-weight:700;
  color:var(--text);
  margin-bottom:4px;
}

.tech-note{
  font-size:12px;
  color:var(--text3);
  line-height:1.5;
}

/* ── PRICING ── */
.pricing-grid{
  display:grid;
  grid-template-columns:repeat(auto-fill, minmax(240px, 1fr));
  gap:20px;
}

.price-card{
  border:1px solid var(--border);
  border-radius:20px;
  background:var(--card);
  padding:32px 28px;
  position:relative;
  overflow:hidden;
  opacity:0;
  transform:translateY(20px);
  transition:all .5s;
}

.price-card.visible{opacity:1;transform:none}

.price-card.featured{
  border-color:rgba(79,143,255,0.4);
  background:linear-gradient(135deg, rgba(79,143,255,0.08) 0%, rgba(124,58,255,0.06) 100%);
}

.price-card.featured::before{
  content:'ПОПУЛЯРНЫЙ';
  position:absolute;
  top:16px;right:16px;
  font-size:9px;
  font-weight:700;
  letter-spacing:.12em;
  color:var(--accent);
  background:rgba(79,143,255,0.15);
  border:1px solid rgba(79,143,255,0.3);
  border-radius:100px;
  padding:3px 10px;
}

.plan-name{
  font-family:'Syne',sans-serif;
  font-size:13px;
  font-weight:700;
  letter-spacing:.08em;
  text-transform:uppercase;
  color:var(--text2);
  margin-bottom:12px;
}

.plan-price{
  font-family:'Syne',sans-serif;
  font-size:44px;
  font-weight:800;
  color:var(--text);
  line-height:1;
  margin-bottom:4px;
}

.plan-period{
  font-size:13px;
  color:var(--text3);
  margin-bottom:24px;
}

.plan-features{
  list-style:none;
  display:flex;
  flex-direction:column;
  gap:10px;
}

.plan-features li{
  display:flex;
  align-items:flex-start;
  gap:10px;
  font-size:13px;
  color:var(--text2);
  line-height:1.5;
}

.plan-features li::before{
  content:'✓';
  color:var(--accent3);
  font-weight:700;
  flex-shrink:0;
  margin-top:1px;
}

/* ── BUDGET TABLE ── */
.budget-table{
  width:100%;
  border-collapse:collapse;
  margin-top:32px;
}

.budget-table th{
  text-align:left;
  font-size:11px;
  letter-spacing:.1em;
  text-transform:uppercase;
  color:var(--text3);
  font-weight:600;
  padding:12px 16px;
  border-bottom:1px solid var(--border);
}

.budget-table td{
  padding:14px 16px;
  border-bottom:1px solid rgba(255,255,255,0.04);
  font-size:14px;
  color:var(--text2);
}

.budget-table td:first-child{color:var(--text);font-weight:500}

.budget-table td:last-child{
  color:var(--accent);
  font-family:'Syne',sans-serif;
  font-weight:700;
  font-size:15px;
}

.budget-table tr:last-child td{
  color:var(--text);
  font-weight:700;
  font-size:15px;
  border-top:1px solid var(--border);
  border-bottom:none;
}

.budget-table tr:last-child td:last-child{
  color:var(--accent3);
  font-size:18px;
}

/* ── COMPETITORS ── */
.comp-grid{
  display:grid;
  grid-template-columns:repeat(auto-fill, minmax(280px, 1fr));
  gap:20px;
}

.comp-card{
  border:1px solid var(--border);
  border-radius:16px;
  background:var(--card);
  padding:24px;
  opacity:0;
  transform:translateY(16px);
  transition:all .5s;
}

.comp-card.visible{opacity:1;transform:none}

.comp-name{
  font-family:'Syne',sans-serif;
  font-size:18px;
  font-weight:700;
  margin-bottom:6px;
}

.comp-price{
  font-size:13px;
  color:var(--accent);
  font-weight:600;
  margin-bottom:12px;
}

.comp-features{
  display:flex;
  flex-direction:column;
  gap:7px;
}

.comp-feat{
  font-size:13px;
  color:var(--text2);
  display:flex;
  gap:8px;
  align-items:flex-start;
}

.comp-feat::before{content:'›';color:var(--text3);font-weight:700}

/* ── TIMELINE ── */
.timeline-grid{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:16px;
}

.tl-card{
  border:1px solid var(--border);
  border-radius:14px;
  background:var(--card);
  padding:20px 18px;
  position:relative;
  opacity:0;
  transform:translateY(16px);
  transition:all .5s;
}

.tl-card.visible{opacity:1;transform:none}

.tl-months{
  font-size:11px;
  letter-spacing:.1em;
  text-transform:uppercase;
  font-weight:600;
  margin-bottom:10px;
}

.tl-card:nth-child(1) .tl-months{color:var(--accent)}
.tl-card:nth-child(2) .tl-months{color:var(--accent2)}
.tl-card:nth-child(3) .tl-months{color:var(--accent3)}
.tl-card:nth-child(4) .tl-months{color:var(--accent4)}

.tl-title{
  font-family:'Syne',sans-serif;
  font-size:15px;
  font-weight:700;
  margin-bottom:10px;
  line-height:1.3;
}

.tl-items{
  display:flex;
  flex-direction:column;
  gap:6px;
}

.tl-item{
  font-size:12px;
  color:var(--text3);
  display:flex;
  gap:7px;
  line-height:1.4;
}

.tl-item::before{content:'—';color:var(--border2)}

/* ── RISKS ── */
.risks-grid{
  display:grid;
  grid-template-columns:repeat(auto-fill, minmax(300px, 1fr));
  gap:16px;
}

.risk-card{
  border:1px solid var(--border);
  border-radius:12px;
  background:var(--card);
  padding:20px 22px;
  display:flex;
  gap:16px;
  align-items:flex-start;
  opacity:0;
  transform:translateY(12px);
  transition:all .4s;
}

.risk-card.visible{opacity:1;transform:none}

.risk-icon{
  width:40px;height:40px;
  border-radius:10px;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:18px;
  flex-shrink:0;
}

.risk-high .risk-icon{background:rgba(255,107,53,0.12)}
.risk-med .risk-icon{background:rgba(255,209,102,0.1)}
.risk-low .risk-icon{background:rgba(0,212,170,0.1)}

.risk-title{
  font-family:'Syne',sans-serif;
  font-size:14px;
  font-weight:700;
  margin-bottom:5px;
}

.risk-desc{
  font-size:12px;
  color:var(--text3);
  line-height:1.55;
}

.risk-level{
  font-size:10px;
  font-weight:700;
  letter-spacing:.1em;
  text-transform:uppercase;
  padding:2px 8px;
  border-radius:100px;
  margin-left:auto;
  align-self:flex-start;
  flex-shrink:0;
}

.risk-high .risk-level{background:rgba(255,107,53,0.12);color:var(--accent4)}
.risk-med .risk-level{background:rgba(255,209,102,0.1);color:var(--accent5)}
.risk-low .risk-level{background:rgba(0,212,170,0.1);color:var(--accent3)}

/* ── ALTERNATIVES ── */
.alt-grid{
  display:grid;
  grid-template-columns:repeat(auto-fill, minmax(260px, 1fr));
  gap:16px;
}

.alt-card{
  border:1px solid var(--border);
  border-radius:14px;
  background:var(--card);
  padding:22px 24px;
  opacity:0;
  transform:translateY(14px);
  transition:all .4s;
}

.alt-card.visible{opacity:1;transform:none}

.alt-name{
  font-family:'Syne',sans-serif;
  font-size:16px;
  font-weight:700;
  margin-bottom:8px;
  color:var(--accent);
}

.alt-desc{
  font-size:13px;
  color:var(--text2);
  line-height:1.6;
  margin-bottom:12px;
}

.alt-pros{
  display:flex;
  flex-direction:column;
  gap:5px;
}

.alt-pro{
  font-size:12px;
  color:var(--text3);
  display:flex;
  gap:7px;
}

.alt-pro::before{content:'✓';color:var(--accent3);font-weight:700}

/* ── FOOTER ── */
.footer{
  border-top:1px solid var(--border);
  padding:48px 24px;
  text-align:center;
}

.footer-logo{
  font-family:'Syne',sans-serif;
  font-size:24px;
  font-weight:800;
  color:var(--text);
  margin-bottom:8px;
}

.footer-note{
  font-size:13px;
  color:var(--text3);
  max-width:480px;
  margin:0 auto;
  line-height:1.7;
}

/* ── DIVIDER ── */
.divider{
  height:1px;
  background:linear-gradient(90deg, transparent, var(--border), transparent);
  margin:0;
}

/* ── NAV ── */
.nav{
  position:fixed;
  top:0;left:0;right:0;
  z-index:100;
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:16px 32px;
  background:rgba(10,11,15,0.8);
  backdrop-filter:blur(20px);
  border-bottom:1px solid var(--border);
}

.nav-logo{
  font-family:'Syne',sans-serif;
  font-size:18px;
  font-weight:800;
  color:var(--text);
}

.nav-logo span{color:var(--accent)}

.nav-links{
  display:flex;
  gap:28px;
  list-style:none;
}

.nav-links a{
  font-size:13px;
  color:var(--text3);
  text-decoration:none;
  font-weight:500;
  transition:color .2s;
  letter-spacing:.01em;
}

.nav-links a:hover{color:var(--text)}

/* ── ANIMATIONS ── */
@keyframes fadeUp{
  from{opacity:0;transform:translateY(20px)}
  to{opacity:1;transform:none}
}

/* ── WIDE CARD ── */
.wide-card{
  border:1px solid var(--border);
  border-radius:16px;
  background:var(--card);
  padding:32px;
  margin-bottom:20px;
  opacity:0;
  transform:translateY(16px);
  transition:all .5s;
}

.wide-card.visible{opacity:1;transform:none}

.wide-card-title{
  font-family:'Syne',sans-serif;
  font-size:18px;
  font-weight:700;
  margin-bottom:14px;
  color:var(--text);
}

.info-grid{
  display:grid;
  grid-template-columns:repeat(auto-fill, minmax(300px, 1fr));
  gap:20px;
}

.info-item{
  padding:20px 22px;
  border:1px solid var(--border);
  border-radius:12px;
  background:rgba(255,255,255,0.02);
}

.info-item-title{
  font-weight:600;
  font-size:14px;
  color:var(--text);
  margin-bottom:8px;
}

.info-item-text{
  font-size:13px;
  color:var(--text2);
  line-height:1.65;
}

/* ── RESPONSIVE ── */
@media(max-width:900px){
  .bureaus-grid{grid-template-columns:1fr}
  .timeline-grid{grid-template-columns:repeat(2,1fr)}
  .nav-links{display:none}
}

@media(max-width:600px){
  .phases::before{display:none}
  .phase{grid-template-columns:1fr}
  .phase-num{display:none}
  .timeline-grid{grid-template-columns:1fr}
  .hero-stats{gap:24px}
}
</style>
</head>
<body>

<!-- NAV -->
<nav class="nav">
  <div class="nav-logo">Credit<span>Core</span></div>
  <ul class="nav-links">
    <li><a href="#plan">Этапы</a></li>
    <li><a href="#bureaus">Бюро</a></li>
    <li><a href="#tech">Технологии</a></li>
    <li><a href="#pricing">Подписки</a></li>
    <li><a href="#budget">Бюджет</a></li>
    <li><a href="#timeline">Timeline</a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-bg"></div>
  <div class="hero-grid"></div>
  <div class="badge"><span class="badge-dot"></span>Дорожная карта проекта 2025–2026</div>
  <h1>Credit<span>Core</span></h1>
  <p class="hero-sub">Платформа мониторинга кредитных историй</p>
  <p class="hero-desc">Полный план создания B2C-платформы кредитного мониторинга на базе данных Equifax, Experian и TransUnion — от юридической регистрации до коммерческого запуска</p>
  <div class="hero-stats">
    <div class="stat">
      <span class="stat-val">$30</span>
      <span class="stat-label">в месяц — цена подписки</span>
    </div>
    <div class="stat">
      <span class="stat-val">3</span>
      <span class="stat-label">кредитных бюро</span>
    </div>
    <div class="stat">
      <span class="stat-val">12 мес</span>
      <span class="stat-label">до запуска</span>
    </div>
    <div class="stat">
      <span class="stat-val">$250K</span>
      <span class="stat-label">стартовый бюджет</span>
    </div>
  </div>
  <div class="scroll-hint">
    <div class="scroll-line"></div>
    SCROLL
  </div>
</section>

<div class="divider"></div>

<!-- PLAN SECTION -->
<section class="section" id="plan">
  <div class="section-label">Стратегия реализации</div>
  <h2 class="section-title">5 фаз от идеи до запуска</h2>
  <p class="section-desc">Пошаговый план, учитывающий юридические, технические и коммерческие аспекты создания платформы уровня IdentityIQ и SmartCredit</p>

  <div class="phases">

    <!-- PHASE 1 -->
    <div class="phase">
      <div class="phase-num">
        <div class="num-circle">01</div>
      </div>
      <div class="phase-body">
        <div class="phase-header">
          <div>
            <div class="phase-title">Юридическая и партнёрская основа</div>
          </div>
          <span class="phase-tag">Месяцы 1–3</span>
        </div>
        <p class="phase-desc">Прежде чем писать код — необходимо создать юридический фундамент. Доступ к кредитным данным потребителей США строго регулируется FCRA, GLBA и CCPA. Это самый сложный и важный этап — без него невозможна никакая техническая работа.</p>
        <div class="tasks">
          <div class="task"><div class="task-icon">⚖</div><div><strong>Регистрация</strong> компании в США — LLC или C-Corp. EIN (налоговый номер), юридический адрес</div></div>
          <div class="task"><div class="task-icon">📄</div><div><strong>FCRA-комплаенс</strong> — получение "Permissible Purpose" для запроса кредитных отчётов</div></div>
          <div class="task"><div class="task-icon">🤝</div><div><strong>Переговоры с бюро</strong> — заявка как Reseller/Distributor в Equifax, Experian, TransUnion</div></div>
          <div class="task"><div class="task-icon">🔐</div><div><strong>Data Use Agreement</strong> — соглашение о хранении и использовании данных потребителей</div></div>
          <div class="task"><div class="task-icon">🛡</div><div><strong>Security Audit</strong> — бюро проверяют инфраструктуру безопасности партнёра</div></div>
          <div class="task"><div class="task-icon">👔</div><div><strong>CISO назначение</strong> — директор по информационной безопасности (требование GLBA)</div></div>
          <div class="task"><div class="task-icon">📋</div><div><strong>Privacy Policy, ToS</strong> — документы, адаптированные под GLBA, FCRA, CCPA</div></div>
          <div class="task"><div class="task-icon">💼</div><div><strong>Страхование</strong> — профессиональная ответственность + защита от киберрисков (до $1 млн)</div></div>
          <div class="task"><div class="task-icon">🔎</div><div><strong>Выбор API-агрегатора</strong> — анализ Array, CRS Credit API, MeridianLink, Bloom Credit</div></div>
          <div class="task"><div class="task-icon">🖥</div><div><strong>VDI-инфраструктура</strong> — виртуальные рабочие столы для защиты данных при офшорной разработке</div></div>
        </div>
        <div style="margin-top:20px;padding:16px 20px;background:rgba(255,107,53,0.06);border:1px solid rgba(255,107,53,0.2);border-radius:10px;">
          <p style="font-size:13px;color:var(--accent4);font-weight:600;margin-bottom:4px">⚠ Критический момент</p>
          <p style="font-size:13px;color:var(--text2)">Прямая аккредитация в каждом бюро занимает от 3 до 12+ месяцев. Оптимальный путь на старте — <strong style="color:var(--text)">API-агрегатор</strong> (Array или CRS), который уже имеет прямые контракты с бюро и позволяет запустить за 4–6 недель.</p>
        </div>
      </div>
    </div>

    <!-- PHASE 2 -->
    <div class="phase">
      <div class="phase-num">
        <div class="num-circle">02</div>
      </div>
      <div class="phase-body">
        <div class="phase-header">
          <div>
            <div class="phase-title">Проектирование и базовая разработка</div>
          </div>
          <span class="phase-tag">Месяцы 3–6</span>
        </div>
        <p class="phase-desc">Построение микросервисной архитектуры, интеграция с API бюро в тестовой среде, разработка ядра платформы. Микросервисный подход обеспечивает независимое масштабирование и изолирует потенциальные сбои.</p>
        <div class="tasks">
          <div class="task"><div class="task-icon">⚙</div><div><strong>Микросервисная архитектура</strong> — отдельные адаптеры для каждого бюро (Equifax, Experian, TU)</div></div>
          <div class="task"><div class="task-icon">🗄</div><div><strong>PostgreSQL + Redis</strong> — БД с AES-256 шифрованием + кэш для снижения частоты запросов к API</div></div>
          <div class="task"><div class="task-icon">☁</div><div><strong>AWS / GCP</strong> — облачная инфраструктура с Geo-шардингом данных</div></div>
          <div class="task"><div class="task-icon">🔗</div><div><strong>API интеграция Sandbox</strong> — тестирование soft pull запросов во всех трёх бюро</div></div>
          <div class="task"><div class="task-icon">🧹</div><div><strong>ETL-процессор</strong> — нормализация XML/JSON данных из разных форматов бюро в единый стандарт</div></div>
          <div class="task"><div class="task-icon">🔀</div><div><strong>Tri-Merge алгоритм</strong> — дедупликация кредитных линий (fuzzy matching по SSN, счетам, датам)</div></div>
          <div class="task"><div class="task-icon">⚛</div><div><strong>React + TypeScript</strong> — фронтенд дашборда с отображением данных 3 бюро</div></div>
          <div class="task"><div class="task-icon">📊</div><div><strong>VantageScore + FICO</strong> — интеграция обеих скоринговых моделей, объяснение разницы</div></div>
          <div class="task"><div class="task-icon">🔐</div><div><strong>2FA + KYC верификация</strong> — аутентификация личности при регистрации</div></div>
          <div class="task"><div class="task-icon">🌐</div><div><strong>API Gateway</strong> — Kong или AWS API Gateway с токенизацией для офшорной команды</div></div>
        </div>
      </div>
    </div>

    <!-- PHASE 3 -->
    <div class="phase">
      <div class="phase-num">
        <div class="num-circle">03</div>
      </div>
      <div class="phase-body">
        <div class="phase-header">
          <div>
            <div class="phase-title">Платёжная система и подписки</div>
          </div>
          <span class="phase-tag">Месяцы 5–8</span>
        </div>
        <p class="phase-desc">Внедрение биллинговой системы для управления рекуррентными платежами. Архитектурный выбор: Stripe как платёжный процессор + Chargebee как слой управления подписками — отраслевой золотой стандарт.</p>
        <div class="tasks">
          <div class="task"><div class="task-icon">💳</div><div><strong>Stripe Payments</strong> — процессинг карт, токенизация, PCI DSS compliant</div></div>
          <div class="task"><div class="task-icon">📦</div><div><strong>Chargebee</strong> — управление подписками, пропорциональные начисления, dunning логика</div></div>
          <div class="task"><div class="task-icon">🎁</div><div><strong>Free Trial</strong> — 7–30 дней пробного периода для привлечения пользователей</div></div>
          <div class="task"><div class="task-icon">⬆</div><div><strong>Upgrade / Downgrade</strong> — плавный переход между тарифами с пересчётом</div></div>
          <div class="task"><div class="task-icon">🔔</div><div><strong>Dunning автоматизация</strong> — умные повторные попытки при неуспешном платеже</div></div>
          <div class="task"><div class="task-icon">📑</div><div><strong>Revenue Recognition</strong> — ASC 606 / IFRS 15 через Chargebee (автоматически)</div></div>
          <div class="task"><div class="task-icon">🌍</div><div><strong>Tax Automation</strong> — расчёт налогов по геолокации пользователя (TaxJar интеграция)</div></div>
          <div class="task"><div class="task-icon">📈</div><div><strong>Аналитика подписок</strong> — LTV, Churn, MRR, CAC дашборд для бизнеса</div></div>
        </div>
      </div>
    </div>

    <!-- PHASE 4 -->
    <div class="phase">
      <div class="phase-num">
        <div class="num-circle">04</div>
      </div>
      <div class="phase-body">
        <div class="phase-header">
          <div>
            <div class="phase-title">Премиум-функции и конкурентные преимущества</div>
          </div>
          <span class="phase-tag">Месяцы 6–9</span>
        </div>
        <p class="phase-desc">Именно эти функции отличают ведущие платформы от простых агрегаторов данных. Успех определяется не только визуализацией — но и инструментами активного управления кредитным профилем.</p>
        <div class="tasks">
          <div class="task"><div class="task-icon">🌑</div><div><strong>Dark Web Monitoring</strong> — сканирование даркнета на предмет утечки SSN и паролей</div></div>
          <div class="task"><div class="task-icon">🏠</div><div><strong>Смена адреса алерт</strong> — мониторинг мошеннических изменений почтового адреса</div></div>
          <div class="task"><div class="task-icon">⚡</div><div><strong>Real-time Alerts</strong> — мгновенные уведомления о новых запросах и изменениях в отчётах</div></div>
          <div class="task"><div class="task-icon">⚔</div><div><strong>Dispute Hub (e-OSCAR)</strong> — автоматическая подача споров через Metro 2 формат</div></div>
          <div class="task"><div class="task-icon">🧮</div><div><strong>Score Simulator</strong> — что будет со скором при погашении карты / открытии счёта</div></div>
          <div class="task"><div class="task-icon">📅</div><div><strong>Best Pay-Down Date</strong> — оптимальная дата досрочного погашения для максимизации балла</div></div>
          <div class="task"><div class="task-icon">🏘</div><div><strong>Rent Reporting</strong> — добавление арендных платежей в кредитную историю</div></div>
          <div class="task"><div class="task-icon">🛡</div><div><strong>ID Theft Insurance</strong> — страховка от кражи личности на $1 млн (партнёрство)</div></div>
          <div class="task"><div class="task-icon">📱</div><div><strong>Mobile App</strong> — iOS + Android с push-уведомлениями</div></div>
          <div class="task"><div class="task-icon">🤖</div><div><strong>AI Insights</strong> — персонализированные рекомендации по улучшению кредитного профиля</div></div>
        </div>
        <div style="margin-top:20px;padding:16px 20px;background:rgba(0,212,170,0.05);border:1px solid rgba(0,212,170,0.2);border-radius:10px;">
          <p style="font-size:13px;color:var(--accent3);font-weight:600;margin-bottom:4px">💡 Ключевой дифференциатор</p>
          <p style="font-size:13px;color:var(--text2)">Dispute Hub через стандарт <strong style="color:var(--text)">e-OSCAR / Metro 2</strong> — возможность автоматически подавать споры напрямую в кредитные бюро. Это то, за что пользователи готовы платить $30/мес.</p>
        </div>
      </div>
    </div>

    <!-- PHASE 5 -->
    <div class="phase">
      <div class="phase-num">
        <div class="num-circle">05</div>
      </div>
      <div class="phase-body">
        <div class="phase-header">
          <div>
            <div class="phase-title">Аудит безопасности, тестирование и запуск</div>
          </div>
          <span class="phase-tag">Месяцы 9–12</span>
        </div>
        <p class="phase-desc">Заключительный этап перед публичным релизом. Бюро проводят строгую проверку соответствия перед выдачей production-доступа. Нельзя пропускать ни один шаг — нарушение ведёт к отключению и штрафам.</p>
        <div class="tasks">
          <div class="task"><div class="task-icon">🔒</div><div><strong>SOC 2 Type II</strong> — независимый аудит безопасности (требование кредитных бюро)</div></div>
          <div class="task"><div class="task-icon">🧪</div><div><strong>Penetration Testing</strong> — пентест системы, проверка шифрования и обработки PII</div></div>
          <div class="task"><div class="task-icon">⚙</div><div><strong>Load Testing</strong> — нагрузочное тестирование микросервисов (имитация 10 000+ пользователей)</div></div>
          <div class="task"><div class="task-icon">✅</div><div><strong>FCRA Compliance Review</strong> — юридический аудит процесса сбора согласий</div></div>
          <div class="task"><div class="task-icon">🧩</div><div><strong>QA End-to-End</strong> — тест credit freezes, fraud alerts, невалидных SSN</div></div>
          <div class="task"><div class="task-icon">🚀</div><div><strong>Beta-запуск</strong> — ограниченная аудитория, сбор обратной связи</div></div>
          <div class="task"><div class="task-icon">📣</div><div><strong>SEO + Paid Ads</strong> — "check all 3 credit bureaus", "credit monitoring service"</div></div>
          <div class="task"><div class="task-icon">🤝</div><div><strong>Партнёрства</strong> — ипотечные брокеры, автодилеры, лизинговые компании</div></div>
          <div class="task"><div class="task-icon">💸</div><div><strong>Affiliate Program</strong> — реферальная программа для снижения CAC</div></div>
          <div class="task"><div class="task-icon">📞</div><div><strong>Поддержка</strong> — FAQ, чат-бот, колл-центр (требование бюро)</div></div>
        </div>
      </div>
    </div>

  </div>
</section>

<div class="divider"></div>

<!-- BUREAUS SECTION -->
<section class="section" id="bureaus">
  <div class="section-label">Партнёры по данным</div>
  <h2 class="section-title">Три кредитных бюро</h2>
  <p class="section-desc">Equifax, Experian и TransUnion контролируют инфраструктуру кредитной системы США с совокупным годовым доходом $13.3 млрд. Доступ к их данным — ключевой актив платформы.</p>

  <div class="bureaus-grid">
    <div class="bureau-card">
      <div class="bureau-logo eq">Equifax</div>
      <div class="bureau-desc">Наиболее открытый для партнёрств — предлагает <strong>Consumer Engagement Suite (CES API)</strong> с multi-bureau отчётами. Поддерживает B2B2C-модель, позволяя получать данные всех трёх бюро сразу через один endpoint. Лучший выбор для MVP.</div>
      <div class="bureau-link">developer.equifax.com</div>
    </div>
    <div class="bureau-card">
      <div class="bureau-logo ex">Experian</div>
      <div class="bureau-desc">Предлагает <strong>Experian Connect API</strong> и корпоративный API Hub. Глобальное присутствие. Важно учитывать GDPR при работе с европейскими пользователями. Experian IdentityWorks — прямой конкурент платформы.</div>
      <div class="bureau-link">experian.com/partner-solutions</div>
    </div>
    <div class="bureau-card">
      <div class="bureau-logo tu">TransUnion</div>
      <div class="bureau-desc">Нет публичного открытого API — работает через <strong>партнёрскую программу</strong> (Reseller/Distributor). Интеграция через посредников (iSoftpull API) или прямые XML/batch-каналы. Требует строжайшей аккредитации.</div>
      <div class="bureau-link">transunion.com/business</div>
    </div>
  </div>

  <div style="margin-top:32px">
    <div class="section-label">Альтернативный путь — API-агрегаторы</div>
    <h3 style="font-family:'Syne',sans-serif;font-size:24px;font-weight:700;margin-bottom:12px">Быстрый старт через посредников</h3>
    <p class="section-desc" style="margin-bottom:28px">Вместо прямой аккредитации в каждом бюро (которая занимает 6–12 месяцев) — использовать специализированные B2B2C агрегаторы, уже имеющие контракты и SOC 2 сертификацию.</p>
    <div class="alt-grid">
      <div class="alt-card">
        <div class="alt-name">Array</div>
        <div class="alt-desc">Лидер встраиваемых финансовых сервисов. Готовые веб-компоненты + API. Запуск кредитного мониторинга за 4–6 недель.</div>
        <div class="alt-pros">
          <div class="alt-pro">My Credit Manager (визуализация)</div>
          <div class="alt-pro">Offers Engine (монетизация лидов)</div>
          <div class="alt-pro">Identity Protect (защита личности)</div>
          <div class="alt-pro">PMPM или Per Transaction модель</div>
        </div>
      </div>
      <div class="alt-card">
        <div class="alt-name">CRS Credit API</div>
        <div class="alt-desc">Единый API с SOC 2 Type II. Синхронный доступ ко всем трём бюро. Soft & Hard pull. Готовые SDK для Python, Ruby, JavaScript.</div>
        <div class="alt-pros">
          <div class="alt-pro">Tri-merge отчёты в одном запросе</div>
          <div class="alt-pro">OFAC / санкционный скрининг</div>
          <div class="alt-pro">Верификация личности встроена</div>
        </div>
      </div>
      <div class="alt-card">
        <div class="alt-name">MeridianLink</div>
        <div class="alt-desc">Запатентованная технология слияния — дедупликация данных 3 бюро и консолидированный отчёт за ~11 секунд. Форматы MISMO 2.3.1 и 3.4.</div>
        <div class="alt-pros">
          <div class="alt-pro">Автоматическая дедупликация tradelines</div>
          <div class="alt-pro">128-bit SSL шифрование</div>
          <div class="alt-pro">Сотни реселлеров в сети</div>
        </div>
      </div>
      <div class="alt-card">
        <div class="alt-name">Bloom Credit</div>
        <div class="alt-desc">Уникальный продукт Bloom+ — учёт альтернативных данных (коммунальные платежи, банковские транзакции) для повышения скора пользователей.</div>
        <div class="alt-pros">
          <div class="alt-pro">API для получения И передачи данных</div>
          <div class="alt-pro">Alternative Consumer Permissioned Data</div>
          <div class="alt-pro">Мощный дифференциатор на рынке</div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- COMPETITORS -->
<section class="section">
  <div class="section-label">Анализ конкурентов</div>
  <h2 class="section-title">Лидеры рынка</h2>
  <p class="section-desc">Компании, которые нужно изучить детально — и взять лучшее от каждого</p>
  <div class="comp-grid">
    <div class="comp-card">
      <div class="comp-name">IdentityIQ</div>
      <div class="comp-price">$7.44 – $31.49 / мес</div>
      <div class="comp-features">
        <div class="comp-feat">3 бюро + прямые отношения (Direct Bureau Power)</div>
        <div class="comp-feat">Мониторинг даркнета и SSN</div>
        <div class="comp-feat">Страховка от кражи личности $1 млн на семью</div>
        <div class="comp-feat">Мониторинг смены адреса</div>
        <div class="comp-feat">Гибкая линейка тарифов (5 планов)</div>
      </div>
    </div>
    <div class="comp-card">
      <div class="comp-name">SmartCredit</div>
      <div class="comp-price">~$19.95 – $29.95 / мес</div>
      <div class="comp-features">
        <div class="comp-feat">Запатентованные Action Buttons (USPTO 7,818,228)</div>
        <div class="comp-feat">ScoreTracker — Auto/Insurance/Hiring скоры</div>
        <div class="comp-feat">ScoreBuilder — 120-дневный план улучшения</div>
        <div class="comp-feat">ScoreBoost — оптимальная дата погашения</div>
        <div class="comp-feat">Прямая связь с кредиторами без телефона</div>
      </div>
    </div>
    <div class="comp-card">
      <div class="comp-name">myFICO</div>
      <div class="comp-price">$19.95 – $39.95 / мес</div>
      <div class="comp-features">
        <div class="comp-feat">Реальные FICO скоры (те, что видит банк)</div>
        <div class="comp-feat">FICO Auto Score, Bankcard Score, Mortgage</div>
        <div class="comp-feat">3 бюро side-by-side сравнение</div>
        <div class="comp-feat">История изменений скора</div>
        <div class="comp-feat">Лучший для покупателей ипотеки/авто</div>
      </div>
    </div>
    <div class="comp-card">
      <div class="comp-name">Credit Karma</div>
      <div class="comp-price">Бесплатно</div>
      <div class="comp-features">
        <div class="comp-feat">Только TransUnion + Equifax (2 из 3)</div>
        <div class="comp-feat">VantageScore (не FICO)</div>
        <div class="comp-feat">Монетизация — агрессивная лидогенерация</div>
        <div class="comp-feat">Купленa Intuit за $7.1 млрд</div>
        <div class="comp-feat">Слабая защита личности — возможность дифференциации</div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- TECH SECTION -->
<section class="section" id="tech">
  <div class="section-label">Технический стек</div>
  <h2 class="section-title">Архитектура платформы</h2>
  <p class="section-desc">Микросервисная архитектура с событийно-ориентированной обработкой данных, обеспечивающая независимое масштабирование и максимальную безопасность</p>

  <div class="tech-grid">
    <div class="tech-card"><div class="tech-category">Бэкенд</div><div class="tech-name">Node.js / NestJS</div><div class="tech-note">Микросервисы, REST API, высокая производительность</div></div>
    <div class="tech-card"><div class="tech-category">Альтернатива</div><div class="tech-name">Python FastAPI</div><div class="tech-note">Для ML-модулей и аналитических сервисов</div></div>
    <div class="tech-card"><div class="tech-category">База данных</div><div class="tech-name">PostgreSQL</div><div class="tech-note">Профили пользователей, история запросов, шифрование AES-256</div></div>
    <div class="tech-card"><div class="tech-category">Кэширование</div><div class="tech-name">Redis</div><div class="tech-note">Кэш кредитных отчётов — снижает частоту и стоимость API-запросов</div></div>
    <div class="tech-card"><div class="tech-category">Облако</div><div class="tech-name">AWS / GCP</div><div class="tech-note">Geo-шардинг, данные не покидают юрисдикцию США</div></div>
    <div class="tech-card"><div class="tech-category">API-шлюз</div><div class="tech-name">Kong Gateway</div><div class="tech-note">Rate limiting, токенизация для офшорных разработчиков</div></div>
    <div class="tech-card"><div class="tech-category">Фронтенд</div><div class="tech-name">React + TypeScript</div><div class="tech-note">Дашборд с данными 3 бюро, история скора, алерты</div></div>
    <div class="tech-card"><div class="tech-category">Мобильные</div><div class="tech-name">React Native</div><div class="tech-note">iOS + Android с push-уведомлениями о изменениях</div></div>
    <div class="tech-card"><div class="tech-category">Платежи</div><div class="tech-name">Stripe + Chargebee</div><div class="tech-note">Процессинг + управление подписками (золотой стандарт SaaS)</div></div>
    <div class="tech-card"><div class="tech-category">Безопасность</div><div class="tech-name">VDI Infrastructure</div><div class="tech-note">Виртуальные рабочие столы — данные не скачиваются на устройства разработчиков</div></div>
    <div class="tech-card"><div class="tech-category">Шифрование</div><div class="tech-name">AES-256 + TLS 1.3</div><div class="tech-note">Данные в покое и при передаче. Требование всех 3 бюро</div></div>
    <div class="tech-card"><div class="tech-category">Сертификация</div><div class="tech-name">SOC 2 Type II</div><div class="tech-note">Обязательный аудит безопасности (AICPA). Без него — нет production API</div></div>
    <div class="tech-card"><div class="tech-category">Споры</div><div class="tech-name">e-OSCAR / Metro 2</div><div class="tech-note">Автоматическая отправка ACDV пакетов в кредитные бюро</div></div>
    <div class="tech-card"><div class="tech-category">Очереди</div><div class="tech-name">RabbitMQ / SQS</div><div class="tech-note">Асинхронная обработка фоновых задач обновления отчётов</div></div>
    <div class="tech-card"><div class="tech-category">Мониторинг</div><div class="tech-name">Datadog / Sentry</div><div class="tech-note">Отслеживание ошибок, производительность API, алерты</div></div>
  </div>

  <div style="margin-top:40px">
    <div class="wide-card" style="opacity:1;transform:none">
      <div class="wide-card-title">🔀 Критический алгоритм: Tri-Merge дедупликация</div>
      <p style="font-size:14px;color:var(--text2);line-height:1.75;margin-bottom:16px">Одна кредитная карта может быть записана как "Bank of America" в Experian и "BofA" в TransUnion с разными датами обновления. Без дедупликации — баланс пользователя удвоится и исказит DTI ratio.</p>
      <div class="info-grid">
        <div class="info-item">
          <div class="info-item-title">Fuzzy Matching алгоритм</div>
          <div class="info-item-text">Кросс-проверка по SSN, хэшам номеров счетов, балансам, лимитам, датам открытия и паттернам платежей</div>
        </div>
        <div class="info-item">
          <div class="info-item-title">Joint Accounts</div>
          <div class="info-item-text">Параметры DBR_JOINT_INC_DEBT — решение о включении совместных обязательств супругов в профиль основного заявителя</div>
        </div>
        <div class="info-item">
          <div class="info-item-title">Сохранение уникальных меток</div>
          <div class="info-item-text">После слияния дубликатов — все уникальные просрочки, зафиксированные только одним бюро, сохраняются в объединённом отчёте</div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- PRICING SECTION -->
<section class="section" id="pricing">
  <div class="section-label">Монетизация</div>
  <h2 class="section-title">Модель подписки</h2>
  <p class="section-desc">Четыре уровня с ориентацией на Premium план в $29.99 — именно он обеспечивает основную выручку при разумной марже</p>
  <div class="pricing-grid">
    <div class="price-card">
      <div class="plan-name">Free</div>
      <div class="plan-price">$0</div>
      <div class="plan-period">навсегда</div>
      <ul class="plan-features">
        <li>1 бюро на выбор</li>
        <li>Обновление раз в 3 месяца</li>
        <li>Базовый кредитный скор</li>
        <li>Ограниченные алерты</li>
      </ul>
    </div>
    <div class="price-card">
      <div class="plan-name">Basic</div>
      <div class="plan-price">$9<span style="font-size:22px">.99</span></div>
      <div class="plan-period">в месяц</div>
      <ul class="plan-features">
        <li>2 бюро (TU + Equifax)</li>
        <li>Обновление раз в месяц</li>
        <li>Email алерты</li>
        <li>Score history (6 мес)</li>
        <li>Базовые инсайты</li>
      </ul>
    </div>
    <div class="price-card featured">
      <div class="plan-name">Premium</div>
      <div class="plan-price">$29<span style="font-size:22px">.99</span></div>
      <div class="plan-period">в месяц</div>
      <ul class="plan-features">
        <li>Все 3 бюро (TU + EQ + EX)</li>
        <li>Еженедельное обновление</li>
        <li>FICO Score (реальный)</li>
        <li>Dark Web Monitoring</li>
        <li>Score Simulator</li>
        <li>Dispute Hub (e-OSCAR)</li>
        <li>ID Theft Insurance $1M</li>
        <li>Mobile App</li>
        <li>AI Credit Advisor</li>
      </ul>
    </div>
    <div class="price-card">
      <div class="plan-name">Family</div>
      <div class="plan-price">$49<span style="font-size:22px">.99</span></div>
      <div class="plan-period">в месяц</div>
      <ul class="plan-features">
        <li>Premium для 2–4 человек</li>
        <li>Мониторинг детей</li>
        <li>Общий семейный дашборд</li>
        <li>Страховка на всю семью</li>
        <li>Приоритетная поддержка</li>
      </ul>
    </div>
  </div>

  <div style="margin-top:40px">
    <div class="section-label">Дополнительные источники дохода</div>
    <div class="info-grid" style="margin-top:16px">
      <div class="info-item">
        <div class="info-item-title">💰 Lead Generation</div>
        <div class="info-item-text">Продажа квалифицированных лидов банкам, ипотечным брокерам и кредитным картам. Самый прибыльный канал в нише — до $50–200 за лид.</div>
      </div>
      <div class="info-item">
        <div class="info-item-title">🏢 White-Label B2B</div>
        <div class="info-item-text">Продажа платформы под брендом другой компании. Ипотечные агентства, банки, HR-компании — все заинтересованы в кредитном мониторинге.</div>
      </div>
      <div class="info-item">
        <div class="info-item-title">🔧 Credit Repair Services</div>
        <div class="info-item-text">Платная услуга по улучшению кредитной истории через Dispute Hub. Высокомаржинальный сервис с хорошим LTV.</div>
      </div>
      <div class="info-item">
        <div class="info-item-title">📊 Affiliate Marketing</div>
        <div class="info-item-text">Партнёрские комиссии от рекомендаций кредитных карт, автокредитов, ипотек на основе кредитного профиля пользователя.</div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- LEGAL SECTION -->
<section class="section">
  <div class="section-label">Регуляторный ландшафт</div>
  <h2 class="section-title">Юридические требования</h2>
  <p class="section-desc">Работа с кредитными данными граждан США — один из самых строгих регуляторных ландшафтов в мире. Несоответствие ведёт к отключению от API и многомиллионным штрафам.</p>
  <div class="info-grid">
    <div class="info-item" style="border-color:rgba(79,143,255,0.2)">
      <div class="info-item-title" style="color:var(--accent)">📘 FCRA — Fair Credit Reporting Act</div>
      <div class="info-item-text">Фундаментальный закон. Требует письменного согласия пользователя ("Permissible Purpose") на каждый запрос отчёта. Ежегодный бесплатный отчёт для пользователя. Процедура оспаривания ошибок (30 дней на расследование).</div>
    </div>
    <div class="info-item" style="border-color:rgba(255,107,53,0.2)">
      <div class="info-item-title" style="color:var(--accent4)">📙 GLBA — Gramm-Leach-Bliley Act</div>
      <div class="info-item-text">Платформа классифицируется как финансовое учреждение. Требует назначения CISO, программы информационной безопасности, политик контроля доступа, шифрования данных и обучения сотрудников.</div>
    </div>
    <div class="info-item" style="border-color:rgba(0,212,170,0.2)">
      <div class="info-item-title" style="color:var(--accent3)">📗 CCPA / CPRA — California Privacy</div>
      <div class="info-item-text">Право пользователей на удаление данных, отказ от продажи информации третьим лицам, прозрачность использования. Применяется ко всем компаниям, обслуживающим жителей Калифорнии.</div>
    </div>
    <div class="info-item" style="border-color:rgba(255,209,102,0.2)">
      <div class="info-item-title" style="color:var(--accent5)">📒 PCI DSS — Payment Security</div>
      <div class="info-item-text">При работе с платёжными данными — обязательная сертификация. Запрет хранения CVV, токенизация номеров карт. Stripe берёт на себя большую часть PCI DSS-требований.</div>
    </div>
    <div class="info-item">
      <div class="info-item-title">🔐 Data Residency — локализация данных</div>
      <div class="info-item-text">Данные граждан США (SSN, кредитные отчёты) не должны физически передаваться за пределы американской юрисдикции. Офшорные разработчики — только через VDI без прямого доступа к данным.</div>
    </div>
    <div class="info-item">
      <div class="info-item-title">🏢 SOC 2 Type II — Security Audit</div>
      <div class="info-item-text">Независимый аудит по 5 критериям: безопасность, доступность, целостность, конфиденциальность, приватность. Обязательное условие для получения production-доступа от всех трёх бюро.</div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- BUDGET SECTION -->
<section class="section" id="budget">
  <div class="section-label">Финансовое планирование</div>
  <h2 class="section-title">Бюджет запуска</h2>
  <p class="section-desc">Ориентировочные затраты на первый год. Реальные цифры зависят от выбора прямой интеграции vs. агрегатора и географии команды разработки.</p>
  <div style="border:1px solid var(--border);border-radius:16px;overflow:hidden;background:var(--card)">
    <table class="budget-table">
      <thead>
        <tr>
          <th>Статья расходов</th>
          <th>Описание</th>
          <th>Стоимость</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Юридические услуги</td>
          <td style="color:var(--text3);font-size:13px">Регистрация, FCRA/GLBA комплаенс, DUA соглашения, ToS/Privacy Policy</td>
          <td>$10K – $30K</td>
        </tr>
        <tr>
          <td>API доступ к бюро</td>
          <td style="color:var(--text3);font-size:13px">Подписки агрегатора (Array/CRS) или прямые контракты. Per-user fee за активных пользователей</td>
          <td>$15K – $50K</td>
        </tr>
        <tr>
          <td>Разработка платформы</td>
          <td style="color:var(--text3);font-size:13px">Бэкенд, фронтенд, мобильное приложение, интеграции, VDI-инфраструктура</td>
          <td>$50K – $150K</td>
        </tr>
        <tr>
          <td>Облачная инфраструктура</td>
          <td style="color:var(--text3);font-size:13px">AWS/GCP, базы данных, CDN, мониторинг, резервное копирование</td>
          <td>$2K – $5K/мес</td>
        </tr>
        <tr>
          <td>SOC 2 Type II аудит</td>
          <td style="color:var(--text3);font-size:13px">Независимый аудит безопасности. Обязателен для production-доступа к бюро</td>
          <td>$20K – $50K</td>
        </tr>
        <tr>
          <td>Маркетинг и запуск</td>
          <td style="color:var(--text3);font-size:13px">SEO, PPC, социальные сети, партнёрские программы, PR</td>
          <td>$10K – $30K</td>
        </tr>
        <tr>
          <td>Страхование</td>
          <td style="color:var(--text3);font-size:13px">Профессиональная ответственность + киберриски + ID Theft покрытие</td>
          <td>$5K – $15K/год</td>
        </tr>
        <tr>
          <td colspan="2" style="font-family:'Syne',sans-serif;font-weight:700;font-size:16px;color:var(--text)">ИТОГО на старт (первый год)</td>
          <td>$120K – $280K</td>
        </tr>
      </tbody>
    </table>
  </div>
  <div style="margin-top:20px;padding:20px 24px;background:rgba(79,143,255,0.06);border:1px solid rgba(79,143,255,0.2);border-radius:12px">
    <p style="font-size:13px;color:var(--text2)">💡 <strong style="color:var(--text)">Экономия через агрегатор:</strong> использование Array или CRS вместо прямой интеграции экономит $30–80K на разработке адаптеров и ускоряет Time-to-Market с 12 до 6 месяцев. На начальном этапе — оптимальный выбор.</p>
  </div>
</section>

<div class="divider"></div>

<!-- TIMELINE -->
<section class="section" id="timeline">
  <div class="section-label">Дорожная карта</div>
  <h2 class="section-title">12-месячный Timeline</h2>
  <p class="section-desc">Последовательный план от регистрации компании до коммерческого запуска</p>
  <div class="timeline-grid">
    <div class="tl-card">
      <div class="tl-months">Месяцы 1–3</div>
      <div class="tl-title">Юридика и партнёрства</div>
      <div class="tl-items">
        <div class="tl-item">Регистрация LLC/C-Corp в США</div>
        <div class="tl-item">Найм юриста по FCRA/GLBA</div>
        <div class="tl-item">Назначение CISO</div>
        <div class="tl-item">Переговоры с агрегаторами (Array, CRS)</div>
        <div class="tl-item">Начало переговоров с бюро (прямой путь)</div>
        <div class="tl-item">Разработка ToS, Privacy Policy</div>
        <div class="tl-item">Настройка VDI инфраструктуры</div>
      </div>
    </div>
    <div class="tl-card">
      <div class="tl-months">Месяцы 4–6</div>
      <div class="tl-title">Базовая разработка</div>
      <div class="tl-items">
        <div class="tl-item">Подписание контрактов с агрегатором</div>
        <div class="tl-item">Настройка Sandbox API доступа</div>
        <div class="tl-item">Разработка микросервисной архитектуры</div>
        <div class="tl-item">PostgreSQL + Redis инфраструктура</div>
        <div class="tl-item">Tri-merge алгоритм дедупликации</div>
        <div class="tl-item">Базовый фронтенд дашборд</div>
        <div class="tl-item">Stripe + Chargebee интеграция</div>
      </div>
    </div>
    <div class="tl-card">
      <div class="tl-months">Месяцы 7–9</div>
      <div class="tl-title">Премиум-функции</div>
      <div class="tl-items">
        <div class="tl-item">e-OSCAR / Metro 2 интеграция (споры)</div>
        <div class="tl-item">Score Simulator алгоритм</div>
        <div class="tl-item">Dark Web Monitoring API</div>
        <div class="tl-item">Mobile App разработка</div>
        <div class="tl-item">AI Credit Advisor модуль</div>
        <div class="tl-item">Real-time Alerts система</div>
        <div class="tl-item">ID Theft Insurance партнёрство</div>
      </div>
    </div>
    <div class="tl-card">
      <div class="tl-months">Месяцы 10–12</div>
      <div class="tl-title">Аудит и запуск</div>
      <div class="tl-items">
        <div class="tl-item">SOC 2 Type II аудит</div>
        <div class="tl-item">Penetration Testing</div>
        <div class="tl-item">Нагрузочное тестирование</div>
        <div class="tl-item">Beta-запуск (закрытый)</div>
        <div class="tl-item">Исправление багов по фидбеку</div>
        <div class="tl-item">Публичный запуск MVP</div>
        <div class="tl-item">Маркетинговая кампания</div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- RISKS -->
<section class="section">
  <div class="section-label">Управление рисками</div>
  <h2 class="section-title">Ключевые риски и митигация</h2>
  <div class="risks-grid">
    <div class="risk-card risk-high">
      <div class="risk-icon">⚖</div>
      <div>
        <div class="risk-title">FCRA нарушения</div>
        <div class="risk-desc">Штрафы до $1 000 за нарушение + уголовная ответственность. Получить данные без согласия — немедленный иск.</div>
      </div>
      <div class="risk-level">Высокий</div>
    </div>
    <div class="risk-card risk-high">
      <div class="risk-icon">🔌</div>
      <div>
        <div class="risk-title">Отключение API бюро</div>
        <div class="risk-desc">Нарушение условий DUA — немедленное прекращение доступа к данным. Вся платформа перестаёт работать.</div>
      </div>
      <div class="risk-level">Высокий</div>
    </div>
    <div class="risk-card risk-high">
      <div class="risk-icon">💻</div>
      <div>
        <div class="risk-title">Утечка данных пользователей</div>
        <div class="risk-desc">SSN, кредитные отчёты — ценнейшие данные для мошенников. Репутационный ущерб + штрафы + иски пользователей.</div>
      </div>
      <div class="risk-level">Высокий</div>
    </div>
    <div class="risk-card risk-med">
      <div class="risk-icon">⏱</div>
      <div>
        <div class="risk-title">Задержка аккредитации</div>
        <div class="risk-desc">Прямая интеграция с бюро может занять 12+ месяцев. Митигация — старт через API-агрегатор.</div>
      </div>
      <div class="risk-level">Средний</div>
    </div>
    <div class="risk-card risk-med">
      <div class="risk-icon">💸</div>
      <div>
        <div class="risk-title">Высокий CAC</div>
        <div class="risk-desc">Стоимость привлечения пользователя в финансовой нише исторически высока ($50–200). Нужны партнёрства и органический рост.</div>
      </div>
      <div class="risk-level">Средний</div>
    </div>
    <div class="risk-card risk-low">
      <div class="risk-icon">🏢</div>
      <div>
        <div class="risk-title">Конкуренция с Credit Karma</div>
        <div class="risk-desc">Бесплатная модель CK неуязвима ценой. Митигация — дифференциация через 3 бюро и реальные FICO скоры.</div>
      </div>
      <div class="risk-level">Низкий</div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- FOOTER -->
<footer class="footer">
  <div class="footer-logo">Credit<span style="color:var(--accent)">Core</span></div>
  <p style="font-size:12px;color:var(--text3);margin-top:4px;margin-bottom:16px">Дорожная карта проекта · 2025–2026</p>
  <p class="footer-note">Данный документ содержит конфиденциальную информацию о стратегии создания платформы кредитного мониторинга. Все данные основаны на анализе рынка, открытой документации кредитных бюро и опыте конкурентов.</p>
  <p style="margin-top:24px;font-size:12px;color:var(--text3)">Equifax · Experian · TransUnion · Array · CRS · MeridianLink · Bloom Credit · Stripe · Chargebee · e-OSCAR</p>
</footer>

<script>
// Intersection Observer for scroll animations
const observer = new IntersectionObserver((entries) => {
  entries.forEach((entry, i) => {
    if (entry.isIntersecting) {
      setTimeout(() => {
        entry.target.classList.add('visible');
      }, entry.target.dataset.delay || 0);
    }
  });
}, { threshold: 0.1 });

// Observe all animated elements
document.querySelectorAll('.phase, .bureau-card, .tech-card, .price-card, .comp-card, .tl-card, .risk-card, .alt-card, .wide-card').forEach((el, i) => {
  const delay = (i % 4) * 80;
  el.dataset.delay = delay;
  observer.observe(el);
});

// Counter animation for stats
function animateCounter(el, target, prefix = '', suffix = '') {
  const duration = 1500;
  const start = Date.now();
  const isFloat = target % 1 !== 0;
  
  function update() {
    const elapsed = Date.now() - start;
    const progress = Math.min(elapsed / duration, 1);
    const eased = 1 - Math.pow(1 - progress, 3);
    const value = target * eased;
    el.textContent = prefix + (isFloat ? value.toFixed(1) : Math.floor(value)) + suffix;
    if (progress < 1) requestAnimationFrame(update);
  }
  requestAnimationFrame(update);
}

// Animate stats when hero is visible
setTimeout(() => {
  const statVals = document.querySelectorAll('.stat-val');
  // these are text-based, just add a fade-in effect
}, 600);

// Smooth active nav
const navLinks = document.querySelectorAll('.nav-links a');
const sections = document.querySelectorAll('section[id]');

const navObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      navLinks.forEach(link => {
        link.style.color = '';
        if (link.getAttribute('href') === '#' + entry.target.id) {
          link.style.color = 'var(--text)';
        }
      });
    }
  });
}, { threshold: 0.3 });

sections.forEach(s => navObserver.observe(s));
</script>
</body>
</html>
