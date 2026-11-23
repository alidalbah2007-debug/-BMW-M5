# -BMW-M5
A modern and responsive website showcasing the history of the BMW M5, from the first generation (E28) to the latest generation (G90), featuring generations, specifications, performance, images, and the evolution of BMW M engineering
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="تاريخ سيارة BMW M5 - رحلة عبر أربعة عقود من القوة والتطور والأداء الرياضي من 1985 إلى 2024">
<title>تاريخ BMW M5 | رحلة عبر أربعة عقود من القوة والأداء</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;900&family=Tajawal:wght@400;500;700;900&family=Rajdhani:wght@500;600;700&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0a0a0c;
  --bg-2:#111317;
  --bg-3:#161a20;
  --surface:#1c2027;
  --border:#262c35;
  --m-blue:#1c9bea;
  --m-blue-deep:#0066b1;
  --m-red:#e32726;
  --text:#f4f6f9;
  --text-dim:#a8b0bd;
  --text-faint:#6b7484;
  --gold:#d4af37;
  --font-ar:'Cairo','Tajawal',sans-serif;
  --font-num:'Rajdhani','Cairo',sans-serif;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  font-family:var(--font-ar);
  background:var(--bg);
  color:var(--text);
  line-height:1.75;
  overflow-x:hidden;
  -webkit-font-smoothing:antialiased;
}
/* M tricolor stripe */
.m-stripe{display:inline-block;width:42px;height:6px;border-radius:1px;vertical-align:middle;
  background:linear-gradient(90deg,var(--m-blue) 0 33%,var(--m-blue-deep) 33% 66%,var(--m-red) 66% 100%);
}
.m-stripe.tall{display:block;width:60px;height:8px}
/* NAV */
nav{
  position:fixed;top:0;right:0;left:0;z-index:1000;
  background:rgba(10,10,12,.82);
  backdrop-filter:blur(14px);
  -webkit-backdrop-filter:blur(14px);
  border-bottom:1px solid var(--border);
  transition:padding .3s ease;
}
.nav-inner{
  max-width:1280px;margin:0 auto;
  display:flex;align-items:center;justify-content:space-between;
  padding:14px 24px;
}
.brand{display:flex;align-items:center;gap:12px;font-weight:900;font-size:1.15rem;letter-spacing:.5px}
.brand .logo-mark{
  width:34px;height:34px;border-radius:50%;
  background:#fff;
  display:flex;align-items:center;justify-content:center;
  position:relative;flex-shrink:0;
  box-shadow:0 0 0 2px rgba(255,255,255,.15);
}
.brand .logo-mark::before{
  content:"";position:absolute;inset:4px;border-radius:50%;
  background:conic-gradient(from 0deg,#1c9bea 0 25%,transparent 25% 50%,#1c9bea 50 75%,transparent 75% 100%);
  background:#000;
  -webkit-mask:radial-gradient(circle,transparent 28%,#000 28% 30%,#000 100%),conic-gradient(#000 0 25%,transparent 25% 50%,#000 50% 75%,transparent 75%);
          mask:radial-gradient(circle,transparent 28%,#000 28% 30%,#000 100%),conic-gradient(#000 0 25%,transparent 25% 50%,#000 50% 75%,transparent 75%);
}
.brand .logo-mark span{
  position:absolute;width:26px;height:26px;border-radius:50%;
  background:#fff;
  -webkit-mask:radial-gradient(circle at 50% 50%,#000 28%,transparent 28% 30%,#000 30%);
          mask:radial-gradient(circle at 50% 50%,#000 28%,transparent 28% 30%,#000 30%);
}
.brand .logo-mark .quadrants{
  width:26px;height:26px;border-radius:50%;
  background:
    conic-gradient(from 0deg,#1c9bea 0 90deg,#fff 90deg 180deg,#1c9bea 180deg 270deg,#fff 270deg 360deg);
  -webkit-mask:radial-gradient(circle,transparent 0 9px,#000 9px 13px,transparent 13px);
          mask:radial-gradient(circle,transparent 0 9px,#000 9px 13px,transparent 13px);
  position:relative;
}
.brand .logo-mark .quadrants::after{
  content:"";position:absolute;inset:0;border-radius:50%;
  background:#000;
  -webkit-mask:radial-gradient(circle,#000 0 2px,transparent 2px);
          mask:radial-gradient(circle,#000 0 2px,transparent 2px);
}
.nav-links{display:flex;gap:26px;align-items:center}
.nav-links a{
  color:var(--text-dim);text-decoration:none;font-size:.92rem;font-weight:600;
  transition:color .2s;
}
.nav-links a:hover{color:var(--m-blue)}
.nav-cta{
  background:linear-gradient(90deg,var(--m-blue-deep),var(--m-blue));
  color:#fff;padding:8px 18px;border-radius:6px;
  font-weight:700;font-size:.88rem;border:none;cursor:pointer;
  text-decoration:none;transition:transform .2s,box-shadow .2s;
}
.nav-cta:hover{transform:translateY(-1px);box-shadow:0 6px 20px rgba(28,155,234,.35)}
.menu-btn{display:none;background:none;border:none;color:var(--text);font-size:1.5rem;cursor:pointer}

/* HERO */
.hero{
  position:relative;min-height:100vh;display:flex;align-items:center;
  padding:120px 24px 80px;
  overflow:hidden;
}
.hero-bg{
  position:absolute;inset:0;
  background:
    linear-gradient(90deg,rgba(10,10,12,.95) 0%,rgba(10,10,12,.72) 45%,rgba(10,10,12,.35) 100%),
    url('https://z-cdn.chatglm.cn/image-search-mcp/images-ppt/b3de28a85b0e.jpeg') center/cover no-repeat;
  z-index:0;
}
.hero-bg::after{
  content:"";position:absolute;inset:0;
  background:linear-gradient(180deg,transparent 0%,transparent 60%,var(--bg) 100%);
}
.hero-inner{position:relative;z-index:2;max-width:1280px;margin:0 auto;width:100%}
.hero .eyebrow{
  display:inline-flex;align-items:center;gap:12px;
  font-family:var(--font-num);font-size:.95rem;font-weight:700;letter-spacing:3px;
  color:var(--m-blue);text-transform:uppercase;
  margin-bottom:22px;
}
.hero h1{
  font-size:clamp(2.6rem,7vw,5.2rem);
  font-weight:900;line-height:1.05;
  margin-bottom:24px;
  letter-spacing:-1px;
}
.hero h1 .accent{
  background:linear-gradient(120deg,var(--m-blue),var(--m-blue-deep));
  -webkit-background-clip:text;background-clip:text;color:transparent;
}
.hero .lead{
  font-size:clamp(1rem,2vw,1.25rem);
  color:var(--text-dim);max-width:680px;margin-bottom:38px;font-weight:400;
}
.hero-cta-row{display:flex;gap:16px;flex-wrap:wrap}
.btn-primary,.btn-ghost{
  padding:15px 32px;border-radius:8px;font-weight:700;font-size:1rem;
  text-decoration:none;display:inline-flex;align-items:center;gap:10px;
  transition:all .25s;cursor:pointer;
}
.btn-primary{
  background:linear-gradient(90deg,var(--m-blue-deep),var(--m-blue));
  color:#fff;border:none;
  box-shadow:0 10px 30px rgba(28,155,234,.25);
}
.btn-primary:hover{transform:translateY(-2px);box-shadow:0 14px 40px rgba(28,155,234,.4)}
.btn-ghost{
  background:transparent;color:var(--text);
  border:1.5px solid var(--border);
}
.btn-ghost:hover{border-color:var(--m-blue);color:var(--m-blue)}
.hero-stats{
  display:grid;grid-template-columns:repeat(4,1fr);gap:28px;
  margin-top:64px;padding-top:36px;border-top:1px solid var(--border);
}
.hero-stat .num{
  font-family:var(--font-num);font-size:clamp(1.8rem,3.5vw,2.6rem);
  font-weight:700;color:var(--text);line-height:1;
}
.hero-stat .num .unit{font-size:.45em;color:var(--m-blue);font-weight:600;margin-right:6px}
.hero-stat .lbl{color:var(--text-faint);font-size:.85rem;margin-top:8px;letter-spacing:.5px}

/* SECTION COMMON */
section{padding:90px 24px;position:relative}
.container{max-width:1280px;margin:0 auto}
.sec-head{margin-bottom:60px;max-width:760px}
.sec-head .kicker{
  display:inline-flex;align-items:center;gap:12px;
  font-family:var(--font-num);font-size:.85rem;font-weight:700;letter-spacing:3px;
  color:var(--m-blue);text-transform:uppercase;margin-bottom:18px;
}
.sec-head h2{
  font-size:clamp(1.9rem,4vw,2.8rem);font-weight:900;line-height:1.15;
  margin-bottom:18px;letter-spacing:-.5px;
}
.sec-head p{color:var(--text-dim);font-size:1.05rem;max-width:680px}

/* INTRO */
.intro{background:linear-gradient(180deg,var(--bg) 0%,var(--bg-2) 100%)}
.intro-grid{
  display:grid;grid-template-columns:1.2fr 1fr;gap:60px;align-items:center;
}
.intro-text p{margin-bottom:18px;color:var(--text-dim);font-size:1.05rem}
.intro-text p strong{color:var(--text)}
.intro-card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:14px;padding:32px;position:relative;overflow:hidden;
}
.intro-card::before{
  content:"";position:absolute;top:0;right:0;left:0;height:4px;
  background:linear-gradient(90deg,var(--m-blue),var(--m-blue-deep),var(--m-red));
}
.intro-card h3{
  font-size:1.3rem;font-weight:700;margin-bottom:20px;
  display:flex;align-items:center;gap:12px;
}
.fact-row{
  display:flex;justify-content:space-between;align-items:center;
  padding:14px 0;border-bottom:1px dashed var(--border);
}
.fact-row:last-child{border-bottom:none}
.fact-row .k{color:var(--text-dim);font-size:.95rem}
.fact-row .v{font-family:var(--font-num);font-weight:700;font-size:1.15rem;color:var(--m-blue)}

/* TIMELINE / GENERATIONS */
.gens{background:var(--bg)}
.gen{
  display:grid;grid-template-columns:1fr 1fr;gap:48px;align-items:center;
  margin-bottom:80px;padding-bottom:80px;border-bottom:1px solid var(--border);
}
.gen:nth-child(even) .gen-img{order:2}
.gen-img{
  position:relative;border-radius:16px;overflow:hidden;
  aspect-ratio:16/10;background:var(--bg-3);
  border:1px solid var(--border);
}
.gen-img img{width:100%;height:100%;object-fit:cover;display:block;transition:transform .6s ease}
.gen:hover .gen-img img{transform:scale(1.05)}
.gen-img .badge{
  position:absolute;top:18px;right:18px;z-index:3;
  background:rgba(10,10,12,.85);backdrop-filter:blur(8px);
  border:1px solid rgba(28,155,234,.4);
  padding:8px 16px;border-radius:8px;
  font-family:var(--font-num);font-weight:700;font-size:.95rem;letter-spacing:1px;
  color:var(--m-blue);
}
.gen-img .year-tag{
  position:absolute;bottom:18px;left:18px;z-index:3;
  background:linear-gradient(90deg,var(--m-blue-deep),var(--m-blue));
  color:#fff;padding:8px 18px;border-radius:8px;
  font-family:var(--font-num);font-weight:700;font-size:1.1rem;
}
.gen-text .gen-num{
  font-family:var(--font-num);font-size:.95rem;font-weight:700;letter-spacing:3px;
  color:var(--m-red);text-transform:uppercase;margin-bottom:14px;display:block;
}
.gen-text h3{
  font-size:clamp(1.7rem,3.5vw,2.4rem);font-weight:900;
  margin-bottom:18px;line-height:1.15;letter-spacing:-.5px;
}
.gen-text .gen-sub{color:var(--m-blue);font-weight:600;margin-bottom:22px;font-size:1.05rem}
.gen-text p{color:var(--text-dim);margin-bottom:22px;font-size:1.02rem}
.spec-grid{
  display:grid;grid-template-columns:repeat(2,1fr);gap:14px;
}
.spec{
  background:var(--surface);border:1px solid var(--border);
  border-radius:10px;padding:16px 18px;
  transition:border-color .2s,transform .2s;
}
.spec:hover{border-color:var(--m-blue);transform:translateY(-2px)}
.spec .lbl{font-size:.8rem;color:var(--text-faint);margin-bottom:6px;letter-spacing:.5px}
.spec .val{font-family:var(--font-num);font-weight:700;font-size:1.25rem;color:var(--text)}
.spec .val .u{font-size:.7em;color:var(--m-blue);margin-right:4px}

/* EVOLUTION CHART */
.evolution{background:linear-gradient(180deg,var(--bg-2),var(--bg))}
.chart-card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:16px;padding:36px;overflow-x:auto;
}
.bar-chart{min-width:680px}
.bar-row{
  display:grid;grid-template-columns:90px 1fr 90px;gap:16px;align-items:center;
  padding:14px 0;border-bottom:1px solid var(--border);
}
.bar-row:last-child{border-bottom:none}
.bar-row .gen-label{
  font-family:var(--font-num);font-weight:700;font-size:1.1rem;color:var(--text);
}
.bar-row .gen-year{font-size:.78rem;color:var(--text-faint);display:block;font-family:var(--font-ar)}
.bar-track{height:30px;background:var(--bg-3);border-radius:6px;overflow:hidden;position:relative}
.bar-fill{
  height:100%;border-radius:6px;
  background:linear-gradient(90deg,var(--m-blue-deep),var(--m-blue));
  position:relative;transition:width 1s ease;
  display:flex;align-items:center;
}
.bar-fill::after{
  content:"";position:absolute;top:0;bottom:0;left:0;width:4px;
  background:var(--m-red);
}
.bar-row .power-val{
  font-family:var(--font-num);font-weight:700;font-size:1.15rem;
  color:var(--m-blue);text-align:left;
}

/* TABLE */
.table-wrap{overflow-x:auto;background:var(--surface);border:1px solid var(--border);border-radius:14px}
table{width:100%;min-width:600px;border-collapse:collapse;text-align:right}
thead th{
  background:var(--bg-3);padding:18px 20px;
  font-weight:700;color:var(--m-blue);font-size:.95rem;
  border-bottom:2px solid var(--m-blue-deep);letter-spacing:.5px;
}
tbody td{padding:16px 20px;border-bottom:1px solid var(--border);font-size:1rem}
tbody tr:last-child td{border-bottom:none}
tbody tr:hover{background:var(--bg-3)}
tbody td.gen-code{font-family:var(--font-num);font-weight:700;color:var(--text)}
tbody td.power{font-family:var(--font-num);font-weight:700;color:var(--m-blue)}

/* EVALUATION */
.eval{background:var(--bg)}
.eval-grid{
  display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:22px;margin-bottom:50px;
}
.eval-card{
  background:var(--surface);border:1px solid var(--border);
  border-radius:14px;padding:28px;text-align:center;position:relative;overflow:hidden;
  transition:transform .25s,border-color .25s;
}
.eval-card:hover{transform:translateY(-4px);border-color:var(--m-blue)}
.eval-card .ic{
  width:54px;height:54px;border-radius:50%;
  background:linear-gradient(135deg,rgba(28,155,234,.15),rgba(0,102,177,.15));
  border:1px solid rgba(28,155,234,.3);
  display:flex;align-items:center;justify-content:center;
  margin:0 auto 18px;font-size:1.6rem;
}
.eval-card h4{font-size:1.15rem;font-weight:700;margin-bottom:8px}
.eval-card .rating{font-family:var(--font-num);font-weight:700;color:var(--m-blue);font-size:1.05rem;margin-bottom:10px}
.eval-card .rating .dot{color:var(--gold);margin:0 1px}
.eval-card p{color:var(--text-dim);font-size:.92rem}
.verdict{
  background:linear-gradient(135deg,var(--bg-2),var(--surface));
  border:1px solid var(--border);border-radius:16px;padding:44px;
  position:relative;overflow:hidden;
}
.verdict::before{
  content:"";position:absolute;top:0;right:0;width:6px;bottom:0;
  background:linear-gradient(180deg,var(--m-blue),var(--m-blue-deep),var(--m-red));
}
.verdict h3{
  font-size:clamp(1.5rem,3vw,2rem);font-weight:900;margin-bottom:18px;
  display:flex;align-items:center;gap:14px;
}
.verdict p{color:var(--text-dim);font-size:1.1rem;line-height:1.9}
.verdict p strong{color:var(--text)}

/* SOURCES */
.sources{background:var(--bg-2)}
.src-list{list-style:none;display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px}
.src-list li{
  background:var(--surface);border:1px solid var(--border);
  border-radius:12px;padding:22px;display:flex;gap:14px;align-items:flex-start;
  transition:border-color .2s;
}
.src-list li:hover{border-color:var(--m-blue)}
.src-list .ic{
  width:38px;height:38px;border-radius:8px;flex-shrink:0;
  background:rgba(28,155,234,.12);color:var(--m-blue);
  display:flex;align-items:center;justify-content:center;font-weight:700;
  font-family:var(--font-num);
}
.src-list .txt strong{display:block;margin-bottom:4px;color:var(--text)}
.src-list .txt span{color:var(--text-faint);font-size:.88rem}

/* FOOTER */
footer{
  background:var(--bg);padding:40px 24px;
  border-top:1px solid var(--border);text-align:center;
}
footer .m-stripe{margin:0 auto 18px}
footer p{color:var(--text-faint);font-size:.9rem}
footer .disclaimer{margin-top:12px;font-size:.78rem;color:var(--text-faint);max-width:680px;margin-left:auto;margin-right:auto}

/* REVEAL ANIMATION */
.reveal{opacity:0;transform:translateY(30px);transition:opacity .8s ease,transform .8s ease}
.reveal.visible{opacity:1;transform:translateY(0)}

/* RESPONSIVE */
@media (max-width:900px){
  .intro-grid{grid-template-columns:1fr;gap:36px}
  .gen{grid-template-columns:1fr;gap:28px;padding-bottom:48px;margin-bottom:48px}
  .gen:nth-child(even) .gen-img{order:0}
  .hero-stats{grid-template-columns:repeat(2,1fr);gap:22px}
}
@media (max-width:680px){
  .nav-links{display:none;position:absolute;top:100%;right:0;left:0;
    background:rgba(10,10,12,.98);backdrop-filter:blur(14px);
    flex-direction:column;padding:20px 24px;gap:18px;border-bottom:1px solid var(--border)}
  .nav-links.open{display:flex}
  .menu-btn{display:block}
  .nav-cta{display:none}
  section{padding:60px 18px}
  .hero{padding:110px 18px 60px}
  .hero h1{font-size:2.4rem}
  .chart-card{padding:20px}
  .verdict{padding:28px 22px}
  .spec-grid{grid-template-columns:1fr}
}
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-inner">
    <div class="brand">
      <div class="logo-mark"><div class="quadrants"></div></div>
      <span>BMW M5 <span style="color:var(--m-blue)">|</span> التاريخ</span>
    </div>
    <div class="nav-links" id="navLinks">
      <a href="#intro">المقدمة</a>
      <a href="#generations">الأجيال</a>
      <a href="#evolution">التطور</a>
      <a href="#evaluation">التقييم</a>
      <a href="#sources">المصادر</a>
      <a href="#intro" class="nav-cta">ابدأ الرحلة</a>
    </div>
    <button class="menu-btn" id="menuBtn" aria-label="القائمة">☰</button>
  </div>
</nav>

<!-- HERO -->
<header class="hero">
  <div class="hero-bg"></div>
  <div class="hero-inner">
    <div class="eyebrow"><span class="m-stripe"></span> 1985 — 2024 · BMW M HERITAGE</div>
    <h1>تاريخ سيارة <span class="accent">BMW M5</span><br>أربعة عقود من القوة والأداء</h1>
    <p class="lead">رحلة عبر سبعة أجيال من سيارة السيدان الرياضية الأشهر في العالم — من محرك سداسي الأسطوانات بقوة 286 حصانًا عام 1985، إلى المنظومة الهجينة بقوة 727 حصانًا عام 2024.</p>
    <div class="hero-cta-row">
      <a href="#generations" class="btn-primary">استكشف الأجيال ←</a>
      <a href="#evolution" class="btn-ghost">منحنى القوة</a>
    </div>
    <div class="hero-stats">
      <div class="hero-stat">
        <div class="num">40<span class="unit">عامًا</span></div>
        <div class="lbl">من الإنتاج المتواصل</div>
      </div>
      <div class="hero-stat">
        <div class="num">7<span class="unit">أجيال</span></div>
        <div class="lbl">من E28 إلى G90</div>
      </div>
      <div class="hero-stat">
        <div class="num">727<span class="unit">حصان</span></div>
        <div class="lbl">أقصى قوة في الجيل الحالي</div>
      </div>
      <div class="hero-stat">
        <div class="num">154%</span>
        <div class="lbl">نمو القوة منذ الجيل الأول</div>
      </div>
    </div>
  </div>
</header>

<!-- INTRO -->
<section class="intro" id="intro">
  <div class="container">
    <div class="intro-grid">
      <div class="intro-text reveal">
        <div class="kicker" style="display:inline-flex;align-items:center;gap:12px;font-family:var(--font-num);font-size:.85rem;font-weight:700;letter-spacing:3px;color:var(--m-blue);text-transform:uppercase;margin-bottom:18px;">
          <span class="m-stripe"></span> المقدمة
        </div>
        <h2 style="font-size:clamp(1.9rem,4vw,2.8rem);font-weight:900;line-height:1.15;margin-bottom:24px;">سيارة أصبحت رمزًا للتميز الهندسي</h2>
        <p>سيارة <strong>BMW M5</strong> واحدة من أشهر سيارات السيدان الرياضية في العالم، وهي تجمع بين الفخامة والراحة والقوة والأداء العالي في آنٍ واحد.</p>
        <p>بدأ تاريخها في ثمانينيات القرن الماضي على يد قسم <strong>BMW Motorsport</strong>، وهو القسم الرياضي الرسمي للشركة، لتتحول على مدى أربعة عقود إلى <strong>رمز للتميز الهندسي</strong> لدى شركة BMW، وإلى المعيار الذي تُقاس عليه سيارات السيدان الرياضية في العالم.</p>
        <p>على هذه الصفحة نستعرض رحلة BMW M5 جيلاً بعد جيل — من E28 الكلاسيكية إلى G90 الهجينة — مع المواصفات والأرقام والتقييم النهائي.</p>
      </div>
      <div class="intro-card reveal">
        <h3><span class="m-stripe"></span> نظرة سريعة</h3>
        <div class="fact-row"><span class="k">الصانع</span><span class="v">BMW M GmbH</span></div>
        <div class="fact-row"><span class="k">القسم</span><span class="v">BMW Motorsport</span></div>
        <div class="fact-row"><span class="k">سنة الإطلاق</span><span class="v">1985</span></div>
        <div class="fact-row"><span class="k">الجيل الأول</span><span class="v">E28</span></div>
        <div class="fact-row"><span class="k">الجيل الحالي</span><span class="v">G90 (2024)</span></div>
        <div class="fact-row"><span class="k">فئة السيارة</span><span class="v">سيدان رياضية</span></div>
        <div class="fact-row"><span class="k">قوة الجيل الحالي</span><span class="v">727 حصان</span></div>
      </div>
    </div>
  </div>
</section>

<!-- GENERATIONS -->
<section class="gens" id="generations">
  <div class="container">
    <div class="sec-head reveal">
      <span class="kicker"><span class="m-stripe"></span> الأجيال السبعة</span>
      <h2>رحلة عبر سبعة أجيال من التطور</h2>
      <p>من المحرك السداسي الأسطوانات إلى المنظومة الهجينة القابلة للشحن — كل جيل أضاف فصلًا جديدًا إلى قصة BMW M5.</p>
    </div>

    <!-- E28 -->
    <div class="gen reveal">
      <div class="gen-img">
        <span class="badge">E28</span>
        <span class="year-tag">1985</span>
        <img src="https://z-cdn.chatglm.cn/image-search-mcp/images-ppt/1339e4f74cc1.jpg" alt="BMW M5 E28 الجيل الأول 1985" loading="lazy">
      </div>
      <div class="gen-text">
        <span class="gen-num">الجيل الأول · 01 / 07</span>
        <h3>البداية: E28 عام 1985</h3>
        <div class="gen-sub">ميلاد أسطورة السيدان الرياضية</div>
        <p>ظهرت الجيل الأول من BMW M5 عام 1985 لتكون أول سيارة سيدان رياضية حقيقية في العالم. حملت اسم <strong>E28</strong> واستخدمت محركًا سداسي الأسطوانات بسعة 3.5 لتر مستوحى من سيارة M1 الفائزة في السباقات، فجمعت بين شكل السيارة العائلية وأداء السيارات الرياضية.</p>
        <div class="spec-grid">
          <div class="spec"><div class="lbl">المحرك</div><div class="val">3.5L <span class="u">سداسي</span></div></div>
          <div class="spec"><div class="lbl">القوة</div><div class="val">286 <span class="u">حصان</span></div></div>
          <div class="spec"><div class="lbl">ناقل الحركة</div><div class="val">5 سرعات <span class="u">يدوي</span></div></div>
          <div class="spec"><div class="lbl">الدفع</div><div class="val">خلفي</div></div>
        </div>
      </div>
    </div>

    <!-- E34 -->
    <div class="gen reveal">
      <div class="gen-img">
        <span class="badge">E34</span>
        <span class="year-tag">1988</span>
        <img src="https://z-cdn.chatglm.cn/image-search-mcp/images-ppt/7c63112e315b.jpg" alt="BMW M5 E34 الجيل الثاني 1988" loading="lazy">
      </div>
      <div class="gen-text">
        <span class="gen-num">الجيل الثاني · 02 / 07</span>
        <h3>الأناقة والقوة: E34 عام 1988</h3>
        <div class="gen-sub">تصميم أكثر تطورًا ونسخة Touring</div>
        <p>جاء الجيل الثاني <strong>E34</strong> بتصميم أكثر تطورًا وأناقة مع توسيعات واضحة في الأداء. استمرت السيارة على المحرك السداسي الأسطوانات، وبلغت قوتها إلى 340 حصانًا في النسخ اللاحقة. وفي عام 1992 ظهرت لأول مرة <strong>نسخة Touring</strong> العملية (الستانشن واغن)، لتفتح بابًا جديدًا لسيارات السيدان الرياضية ذات المساحة العائلية.</p>
        <div class="spec-grid">
          <div class="spec"><div class="lbl">المحرك</div><div class="val">3.6–3.8L <span class="u">سداسي</span></div></div>
          <div class="spec"><div class="lbl">القوة</div><div class="val">315–340 <span class="u">حصان</span></div></div>
          <div class="spec"><div class="lbl">نسخة Touring</div><div class="val">1992</div></div>
          <div class="spec"><div class="lbl">ناقل الحركة</div><div class="val">5/6 سرعات <span class="u">يدوي</span></div></div>
        </div>
      </div>
    </div>

    <!-- E39 -->
    <div class="gen reveal">
      <div class="gen-img">
        <span class="badge">E39</span>
        <span class="year-tag">1998</span>
        <img src="https://z-cdn.chatglm.cn/image-search-mcp/images-ppt/0b4481df1ebb.jpg" alt="BMW M5 E39 الجيل الثالث 1998" loading="lazy">
      </div>
      <div class="gen-text">
        <span class="gen-num">الجيل الثالث · 03 / 07</span>
        <h3>الجيل الأشهر: E39 عام 1998</h3>
        <div class="gen-sub">أول محرك V8 في تاريخ M5</div>
        <p>دخل الجيل الثالث <strong>E39</strong> التاريخ بوصفه أشهر أجيال M5 بين عشاق السيارات. حمل لأول مرة محرك <strong>V8</strong> بسعة 5.0 لتر بقوة 400 حصان وعزم دوران 500 نيوتن متر، وتسارع من 0 إلى 100 كم/ساعة خلال 5.3 ثانية فقط. تصميمه المتوازن ما زال يُعد مرجعًا للجمال الكلاسيكي.</p>
        <div class="spec-grid">
          <div class="spec"><div class="lbl">المحرك</div><div class="val">5.0L <span class="u">V8</span></div></div>
          <div class="spec"><div class="lbl">القوة</div><div class="val">400 <span class="u">حصان</span></div></div>
          <div class="spec"><div class="lbl">العزم</div><div class="val">500 <span class="u">نيوتن متر</span></div></div>
          <div class="spec"><div class="lbl">0 → 100</div><div class="val">5.3 <span class="u">ثانية</span></div></div>
        </div>
      </div>
    </div>

    <!-- E60 -->
    <div class="gen reveal">
      <div class="gen-img">
        <span class="badge">E60</span>
        <span class="year-tag">2005</span>
        <img src="https://z-cdn.chatglm.cn/image-search-mcp/images-ppt/b3de28a85b0e.jpeg" alt="BMW M5 E60 الجيل الرابع 2005 محرك V10" loading="lazy">
      </div>
      <div class="gen-text">
        <span class="gen-num">الجيل الرابع · 04 / 07</span>
        <h3>صرخة المحرك: E60 عام 2005</h3>
        <div class="gen-sub">محرك V10 بصوت رياضي فريد</div>
        <p>رفع الجيل الرابع <strong>E60</strong> سقف الأداء إلى مستوى جديد عبر محرك <strong>V10</strong> بسعة 5.0 لتر بقوة 507 أحصنة، مع سرعة دوران تصل إلى 8,250 دورة في الدقيقة — رقم نادر في سيارات السيدان. اقترن بناقل حركة <strong>SMG</strong> بسبع سرعات، وتميز بصوت محرك رياضي فريد جعله أيقونة لعشاق القيادة.</p>
        <div class="spec-grid">
          <div class="spec"><div class="lbl">المحرك</div><div class="val">5.0L <span class="u">V10</span></div></div>
          <div class="spec"><div class="lbl">القوة</div><div class="val">507 <span class="u">حصان</span></div></div>
          <div class="spec"><div class="lbl">أقصى دورة</div><div class="val">8,250 <span class="u">RPM</span></div></div>
          <div class="spec"><div class="lbl">ناقل الحركة</div><div class="val">SMG <span class="u">7 سرعات</span></div></div>
        </div>
      </div>
    </div>

    <!-- F10 -->
    <div class="gen reveal">
      <div class="gen-img">
        <span class="badge">F10</span>
        <span class="year-tag">2011</span>
        <img src="https://z-cdn.chatglm.cn/image-search-mcp/images-ppt/b3d5a96f896a.jpg" alt="BMW M5 F10 الجيل الخامس 2011 محرك V8 تيربو" loading="lazy">
      </div>
      <div class="gen-text">
        <span class="gen-num">الجيل الخامس · 05 / 07</span>
        <h3>عصر التيربو: F10 عام 2011</h3>
        <div class="gen-sub">V8 مزدوج التيربو بكفاءة أعلى</div>
        <p>انتقل الجيل الخامس <strong>F10</strong> إلى محرك <strong>V8 مزدوج التيربو</strong> بسعة 4.4 لتر بقوة 560 حصانًا في النسخة الأساسية وعزم دوران 680 نيوتن متر. هذا التحوّل قدّم أداءً أقوى مع <strong>استهلاك أكثر كفاءة نسبيًا</strong> مقارنة بالجيل السابق ذي المحرك V10، فجمع بين القوة والاقتصادية في آنٍ واحد.</p>
        <div class="spec-grid">
          <div class="spec"><div class="lbl">المحرك</div><div class="val">4.4L <span class="u">V8 توين تيربو</span></div></div>
          <div class="spec"><div class="lbl">القوة</div><div class="val">560 <span class="u">حصان</span></div></div>
          <div class="spec"><div class="lbl">العزم</div><div class="val">680 <span class="u">نيوتن متر</span></div></div>
          <div class="spec"><div class="lbl">ناقل الحركة</div><div class="val">M-DCT <span class="u">7 سرعات</span></div></div>
        </div>
      </div>
    </div>

    <!-- F90 -->
    <div class="gen reveal">
      <div class="gen-img">
        <span class="badge">F90</span>
        <span class="year-tag">2017</span>
        <img src="https://z-cdn.chatglm.cn/image-search-mcp/images-ppt/68ac9b760e28.jpg" alt="BMW M5 F90 الجيل السادس 2017 Competition" loading="lazy">
      </div>
      <div class="gen-text">
        <span class="gen-num">الجيل السادس · 06 / 07</span>
        <h3>الدفع الرباعي: F90 عام 2017</h3>
        <div class="gen-sub">نظام M xDrive ونسخة Competition</div>
        <p>أحدث الجيل السادس <strong>F90</strong> نقلة جوهرية بإدخال نظام الدفع الرباعي <strong>M xDrive</strong> لأول مرة في تاريخ M5، ما منح السيارة تسارعًا أقوى وثباتًا أفضل على الطريق. اعتمدت على محرك V8 مزدوج التيربو وبلغت قوتها إلى <strong>625 حصانًا</strong> في نسخة Competition الأكثر تطورًا.</p>
        <div class="spec-grid">
          <div class="spec"><div class="lbl">المحرك</div><div class="val">4.4L <span class="u">V8 توين تيربو</span></div></div>
          <div class="spec"><div class="lbl">القوة (Comp.)</div><div class="val">625 <span class="u">حصان</span></div></div>
          <div class="spec"><div class="lbl">الدفع</div><div class="val">M xDrive <span class="u">رباعي</span></div></div>
          <div class="spec"><div class="lbl">ناقل الحركة</div><div class="val">أوتوماتيكي <span class="u">8 سرعات</span></div></div>
        </div>
      </div>
    </div>

    <!-- G90 -->
    <div class="gen reveal">
      <div class="gen-img">
        <span class="badge">G90</span>
        <span class="year-tag">2024</span>
        <img src="https://z-cdn.chatglm.cn/image-search-mcp/images-ppt/02e47e8c63c4.webp" alt="BMW M5 G90 الجيل السابع 2024 هجين قابل للشحن" loading="lazy">
      </div>
      <div class="gen-text">
        <span class="gen-num">الجيل السابع · 07 / 07</span>
        <h3>العصر الهجين: G90 عام 2024</h3>
        <div class="gen-sub">727 حصانًا من منظومة هجينة قابلة للشحن</div>
        <p>دخل الجيل السابع <strong>G90</strong> تقنية المحرك الهجين القابل للشحن لأول مرة، عبر دمج محرك V8 مع محرك كهربائي. بلغت القوة الإجمالية <strong>727 حصانًا</strong> — أعلى رقم في تاريخ M5 — مع تطور كبير في التكنولوجيا وأنظمة القيادة، مع المحافظة الكاملة على هوية M5 الرياضية.</p>
        <div class="spec-grid">
          <div class="spec"><div class="lbl">المنظومة</div><div class="val">V8 + كهربائي <span class="u">هجين PHEV</span></div></div>
          <div class="spec"><div class="lbl">القوة الإجمالية</div><div class="val">727 <span class="u">حصان</span></div></div>
          <div class="spec"><div class="lbl">الدفع</div><div class="val">M xDrive <span class="u">رباعي</span></div></div>
          <div class="spec"><div class="lbl">الجيل</div><div class="val">الأحدث <span class="u">2024</span></div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EVOLUTION CHART -->
<section class="evolution" id="evolution">
  <div class="container">
    <div class="sec-head reveal">
      <span class="kicker"><span class="m-stripe"></span> منحنى القوة</span>
      <h2>تطور القوة عبر الأجيال</h2>
      <p>من 286 حصانًا في الجيل الأول إلى 727 حصانًا في الجيل السابع — نمو بنسبة 154% على مدى 40 عامًا.</p>
    </div>
    <div class="chart-card reveal">
      <div class="bar-chart" id="barChart">
        <div class="bar-row">
          <div class="gen-label">E28<span class="gen-year">1985</span></div>
          <div class="bar-track"><div class="bar-fill" data-w="39"></div></div>
          <div class="power-val">286 حصان</div>
        </div>
        <div class="bar-row">
          <div class="gen-label">E34<span class="gen-year">1988</span></div>
          <div class="bar-track"><div class="bar-fill" data-w="47"></div></div>
          <div class="power-val">315–340 حصان</div>
        </div>
        <div class="bar-row">
          <div class="gen-label">E39<span class="gen-year">1998</span></div>
          <div class="bar-track"><div class="bar-fill" data-w="55"></div></div>
          <div class="power-val">400 حصان</div>
        </div>
        <div class="bar-row">
          <div class="gen-label">E60<span class="gen-year">2005</span></div>
          <div class="bar-track"><div class="bar-fill" data-w="70"></div></div>
          <div class="power-val">507 حصان</div>
        </div>
        <div class="bar-row">
          <div class="gen-label">F10<span class="gen-year">2011</span></div>
          <div class="bar-track"><div class="bar-fill" data-w="77"></div></div>
          <div class="power-val">560 حصان</div>
        </div>
        <div class="bar-row">
          <div class="gen-label">F90<span class="gen-year">2017</span></div>
          <div class="bar-track"><div class="bar-fill" data-w="86"></div></div>
          <div class="power-val">625 حصان</div>
        </div>
        <div class="bar-row">
          <div class="gen-label">G90<span class="gen-year">2024</span></div>
          <div class="bar-track"><div class="bar-fill" data-w="100"></div></div>
          <div class="power-val">727 حصان</div>
        </div>
      </div>
    </div>

    <div class="table-wrap reveal" style="margin-top:36px">
      <table>
        <thead>
          <tr>
            <th>الجيل</th>
            <th>سنة الإطلاق</th>
            <th>المحرك</th>
            <th>القوة</th>
          </tr>
        </thead>
        <tbody>
          <tr><td class="gen-code">E28</td><td>1985</td><td>3.5L سداسي الأسطوانات</td><td class="power">286 حصانًا</td></tr>
          <tr><td class="gen-code">E34</td><td>1988</td><td>3.6–3.8L سداسي الأسطوانات</td><td class="power">315–340 حصانًا</td></tr>
          <tr><td class="gen-code">E39</td><td>1998</td><td>5.0L V8</td><td class="power">400 حصان</td></tr>
          <tr><td class="gen-code">E60</td><td>2005</td><td>5.0L V10</td><td class="power">507 أحصنة</td></tr>
          <tr><td class="gen-code">F10</td><td>2011</td><td>4.4L V8 مزدوج التيربو</td><td class="power">560 حصانًا</td></tr>
          <tr><td class="gen-code">F90</td><td>2017</td><td>4.4L V8 مزدوج التيربو</td><td class="power">حتى 625 حصانًا</td></tr>
          <tr><td class="gen-code">G90</td><td>2024</td><td>V8 + محرك كهربائي (هجين PHEV)</td><td class="power">727 حصانًا</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<!-- EVALUATION -->
<section class="eval" id="evaluation">
  <div class="container">
    <div class="sec-head reveal">
      <span class="kicker"><span class="m-stripe"></span> التقييم النهائي</span>
      <h2>تقييم BMW M5</h2>
      <p>تُظهر رحلة BMW M5 كيف تطورت صناعة السيارات عبر الزمن، من المحركات التقليدية إلى المحركات التوربينية والهجينة. فيما يلي التقييم النهائي وفق خمسة محاور رئيسية.</p>
    </div>

    <div class="eval-grid reveal">
      <div class="eval-card">
        <div class="ic">⚡</div>
        <h4>الأداء</h4>
        <div class="rating">ممتاز <span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span></div>
        <p>قوة متصاعدة من 286 إلى 727 حصانًا عبر الأجيال السبعة، مع تسارع استثنائي.</p>
      </div>
      <div class="eval-card">
        <div class="ic">🎨</div>
        <h4>التصميم</h4>
        <div class="rating">مميز <span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span></div>
        <p>هوية رياضية واضحة مع تطور متواصل في الخطوط والتفاصيل بين كل جيل.</p>
      </div>
      <div class="eval-card">
        <div class="ic">🔧</div>
        <h4>التكنولوجيا</h4>
        <div class="rating">متطورة <span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span></div>
        <p>من SMG إلى M xDrive وأنظمة القيادة الهجينة القابلة للشحن.</p>
      </div>
      <div class="eval-card">
        <div class="ic">💎</div>
        <h4>الفخامة</h4>
        <div class="rating">عالية <span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span></div>
        <p>مقصورة فاخرة بمواد عالية الجودة تجمع بين الراحة والأداء الرياضي.</p>
      </div>
      <div class="eval-card">
        <div class="ic">🚀</div>
        <h4>الابتكار</h4>
        <div class="rating">مستمر <span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span></div>
        <p>أول سيدان رياضية، أول V8، أول V10، أول دفع رباعي، أول هجين في فئتها.</p>
      </div>
      <div class="eval-card">
        <div class="ic">🏆</div>
        <h4>الإرث</h4>
        <div class="rating">أيقوني <span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span><span class="dot">●</span></div>
        <p>40 عامًا من الريادة جعلت M5 المعيار الذي تُقاس به سيارات السيدان الرياضية.</p>
      </div>
    </div>

    <div class="verdict reveal">
      <h3><span class="m-stripe tall"></span> الخلاصة</h3>
      <p>BMW M5 ليست مجرد سيارة، بل <strong>قصة نجاح</strong> تجمع بين الهندسة الألمانية والسرعة والفخامة. على مدى أربعة عقود وأجيال سبعة، حافظت على هويتها الرياضية وقدّمت في كل جيل إنجازًا تقنيًا جديدًا — من المحرك السداسي الكلاسيكي إلى المنظومة الهجينة الحديثة — لتظل المرجع الذي تُقاس عليه سيارات السيدان الرياضية في العالم.</p>
    </div>
  </div>
</section>

<!-- SOURCES -->
<section class="sources" id="sources">
  <div class="container">
    <div class="sec-head reveal">
      <span class="kicker"><span class="m-stripe"></span> المصادر</span>
      <h2>المصادر والمراجع</h2>
      <p>البيانات والأرقام الواردة في هذا العرض مستندة إلى المصادر الرسمية والمراجع المعتمدة في تاريخ BMW M5.</p>
    </div>
    <ul class="src-list reveal">
      <li>
        <div class="ic">01</div>
        <div class="txt"><strong>الموقع الرسمي BMW M</strong><span>تاريخ أجيال M5 — bmw-m.com</span></div>
      </li>
      <li>
        <div class="ic">02</div>
        <div class="txt"><strong>BMW M Heritage</strong><span>تاريخ سيارات BMW M وقسم Motorsport</span></div>
      </li>
      <li>
        <div class="ic">03</div>
        <div class="txt"><strong>BMW Group</strong><span>تاريخ وتطور BMW M5 عبر الأجيال</span></div>
      </li>
    </ul>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <span class="m-stripe"></span>
  <p>تاريخ BMW M5 · رحلة عبر أربعة عقود من القوة والتطور والأداء الرياضي</p>
  <p class="disclaimer">هذا الموقع لأغراض تعليمية وتثقيفية. BMW و M5 و M علامات تجارية مملوكة لشركة BMW Group. الصور مستضافة عبر خدمة بحث الصور.</p>
</footer>

<script>
// Mobile menu
const menuBtn=document.getElementById('menuBtn');
const navLinks=document.getElementById('navLinks');
menuBtn.addEventListener('click',()=>navLinks.classList.toggle('open'));
navLinks.querySelectorAll('a').forEach(a=>a.addEventListener('click',()=>navLinks.classList.remove('open')));

// Reveal on scroll
const io=new IntersectionObserver((entries)=>{
  entries.forEach(e=>{
    if(e.isIntersecting){
      e.target.classList.add('visible');
      io.unobserve(e.target);
    }
  });
},{threshold:.12,rootMargin:'0px 0px -60px 0px'});
document.querySelectorAll('.reveal').forEach(el=>io.observe(el));

// Animate bars when chart enters viewport
const chart=document.getElementById('barChart');
const bars=document.querySelectorAll('.bar-fill');
const chartIo=new IntersectionObserver((entries)=>{
  entries.forEach(e=>{
    if(e.isIntersecting){
      bars.forEach(b=>{const w=b.dataset.w;b.style.width=w+'%';});
      chartIo.unobserve(e.target);
    }
  });
},{threshold:.3});
if(chart)chartIo.observe(chart);
// init bars at 0
bars.forEach(b=>b.style.width='0%');

// Nav shrink on scroll
const nav=document.querySelector('nav');
window.addEventListener('scroll',()=>{
  if(window.scrollY>40)nav.style.padding='0';
});
</script>
</body>
</html>
