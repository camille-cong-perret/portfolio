<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Camille Cong-Perret — Product Designer</title>
<link href="https://fonts.googleapis.com/css2?family=Caveat:wght@600;700&family=DM+Sans:ital,wght@0,400;0,500;1,400;1,500&display=swap" rel="stylesheet">
<style>
:root {
  --bg: #111111;
  --chalk: #F0EAE0;
  --chalk-muted: rgba(240,234,224,0.55);
  --chalk-dim: rgba(240,234,224,0.25);
  --accent: #FF3D1F;
  --c-red: #FF3D1F;
  --c-orange: #FF8C00;
  --c-yellow: #FFD000;
  --c-green: #00B06C;
  --c-blue: #1A3FFF;
  --font-display: 'Caveat', cursive;
  --font-body: 'DM Sans', sans-serif;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  background: var(--bg);
  color: var(--chalk);
  font-family: var(--font-body);
  font-size: 16px;
  line-height: 1.7;
  cursor: none;
  overflow-x: hidden;
}

/* GRAIN TEXTURE */
body::before {
  content: '';
  position: fixed;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='1'/%3E%3C/svg%3E");
  opacity: 0.04;
  pointer-events: none;
  z-index: 9999;
}

/* CUSTOM CURSOR */
#cursor-dot {
  position: fixed;
  width: 8px; height: 8px;
  background: var(--chalk);
  border-radius: 50%;
  pointer-events: none;
  z-index: 99999;
  transform: translate(-50%, -50%);
  transition: width 0.2s, height 0.2s, background 0.2s, border-radius 0.2s;
}
#cursor-ring {
  position: fixed;
  width: 28px; height: 28px;
  border: 1.5px solid var(--chalk);
  border-radius: 50%;
  pointer-events: none;
  z-index: 99998;
  transform: translate(-50%, -50%);
  transition: width 0.25s, height 0.25s, border-radius 0.25s, opacity 0.2s;
}
body.cursor-open #cursor-ring { width: 44px; height: 44px; }
body.cursor-pill #cursor-dot {
  width: auto; height: auto;
  background: var(--chalk);
  border-radius: 20px;
  padding: 4px 12px;
  font-family: var(--font-body);
  font-size: 11px;
  color: var(--bg);
  white-space: nowrap;
  transform: translate(-50%, -50%);
}
body.cursor-pill #cursor-ring { opacity: 0; }

/* BOTTOM NAV */
#bottom-nav {
  position: fixed;
  bottom: 28px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  gap: 14px;
  z-index: 1000;
  opacity: 0;
  transition: opacity 0.6s;
  pointer-events: none;
}
#bottom-nav.visible { opacity: 1; pointer-events: all; }
.nav-circle {
  position: relative;
  width: 36px; height: 36px;
  cursor: none;
}
.nav-circle svg { width: 36px; height: 36px; overflow: visible; }
.nav-circle .nc-path {
  fill: transparent;
  stroke-width: 2;
  transition: fill 0.3s;
}
.nav-circle.active .nc-path { fill-opacity: 0.9; }
.nav-circle:hover .nc-path { fill-opacity: 0.3; }
.nav-label {
  position: absolute;
  bottom: calc(100% + 6px);
  left: 50%;
  transform: translateX(-50%);
  font-family: var(--font-body);
  font-size: 10px;
  color: var(--chalk);
  white-space: nowrap;
  opacity: 0;
  transition: opacity 0.2s;
  letter-spacing: 0.08em;
}
.nav-circle:hover .nav-label { opacity: 1; }
@keyframes nav-wobble {
  0%,100% { transform: rotate(0deg) scale(1); }
  25% { transform: rotate(-8deg) scale(1.1); }
  75% { transform: rotate(8deg) scale(1.1); }
}
.nav-circle:hover svg { animation: nav-wobble 0.4s ease; }

/* SECTIONS */
section { position: relative; overflow: hidden; }

/* HERO */
#hero {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}
#hero-circles {
  position: absolute;
  inset: 0;
  pointer-events: none;
}
.hero-circle {
  position: absolute;
  border-radius: 50%;
  opacity: 0;
}
.hero-circle svg { display: block; }

#hero-content {
  position: relative;
  z-index: 2;
  text-align: center;
  padding: 0 24px;
}
.hero-line {
  overflow: hidden;
  display: block;
}
.hero-line-inner {
  display: block;
  transform: translateY(100%);
  opacity: 0;
  transition: transform 0.8s cubic-bezier(0.16,1,0.3,1), opacity 0.6s ease;
}
.hero-line-inner.revealed {
  transform: translateY(0);
  opacity: 1;
}

h1.hero-title {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: clamp(40px, 6.5vw, 96px);
  letter-spacing: 0.01em;
  line-height: 0.95;
  color: var(--chalk);
  margin-bottom: 16px;
}
.hero-name {
  font-family: var(--font-display);
  font-weight: 800;
  font-size: clamp(18px, 2.5vw, 38px);
  color: var(--chalk);
  margin-bottom: 6px;
}
.hero-role {
  font-family: var(--font-body);
  font-size: clamp(12px, 1.4vw, 18px);
  color: var(--chalk-muted);
  letter-spacing: 0.1em;
  text-transform: uppercase;
  margin-bottom: 28px;
}
.hero-phrase {
  font-family: var(--font-body);
  font-size: clamp(15px, 1.8vw, 22px);
  color: var(--chalk);
}
.hero-phrase .cycling-word {
  color: var(--accent);
  font-style: italic;
  font-family: var(--font-display);
  font-weight: 700;
  display: inline-block;
  min-width: 120px;
}

.hero-scroll-hint {
  position: absolute;
  bottom: 32px;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
  opacity: 0;
  transition: opacity 0.6s 2s;
}
.hero-scroll-hint.show { opacity: 0.4; }
.scroll-arrow {
  animation: bounce 2s ease-in-out infinite;
}
@keyframes bounce {
  0%,100% { transform: translateY(0); }
  50% { transform: translateY(6px); }
}

/* SEPARATOR MARQUEE */
#separator {
  padding: 40px 0;
  overflow: hidden;
  border-top: 1px solid rgba(240,234,224,0.08);
  border-bottom: 1px solid rgba(240,234,224,0.08);
  position: relative;
  z-index: 2;
}
.marquee-track {
  display: flex;
  white-space: nowrap;
  will-change: transform;
}
.marquee-text {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: clamp(44px, 6.5vw, 100px);
  color: var(--chalk);
  padding-right: 80px;
  display: flex;
  gap: 0;
}
.marquee-text .ml {
  display: inline-block;
}
.marquee-sep {
  color: var(--accent);
  padding: 0 24px;
  font-style: normal;
}

