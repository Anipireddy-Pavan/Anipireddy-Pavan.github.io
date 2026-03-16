# Anipireddy-Pavan.github.io

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Pavan Anipireddy | Data Analyst & Data Scientist</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Merriweather:ital,wght@0,700;1,400&display=swap" rel="stylesheet"/>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:'Inter',sans-serif;background:#ffffff;color:#1a1a2e;font-size:15px;line-height:1.7;overflow-x:hidden}
:root{--navy:#1a1a2e;--navy2:#16213e;--blue:#0f3460;--accent:#e94560;--teal:#0a7fa3;--teal2:#e6f6fa;--gold:#f5a623;--light:#f7f8fc;--border:#e2e8f0;--text:#334155;--muted:#64748b;--radius:12px;--shadow:0 4px 20px rgba(0,0,0,0.07);--shadow-md:0 8px 40px rgba(0,0,0,0.12)}
.navbar{position:fixed;top:0;left:0;right:0;z-index:999;background:rgba(255,255,255,0.97);backdrop-filter:blur(12px);border-bottom:1px solid var(--border);height:64px;display:flex;align-items:center;justify-content:space-between;padding:0 5%}
.nb-logo{display:flex;align-items:center;gap:10px;text-decoration:none}
.nb-avatar{width:38px;height:38px;border-radius:10px;background:linear-gradient(135deg,var(--blue),var(--teal));color:#fff;font-weight:800;font-size:15px;display:flex;align-items:center;justify-content:center}
.nb-name{font-weight:700;font-size:15px;color:var(--navy)}
.nb-links{display:flex;align-items:center;gap:6px}
.nb-links a{padding:7px 16px;border-radius:8px;font-size:13px;font-weight:500;color:var(--muted);text-decoration:none;transition:all 0.2s}
.nb-links a:hover{background:var(--light);color:var(--navy)}
.nb-cta{padding:9px 20px !important;background:var(--accent) !important;color:#fff !important;font-weight:600 !important;border-radius:8px !important}
.nb-cta:hover{background:#c73652 !important}
.hero{min-height:100vh;background:linear-gradient(160deg,var(--navy) 0%,var(--navy2) 50%,var(--blue) 100%);display:flex;align-items:center;padding:100px 5% 80px;position:relative;overflow:hidden}
.hero::before{content:'';position:absolute;top:-200px;right:-200px;width:600px;height:600px;border-radius:50%;background:radial-gradient(circle,rgba(14,127,163,0.2) 0%,transparent 65%);pointer-events:none}
.hero::after{content:'';position:absolute;bottom:-100px;left:10%;width:400px;height:400px;border-radius:50%;background:radial-gradient(circle,rgba(233,69,96,0.1) 0%,transparent 65%);pointer-events:none}
.hero-inner{max-width:1200px;margin:0 auto;width:100%;display:grid;grid-template-columns:1fr 380px;gap:80px;align-items:center}
.hero-badge{display:inline-flex;align-items:center;gap:8px;background:rgba(255,255,255,0.08);border:1px solid rgba(255,255,255,0.15);color:rgba(255,255,255,0.85);font-size:12px;font-weight:600;letter-spacing:0.08em;text-transform:uppercase;padding:7px 14px;border-radius:100px;margin-bottom:24px}
.hero-badge span{width:7px;height:7px;border-radius:50%;background:#4ade80;display:inline-block;animation:blink 1.5s ease infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0.3}}
.hero-title{font-family:'Merriweather',serif;font-size:clamp(40px,5vw,66px);font-weight:700;color:#fff;line-height:1.15;letter-spacing:-1px;margin-bottom:10px}
.hero-title .accent{color:#67e8f9}
.hero-subtitle{font-size:clamp(16px,2vw,20px);font-weight:400;color:rgba(255,255,255,0.55);margin-bottom:10px;font-style:italic}
.hero-location{font-size:14px;color:rgba(255,255,255,0.45);margin-bottom:24px;display:flex;align-items:center;gap:6px}
.hero-desc{font-size:16px;font-weight:400;color:rgba(255,255,255,0.72);line-height:1.85;max-width:540px;margin-bottom:40px}
.hero-desc strong{color:#fff;font-weight:600}
.hero-btns{display:flex;gap:14px;flex-wrap:wrap;margin-bottom:52px}
.btn-primary{display:inline-flex;align-items:center;gap:8px;background:var(--accent);color:#fff;padding:13px 28px;border-radius:10px;font-size:14px;font-weight:600;text-decoration:none;transition:all 0.2s;box-shadow:0 4px 20px rgba(233,69,96,0.35)}
.btn-primary:hover{background:#c73652;transform:translateY(-2px)}
.btn-secondary{display:inline-flex;align-items:center;gap:8px;background:rgba(255,255,255,0.08);color:rgba(255,255,255,0.85);padding:13px 28px;border-radius:10px;font-size:14px;font-weight:500;text-decoration:none;border:1px solid rgba(255,255,255,0.18);transition:all 0.2s}
.btn-secondary:hover{background:rgba(255,255,255,0.15)}
.hero-stats{display:flex;gap:36px;padding-top:36px;border-top:1px solid rgba(255,255,255,0.12)}
.stat-val{font-size:30px;font-weight:800;color:#fff;line-height:1;font-family:'Merriweather',serif}
.stat-val sup{font-size:14px;color:#67e8f9}
.stat-lbl{font-size:11px;font-weight:500;color:rgba(255,255,255,0.45);letter-spacing:0.08em;text-transform:uppercase;margin-top:4px}
.hero-card{background:rgba(255,255,255,0.06);border:1px solid rgba(255,255,255,0.12);border-radius:16px;padding:32px 28px;backdrop-filter:blur(10px)}
.hc-label{font-size:10px;font-weight:700;letter-spacing:0.18em;text-transform:uppercase;color:#67e8f9;margin-bottom:22px}
.hc-skill{display:flex;align-items:center;justify-content:space-between;padding:11px 0;border-bottom:1px solid rgba(255,255,255,0.07)}
.hc-skill:last-of-type{border-bottom:none}
.hc-skill-name{font-size:13px;color:rgba(255,255,255,0.8);font-weight:400}
.hc-bar{width:110px;height:4px;background:rgba(255,255,255,0.1);border-radius:4px;overflow:hidden}
.hc-fill{height:100%;background:linear-gradient(90deg,#0a7fa3,#67e8f9);border-radius:4px}
.hc-avail{margin-top:22px;padding:14px 16px;background:rgba(74,222,128,0.08);border:1px solid rgba(74,222,128,0.2);border-radius:10px;display:flex;align-items:center;gap:10px}
.hc-avail-dot{width:9px;height:9px;border-radius:50%;background:#4ade80;flex-shrink:0;animation:blink 1.5s ease infinite}
.hc-avail-text{font-size:13px;font-weight:600;color:rgba(255,255,255,0.85)}
.hc-avail-sub{font-size:11px;color:rgba(255,255,255,0.4)}
.section{padding:88px 5%}
.section.alt{background:var(--light)}
.sec-inner{max-width:1200px;margin:0 auto}
.sec-header{text-align:center;margin-bottom:56px}
.sec-tag{display:inline-block;background:var(--teal2);color:var(--teal);font-size:11px;font-weight:700;letter-spacing:0.14em;text-transform:uppercase;padding:5px 14px;border-radius:100px;margin-bottom:14px}
.sec-title{font-family:'Merriweather',serif;font-size:clamp(26px,3.5vw,40px);font-weight:700;color:var(--navy);letter-spacing:-0.8px;line-height:1.2;margin-bottom:14px}
.sec-desc{font-size:16px;color:var(--muted);max-width:560px;margin:0 auto;line-height:1.7}
.skill-domain{background:#fff;border:1px solid var(--border);border-radius:var(--radius);padding:28px 28px 24px;box-shadow:var(--shadow);margin-bottom:20px;transition:box-shadow 0.2s}
.skill-domain:hover{box-shadow:var(--shadow-md)}
.sd-head{display:flex;align-items:center;gap:12px;margin-bottom:18px;padding-bottom:16px;border-bottom:2px solid var(--light)}
.sd-icon{width:40px;height:40px;border-radius:10px;background:linear-gradient(135deg,var(--blue),var(--teal));color:#fff;font-size:18px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.sd-title{font-size:16px;font-weight:700;color:var(--navy)}
.sd-count{margin-left:auto;font-size:11px;font-weight:600;color:var(--muted);background:var(--light);padding:3px 10px;border-radius:100px}
.tag-wrap{display:flex;flex-wrap:wrap;gap:8px}
.tag{display:inline-flex;align-items:center;gap:6px;padding:6px 13px;border-radius:8px;font-size:13px;font-weight:500;border:1.5px solid var(--border);background:#fff;color:var(--text);transition:all 0.18s;cursor:default}
.tag:hover{border-color:var(--teal);background:var(--teal2);color:var(--teal);transform:translateY(-1px)}
.tag.core{border-left:3px solid var(--teal)}.tag.advanced{border-left:3px solid var(--gold)}.tag.familiar{border-left:3px solid #cbd5e1}
.tag::before{content:'';width:6px;height:6px;border-radius:50%;flex-shrink:0}
.tag.core::before{background:var(--teal)}.tag.advanced::before{background:var(--gold)}.tag.familiar::before{background:#cbd5e1}
.skill-legend{display:flex;gap:24px;flex-wrap:wrap;margin-top:32px;padding:18px 24px;background:#fff;border:1px solid var(--border);border-radius:10px}
.leg-item{display:flex;align-items:center;gap:8px;font-size:13px;color:var(--muted)}
.leg-dot{width:10px;height:10px;border-radius:3px}
.projects-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.proj-card{background:#fff;border:1px solid var(--border);border-radius:var(--radius);overflow:hidden;display:flex;flex-direction:column;text-decoration:none;color:inherit;box-shadow:var(--shadow);transition:all 0.25s}
.proj-card:hover{transform:translateY(-5px);box-shadow:var(--shadow-md);border-color:var(--teal)}
.proj-card.wide{grid-column:span 2}
.proj-top{padding:24px 24px 0;display:flex;justify-content:space-between;align-items:flex-start}
.proj-badge{display:inline-flex;align-items:center;gap:6px;font-size:11px;font-weight:700;letter-spacing:0.1em;text-transform:uppercase;padding:5px 12px;border-radius:8px}
.b-ml{background:#e0f2fe;color:#0369a1}.b-sql{background:#fef9c3;color:#854d0e}.b-viz{background:#f3e8ff;color:#7c3aed}.b-risk{background:#fee2e2;color:#991b1b}.b-bi{background:#dcfce7;color:#166534}
.proj-link-icon{width:34px;height:34px;border-radius:8px;border:1.5px solid var(--border);background:var(--light);display:flex;align-items:center;justify-content:center;font-size:14px;color:var(--muted);transition:all 0.2s}
.proj-card:hover .proj-link-icon{background:var(--navy);border-color:var(--navy);color:#fff}
.proj-body{padding:16px 24px 24px;flex:1;display:flex;flex-direction:column}
.proj-title{font-size:17px;font-weight:700;color:var(--navy);margin-bottom:10px;line-height:1.3}
.proj-card.wide .proj-title{font-size:21px}
.proj-desc{font-size:13px;color:var(--muted);line-height:1.75;flex:1;margin-bottom:14px}
.proj-bullets{margin-bottom:16px;display:flex;flex-direction:column;gap:5px}
.proj-bullet{font-size:12px;color:var(--text);display:flex;align-items:flex-start;gap:7px}
.proj-bullet::before{content:'&#9658;';color:var(--teal);flex-shrink:0;font-size:11px;margin-top:2px}
.proj-stack{display:flex;flex-wrap:wrap;gap:6px;padding-top:14px;border-top:1px solid var(--border)}
.chip{font-size:11px;font-weight:500;color:var(--muted);background:var(--light);border:1px solid var(--border);padding:3px 10px;border-radius:6px}
.about-grid{display:grid;grid-template-columns:1.1fr 0.9fr;gap:64px;align-items:start}
.about-quote{font-family:'Merriweather',serif;font-style:italic;font-size:17px;color:var(--navy);line-height:1.65;padding:20px 24px;border-left:4px solid var(--teal);background:var(--teal2);border-radius:0 10px 10px 0;margin-bottom:28px}
.about-text{font-size:15px;color:var(--text);line-height:1.85;margin-bottom:32px}
.about-text p{margin-bottom:14px}.about-text strong{font-weight:600;color:var(--navy)}
.timeline{display:flex;flex-direction:column}
.tl-item{display:flex;gap:18px;padding-bottom:28px;position:relative}
.tl-item::before{content:'';position:absolute;left:15px;top:32px;bottom:0;width:1px;background:var(--border)}
.tl-item:last-child::before{display:none}
.tl-dot{width:32px;height:32px;border-radius:50%;background:#fff;border:2px solid var(--teal);display:flex;align-items:center;justify-content:center;flex-shrink:0;margin-top:2px}
.tl-dot-inner{width:10px;height:10px;border-radius:50%;background:var(--teal)}
.tl-date{font-size:11px;font-weight:700;letter-spacing:0.1em;text-transform:uppercase;color:var(--teal);margin-bottom:3px}
.tl-role{font-size:15px;font-weight:700;color:var(--navy);margin-bottom:2px}
.tl-org{font-size:12px;color:var(--muted);margin-bottom:6px}
.tl-desc{font-size:13px;color:var(--text);line-height:1.65}
.info-card{background:#fff;border:1px solid var(--border);border-radius:var(--radius);overflow:hidden;box-shadow:var(--shadow);margin-bottom:24px}
.info-row{display:flex;border-bottom:1px solid var(--border)}.info-row:last-child{border-bottom:none}
.ik{width:110px;flex-shrink:0;padding:13px 16px;font-size:11px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:var(--muted);background:var(--light);border-right:1px solid var(--border)}
.iv{padding:13px 16px;font-size:13px;color:var(--text)}
.iv a{color:var(--teal);text-decoration:none;font-weight:500}.iv a:hover{text-decoration:underline}
.iv.open{color:#16a34a;font-weight:600}
.cert-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.cert-card{background:#fff;border:1px solid var(--border);border-radius:10px;padding:14px 16px;box-shadow:0 2px 8px rgba(0,0,0,0.05);border-top:3px solid var(--teal)}
.cert-by{font-size:10px;font-weight:700;letter-spacing:0.1em;text-transform:uppercase;color:var(--teal);margin-bottom:5px}
.cert-name{font-size:12px;font-weight:600;color:var(--navy);line-height:1.35}
.edu-card{background:#fff;border:1px solid var(--border);border-radius:var(--radius);padding:28px 32px;box-shadow:var(--shadow);display:flex;align-items:flex-start;gap:24px}
.edu-icon{width:52px;height:52px;border-radius:12px;background:linear-gradient(135deg,var(--blue),var(--teal));color:#fff;font-size:22px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.edu-degree{font-size:17px;font-weight:700;color:var(--navy);margin-bottom:4px}
.edu-field{font-size:14px;font-weight:600;color:var(--teal);margin-bottom:4px}
.edu-inst{font-size:13px;color:var(--muted);margin-bottom:4px}
.edu-meta{display:flex;gap:16px;flex-wrap:wrap;margin-top:8px}
.edu-pill{font-size:12px;font-weight:500;background:var(--light);border:1px solid var(--border);color:var(--text);padding:4px 12px;border-radius:100px}
.contact-section{background:linear-gradient(160deg,var(--navy) 0%,var(--blue) 100%);padding:88px 5%}
.contact-inner{max-width:1200px;margin:0 auto}
.contact-inner .sec-tag{background:rgba(103,232,249,0.12);color:#67e8f9}
.contact-inner .sec-title{color:#fff}
.contact-inner .sec-desc{color:rgba(255,255,255,0.5)}
.contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:40px}
.clink-list{display:flex;flex-direction:column;gap:12px}
.clink{display:flex;align-items:center;gap:16px;background:rgba(255,255,255,0.06);border:1px solid rgba(255,255,255,0.1);border-radius:12px;padding:18px 20px;text-decoration:none;color:inherit;transition:all 0.2s}
.clink:hover{background:rgba(255,255,255,0.1);border-color:rgba(103,232,249,0.3);transform:translateX(4px)}
.clink-icon{width:44px;height:44px;border-radius:10px;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-size:20px}
.ci-gh{background:#24292e}.ci-li{background:#0077b5}.ci-mail{background:var(--accent)}.ci-web{background:var(--teal)}.ci-ph{background:#16a34a}
.clink-type{font-size:10px;font-weight:700;letter-spacing:0.14em;text-transform:uppercase;color:rgba(255,255,255,0.4);margin-bottom:3px}
.clink-val{font-size:14px;font-weight:600;color:rgba(255,255,255,0.9)}
.clink-arrow{margin-left:auto;font-size:16px;color:rgba(255,255,255,0.25);transition:all 0.2s}
.clink:hover .clink-arrow{color:#67e8f9;transform:translateX(3px)}
.contact-msg{font-family:'Merriweather',serif;font-size:28px;font-weight:700;color:#fff;line-height:1.3;letter-spacing:-0.5px;margin-bottom:16px}
.contact-msg em{font-style:italic;color:#67e8f9}
.contact-sub{font-size:15px;color:rgba(255,255,255,0.5);line-height:1.75;margin-bottom:32px}
.quick-info{background:rgba(255,255,255,0.05);border:1px solid rgba(255,255,255,0.1);border-radius:12px;overflow:hidden}
.qi-row{display:flex;justify-content:space-between;align-items:center;padding:14px 20px;border-bottom:1px solid rgba(255,255,255,0.06);font-size:13px}
.qi-row:last-child{border-bottom:none}
.qi-key{color:rgba(255,255,255,0.4);font-weight:500}
.qi-val{color:rgba(255,255,255,0.85);font-weight:600}
.qi-val.green{color:#4ade80}
footer{background:#0d0d1a;padding:24px 5%;display:flex;justify-content:space-between;align-items:center;border-top:1px solid rgba(255,255,255,0.05)}
footer span{font-size:12px;color:rgba(255,255,255,0.25)}
.fade{opacity:0;transform:translateY(24px);transition:opacity 0.65s ease,transform 0.65s ease}
.fade.in{opacity:1;transform:none}
@media(max-width:1024px){.hero-inner{grid-template-columns:1fr}.hero-card{display:none}.projects-grid{grid-template-columns:1fr 1fr}.proj-card.wide{grid-column:span 2}.about-grid{grid-template-columns:1fr;gap:40px}.contact-grid{grid-template-columns:1fr}}
@media(max-width:768px){.nb-links{display:none}.projects-grid{grid-template-columns:1fr}.proj-card.wide{grid-column:span 1}.cert-grid{grid-template-columns:1fr}.contact-msg{font-size:22px}footer{flex-direction:column;gap:6px;text-align:center}}
</style>
</head>
<body>

<nav class="navbar">
  <a href="#" class="nb-logo">
    <div class="nb-avatar">PA</div>
    <span class="nb-name">Pavan Anipireddy</span>
  </a>
  <div class="nb-links">
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#contact" class="nb-cta">Hire Me</a>
  </div>
</nav>

<section class="hero">
  <div class="hero-inner">
    <div class="hero-left">
      <div class="hero-badge"><span></span> Available for Opportunities</div>
      <h1 class="hero-title">Pavan<br><span class="accent">Anipireddy</span></h1>
      <p class="hero-subtitle">Data Analyst &amp; Data Scientist</p>
      <p class="hero-location">&#128205; Bengaluru, India &nbsp;|&nbsp; &#128222; +91 93987 99207</p>
      <p class="hero-desc">
        <strong>B.Tech in Computer Science</strong> with hands-on expertise in Python, SQL, Machine Learning, and Power BI. Trained at <strong>360 Digi TMG, Bengaluru</strong> following the CRISP-ML methodology. Passionate about turning raw data into actionable insights through end-to-end ML pipelines and clear data storytelling.
      </p>
      <div class="hero-btns">
        <a href="#projects" class="btn-primary">View Projects &#8595;</a>
        <a href="https://github.com/Anipireddy-Pavan" target="_blank" class="btn-secondary">GitHub Profile &#8599;</a>
      </div>
      <div class="hero-stats">
        <div><div class="stat-val">3<sup>+</sup></div><div class="stat-lbl">Projects</div></div>
        <div><div class="stat-val">0.93</div><div class="stat-lbl">R&sup2; Score</div></div>
        <div><div class="stat-val">10k<sup>+</sup></div><div class="stat-lbl">Records Analysed</div></div>
      </div>
    </div>
    <div class="hero-card">
      <div class="hc-label">&#9889; Core Proficiency</div>
      <div class="hc-skill"><span class="hc-skill-name">Python &amp; Pandas</span><div class="hc-bar"><div class="hc-fill" style="width:92%"></div></div></div>
      <div class="hc-skill"><span class="hc-skill-name">SQL (MySQL)</span><div class="hc-bar"><div class="hc-fill" style="width:90%"></div></div></div>
      <div class="hc-skill"><span class="hc-skill-name">Machine Learning</span><div class="hc-bar"><div class="hc-fill" style="width:85%"></div></div></div>
      <div class="hc-skill"><span class="hc-skill-name">Power BI &amp; DAX</span><div class="hc-bar"><div class="hc-fill" style="width:88%"></div></div></div>
      <div class="hc-skill"><span class="hc-skill-name">Tableau</span><div class="hc-bar"><div class="hc-fill" style="width:82%"></div></div></div>
      <div class="hc-skill"><span class="hc-skill-name">Statistics &amp; EDA</span><div class="hc-bar"><div class="hc-fill" style="width:87%"></div></div></div>
      <div class="hc-skill"><span class="hc-skill-name">Time Series / ARIMA</span><div class="hc-bar"><div class="hc-fill" style="width:85%"></div></div></div>
      <div class="hc-skill"><span class="hc-skill-name">Advanced Excel</span><div class="hc-bar"><div class="hc-fill" style="width:88%"></div></div></div>
      <div class="hc-avail">
        <div class="hc-avail-dot"></div>
        <div><div class="hc-avail-text">Open to Work</div><div class="hc-avail-sub">Full-time &middot; Remote &middot; Contract</div></div>
      </div>
    </div>
  </div>
</section>

<section class="section alt" id="skills">
  <div class="sec-inner">
    <div class="sec-header fade">
      <div class="sec-tag">01 &mdash; Skills</div>
      <h2 class="sec-title">Technical Skills &amp; Tools</h2>
      <p class="sec-desc">Full toolkit across Data Analytics and Data Science &mdash; directly from CV and training.</p>
    </div>
    <div class="skill-domain fade">
      <div class="sd-head"><div class="sd-icon">{}</div><div class="sd-title">Programming &amp; Querying</div><div class="sd-count">6 skills</div></div>
      <div class="tag-wrap">
        <span class="tag core">Python</span><span class="tag core">SQL</span><span class="tag core">MySQL</span><span class="tag core">Pandas</span><span class="tag core">NumPy</span><span class="tag core">Scikit-learn</span>
      </div>
    </div>
    <div class="skill-domain fade">
      <div class="sd-head"><div class="sd-icon">&#128202;</div><div class="sd-title">BI &amp; Visualisation Tools</div><div class="sd-count">10 skills</div></div>
      <div class="tag-wrap">
        <span class="tag core">Power BI</span><span class="tag core">DAX</span><span class="tag core">Power Query</span><span class="tag core">Tableau</span><span class="tag core">Advanced Excel</span><span class="tag core">Pivot Tables</span><span class="tag core">VLOOKUP</span><span class="tag core">Google Sheets</span><span class="tag core">KPI Tracking</span><span class="tag core">Dashboard Design</span>
      </div>
    </div>
    <div class="skill-domain fade">
      <div class="sd-head"><div class="sd-icon">&#128300;</div><div class="sd-title">Data Visualisation Libraries</div><div class="sd-count">4 skills</div></div>
      <div class="tag-wrap">
        <span class="tag core">Matplotlib</span><span class="tag core">Seaborn</span><span class="tag advanced">Plotly</span><span class="tag advanced">Jupyter Notebook</span>
      </div>
    </div>
    <div class="skill-domain fade">
      <div class="sd-head"><div class="sd-icon">&#129302;</div><div class="sd-title">Machine Learning &amp; AI</div><div class="sd-count">12 skills</div></div>
      <div class="tag-wrap">
        <span class="tag core">Scikit-learn</span><span class="tag core">Regression (Linear &amp; Logistic)</span><span class="tag core">Classification</span><span class="tag core">Clustering</span><span class="tag core">Feature Engineering</span><span class="tag core">Model Evaluation</span><span class="tag advanced">Hyperparameter Tuning</span><span class="tag advanced">Cross-Validation</span><span class="tag advanced">Ensemble Methods</span><span class="tag advanced">Pipeline Construction</span><span class="tag advanced">SMOTE (Imbalanced Data)</span><span class="tag familiar">Deep Learning (Basics)</span>
      </div>
    </div>
    <div class="skill-domain fade">
      <div class="sd-head"><div class="sd-icon">&#128200;</div><div class="sd-title">Analytics &amp; Statistics</div><div class="sd-count">14 skills</div></div>
      <div class="tag-wrap">
        <span class="tag core">Exploratory Data Analysis (EDA)</span><span class="tag core">Data Cleaning &amp; Wrangling</span><span class="tag core">Feature Engineering</span><span class="tag core">Statistical Analysis</span><span class="tag core">Hypothesis Testing</span><span class="tag core">A/B Testing</span><span class="tag core">Regression Analysis</span><span class="tag core">Time Series Analysis</span><span class="tag core">ARIMA / Forecasting</span><span class="tag core">Customer Segmentation</span><span class="tag core">KPI Reporting</span><span class="tag core">ETL Pipelines</span><span class="tag core">Trend Analysis</span><span class="tag core">Performance Analysis</span>
      </div>
    </div>
    <div class="skill-domain fade">
      <div class="sd-head"><div class="sd-icon">&#128451;</div><div class="sd-title">SQL &amp; Database Skills</div><div class="sd-count">8 skills</div></div>
      <div class="tag-wrap">
        <span class="tag core">MySQL</span><span class="tag core">Complex JOINs</span><span class="tag core">CTEs</span><span class="tag core">Subqueries</span><span class="tag core">Window Functions</span><span class="tag core">Multi-table Joins</span><span class="tag core">Query Optimisation</span><span class="tag advanced">Database Design</span>
      </div>
    </div>
    <div class="skill-domain fade">
      <div class="sd-head"><div class="sd-icon">&#128295;</div><div class="sd-title">Tools &amp; Workflow</div><div class="sd-count">6 skills</div></div>
      <div class="tag-wrap">
        <span class="tag core">Jupyter Notebook</span><span class="tag core">Git &amp; GitHub</span><span class="tag core">Google Colab</span><span class="tag core">VS Code</span><span class="tag core">MS Excel (Advanced)</span><span class="tag familiar">Automation (Excel/BI)</span>
      </div>
    </div>
    <div class="skill-domain fade">
      <div class="sd-head"><div class="sd-icon">&#128161;</div><div class="sd-title">Soft Skills &amp; Business</div><div class="sd-count">9 skills</div></div>
      <div class="tag-wrap">
        <span class="tag core">Analytical Thinking</span><span class="tag core">Data Storytelling</span><span class="tag core">Problem Solving</span><span class="tag core">Attention to Detail</span><span class="tag core">Communication &amp; Presentation</span><span class="tag core">Team Collaboration</span><span class="tag core">Business Analysis</span><span class="tag core">Documentation</span><span class="tag advanced">CRISP-ML Methodology</span>
      </div>
    </div>
    <div class="skill-legend fade">
      <div class="leg-item"><div class="leg-dot" style="background:var(--teal)"></div> Core / Strong</div>
      <div class="leg-item"><div class="leg-dot" style="background:var(--gold)"></div> Advanced / Growing</div>
      <div class="leg-item"><div class="leg-dot" style="background:#cbd5e1"></div> Familiar / Exposure</div>
    </div>
  </div>
</section>

<section class="section" id="projects">
  <div class="sec-inner">
    <div class="sec-header fade">
      <div class="sec-tag">02 &mdash; Projects</div>
      <h2 class="sec-title">Featured Projects</h2>
      <p class="sec-desc">Completed at 360 Digi TMG, Bengaluru (2024&ndash;2025) using CRISP-ML methodology.</p>
    </div>
    <div class="projects-grid">

      <a href="https://github.com/Anipireddy-Pavan/Coal_Price_Forecasting" target="_blank" class="proj-card wide fade">
        <div class="proj-top"><div class="proj-badge b-ml">ML &middot; Time Series &middot; Forecasting</div><div class="proj-link-icon">&#8599;</div></div>
        <div class="proj-body">
          <div class="proj-title">Coal Price Forecasting</div>
          <p class="proj-desc">End-to-end time series forecasting on 4+ years of coal price data. Benchmarked ARIMA and regression models with interactive Power BI dashboards for business decision-making.</p>
          <div class="proj-bullets">
            <div class="proj-bullet">Analysed 4+ years of data &mdash; detected seasonal trends, market cycles, and price volatility</div>
            <div class="proj-bullet">Engineered lag features and rolling averages &mdash; improved model accuracy by 18%</div>
            <div class="proj-bullet">Achieved R&sup2; score of 0.93 using ARIMA and linear regression models</div>
            <div class="proj-bullet">Designed Power BI dashboards to visualise forecasts and risk indicators</div>
          </div>
          <div class="proj-stack"><span class="chip">Python</span><span class="chip">Pandas</span><span class="chip">NumPy</span><span class="chip">Scikit-learn</span><span class="chip">ARIMA</span><span class="chip">Power BI</span><span class="chip">SQL</span></div>
        </div>
      </a>

      <a href="https://github.com/Anipireddy-Pavan/Retail_Sales_Analysis" target="_blank" class="proj-card fade">
        <div class="proj-top"><div class="proj-badge b-viz">EDA &middot; Retail Analytics</div><div class="proj-link-icon">&#8599;</div></div>
        <div class="proj-body">
          <div class="proj-title">Retail Sales Analysis</div>
          <p class="proj-desc">In-depth EDA on 10,000+ retail transaction records uncovering sales trends, customer behaviour, and seasonal demand.</p>
          <div class="proj-bullets">
            <div class="proj-bullet">Identified top 5 revenue-generating categories &mdash; improved stakeholder clarity by 20%</div>
            <div class="proj-bullet">Created 12 visualisations (heatmaps, bar charts, trend lines)</div>
            <div class="proj-bullet">Actionable recommendations on restocking and promotional timing</div>
          </div>
          <div class="proj-stack"><span class="chip">Python</span><span class="chip">Pandas</span><span class="chip">Matplotlib</span><span class="chip">Seaborn</span></div>
        </div>
      </a>

      <a href="https://github.com/Anipireddy-Pavan/Job_Market_Analysis_SQL" target="_blank" class="proj-card wide fade">
        <div class="proj-top"><div class="proj-badge b-sql">SQL &middot; Business Intelligence &middot; Data Mining</div><div class="proj-link-icon">&#8599;</div></div>
        <div class="proj-body">
          <div class="proj-title">Job Market Analysis (SQL)</div>
          <p class="proj-desc">Mined and analysed 10,000+ job market records to extract skill demand trends, salary benchmarks, and geographic segmentation. Built a semantic layer for self-serve stakeholder analytics.</p>
          <div class="proj-bullets">
            <div class="proj-bullet">Standardised business metrics across 10,000+ records &mdash; skill demand, salary benchmarks, geo segmentation</div>
            <div class="proj-bullet">Optimised SQL queries using CTEs, subqueries, multi-table joins &mdash; improved efficiency by 25%</div>
            <div class="proj-bullet">Built segmentation reports for independent self-serve analytics</div>
            <div class="proj-bullet">Translated business questions into structured analytical models</div>
          </div>
          <div class="proj-stack"><span class="chip">SQL</span><span class="chip">MySQL</span><span class="chip">CTEs</span><span class="chip">Subqueries</span><span class="chip">Window Functions</span><span class="chip">Excel</span></div>
        </div>
      </a>

      <a href="https://github.com/Anipireddy-Pavan/Customer_Behavior_Analysis" target="_blank" class="proj-card fade">
        <div class="proj-top"><div class="proj-badge b-viz">ML &middot; Customer Analytics</div><div class="proj-link-icon">&#8599;</div></div>
        <div class="proj-body">
          <div class="proj-title">Customer Behavior Analysis</div>
          <p class="proj-desc">RFM analysis and K-Means clustering to segment customers and identify retention opportunities.</p>
          <div class="proj-bullets">
            <div class="proj-bullet">RFM segmentation &amp; customer scoring</div>
            <div class="proj-bullet">K-Means cluster profiling for targeted marketing</div>
          </div>
          <div class="proj-stack"><span class="chip">Python</span><span class="chip">Scikit-learn</span><span class="chip">K-Means</span><span class="chip">Seaborn</span></div>
        </div>
      </a>

      <a href="https://github.com/Anipireddy-Pavan/Sales_Dashboard" target="_blank" class="proj-card fade">
        <div class="proj-top"><div class="proj-badge b-bi">Power BI &middot; Dashboard</div><div class="proj-link-icon">&#8599;</div></div>
        <div class="proj-body">
          <div class="proj-title">Sales Performance Dashboard</div>
          <p class="proj-desc">Interactive Power BI dashboard with KPI cards, regional breakdowns, and YoY trend comparisons using DAX.</p>
          <div class="proj-bullets">
            <div class="proj-bullet">Dynamic DAX measures for KPI tracking</div>
            <div class="proj-bullet">Drill-through pages &amp; interactive slicers</div>
          </div>
          <div class="proj-stack"><span class="chip">Power BI</span><span class="chip">DAX</span><span class="chip">Power Query</span><span class="chip">Excel</span></div>
        </div>
      </a>

      <a href="https://github.com/Anipireddy-Pavan/Credit_risk_data_analysis" target="_blank" class="proj-card fade">
        <div class="proj-top"><div class="proj-badge b-risk">ML &middot; Risk Analytics</div><div class="proj-link-icon">&#8599;</div></div>
        <div class="proj-body">
          <div class="proj-title">Credit Risk Analysis</div>
          <p class="proj-desc">Financial risk analysis on borrower profiles and default probabilities using classification models.</p>
          <div class="proj-bullets">
            <div class="proj-bullet">Borrower segmentation &amp; risk-tier classification</div>
            <div class="proj-bullet">ROC-AUC &amp; full model evaluation metrics</div>
          </div>
          <div class="proj-stack"><span class="chip">Python</span><span class="chip">Logistic Regression</span><span class="chip">Pandas</span><span class="chip">Seaborn</span></div>
        </div>
      </a>

    </div>
  </div>
</section>

<section class="section alt" id="about">
  <div class="sec-inner">
    <div class="sec-header fade">
      <div class="sec-tag">03 &mdash; About Me</div>
      <h2 class="sec-title">Who I Am</h2>
    </div>
    <div class="about-grid">
      <div class="fade">
        <div class="about-quote">"Passionate about turning raw data into actionable insights through end-to-end ML pipelines, feature engineering, and data-driven storytelling."</div>
        <div class="about-text">
          <p>I'm <strong>Pavan Anipireddy</strong>, a Data Analyst and Data Scientist based in <strong>Bengaluru, India</strong>. I hold a <strong>B.Tech in Computer Science Engineering</strong> from Chaitanya Bharathi Institute of Technology (CGPA: 7.6/10).</p>
          <p>I completed specialised training in <strong>Data Science with AI at 360 Digi TMG, Bengaluru (2024&ndash;2025)</strong>, implementing projects independently using the <strong>CRISP-ML methodology</strong>.</p>
          <p>My core strengths lie in <strong>SQL, Python, Power BI, and Machine Learning</strong> &mdash; focused on data cleaning, EDA, forecasting, and building dashboards that drive faster, smarter decisions.</p>
        </div>
        <div class="timeline">
          <div class="tl-item">
            <div class="tl-dot"><div class="tl-dot-inner"></div></div>
            <div>
              <div class="tl-date">2024 &ndash; 2025</div>
              <div class="tl-role">Data Science with AI Training</div>
              <div class="tl-org">360 Digi TMG, Bengaluru</div>
              <div class="tl-desc">Intensive training covering ML, time series, EDA, SQL analytics, and data visualisation using CRISP-ML methodology.</div>
            </div>
          </div>
          <div class="tl-item">
            <div class="tl-dot"><div class="tl-dot-inner"></div></div>
            <div>
              <div class="tl-date">2020 &ndash; 2024</div>
              <div class="tl-role">Bachelor of Technology &mdash; CSE</div>
              <div class="tl-org">Chaitanya Bharathi Institute of Technology, Proddatur, AP</div>
              <div class="tl-desc">Graduated with CGPA 7.6/10. Core studies in Computer Science, Mathematics, Statistics, and Programming.</div>
            </div>
          </div>
        </div>
      </div>
      <div class="fade">
        <div class="info-card">
          <div class="info-row"><div class="ik">Name</div><div class="iv">Pavan Anipireddy</div></div>
          <div class="info-row"><div class="ik">Role</div><div class="iv">Data Analyst / Data Scientist</div></div>
          <div class="info-row"><div class="ik">Location</div><div class="iv">Bengaluru, India</div></div>
          <div class="info-row"><div class="ik">Phone</div><div class="iv"><a href="tel:+919398799207">+91 93987 99207</a></div></div>
          <div class="info-row"><div class="ik">Email</div><div class="iv"><a href="mailto:anipireddypavan@gmail.com">anipireddypavan@gmail.com</a></div></div>
          <div class="info-row"><div class="ik">LinkedIn</div><div class="iv"><a href="https://www.linkedin.com/in/pavan-anipireddy" target="_blank">pavan-anipireddy &#8599;</a></div></div>
          <div class="info-row"><div class="ik">GitHub</div><div class="iv"><a href="https://github.com/Anipireddy-Pavan" target="_blank">Anipireddy-Pavan &#8599;</a></div></div>
          <div class="info-row"><div class="ik">Status</div><div class="iv open">&#9679; Open to Opportunities</div></div>
        </div>
        <div style="font-size:12px;font-weight:700;letter-spacing:0.1em;text-transform:uppercase;color:var(--muted);margin-bottom:12px;">Certifications</div>
        <div class="cert-grid">
          <div class="cert-card"><div class="cert-by">360 Digi TMG &middot; 2024&ndash;25</div><div class="cert-name">Data Science with Artificial Intelligence</div></div>
          <div class="cert-card"><div class="cert-by">Deloitte &middot; Forage &middot; 2025</div><div class="cert-name">Data Analytics Virtual Experience</div></div>
          <div class="cert-card"><div class="cert-by">Power BI &middot; 2024</div><div class="cert-name">BI Professional Certificate</div></div>
          <div class="cert-card"><div class="cert-by">GitHub Portfolio</div><div class="cert-name">3+ Live Data Science Projects</div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section" id="education">
  <div class="sec-inner">
    <div class="sec-header fade">
      <div class="sec-tag">04 &mdash; Education &amp; Training</div>
      <h2 class="sec-title">Academic Background</h2>
    </div>
    <div style="display:flex;flex-direction:column;gap:20px;">
      <div class="edu-card fade">
        <div class="edu-icon">&#127891;</div>
        <div>
          <div class="edu-degree">Bachelor of Technology</div>
          <div class="edu-field">Computer Science Engineering</div>
          <div class="edu-inst">Chaitanya Bharathi Institute of Technology, Proddatur, Andhra Pradesh</div>
          <div class="edu-meta"><span class="edu-pill">2020 &ndash; 2024</span><span class="edu-pill">CGPA: 7.6 / 10</span></div>
        </div>
      </div>
      <div class="edu-card fade">
        <div class="edu-icon">&#129302;</div>
        <div>
          <div class="edu-degree">Data Science with Artificial Intelligence</div>
          <div class="edu-field">Professional Training Program</div>
          <div class="edu-inst">360 Digi TMG, Bengaluru</div>
          <div class="edu-meta"><span class="edu-pill">2024 &ndash; 2025</span><span class="edu-pill">CRISP-ML Methodology</span><span class="edu-pill">3 Major Projects</span></div>
        </div>
      </div>
      <div class="edu-card fade">
        <div class="edu-icon">&#128196;</div>
        <div>
          <div class="edu-degree">Deloitte Data Analytics Virtual Experience</div>
          <div class="edu-field">Industry Certification</div>
          <div class="edu-inst">Deloitte via Forage Platform</div>
          <div class="edu-meta"><span class="edu-pill">2025</span><span class="edu-pill">Industry Recognised</span></div>
        </div>
      </div>
      <div class="edu-card fade">
        <div class="edu-icon">&#128202;</div>
        <div>
          <div class="edu-degree">Power BI Business Intelligence Professional</div>
          <div class="edu-field">Professional Certification</div>
          <div class="edu-inst">Power BI Certification</div>
          <div class="edu-meta"><span class="edu-pill">2024</span><span class="edu-pill">DAX &middot; Power Query &middot; Dashboards</span></div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="contact-section" id="contact">
  <div class="contact-inner">
    <div class="sec-header fade">
      <div class="sec-tag">05 &mdash; Contact</div>
      <h2 class="sec-title">Let's Connect</h2>
      <p class="sec-desc">Open to full-time Data Analyst and Data Scientist roles. Let's talk!</p>
    </div>
    <div class="contact-grid fade">
      <div class="clink-list">
        <a href="mailto:anipireddypavan@gmail.com" class="clink">
          <div class="clink-icon ci-mail">&#9993;</div>
          <div class="clink-info"><div class="clink-type">Email</div><div class="clink-val">anipireddypavan@gmail.com</div></div>
          <div class="clink-arrow">&#8594;</div>
        </a>
        <a href="tel:+919398799207" class="clink">
          <div class="clink-icon ci-ph">&#128222;</div>
          <div class="clink-info"><div class="clink-type">Phone</div><div class="clink-val">+91 93987 99207</div></div>
          <div class="clink-arrow">&#8594;</div>
        </a>
        <a href="https://www.linkedin.com/in/pavan-anipireddy" target="_blank" class="clink">
          <div class="clink-icon ci-li">&#128188;</div>
          <div class="clink-info"><div class="clink-type">LinkedIn</div><div class="clink-val">linkedin.com/in/pavan-anipireddy</div></div>
          <div class="clink-arrow">&#8594;</div>
        </a>
        <a href="https://github.com/Anipireddy-Pavan" target="_blank" class="clink">
          <div class="clink-icon ci-gh">&#128025;</div>
          <div class="clink-info"><div class="clink-type">GitHub</div><div class="clink-val">github.com/Anipireddy-Pavan</div></div>
          <div class="clink-arrow">&#8594;</div>
        </a>
        <a href="https://anipireddy-pavan.github.io" target="_blank" class="clink">
          <div class="clink-icon ci-web">&#127760;</div>
          <div class="clink-info"><div class="clink-type">Portfolio</div><div class="clink-val">anipireddy-pavan.github.io</div></div>
          <div class="clink-arrow">&#8594;</div>
        </a>
      </div>
      <div>
        <h3 class="contact-msg">Ready to turn your data into <em>decisions</em>.</h3>
        <p class="contact-sub">Actively seeking full-time roles in Data Analytics and Data Science. Whether you have a project in mind or want to connect &mdash; my inbox is always open.</p>
        <div class="quick-info">
          <div class="qi-row"><span class="qi-key">Availability</span><span class="qi-val green">&#9679; Immediate</span></div>
          <div class="qi-row"><span class="qi-key">Preferred Role</span><span class="qi-val">Data Analyst / Data Scientist</span></div>
          <div class="qi-row"><span class="qi-key">Work Mode</span><span class="qi-val">Remote &middot; Hybrid &middot; On-site</span></div>
          <div class="qi-row"><span class="qi-key">Location</span><span class="qi-val">Bengaluru &middot; Open to Relocate</span></div>
          <div class="qi-row"><span class="qi-key">Training</span><span class="qi-val">360 Digi TMG, Bengaluru</span></div>
          <div class="qi-row"><span class="qi-key">Response</span><span class="qi-val">Within 24 hours</span></div>
        </div>
      </div>
    </div>
  </div>
</section>

<footer>
  <span>&#169; 2025 Pavan Anipireddy &mdash; Data Analyst &amp; Data Scientist &middot; Bengaluru, India</span>
  <span>anipireddypavan@gmail.com &middot; +91 93987 99207</span>
</footer>

<script>
const obs = new IntersectionObserver(entries => {
  entries.forEach(e => { if(e.isIntersecting) e.target.classList.add('in'); });
}, { threshold: 0.08, rootMargin: '0px 0px -30px 0px' });
document.querySelectorAll('.fade').forEach((el, i) => {
  el.style.transitionDelay = (i % 4) * 80 + 'ms';
  obs.observe(el);
});
</script>
</body>
</html>
