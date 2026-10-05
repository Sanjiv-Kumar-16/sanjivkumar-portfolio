* {
  box-sizing: border-box;
}

:root {
  --bg: #050b1a;
  --bg-strong: #030915;
  --panel: rgba(15, 23, 42, 0.72);
  --panel-strong: rgba(12, 18, 30, 0.9);
  --panel-soft: rgba(18, 30, 48, 0.7);
  --card-border: rgba(148, 163, 184, 0.2);
  --text: #ecf3ff;
  --muted: rgba(203, 213, 225, 0.8);
  --accent: #6ee7f9;
  --accent-2: #7c9bff;
  --accent-3: #87f7c7;
  --glow: rgba(110, 231, 249, 0.25);
  --shadow: 0 20px 50px rgba(3, 7, 18, 0.45);
  --max-width: 1200px;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: "Inter", sans-serif;
  background:
    radial-gradient(circle at top, rgba(107, 139, 255, 0.16), transparent 18%),
    radial-gradient(circle at bottom right, rgba(73, 195, 255, 0.12), transparent 24%),
    var(--bg);
  color: var(--text);
  line-height: 1.7;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  display: block;
}

a {
  color: inherit;
  text-decoration: none;
}

button, input, textarea {
  font: inherit;
}

.container {
  width: min(var(--max-width), calc(100% - 32px));
  margin: 0 auto;
}

.section-shell {
  position: relative;
  padding: 110px 0;
}

.space-bg {
  position: fixed;
  inset: 0;
  pointer-events: none;
  z-index: 0;
  overflow: hidden;
}

.nebula {
  position: absolute;
  border-radius: 50%;
  filter: blur(90px);
  opacity: 0.5;
}

.nebula-1 {
  width: 520px;
  height: 520px;
  background: rgba(18, 116, 255, 0.16);
  left: -6%;
  top: 12%;
}

.nebula-2 {
  width: 520px;
  height: 520px;
  background: rgba(122, 92, 255, 0.14);
  right: -8%;
  top: 18%;
}

.nebula-3 {
  width: 540px;
  height: 540px;
  background: rgba(34, 211, 238, 0.12);
  left: 30%;
  bottom: -15%;
}

.stars {
  position: absolute;
  inset: 0;
  background-repeat: repeat;
  opacity: 0.8;
}

.stars-back {
  background-image:
    radial-gradient(1px 1px at 10% 15%, rgba(255,255,255,0.9), transparent 100%),
    radial-gradient(1.5px 1.5px at 70% 25%, rgba(255,255,255,0.7), transparent 100%),
    radial-gradient(1.1px 1.1px at 30% 60%, rgba(157, 212, 255, 0.9), transparent 100%),
    radial-gradient(1.3px 1.3px at 80% 70%, rgba(255,255,255,0.9), transparent 100%),
    radial-gradient(1.5px 1.5px at 55% 90%, rgba(255,255,255,0.7), transparent 100%);
  background-size: 240px 240px;
  animation: driftSlow 130s linear infinite;
}

.stars-mid {
  background-image:
    radial-gradient(1.5px 1.5px at 18% 32%, rgba(139,197,255,0.85), transparent 100%),
    radial-gradient(1.2px 1.2px at 65% 42%, rgba(255,255,255,0.9), transparent 100%),
    radial-gradient(1.4px 1.4px at 82% 20%, rgba(124, 194, 255, 0.9), transparent 100%),
    radial-gradient(1.2px 1.2px at 42% 80%, rgba(255,255,255,0.85), transparent 100%);
  background-size: 260px 260px;
  animation: driftSlow 200s linear infinite reverse;
}

.stars-front {
  background-image:
    radial-gradient(1.1px 1.1px at 12% 45%, rgba(255,255,255,0.9), transparent 92%),
    radial-gradient(1.3px 1.3px at 50% 25%, rgba(189, 147, 255, 0.7), transparent 90%),
    radial-gradient(1.1px 1.1px at 72% 56%, rgba(127, 210, 255, 0.85), transparent 90%),
    radial-gradient(1.2px 1.2px at 88% 78%, rgba(255,255,255,0.8), transparent 90%);
  background-size: 220px 220px;
  animation: driftSlow 240s linear infinite;
}