/* ABOUT */
#about {
  padding: 120px 60px;
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 80px;
  align-items: start;
}
.section-label {
  font-family: var(--font-body);
  font-size: 11px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--chalk);
  margin-bottom: 24px;
  display: flex;
  align-items: center;
  gap: 12px;
}
.section-label::after {
  content: '';
  display: block;
  height: 1px;
  width: 48px;
  background: var(--chalk-dim);
}

.about-bio {
  font-size: 16px;
  line-height: 1.8;
  color: var(--chalk-muted);
  margin-bottom: 32px;
}
.about-bio strong { color: var(--chalk); font-weight: 500; }

.about-photo {
  width: 100%;
  max-width: 280px;
  aspect-ratio: 3/4;
  background: #222;
  border-radius: 8px;
  transform: rotate(-1.5deg);
  position: relative;
  overflow: hidden;
  margin-bottom: 20px;
}
.about-photo img {
  width: 100%; height: 100%;
  object-fit: cover;
  display: block;
}
.about-photo-placeholder {
  width: 100%; height: 100%;
  background: #1e1e1e;
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--chalk-dim);
  font-size: 13px;
  font-family: var(--font-body);
}
.chalk-frame {
  position: absolute;
  inset: -4px;
  pointer-events: none;
}

.lang-tags {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
}
.lang-tag {
  border: 1px dashed rgba(240,234,224,0.35);
  border-radius: 20px;
  padding: 4px 12px;
  font-size: 11px;
  color: var(--chalk-muted);
  font-family: var(--font-body);
}

/* CHECKLIST */
.checklist-title {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: 34px;
  color: var(--chalk);
  margin-bottom: 28px;
}
.checklist { list-style: none; margin-bottom: 32px; }
.checklist-item {
  display: flex;
  align-items: center;
  gap: 16px;
  padding: 14px 0;
  border-bottom: 1px solid rgba(240,234,224,0.08);
  cursor: none;
  position: relative;
}
.checkbox-wrap {
  width: 22px; height: 22px;
  flex-shrink: 0;
  position: relative;
}
.checkbox-wrap svg { width: 22px; height: 22px; overflow: visible; }
.cb-box {
  fill: none;
  stroke: rgba(240,234,224,0.5);
  stroke-width: 1.5;
}
.cb-check {
  fill: none;
  stroke: var(--accent);
  stroke-width: 2;
  stroke-linecap: round;
  stroke-dasharray: 30;
  stroke-dashoffset: 30;
  transition: stroke-dashoffset 0.35s ease;
}
.checklist-item.checked .cb-check { stroke-dashoffset: 0; }

.checklist-text {
  font-size: 16px;
  color: var(--chalk);
  position: relative;
  transition: color 0.3s;
}
.strike-line {
  position: absolute;
  top: 50%; left: 0;
  height: 1.5px;
  background: rgba(240,234,224,0.5);
  width: 0;
  transition: width 0.4s 0.2s ease;
}
.checklist-item.checked .strike-line { width: 100%; }
.checklist-item.checked .checklist-text { color: var(--chalk-muted); }

.illustration-frame {
  width: 100%;
  max-width: 300px;
  aspect-ratio: 4/3;
  border: 1.5px dashed rgba(240,234,224,0.25);
  border-radius: 10px;
  margin-bottom: 24px;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  overflow: hidden;
}
.illus-layer {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;
  transition: opacity 0.5s ease;
}
.illus-layer.show { opacity: 1; }

.cta-connect {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  border: 1.5px dashed rgba(240,234,224,0.5);
  padding: 14px 28px;
  font-family: var(--font-display);
  font-weight: 700;
  font-size: 14px;
  color: var(--chalk);
  cursor: none;
  opacity: 0;
  transform: scale(0.9);
  transition: opacity 0.4s, transform 0.4s cubic-bezier(0.34,1.56,0.64,1), border-color 0.3s;
  margin-bottom: 32px;
  letter-spacing: 0.05em;
  text-transform: uppercase;
}
.cta-connect.show { opacity: 1; transform: scale(1); }
.cta-connect:hover { border-color: var(--chalk); }

.skills-wrap {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}
.skill-pill {
  border: 1px dashed rgba(240,234,224,0.3);
  border-radius: 20px;
  padding: 5px 14px;
  font-size: 12px;
  color: var(--chalk-muted);
  font-family: var(--font-body);
  opacity: 0;
  transform: scale(0.8) translateY(10px);
  transition: opacity 0.4s, transform 0.4s;
}
.skill-pill.show { opacity: 1; transform: scale(1) translateY(0); }

/* WORKS SEPARATOR */
.chalk-divider {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 60px;
  display: flex;
  align-items: center;
  gap: 20px;
  opacity: 0;
  transform: translateX(-20px);
  transition: opacity 0.6s, transform 0.6s;
}
.chalk-divider.show { opacity: 1; transform: translateX(0); }
.chalk-divider svg { flex: 1; }
.chalk-annot {
  font-family: var(--font-body);
  font-style: italic;
  font-size: 13px;
  color: var(--chalk-dim);
  white-space: nowrap;
}

/* WORKS */
#works {
  padding: 80px 60px 120px;
  max-width: 1200px;
  margin: 0 auto;
}
.works-title {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: clamp(56px, 8vw, 120px);
  letter-spacing: 0.01em;
  line-height: 0.9;
  color: var(--chalk);
  margin-bottom: 60px;
}
.works-stack { display: flex; flex-direction: column; gap: 18px; }

.work-card {
  width: 100%;
  height: 160px;
  background: #1a1a1a;
  border: 1.5px dashed rgba(240,234,224,0.3);
  border-radius: 8px;
  padding: 20px 28px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  cursor: none;
  position: relative;
  overflow: hidden;
  will-change: transform;
  transition: border-color 0.3s;
  opacity: 0;
  transform: translateY(30px);
}
.work-card.show {
  opacity: 1;
  transform: translateY(0) rotate(var(--tilt));
  transition: opacity 0.6s ease, transform 0.6s ease;
}
.work-card:hover { border-color: rgba(240,234,224,0.6); }

