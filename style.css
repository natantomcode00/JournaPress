:root{
  --bg:#f6f8fb;
  --accent-1:#0f172a;
  --accent-2:#1d4ed8;
  --muted:#6b7280;
  --card:#ffffff;
  --glass: rgba(255,255,255,0.6);
  --radius:14px;
}

*{box-sizing:border-box}
html,body{height:100%}
body{
  margin:0;
  font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  background:linear-gradient(180deg,var(--bg),#ffffff);
  color:var(--accent-1);
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  scroll-behavior:smooth;
}

/* Container */
.container{max-width:1100px;margin:0 auto;padding:28px}

/* Header / nav */
.site-header{
  position:sticky;top:0;z-index:60;background:rgba(255,255,255,0.6);backdrop-filter: blur(6px);
  border-bottom:1px solid rgba(15,23,42,0.05);
}
.header-inner{display:flex;align-items:center;justify-content:space-between;gap:16px}
.logo{font-weight:700;color:var(--accent-2);text-decoration:none;font-size:1.125rem}
.nav{display:block}
.nav ul{display:flex;gap:18px;list-style:none;margin:0;padding:0;align-items:center}
.nav a{color:var(--accent-1);text-decoration:none;font-weight:600;padding:8px 10px;border-radius:8px}
.nav a:hover, .nav a.active{background:rgba(29,78,216,0.08);color:var(--accent-2)}

/* mobile toggle */
.nav-toggle{display:none;background:none;border:0;cursor:pointer;padding:8px}
.nav-toggle .burger{display:inline-block;width:22px;height:2px;background:var(--accent-1);position:relative}
.nav-toggle .burger::before,.nav-toggle .burger::after{content:"";position:absolute;left:0;width:22px;height:2px;background:var(--accent-1)}
.nav-toggle .burger::before{top:-7px}
.nav-toggle .burger::after{top:7px}

/* Hero */
.hero{padding:80px 20px 60px;background:linear-gradient(135deg,#0ea5e9 0%, #1d4ed8 100%);color:white}
.hero-inner{position:relative;overflow:hidden;border-radius:18px;padding:60px 28px;background:linear-gradient(180deg, rgba(255,255,255,0.06), rgba(255,255,255,0.02))}
.hero-title{font-size:2rem;margin-bottom:12px}
.hero-sub{opacity:0.95;margin-bottom:18px;max-width:720px}
.btn{display:inline-block;padding:10px 16px;border-radius:10px;background:var(--accent-2);color:white;text-decoration:none;font-weight:700;margin-right:10px;box-shadow:0 6px 20px rgba(29,78,216,0.18)}
.btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.12)}
.hero-decor{position:absolute;right:-80px;bottom:-40px;width:360px;height:360px;border-radius:50%;background:radial-gradient(circle at 30% 30%, rgba(255,255,255,0.12), transparent 40%);transform:rotate(20deg);filter:blur(18px);opacity:0.85}

/* Sections */
.section{padding:64px 0}
.section h2{font-size:1.5rem;margin-bottom:12px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 8px 30px rgba(15,23,42,0.06)}
.updates-list{display:flex;flex-direction:column;gap:14px}
/* reveal animations */
.reveal{opacity:0;transform:translateY(18px);transition:all 700ms cubic-bezier(.2,.9,.2,1)}
.reveal.in-view{opacity:1;transform:none}

/* footer */
.site-footer{background:#0f172a;color:white;padding:18px 0;margin-top:40px;text-align:center}

/* responsive */
@media(max-width:900px){
  .grid{grid-template-columns:repeat(2,1fr)}
}
@media(max-width:680px){
  .nav ul{display:none;position:absolute;right:18px;top:64px;background:white;padding:14px;border-radius:12px;box-shadow:0 14px 40px rgba(15,23,42,0.12)}
  .nav.open ul{display:flex;flex-direction:column;gap:8px}
  .nav-toggle{display:block}
  .hero-title{font-size:1.5rem}
  .grid{grid-template-columns:1fr}
  .container{padding:18px}
}