.planet {
  position: absolute;
  right: 10%;
  top: 12%;
  width: min(28vw, 430px);
  aspect-ratio: 1;
  border-radius: 50%;
  background:
    radial-gradient(circle at 32% 30%, rgba(122, 233, 255, 0.92) 0%, rgba(87, 114, 255, 0.9) 28%, rgba(14, 25, 46, 1) 68%, rgba(8, 14, 28, 1) 100%);
  box-shadow: 0 0 100px rgba(80, 199, 255, 0.25), inset -30px -25px 45px rgba(3, 11, 24, 0.7);
  opacity: 0.85;
  animation: planetFloat 14s ease-in-out infinite alternate;
}

.planet-glow {
  position: absolute;
  inset: -16%;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(110, 231, 249, 0.18), transparent 62%);
  filter: blur(28px);
}

.topbar,
main,
.site-footer {
  position: relative;
  z-index: 1;
}

.topbar {
  position: sticky;
  top: 0;
  z-index: 20;
  backdrop-filter: blur(14px);
  background: rgba(6, 12, 24, 0.45);
  border-bottom: 1px solid rgba(148, 163, 184, 0.12);
}

.nav-shell {
  display: flex;
  align-items: center;
  justify-content: space-between;
  min-height: 78px;
}

.brand {
  display: inline-flex;
  align-items: center;
  gap: 12px;
  font-weight: 700;
  letter-spacing: 0.04em;
}

.brand-mark {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background: linear-gradient(135deg, rgba(110, 231, 249, 0.2), rgba(124, 155, 255, 0.2));
  border: 1px solid rgba(110, 231, 249, 0.25);
  color: var(--accent);
  font-size: 0.74rem;
}

.brand-text {
  font-size: 0.92rem;
  text-transform: uppercase;
}

.main-nav {
  display: flex;
  align-items: center;
  gap: 26px;
  color: var(--muted);
  font-size: 0.9rem;
}

.main-nav a {
  position: relative;
  transition: color 0.25s ease;
}

.main-nav a::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: -8px;
  width: 100%;
  height: 1px;
  background: linear-gradient(90deg, transparent, var(--accent), transparent);
  transform: scaleX(0);
  transform-origin: center;
  transition: transform 0.25s ease;
}

.main-nav a:hover,
.main-nav a:focus-visible {
  color: var(--text);
}

.main-nav a:hover::after,
.main-nav a:focus-visible::after {
  transform: scaleX(1);
}

.menu-toggle {
  display: none;
  width: 46px;
  height: 46px;
  border: 1px solid rgba(148, 163, 184, 0.2);
  border-radius: 12px;
  background: rgba(15, 23, 42, 0.5);
  padding: 10px 12px;
  cursor: pointer;
}

.menu-toggle span {
  display: block;
  width: 100%;
  height: 2px;
  background: var(--text);
  margin: 5px 0;
  border-radius: 999px;
}

.mobile-menu {
  position: fixed;
  top: 78px;
  right: 18px;
  z-index: 40;
  display: none;
  flex-direction: column;
  gap: 14px;
  min-width: 220px;
  padding: 18px 16px;
  border: 1px solid rgba(148, 163, 184, 0.2);
  border-radius: 18px;
  background: rgba(11, 17, 27, 0.88);
  box-shadow: var(--shadow);
}

.mobile-menu.is-open {
  display: flex;
}

.hero {
  padding-top: 90px;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  align-items: center;
  gap: 44px;
}

.eyebrow {
  display: inline-block;
  margin: 0 0 18px;
  color: var(--accent);
  letter-spacing: 0.18em;
  text-transform: uppercase;
  font-weight: 700;
  font-size: 0.74rem;
}

.hero h1,
.section-heading h2 {
  font-size: clamp(2.5rem, 5vw, 5rem);
  line-height: 0.95;
  letter-spacing: -0.06em;
  margin: 0;
  font-weight: 800;
}