.card-num {
  position: absolute;
  top: 16px; left: 28px;
  font-family: 'DM Sans', monospace;
  font-size: 11px;
  color: rgba(240,234,224,0.3);
  letter-spacing: 0.1em;
}
.card-main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-top: 20px;
}
.card-title {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: clamp(22px, 2.8vw, 38px);
  color: var(--chalk);
  margin-bottom: 6px;
  line-height: 1.1;
}
.card-subtitle {
  font-size: 13px;
  color: var(--chalk-muted);
  font-family: var(--font-body);
}
.card-tag {
  position: absolute;
  bottom: 16px; left: 28px;
  border: 1px dashed rgba(240,234,224,0.25);
  border-radius: 20px;
  padding: 3px 10px;
  font-size: 11px;
  color: var(--chalk-muted);
  font-family: var(--font-body);
}
.card-blob {
  position: absolute;
  right: -30px; top: 50%;
  transform: translateY(-50%);
  opacity: 0.07;
  pointer-events: none;
  transition: opacity 0.3s;
}
.work-card:hover .card-blob { opacity: 0.12; }

/* CARD DOODLES */
.card-doodles {
  position: absolute;
  inset: 0;
  pointer-events: none;
  opacity: 0;
  transition: opacity 0.3s;
}
.work-card:hover .card-doodles { opacity: 1; }
.doodle-path {
  stroke: rgba(240,234,224,0.4);
  stroke-width: 1.5;
  fill: none;
  stroke-linecap: round;
  stroke-dasharray: 100;
  stroke-dashoffset: 100;
}
.work-card:hover .doodle-path {
  animation: doodle-draw 0.5s ease forwards;
}
@keyframes doodle-draw {
  to { stroke-dashoffset: 0; }
}

/* BLOB TRANSITION */
#blob-overlay {
  position: fixed;
  inset: 0;
  z-index: 9000;
  pointer-events: none;
  display: flex;
  align-items: center;
  justify-content: center;
}
#blob-svg {
  position: absolute;
  inset: 0;
  width: 100%; height: 100%;
}
#blob-path {
  fill: #F0EAE0;
  transform-origin: 0 0;
  transform: scale(0);
  transition: transform 0.65s cubic-bezier(0.7, 0, 0.3, 1);
}
#blob-overlay.active #blob-path { transform: scale(3); }
#blob-overlay.active { pointer-events: all; }

/* PROJECT DETAIL */
#project-detail {
  position: fixed;
  inset: 0;
  background: var(--bg);
  z-index: 8999;
  overflow-y: auto;
  transform: translateY(10px);
  opacity: 0;
  transition: opacity 0.3s 0.3s, transform 0.3s 0.3s;
  padding: 80px 60px;
  max-width: 900px;
  margin: 0 auto;
  display: none;
}
#project-detail.show { display: block; }
#project-detail.visible { opacity: 1; transform: translateY(0); }
.detail-back {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  font-family: var(--font-body);
  font-size: 13px;
  color: var(--chalk-muted);
  cursor: none;
  margin-bottom: 60px;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  transition: color 0.2s;
}
.detail-back:hover { color: var(--chalk); }
.detail-title {
  font-family: var(--font-display);
  font-weight: 800;
  font-size: clamp(40px, 6vw, 80px);
  letter-spacing: -0.04em;
  line-height: 0.9;
  color: var(--chalk);
  margin-bottom: 12px;
}
.detail-type {
  font-size: 13px;
  color: var(--chalk-muted);
  letter-spacing: 0.1em;
  text-transform: uppercase;
  margin-bottom: 48px;
}
.detail-img {
  width: 100%;
  aspect-ratio: 16/9;
  background: #1e1e1e;
  border: 1.5px dashed rgba(240,234,224,0.2);
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--chalk-dim);
  font-size: 13px;
  margin-bottom: 60px;
}
.detail-section { margin-bottom: 48px; }
.detail-section-title {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: 20px;
  color: var(--chalk);
  margin-bottom: 16px;
  display: flex;
  align-items: center;
  gap: 12px;
}
.detail-section-title::before {
  content: '';
  display: block;
  width: 32px; height: 1px;
  background: var(--accent);
}
.detail-text {
  color: var(--chalk-muted);
  line-height: 1.8;
  font-size: 16px;
}
.detail-nav {
  display: flex;
  justify-content: space-between;
  margin-top: 80px;
  padding-top: 32px;
  border-top: 1px solid rgba(240,234,224,0.08);
}
.detail-nav-btn {
  font-family: var(--font-body);
  font-size: 13px;
  color: var(--chalk-muted);
  cursor: none;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  transition: color 0.2s;
}
.detail-nav-btn:hover { color: var(--chalk); }

/* CONTACT */
#contact {
  padding: 120px 60px;
  max-width: 1200px;
  margin: 0 auto;
  position: relative;
}
.contact-blob {
  position: absolute;
  bottom: 0; right: 0;
  opacity: 0.05;
  pointer-events: none;
}
.contact-headline {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: clamp(50px, 7.5vw, 110px);
  letter-spacing: 0.01em;
  line-height: 0.9;
  color: var(--chalk);
  margin-bottom: 48px;
  overflow: hidden;
}
.contact-email-wrap {
  position: relative;
  display: inline-block;
  margin-bottom: 32px;
}
.contact-email {
  font-family: var(--font-body);
  font-size: clamp(16px, 2vw, 24px);
  color: var(--chalk);
  font-weight: 500;
  text-decoration: none;
  display: block;
}
.email-underline {
  position: absolute;
  bottom: -3px; left: 0;
  height: 1.5px;
  background: var(--chalk);
  width: 0;
  transition: width 0.4s ease;
}
.contact-email-wrap:hover .email-underline { width: 100%; }

.chalk-arrow-wrap {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 40px;
  opacity: 0;
  transition: opacity 0.6s;
}
.chalk-arrow-wrap.show { opacity: 1; }
.chalk-arrow-svg .arrow-path {
  stroke: rgba(240,234,224,0.4);
  stroke-width: 1.5;
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 80;
  stroke-dashoffset: 80;
  transition: stroke-dashoffset 0.8s ease 0.3s;
}
.chalk-arrow-wrap.show .arrow-path { stroke-dashoffset: 0; }

.contact-links {
  display: flex;
  align-items: center;
  gap: 24px;
  margin-bottom: 40px;
}
.contact-link {
  display: flex;
  align-items: center;
  gap: 8px;
  font-family: var(--font-body);
  font-size: 13px;
  color: var(--chalk-muted);
  text-decoration: none;
  cursor: none;
  transition: color 0.2s;
  letter-spacing: 0.05em;
}
.contact-link:hover { color: var(--chalk); }
.contact-annot {
  font-family: var(--font-body);
  font-style: italic;
  font-size: 13px;
  color: rgba(240,234,224,0.35);
}

