@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;600;800&display=swap');

:root {
  --bg: #0a0e1a;
  --surface: #111827;
  --card: #1a2235;
  --accent: #00d4ff;
  --accent2: #ff6b35;
  --text: #e8eaf0;
  --muted: #8892a4;
  --border: #1e2d42;
  --nav-width: 260px;
}

* { margin: 0; padding: 0; box-sizing: border-box; }

body {
  font-family: 'Syne', sans-serif;
  background: var(--bg);
  color: var(--text);
  display: flex;
  min-height: 100vh;
}

nav {
  width: var(--nav-width);
  background: var(--surface);
  border-right: 1px solid var(--border);
  position: fixed;
  top: 0; left: 0;
  height: 100vh;
  overflow-y: auto;
  z-index: 100;
  display: flex;
  flex-direction: column;
}

nav .nav-logo {
  padding: 24px 20px 16px;
  border-bottom: 1px solid var(--border);
}

nav .nav-logo span {
  font-size: 11px;
  font-family: 'Space Mono', monospace;
  color: var(--accent);
  letter-spacing: 2px;
  text-transform: uppercase;
}

nav .nav-logo h2 {
  font-size: 15px;
  font-weight: 800;
  color: var(--text);
  margin-top: 4px;
}

nav ul { list-style: none; padding: 12px 0; }

nav ul li a {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 9px 20px;
  color: var(--muted);
  text-decoration: none;
  font-size: 12.5px;
  font-weight: 600;
  border-left: 3px solid transparent;
  transition: all 0.2s;
}

nav ul li a:hover, nav ul li a.active {
  color: var(--accent);
  background: rgba(0,212,255,0.06);
  border-left-color: var(--accent);
}

nav ul li a .num {
  font-family: 'Space Mono', monospace;
  font-size: 10px;
  color: var(--accent2);
  min-width: 20px;
}

main { margin-left: var(--nav-width); flex: 1; }

.hero {
  background: linear-gradient(135deg, #0d1b2e 0%, #0a0e1a 60%);
  border-bottom: 1px solid var(--border);
  padding: 60px 60px 50px;
}

.hero-tag {
  font-family: 'Space Mono', monospace;
  font-size: 11px;
  color: var(--accent);
  letter-spacing: 3px;
  text-transform: uppercase;
  margin-bottom: 14px;
}

.hero h1 {
  font-size: 48px;
  font-weight: 800;
  line-height: 1.1;
  letter-spacing: -1px;
  margin-bottom: 16px;
}

.hero h1 .highlight { color: var(--accent); }

.hero p.subtitle {
  font-size: 15px;
  color: var(--muted);
  max-width: 580px;
  line-height: 1.7;
}

.content { padding: 50px 60px; max-width: 900px; }

.term-image {
  width: 100%;
  max-width: 680px;
  height: 260px;
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: 12px;
  margin-bottom: 40px;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
}

.term-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.term-image .img-placeholder {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 10px;
  color: var(--muted);
  font-family: 'Space Mono', monospace;
  font-size: 12px;
}

.definition {
  background: var(--card);
  border-left: 3px solid var(--accent);
  border-radius: 0 10px 10px 0;
  padding: 24px 28px;
  margin-bottom: 28px;
}

.definition h2 {
  font-size: 13px;
  font-family: 'Space Mono', monospace;
  color: var(--accent);
  letter-spacing: 2px;
  margin-bottom: 10px;
}

.definition p { font-size: 15px; line-height: 1.8; color: var(--text); }

.section-heading {
  font-size: 20px;
  font-weight: 800;
  color: var(--text);
  margin: 36px 0 14px;
}

.info-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
  margin-bottom: 36px;
}

.info-card {
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 22px;
}

.info-card h3 {
  font-size: 11px;
  font-family: 'Space Mono', monospace;
  color: var(--accent2);
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 10px;
}

.info-card p { font-size: 14px; color: var(--muted); line-height: 1.7; }

.prose p { font-size: 15px; line-height: 1.85; color: var(--muted); margin-bottom: 16px; }

.related {
  margin-top: 48px;
  padding-top: 32px;
  border-top: 1px solid var(--border);
}

.related h3 {
  font-size: 13px;
  font-family: 'Space Mono', monospace;
  color: var(--muted);
  letter-spacing: 2px;
  margin-bottom: 16px;
}

.related-links { display: flex; flex-wrap: wrap; gap: 10px; }

.related-links a {
  background: var(--card);
  border: 1px solid var(--border);
  color: var(--accent);
  text-decoration: none;
  padding: 7px 14px;
  border-radius: 6px;
  font-size: 12px;
  font-weight: 600;
  transition: all 0.2s;
}

.related-links a:hover {
  background: rgba(0,212,255,0.1);
  border-color: var(--accent);
}

.terms-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  gap: 16px;
  padding: 50px 60px;
}

.term-card {
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 22px;
  text-decoration: none;
  color: var(--text);
  transition: all 0.25s;
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.term-card:hover {
  border-color: var(--accent);
  transform: translateY(-2px);
}

.term-card .card-num {
  font-family: 'Space Mono', monospace;
  font-size: 11px;
  color: var(--accent2);
}

.term-card h3 { font-size: 15px; font-weight: 800; }

.term-card p { font-size: 12px; color: var(--muted); line-height: 1.6; }

.term-card .arrow { color: var(--accent); font-size: 18px; margin-top: auto; }