.accent-text {
  background: linear-gradient(90deg, var(--accent) 0%, #b4c3ff 38%, var(--accent-3) 100%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}

.lead {
  max-width: 640px;
  margin: 22px 0 0;
  color: var(--muted);
  font-size: 1.08rem;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  margin-top: 28px;
}

.primary-btn,
.secondary-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 52px;
  padding: 0 22px;
  border-radius: 999px;
  font-weight: 700;
  border: 1px solid rgba(148, 163, 184, 0.18);
  transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
}

.primary-btn {
  background: linear-gradient(135deg, rgba(110, 231, 249, 0.18), rgba(124, 155, 255, 0.18));
  box-shadow: 0 15px 35px rgba(71, 119, 255, 0.28);
}

.secondary-btn {
  background: rgba(15, 23, 42, 0.25);
  color: var(--text);
}

.primary-btn:hover,
.secondary-btn:hover,
.primary-btn:focus-visible,
.secondary-btn:focus-visible {
  transform: translateY(-2px);
  border-color: rgba(110, 231, 249, 0.35);
}

.quick-stats {
  list-style: none;
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
  padding: 0;
  margin: 34px 0 0;
  max-width: 440px;
}

.quick-stats li {
  padding: 18px 16px;
  border-radius: 18px;
  border: 1px solid rgba(148, 163, 184, 0.18);
  background: rgba(13, 20, 32, 0.45);
  box-shadow: inset 0 1px 0 rgba(255,255,255,0.03);
}

.quick-stats span {
  display: block;
  color: var(--muted);
  font-size: 0.73rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.quick-stats strong {
  display: block;
  margin-top: 6px;
  font-size: clamp(1.4rem, 2vw, 2rem);
}

.hero-visual {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 560px;
}

.hero-card {
  position: relative;
  width: min(78vw, 420px);
  aspect-ratio: 0.92;
  border-radius: 34px;
  background: linear-gradient(180deg, rgba(15, 23, 42, 0.72), rgba(11, 18, 32, 0.9));
  border: 1px solid rgba(148, 163, 184, 0.2);
  box-shadow: var(--shadow);
  overflow: hidden;
}

.hero-card::before {
  content: "";
  position: absolute;
  inset: 18px;
  border: 1px solid rgba(148, 163, 184, 0.12);
  border-radius: 26px;
}

.orbital-ring {
  position: absolute;
  border-radius: 50%;
  border: 1px solid rgba(151, 197, 255, 0.28);
}

.ring-one {
  inset: 24% 18% 24% 18%;
  transform: rotate(15deg);
}

.ring-two {
  inset: 12% 8% 12% 8%;
  transform: rotate(-20deg);
}

.core-badge {
  position: absolute;
  width: 170px;
  height: 170px;
  inset: 50% auto auto 50%;
  transform: translate(-50%, -50%);
  border-radius: 50%;
  background: radial-gradient(circle at 30% 30%, rgba(210, 244, 255, 0.9), rgba(101, 165, 255, 0.8) 18%, rgba(18, 25, 45, 0.9) 54%, rgba(8, 12, 21, 1) 100%);
  box-shadow: 0 0 40px rgba(108, 163, 255, 0.28), inset -18px -16px 30px rgba(5, 10, 18, 0.8);
  display: grid;
  place-items: center;
}

.core-badge span {
  font-size: 2.1rem;
  font-weight: 800;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--text);
}

.section-heading {
  margin-bottom: 36px;
}

.section-heading h2 {
  font-size: clamp(2rem, 4vw, 3.2rem);
  max-width: 780px;
}

.about-grid,
.skills-grid,
.edu-grid,
.contact-wrap,
.cert-grid {
  display: grid;
  gap: 26px;
}

.about-grid {
  grid-template-columns: 0.9fr 1.1fr;
}

.skills-grid,
.edu-grid {
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.glass-card {
  background: rgba(12, 18, 30, 0.66);
  border: 1px solid var(--card-border);
  box-shadow: var(--shadow);
  border-radius: 26px;
  padding: 28px;
}

.about-grid .glass-card p,
.contact-card p,
.timeline-card p,
.project-body p,
.cert-card p {
  margin: 0;
  color: var(--muted);
}

.feature-stack {
  display: grid;
  gap: 18px;
}

.feature-item {
  display: flex;
  gap: 18px;
  align-items: flex-start;
  padding: 20px 18px;
  border-radius: 20px;
  background: rgba(13, 20, 32, 0.5);
  border: 1px solid rgba(148, 163, 184, 0.18);
}

.feature-icon {
  display: grid;
  place-items: center;
  width: 44px;
  height: 44px;
  border-radius: 12px;
  background: linear-gradient(135deg, rgba(110, 231, 249, 0.2), rgba(124, 155, 255, 0.18));
  border: 1px solid rgba(110, 231, 249, 0.2);
  color: var(--accent);
  font-weight: 800;
}

.feature-item h3,
.skill-card h3,
.cert-card h3,
.project-body h3,
.timeline-header h3,
.edu-grid h3 {
  margin: 0 0 8px;
  font-size: 1.2rem;
}

.feature-item p {
  margin: 0;
  color: var(--muted);
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 18px;
}

.skill-tags span,
.pill {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 38px;
  padding: 0 14px;
  border-radius: 999px;
  background: rgba(110, 231, 249, 0.08);
  border: 1px solid rgba(110, 231, 249, 0.2);
  color: #d8f6ff;
  font-size: 0.85rem;
}

.cert-grid {
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.cert-card {
  display: grid;
  grid-template-columns: 170px 1fr;
  gap: 18px;
  align-items: center;
  padding: 20px;
  border-radius: 24px;
  border: 1px solid var(--card-border);
  background: rgba(12, 18, 30, 0.68);
  box-shadow: var(--shadow);
}

.cert-card img {
  width: 170px;
  height: 140px;
  object-fit: cover;
  border-radius: 18px;
  border: 1px solid rgba(148, 163, 184, 0.14);
}

.timeline {
  display: grid;
  gap: 22px;
}

.timeline-item {
  position: relative;
  display: grid;
  grid-template-columns: 20px 1fr;
  gap: 18px;
}

.timeline-dot {
  position: relative;
  width: 18px;
  height: 18px;
  border-radius: 50%;
  background: linear-gradient(135deg, var(--accent), var(--accent-2));
  box-shadow: 0 0 30px rgba(110, 231, 249, 0.28);
  margin-top: 16px;
  z-index: 1;
}

.timeline-item::before {
  content: "";
  position: absolute;
  left: 8px;
  top: 0;
  bottom: 0;
  width: 2px;
  background: linear-gradient(180deg, rgba(110, 231, 249, 0.3), rgba(148, 163, 184, 0.08));
}

.timeline-card {
  padding: 24px 26px;
}

.timeline-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  margin-bottom: 12px;
}

.timeline-header span {
  color: var(--accent);
  font-size: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 0.1em;
}

.timeline-meta {
  margin-top: 16px;
  color: var(--accent);
  font-size: 0.82rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.internship-certificate {
  margin-top: 36px;
  display: flex;
  justify-content: center;
}

.internship-certificate img {
  width: min(100%, 980px);
  border-radius: 24px;
  border: 1px solid rgba(148, 163, 184, 0.14);
  box-shadow: var(--shadow);
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 24px;
}

.project-card {
  background: rgba(12, 18, 30, 0.7);
  border: 1px solid rgba(148, 163, 184, 0.18);
  border-radius: 24px;
  overflow: hidden;
  box-shadow: var(--shadow);
  transition: transform 0.25s ease, border-color 0.25s ease;
}

.project-card:hover,
.project-card:focus-within {
  transform: translateY(-6px);
  border-color: rgba(110, 231, 249, 0.28);
}

.project-visual {
  height: 210px;
  position: relative;
  overflow: hidden;
  background-size: cover;
  background-position: center;
}

.visual-one {
  background:
    linear-gradient(135deg, rgba(110, 231, 249, 0.18), rgba(124, 155, 255, 0.26)),
    radial-gradient(circle at 20% 20%, rgba(191, 219, 254, 0.9), transparent 12%),
    linear-gradient(120deg, rgba(15, 23, 42, 1), rgba(21, 40, 72, 1));
}

.visual-two {
  background:
    linear-gradient(135deg, rgba(151, 147, 255, 0.16), rgba(117, 239, 214, 0.2)),
    radial-gradient(circle at 75% 25%, rgba(184, 246, 255, 0.8), transparent 10%),
    linear-gradient(120deg, rgba(15, 20, 27, 1), rgba(27, 47, 71, 1));
}

.visual-three {
  background:
    linear-gradient(135deg, rgba(116, 219, 193, 0.18), rgba(110, 231, 249, 0.14)),
    radial-gradient(circle at 60% 30%, rgba(170, 223, 255, 0.8), transparent 11%),
    linear-gradient(120deg, rgba(13, 17, 24, 1), rgba(20, 35, 52, 1));
}

.project-body {
  padding: 22px 20px 24px;
}

.metrics {
  list-style: none;
  padding: 0;
  margin: 18px 0 0;
  display: grid;
  gap: 14px;
}

.metrics li {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  color: var(--muted);
  border-bottom: 1px solid rgba(148, 163, 184, 0.1);
  padding-bottom: 10px;
}

.metrics li:last-child {
  border-bottom: none;
  padding-bottom: 0;
}

.metrics strong {
  color: var(--text);
}

.contact-shell {
  padding-bottom: 120px;
}

.contact-wrap {
  grid-template-columns: 0.9fr 1.1fr;
  align-items: stretch;
}

.contact-card {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.contact-lines {
  display: grid;
  gap: 12px;
  margin-top: 22px;
}

.contact-lines a {
  color: var(--accent);
}

.form-card {
  display: grid;
  gap: 18px;
}

.field-row {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 16px;
}

label {
  display: grid;
  gap: 8px;
  color: var(--muted);
  font-size: 0.9rem;
}

input,
textarea {
  width: 100%;
  border: 1px solid rgba(148, 163, 184, 0.18);
  border-radius: 14px;
  background: rgba(9, 15, 24, 0.6);
  color: var(--text);
  padding: 14px 16px;
  outline: none;
  transition: border-color 0.25s ease, box-shadow 0.25s ease;
}

input:focus,
textarea:focus {
  border-color: rgba(110, 231, 249, 0.45);
  box-shadow: 0 0 0 3px rgba(110, 231, 249, 0.12);
}

textarea {
  min-height: 150px;
  resize: vertical;
}

.site-footer {
  border-top: 1px solid rgba(148, 163, 184, 0.14);
  padding: 28px 0 48px;
}

.footer-shell {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 16px;
  color: var(--muted);
  font-size: 0.9rem;
}

.scroll-progress {
  position: fixed;
  left: 0;
  top: 0;
  width: 0;
  height: 3px;
  z-index: 30;
  background: linear-gradient(90deg, var(--accent), var(--accent-3));
  box-shadow: 0 0 20px rgba(110, 231, 249, 0.5);
}

.reveal {
  opacity: 0;
  transform: translateY(28px);
  transition: opacity 0.7s ease, transform 0.7s ease;
}

.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}

@keyframes planetFloat {
  0% {
    transform: translate3d(0, 0, 0) scale(0.98);
  }
  100% {
    transform: translate3d(18px, -12px, 0) scale(1.03);
  }
}

@keyframes driftSlow {
  0% {
    transform: translate3d(0, 0, 0);
  }
  50% {
    transform: translate3d(-18px, 15px, 0);
  }
  100% {
    transform: translate3d(0, 0, 0);
  }
}

@media (max-width: 900px) {
  .main-nav {
    display: none;
  }

  .menu-toggle {
    display: block;
  }

  .hero-grid,
  .about-grid,
  .contact-wrap,
  .project-grid,
  .skills-grid,
  .edu-grid,
  .cert-grid {
    grid-template-columns: 1fr;
  }

  .hero-visual {
    min-height: 430px;
  }

  .field-row {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  .section-shell {
    padding: 90px 0;
  }

  .hero {
    padding-top: 70px;
  }

  .hero-actions {
    flex-direction: column;
    align-items: stretch;
  }

  .primary-btn,
  .secondary-btn {
    width: 100%;
  }

  .quick-stats {
    grid-template-columns: 1fr;
  }

  .cert-card {
    grid-template-columns: 1fr;
  }

  .cert-card img {
    width: 100%;
    height: auto;
  }

  .footer-shell {
    flex-direction: column;
    text-align: center;
  }
}

@media (prefers-reduced-motion: reduce) {
  html {
    scroll-behavior: auto;
  }

  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
  }

  .reveal {
    opacity: 1;
    transform: none;
  }
}