/* FOOTER */
footer {
  border-top: 1px solid rgba(240,234,224,0.06);
  padding: 24px 60px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.footer-name {
  font-family: var(--font-display);
  font-weight: 700;
  font-size: 13px;
  color: var(--chalk-dim);
}
.footer-year {
  font-size: 12px;
  color: rgba(240,234,224,0.2);
}

/* SCROLL REVEAL */
.reveal {
  opacity: 0;
  transform: translateY(40px);
  transition: opacity 0.7s ease, transform 0.7s ease;
}
.reveal.show { opacity: 1; transform: translateY(0); }

/* BLOBS decorative */
.deco-blob {
  position: absolute;
  pointer-events: none;
  opacity: 0;
  transition: opacity 1s;
}
.deco-blob.show { opacity: 1; }

@media (max-width: 768px) {
  #about { grid-template-columns: 1fr; padding: 80px 24px; gap: 48px; }
  #works { padding: 60px 24px 100px; }
  #contact { padding: 80px 24px; }
  footer { padding: 20px 24px; }
  .works-title { margin-bottom: 40px; }
  .work-card { height: auto; min-height: 140px; }
}
</style>
</head>
<body>

<!-- CURSOR -->
<div id="cursor-dot"></div>
<div id="cursor-ring"></div>

<!-- BLOB TRANSITION -->
<div id="blob-overlay">
  <svg id="blob-svg" viewBox="0 0 100 100" preserveAspectRatio="none">
    <path id="blob-path" d="M0,0 Q30,10 60,0 Q90,-10 100,20 Q110,50 100,70 Q90,90 60,100 Q30,110 0,100 Z"/>
  </svg>
</div>

<!-- PROJECT DETAIL -->
<div id="project-detail">
  <div class="detail-back" id="detail-back">
    <svg width="20" height="12" viewBox="0 0 20 12"><path d="M19 6H1M6 1L1 6l5 5" stroke="currentColor" stroke-width="1.5" fill="none" stroke-linecap="round" stroke-linejoin="round"/></svg>
    Back to playground
  </div>
  <div id="detail-content"></div>
</div>

<!-- BOTTOM NAV -->
<nav id="bottom-nav">
  <div class="nav-circle" data-target="hero" id="nc-0">
    <svg viewBox="0 0 36 36"><circle cx="18" cy="18" r="14" class="nc-path" stroke="var(--c-red)" stroke-width="2"/></svg>
    <span class="nav-label">Home</span>
  </div>
  <div class="nav-circle" data-target="about" id="nc-1">
    <svg viewBox="0 0 36 36"><circle cx="18" cy="18" r="14" class="nc-path" stroke="var(--c-orange)" stroke-width="2"/></svg>
    <span class="nav-label">About</span>
  </div>
  <div class="nav-circle" data-target="works" id="nc-2">
    <svg viewBox="0 0 36 36"><circle cx="18" cy="18" r="14" class="nc-path" stroke="var(--c-yellow)" stroke-width="2"/></svg>
    <span class="nav-label">Works</span>
  </div>
  <div class="nav-circle" data-target="contact" id="nc-3">
    <svg viewBox="0 0 36 36"><circle cx="18" cy="18" r="14" class="nc-path" stroke="var(--c-blue)" stroke-width="2"/></svg>
    <span class="nav-label">Contact</span>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <!-- Decorative blobs -->
  <div class="deco-blob" style="top:-80px;left:-80px;" id="dblob1">
    <svg width="320" height="320" viewBox="0 0 320 320"><ellipse cx="160" cy="160" rx="130" ry="120" fill="none" stroke="var(--c-red)" stroke-width="1.5" opacity="0.4"/></svg>
  </div>
  <div class="deco-blob" style="bottom:-60px;right:-60px;" id="dblob2">
    <svg width="280" height="280" viewBox="0 0 280 280"><ellipse cx="140" cy="140" rx="110" ry="105" fill="var(--c-blue)" opacity="0.08"/><ellipse cx="140" cy="140" rx="110" ry="105" fill="none" stroke="var(--c-blue)" stroke-width="1.5" opacity="0.3"/></svg>
  </div>

  <div id="hero-circles">
    <!-- SVG circles injected by JS -->
  </div>
  <div id="hero-content">
    <h1 class="hero-title">
      <span class="hero-line"><span class="hero-line-inner" id="hl0">WELCOME TO MY</span></span>
      <span class="hero-line"><span class="hero-line-inner" id="hl1">PLAYGROUND</span></span>
    </h1>
    <p class="hero-name"><span class="hero-line"><span class="hero-line-inner" id="hl2">Camille Cong-Perret</span></span></p>
    <p class="hero-role"><span class="hero-line"><span class="hero-line-inner" id="hl3">Product Designer</span></span></p>
    <p class="hero-phrase"><span class="hero-line"><span class="hero-line-inner" id="hl4">Design rooted in <span class="cycling-word" id="cycling-word">curiosity</span></span></span></p>
  </div>
  <div class="hero-scroll-hint" id="scroll-hint">
    <span class="scroll-arrow">
      <svg width="16" height="24" viewBox="0 0 16 24" fill="none">
        <path d="M8 2v20M2 16l6 6 6-6" stroke="rgba(240,234,224,0.5)" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </span>
    <span style="font-size:10px;letter-spacing:0.15em;text-transform:uppercase;color:rgba(240,234,224,0.35)">scroll</span>
  </div>
</section>

<!-- SEPARATOR MARQUEE -->
<div id="separator">
  <div class="marquee-track" id="marquee-track">
    <div class="marquee-text" id="mtext1"></div>
    <div class="marquee-text" id="mtext2"></div>
  </div>
</div>

<!-- ABOUT -->
<section style="padding: 0;">
  <div id="about">
    <!-- LEFT -->
    <div>
      <div class="section-label reveal">About</div>
      <p class="about-bio reveal" style="transition-delay:0.1s">
        Through marketing and communication, I built a sensitivity to design and user journeys.
        Now pivoting to <strong>product design</strong> with conviction — driven by
        <strong>curiosity</strong>, <strong>empathy</strong>, and a strong attention to detail.
      </p>
      <div class="about-photo reveal" style="transition-delay:0.2s">
        <div class="about-photo-placeholder">[ your photo here ]</div>
        <svg class="chalk-frame" viewBox="0 0 290 380" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M8,12 Q9,4 18,6 L272,8 Q282,8 284,18 L286,362 Q286,374 274,374 L16,372 Q6,372 6,362 Z" stroke="rgba(240,234,224,0.45)" stroke-width="2" fill="none" stroke-dasharray="6 4"/>
        </svg>
      </div>
      <div class="lang-tags reveal" style="transition-delay:0.3s;margin-top:16px">
        <span class="lang-tag">French — native</span>
        <span class="lang-tag">English — C1, TOEIC 980</span>
      </div>
    </div>
    <!-- RIGHT -->
    <div>
      <div class="illustration-frame reveal" id="illus-frame">
        <div class="illus-layer" id="il0">
          <svg width="200" height="140" viewBox="0 0 200 140"><circle cx="100" cy="70" r="50" fill="none" stroke="rgba(240,234,224,0.12)" stroke-width="1.5" stroke-dasharray="4 3"/><text x="100" y="75" text-anchor="middle" font-family="DM Sans" font-size="12" fill="rgba(240,234,224,0.25)">check all items</text></svg>
        </div>
        <div class="illus-layer" id="il1">
          <svg width="200" height="140" viewBox="0 0 200 140"><circle cx="100" cy="70" r="40" fill="none" stroke="rgba(255,61,31,0.4)" stroke-width="1.5"/><path d="M70,70 Q100,40 130,70" stroke="rgba(240,234,224,0.3)" stroke-width="1.5" fill="none"/></svg>
        </div>
        <div class="illus-layer" id="il2">
          <svg width="200" height="140" viewBox="0 0 200 140"><circle cx="100" cy="70" r="40" fill="none" stroke="rgba(255,61,31,0.4)" stroke-width="1.5"/><path d="M70,70 Q100,40 130,70" stroke="rgba(240,234,224,0.3)" stroke-width="1.5" fill="none"/><circle cx="100" cy="70" r="8" fill="rgba(255,140,0,0.4)"/></svg>
        </div>
        <div class="illus-layer" id="il3">
          <svg width="200" height="140" viewBox="0 0 200 140"><circle cx="100" cy="70" r="40" fill="none" stroke="rgba(255,61,31,0.4)" stroke-width="1.5"/><path d="M70,70 Q100,40 130,70" stroke="rgba(240,234,224,0.3)" stroke-width="1.5" fill="none"/><circle cx="100" cy="70" r="8" fill="rgba(255,140,0,0.4)"/><path d="M60,95 Q100,115 140,95" stroke="rgba(0,176,108,0.5)" stroke-width="1.5" fill="none" stroke-linecap="round"/></svg>
        </div>
        <div class="illus-layer" id="il4">
          <svg width="200" height="140" viewBox="0 0 200 140"><circle cx="100" cy="70" r="40" fill="rgba(255,61,31,0.06)" stroke="rgba(255,61,31,0.5)" stroke-width="1.5"/><path d="M70,70 Q100,40 130,70" stroke="rgba(240,234,224,0.4)" stroke-width="2" fill="none"/><circle cx="100" cy="70" r="8" fill="rgba(255,140,0,0.6)"/><path d="M60,95 Q100,115 140,95" stroke="rgba(0,176,108,0.6)" stroke-width="2" fill="none" stroke-linecap="round"/><path d="M80,50 L86,56 M120,50 L114,56" stroke="rgba(255,208,0,0.6)" stroke-width="1.5" stroke-linecap="round"/></svg>
        </div>
      </div>

      <h3 class="checklist-title reveal" style="transition-delay:0.1s">What I bring</h3>
      <ul class="checklist reveal" style="transition-delay:0.15s" id="checklist">
        <li class="checklist-item" data-index="0">
          <div class="checkbox-wrap">
            <svg viewBox="0 0 22 22"><rect class="cb-box" x="2" y="2" width="18" height="18" rx="2"/><path class="cb-check" d="M5,5 L17,17 M17,5 L5,17"/></svg>
          </div>
          <span class="checklist-text">Curiosity-driven thinking<span class="strike-line"></span></span>
        </li>
        <li class="checklist-item" data-index="1">
          <div class="checkbox-wrap">
            <svg viewBox="0 0 22 22"><rect class="cb-box" x="2" y="2" width="18" height="18" rx="2"/><path class="cb-check" d="M5,5 L17,17 M17,5 L5,17"/></svg>
          </div>
          <span class="checklist-text">Empathy for real users<span class="strike-line"></span></span>
        </li>
        <li class="checklist-item" data-index="2">
          <div class="checkbox-wrap">
            <svg viewBox="0 0 22 22"><rect class="cb-box" x="2" y="2" width="18" height="18" rx="2"/><path class="cb-check" d="M5,5 L17,17 M17,5 L5,17"/></svg>
          </div>
          <span class="checklist-text">Attention to every detail<span class="strike-line"></span></span>
        </li>
        <li class="checklist-item" data-index="3">
          <div class="checkbox-wrap">
            <svg viewBox="0 0 22 22"><rect class="cb-box" x="2" y="2" width="18" height="18" rx="2"/><path class="cb-check" d="M5,5 L17,17 M17,5 L5,17"/></svg>
          </div>
          <span class="checklist-text">Clear visual communication<span class="strike-line"></span></span>
        </li>
        <li class="checklist-item" data-index="4">
          <div class="checkbox-wrap">
            <svg viewBox="0 0 22 22"><rect class="cb-box" x="2" y="2" width="18" height="18" rx="2"/><path class="cb-check" d="M5,5 L17,17 M17,5 L5,17"/></svg>
          </div>
          <span class="checklist-text">Fast learner, proactive<span class="strike-line"></span></span>
        </li>
      </ul>

      <div class="cta-connect" id="cta-connect">Let's connect →</div>

      <div class="skills-wrap" id="skills-wrap">
        <span class="skill-pill">Figma</span>
        <span class="skill-pill">Wireframing</span>
        <span class="skill-pill">Mockup</span>
        <span class="skill-pill">Prototyping</span>
        <span class="skill-pill">WordPress</span>
        <span class="skill-pill">Canva</span>
      </div>
    </div>
  </div>
</section>

<!-- WORKS DIVIDER -->
<div class="chalk-divider" id="chalk-div">
  <svg height="1" viewBox="0 0 600 1"><line x1="0" y1="0.5" x2="600" y2="0.5" stroke="rgba(240,234,224,0.12)" stroke-width="1"/></svg>
  <span class="chalk-annot">— my work so far</span>
</div>

<!-- WORKS -->
<section style="background:var(--bg);">
  <div id="works">
    <h2 class="works-title reveal">Works</h2>
    <div class="works-stack">

      <div class="work-card" style="--tilt:1.5deg;" data-project="0">
        <span class="card-num">01</span>
        <div class="card-main">
          <div class="card-title">Alinea</div>
          <div class="card-subtitle">Website for a copywriting agency</div>
        </div>
        <span class="card-tag">Web Design</span>
        <div class="card-blob">
          <svg width="180" height="180" viewBox="0 0 180 180"><ellipse cx="90" cy="90" rx="80" ry="75" fill="var(--c-red)"/></svg>
        </div>
        <svg class="card-doodles" viewBox="0 0 100% 160" preserveAspectRatio="none" style="position:absolute;inset:0;width:100%;height:100%">
          <path class="doodle-path" d="M10,10 L20,8 M90%,20 L90%-10,22" style="stroke-dasharray:20"/>
          <path class="doodle-path" d="M95%,140 L95%-8,132 L95%-4,148" style="stroke-dasharray:20;animation-delay:0.1s"/>
        </svg>
      </div>

      <div class="work-card" style="--tilt:-1deg;" data-project="1">
        <span class="card-num">02</span>
        <div class="card-main">
          <div class="card-title">United Healthcare</div>
          <div class="card-subtitle">Eligibility tool for a CLIOS submission</div>
        </div>
        <span class="card-tag">UX Design</span>
        <div class="card-blob">
          <svg width="180" height="180" viewBox="0 0 180 180"><ellipse cx="90" cy="90" rx="80" ry="75" fill="var(--c-blue)"/></svg>
        </div>
      </div>

      <div class="work-card" style="--tilt:0.8deg;" data-project="2">
        <span class="card-num">03</span>
        <div class="card-main">
          <div class="card-title">Innocent</div>
          <div class="card-subtitle">Vending machine interactive screen</div>
        </div>
        <span class="card-tag">Interaction Design</span>
        <div class="card-blob">
          <svg width="180" height="180" viewBox="0 0 180 180"><ellipse cx="90" cy="90" rx="80" ry="75" fill="var(--c-green)"/></svg>
        </div>
      </div>

      <div class="work-card" style="--tilt:-1.5deg;" data-project="3">
        <span class="card-num">04</span>
        <div class="card-main">
          <div class="card-title">La Pivoine</div>
          <div class="card-subtitle">Loyalty card on wallet app</div>
        </div>
        <span class="card-tag">Mobile UX</span>
        <div class="card-blob">
          <svg width="180" height="180" viewBox="0 0 180 180"><ellipse cx="90" cy="90" rx="80" ry="75" fill="var(--c-yellow)"/></svg>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- CONTACT -->
<section style="background:var(--bg);">
  <div id="contact">
    <div class="contact-blob">
      <svg width="380" height="380" viewBox="0 0 380 380"><ellipse cx="190" cy="190" rx="160" ry="150" fill="var(--c-blue)"/></svg>
    </div>
    <div class="contact-headline reveal">Get in touch.</div>

    <div class="chalk-arrow-wrap" id="chalk-arrow">
      <svg class="chalk-arrow-svg" width="80" height="30" viewBox="0 0 80 30">
        <path class="arrow-path" d="M0,15 Q20,8 40,15 Q60,22 75,15 M68,8 L75,15 L68,22"/>
      </svg>
      <span style="font-size:13px;color:rgba(240,234,224,0.4);font-style:italic;font-family:var(--font-body)">say hello</span>
    </div>

    <div class="contact-email-wrap reveal" style="transition-delay:0.1s">
      <a href="mailto:camillecong.ccg@gmail.com" class="contact-email">camillecong.ccg@gmail.com</a>
      <div class="email-underline"></div>
    </div>

    <div class="contact-links reveal" style="transition-delay:0.2s">
      <a href="https://linkedin.com/in/" target="_blank" class="contact-link">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
        LinkedIn
      </a>
    </div>

    <p class="contact-annot reveal" style="transition-delay:0.3s">— open to product design opportunities</p>
  </div>
</section>

<footer>
  <span class="footer-name">Camille Cong-Perret</span>
  <span class="footer-year">2026</span>
</footer>

<script>
// PROJECT DATA
const projects = [
  {
    title: 'Alinea',
    type: 'Website Design · Copywriting Agency',
    challenge: 'Design a compelling website for Alinea, a copywriting agency that needed a digital presence reflecting their craft and voice.',
    approach: 'I focused on typography-driven layouts that let the words breathe. The information architecture was built around the agency\'s services and portfolio, with clear user flows from landing to contact.',
    outcome: 'A clean, editorial website that positions Alinea as a credible, creative agency. Designed in Figma with full desktop and mobile layouts.'
  },
  {
    title: 'United Healthcare',
    type: 'UX Design · CLIOS Submission · Eligibility Tool',
    challenge: 'Redesign an eligibility verification tool to reduce friction for healthcare professionals navigating complex insurance data.',
    approach: 'User research revealed key pain points around information density and error handling. I simplified the flow into clear steps, improved feedback states, and restructured the data hierarchy.',
    outcome: 'A streamlined tool submitted as a CLIOS entry, demonstrating measurable reduction in task completion time through improved UX patterns.'
  },
  {
    title: 'Innocent',
    type: 'Interaction Design · Vending Machine Screen',
    challenge: 'Design the interactive screen experience for an Innocent brand vending machine — playful, on-brand, and easy to use in a 5-second interaction window.',
    approach: 'I designed around the constraint of extremely short interaction time. Large touch targets, bold visuals, and immediate feedback animations kept the experience fun and friction-free.',
    outcome: 'A fully prototyped screen flow in Figma, matching Innocent\'s playful brand identity while optimizing for speed and clarity.'
  },
  {
    title: 'La Pivoine',
    type: 'Mobile UX · Loyalty Card · Wallet App',
    challenge: 'Create a loyalty card experience for La Pivoine that lives inside a native wallet app — simple, beautiful, and adds genuine value to returning customers.',
    approach: 'I explored how to surface the right information at the right moment — points balance, reward progress, next benefit. Designed for one-glance readability and minimal interaction.',
    outcome: 'A wallet-native loyalty card design that integrates seamlessly with Apple Wallet and Google Pay patterns while maintaining La Pivoine\'s brand warmth.'
  }
];

// CURSOR
const dot = document.getElementById('cursor-dot');
const ring = document.getElementById('cursor-ring');
let mx = 0, my = 0, rx = 0, ry = 0;

document.addEventListener('mousemove', e => {
  mx = e.clientX; my = e.clientY;
  dot.style.left = mx + 'px';
  dot.style.top = my + 'px';
});

function animRing() {
  rx += (mx - rx) * 0.12;
  ry += (my - ry) * 0.12;
  ring.style.left = rx + 'px';
  ring.style.top = ry + 'px';
  requestAnimationFrame(animRing);
}
animRing();

document.querySelectorAll('a, button, .work-card, .checklist-item, .nav-circle, .cta-connect, .detail-back, .detail-nav-btn').forEach(el => {
  el.addEventListener('mouseenter', () => document.body.classList.add('cursor-open'));
  el.addEventListener('mouseleave', () => document.body.classList.remove('cursor-open'));
});

document.querySelectorAll('.work-card').forEach(card => {
  card.addEventListener('mouseenter', () => {
    document.body.classList.add('cursor-pill');
    dot.textContent = 'open';
  });
  card.addEventListener('mouseleave', () => {
    document.body.classList.remove('cursor-pill');
    dot.textContent = '';
  });
});

document.querySelector('.contact-email')?.addEventListener('mouseenter', () => {
  document.body.classList.add('cursor-pill');
  dot.textContent = 'write to me';
});
document.querySelector('.contact-email')?.addEventListener('mouseleave', () => {
  document.body.classList.remove('cursor-pill');
  dot.textContent = '';
});

// HERO CIRCLES
const circleData = [
  { color: '#FF3D1F', fill: 'rgba(255,61,31,0.08)', x: '8%',  y: '10%', r: 130, dur: 8 },
  { color: '#FF8C00', fill: 'rgba(255,140,0,0.07)',  x: '72%', y: '6%',  r: 110, dur: 11 },
  { color: '#FFD000', fill: 'rgba(255,208,0,0.07)',  x: '82%', y: '55%', r: 90,  dur: 13 },
  { color: '#00B06C', fill: 'rgba(0,176,108,0.07)',  x: '4%',  y: '65%', r: 100, dur: 9  },
  { color: '#1A3FFF', fill: 'rgba(26,63,255,0.07)',  x: '50%', y: '78%', r: 80,  dur: 12 }
];

const heroCirclesEl = document.getElementById('hero-circles');
const heroCircleSVGs = [];

circleData.forEach((c, i) => {
  const wrap = document.createElement('div');
  wrap.style.cssText = `position:absolute;left:${c.x};top:${c.y};transform:translate(-50%,-50%);opacity:0;transition:opacity 0.3s;`;
  wrap.id = `hc-${i}`;

  const circ = c.r;
  const size = circ * 2 + 10;
  const circumference = Math.round(2 * Math.PI * circ);

  wrap.innerHTML = `<svg width="${size}" height="${size}" viewBox="0 0 ${size} ${size}">
    <circle cx="${size/2}" cy="${size/2}" r="${circ}" fill="${c.fill}" stroke="${c.color}" stroke-width="1.5"
      stroke-dasharray="${circumference}" stroke-dashoffset="${circumference}" id="hcirc-${i}"
      style="transition:stroke-dashoffset 1.2s ease;"/>
  </svg>`;

  heroCirclesEl.appendChild(wrap);
  heroCircleSVGs.push({ wrap, circ: wrap.querySelector('circle'), circumference, r: circ, color: c.color, fill: c.fill, x: c.x, y: c.y });

  // Float animation
  const floatKf = [
    { transform: 'translate(-50%, -50%) translateY(0px) rotate(0deg)' },
    { transform: `translate(-50%, -50%) translateY(-${16 + i * 3}px) rotate(${i % 2 === 0 ? 4 : -4}deg)` },
    { transform: 'translate(-50%, -50%) translateY(0px) rotate(0deg)' }
  ];
  wrap._floatAnim = () => wrap.animate(floatKf, { duration: (c.dur * 1000), iterations: Infinity, easing: 'ease-in-out' });
});

// Animate hero circles on load
function drawHeroCircles() {
  heroCircleSVGs.forEach((c, i) => {
    setTimeout(() => {
      c.wrap.style.opacity = '1';
      c.circ.style.strokeDashoffset = '0';
      setTimeout(() => c.wrap._floatAnim(), 1300);
    }, 300 + i * 150);
  });
}

// HERO TEXT
function revealHeroText() {
  ['hl0','hl1','hl2','hl3','hl4'].forEach((id, i) => {
    setTimeout(() => {
      const el = document.getElementById(id);
      if (el) el.classList.add('revealed');
    }, 900 + i * 120);
  });
  setTimeout(() => {
    document.getElementById('scroll-hint')?.classList.add('show');
  }, 2200);
}

drawHeroCircles();
revealHeroText();
setTimeout(() => {
  document.getElementById('dblob1').classList.add('show');
  document.getElementById('dblob2').classList.add('show');
}, 400);

// TYPEWRITER
const words = ['curiosity','people','intent','logic','care','clarity','craft'];
let wIdx = 0;
const cycleEl = document.getElementById('cycling-word');

function typeWord(word) {
  let i = 0;
  cycleEl.textContent = '';
  const iv = setInterval(() => {
    cycleEl.textContent += word[i] || '';
    i++;
    if (i >= word.length) clearInterval(iv);
  }, 45);
}

function eraseWord() {
  return new Promise(res => {
    const len = cycleEl.textContent.length;
    let i = len;
    const iv = setInterval(() => {
      cycleEl.textContent = cycleEl.textContent.slice(0, -1);
      i--;
      if (i <= 0) { clearInterval(iv); res(); }
    }, 35);
  });
}

async function cycleWords() {
  await new Promise(r => setTimeout(r, 2500));
  while(true) {
    await eraseWord();
    wIdx = (wIdx + 1) % words.length;
    typeWord(words[wIdx]);
    await new Promise(r => setTimeout(r, 2500));
  }
}
cycleWords();

cycleEl.addEventListener('click', async () => {
  await eraseWord();
  wIdx = (wIdx + 1) % words.length;
  typeWord(words[wIdx]);
});

// MARQUEE
const marqueeTrack = document.getElementById('marquee-track');
const phrase = 'Curiosity leads me. Design is where I land.';
['mtext1','mtext2'].forEach(id => {
  const el = document.getElementById(id);
  const full = phrase + ' ✦ ' + phrase + ' ✦ ' + phrase + ' ✦ ';
  el.innerHTML = full.split('').map(ch =>
    ch === ' ' ? ' ' : `<span class="ml" style="display:inline-block;transform:rotate(${(Math.random()-0.5)*6}deg) translateY(${(Math.random()-0.5)*8}px)">${ch}</span>`
  ).join('');
});

let scrollY = 0, lastScrollY = 0, marqueeX = 0, marqueeVel = 0;
window.addEventListener('scroll', () => { scrollY = window.scrollY; });

function animMarquee() {
  const vel = scrollY - lastScrollY;
  lastScrollY = scrollY;
  marqueeVel += (vel * 2 - marqueeVel) * 0.08;
  marqueeX -= (0.6 + Math.abs(marqueeVel) * 0.4);
  const w = document.getElementById('mtext1').offsetWidth;
  if (marqueeX < -w) marqueeX = 0;
  marqueeTrack.style.transform = `translateX(${marqueeX}px)`;
  requestAnimationFrame(animMarquee);
}
animMarquee();

// SCROLL → COMPRESS CIRCLES TO NAV
let hasCompressed = false;
window.addEventListener('scroll', () => {
  if (!hasCompressed && window.scrollY > 80) {
    hasCompressed = true;
    compressCirclesToNav();
  }
  updateActiveNav();
}, { passive: true });

function compressCirclesToNav() {
  const nav = document.getElementById('bottom-nav');
  const navCircles = nav.querySelectorAll('.nav-circle');

  heroCircleSVGs.forEach((c, i) => {
    const navEl = navCircles[i];
    if (!navEl) { c.wrap.style.opacity = '0'; return; }
    const navRect = navEl.getBoundingClientRect();
    const wrapRect = c.wrap.getBoundingClientRect();

    const dx = (navRect.left + navRect.width/2) - (wrapRect.left + wrapRect.width/2);
    const dy = (navRect.top + navRect.height/2) - (wrapRect.top + wrapRect.height/2);

    c.wrap.style.transition = `transform 0.9s cubic-bezier(0.34,1.2,0.64,1), opacity 0.4s 0.7s`;
    c.wrap.style.transform = `translate(calc(-50% + ${dx}px), calc(-50% + ${dy}px)) scale(0.1)`;

    setTimeout(() => {
      c.wrap.style.opacity = '0';
    }, 700);
  });

  setTimeout(() => { nav.classList.add('visible'); }, 800);
}

function updateActiveNav() {
  const sections = ['hero','about','works','contact'];
  const navCircles = document.querySelectorAll('.nav-circle');
  let active = 0;
  sections.forEach((id, i) => {
    const el = document.getElementById(id);
    if (!el) return;
    if (window.scrollY >= el.offsetTop - 200) active = i;
  });
  navCircles.forEach((nc, i) => {
    nc.classList.toggle('active', i === (active < 4 ? active : 3));
  });
}

document.querySelectorAll('.nav-circle').forEach(nc => {
  nc.addEventListener('click', () => {
    const target = nc.dataset.target;
    const el = document.getElementById(target);
    if (el) el.scrollIntoView({ behavior: 'smooth' });
  });
});

// SCROLL REVEAL
const revealEls = document.querySelectorAll('.reveal, .work-card, .chalk-divider, .skill-pill');
const observer = new IntersectionObserver(entries => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      const el = e.target;
      const delay = el.style.transitionDelay || '0s';
      el.classList.add('show');
      if (el.classList.contains('skill-pill')) {
        const pills = document.querySelectorAll('.skill-pill');
        pills.forEach((p, i) => {
          setTimeout(() => p.classList.add('show'), i * 80);
        });
      }
      observer.unobserve(el);
    }
  });
}, { threshold: 0.12 });

revealEls.forEach(el => observer.observe(el));

// CHALK ARROW
const arrowObs = new IntersectionObserver(entries => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      document.getElementById('chalk-arrow')?.classList.add('show');
    }
  });
}, { threshold: 0.3 });
const contactEl = document.getElementById('contact');
if (contactEl) arrowObs.observe(contactEl);

// CHECKLIST
let checkedCount = 0;
document.querySelectorAll('.checklist-item').forEach(item => {
  item.addEventListener('click', () => {
    if (item.classList.contains('checked')) return;
    item.classList.add('checked');
    checkedCount++;
    const idx = parseInt(item.dataset.index);
    const il = document.getElementById('il' + idx);
    if (il) il.classList.add('show');
    if (checkedCount >= 5) {
      document.getElementById('cta-connect')?.classList.add('show');
    }
  });
});
document.getElementById('cta-connect')?.addEventListener('click', () => {
  document.getElementById('contact')?.scrollIntoView({ behavior: 'smooth' });
});

// 3D TILT ON CARDS
document.querySelectorAll('.work-card').forEach(card => {
  card.addEventListener('mousemove', e => {
    const rect = card.getBoundingClientRect();
    const x = (e.clientX - rect.left) / rect.width - 0.5;
    const y = (e.clientY - rect.top) / rect.height - 0.5;
    const tilt = parseFloat(card.style.getPropertyValue('--tilt')) || 0;
    card.style.transform = `rotate(0deg) perspective(800px) rotateX(${-y * 8}deg) rotateY(${x * 8}deg) scale(1.03)`;
  });
  card.addEventListener('mouseleave', () => {
    const tilt = card.style.getPropertyValue('--tilt');
    card.style.transform = `rotate(${tilt})`;
  });
});

// BLOB TRANSITION → PROJECT DETAIL
const blobOverlay = document.getElementById('blob-overlay');
const blobPath = document.getElementById('blob-path');
const projectDetail = document.getElementById('project-detail');
const detailContent = document.getElementById('detail-content');

function openProject(idx) {
  const p = projects[idx];
  blobOverlay.classList.add('active');

  setTimeout(() => {
    detailContent.innerHTML = `
      <div class="detail-title">${p.title}</div>
      <div class="detail-type">${p.type}</div>
      <div class="detail-img">[ project image placeholder ]</div>
      <div class="detail-section">
        <div class="detail-section-title">The Challenge</div>
        <p class="detail-text">${p.challenge}</p>
      </div>
      <div class="detail-section">
        <div class="detail-section-title">My Approach</div>
        <p class="detail-text">${p.approach}</p>
      </div>
      <div class="detail-section">
        <div class="detail-section-title">The Outcome</div>
        <p class="detail-text">${p.outcome}</p>
      </div>
      <div class="detail-nav">
        <span class="detail-nav-btn" onclick="closeProject()">← Back to works</span>
        <span class="detail-nav-btn" onclick="openProject(${(idx+1)%4})">Next project →</span>
      </div>
    `;
    projectDetail.classList.add('show');
    setTimeout(() => projectDetail.classList.add('visible'), 50);
    setTimeout(() => {
      blobOverlay.classList.remove('active');
    }, 300);
  }, 350);
}

function closeProject() {
  blobOverlay.classList.add('active');
  projectDetail.classList.remove('visible');
  setTimeout(() => {
    projectDetail.classList.remove('show');
    blobOverlay.classList.remove('active');
  }, 400);
}

document.querySelectorAll('.work-card').forEach(card => {
  card.addEventListener('click', () => {
    const idx = parseInt(card.dataset.project);
    openProject(idx);
  });
});
document.getElementById('detail-back')?.addEventListener('click', closeProject);

// KEYBOARD ESC
document.addEventListener('keydown', e => {
  if (e.key === 'Escape') closeProject();
});
</script>
</body>
</html>
