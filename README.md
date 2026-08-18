<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohlalefi Joshua Motsima — IT Support &amp; Systems Specialist</title>
  <meta name="description" content="Portfolio of Mohlalefi Joshua Motsima — IT Support & Systems Specialist, Automation & Infrastructure, based in Alberton, South Africa.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <link rel="icon" href="/favicon.ico">
  <meta name="theme-color" content="#08080b">
  <link rel="canonical" href="https://mjmotsima.github.io/">
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Mohlalefi Joshua Motsima",
    "url": "https://mjmotsima.github.io/",
    "sameAs": [
      "https://github.com/mjmotsima",
      "https://www.linkedin.com/in/your-profile"
    ],
    "email": "mailto:mohlalefi.motsima@gmail.com",
    "telephone": "+27742719819",
    "jobTitle": "IT Support & Systems Specialist",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Alberton",
      "addressRegion": "Gauteng",
      "addressCountry": "South Africa"
    }
  }
  </script>
  <style>
    :root{
      --bg:#08080b;
      --bg-panel:#111116;
      --card:#16161d;
      --card-border:#232330;
      --text:#f2f2f0;
      --text-dim:#9a9aa6;
      --text-faint:#5c5c66;
      --purple:#8b5cf6;
      --magenta:#d946ef;
      --cyan:#22d3ee;
      --gradient:linear-gradient(90deg,var(--purple),var(--magenta),var(--cyan));
    }
    *{box-sizing:border-box; margin:0; padding:0;}
    html{scroll-behavior:smooth;}
    body{
      background:var(--bg);
      color:var(--text);
      font-family:'Inter',sans-serif;
      line-height:1.6;
      -webkit-font-smoothing:antialiased;
      position:relative;
    }
    h1,h2,h3{ font-family:'Space Grotesk',sans-serif; letter-spacing:-0.01em; }
    .mono{ font-family:'JetBrains Mono',monospace; }
    a{ color:inherit; }
    .wrap{ max-width:920px; margin:0 auto; padding:0 28px; }

    /* Skip link */
    .skip-link{
      position:absolute;
      left:-999px;
      top:auto;
      width:1px;
      height:1px;
      overflow:hidden;
    }
    .skip-link:focus{
      left:16px;
      top:16px;
      width:auto;
      height:auto;
      background:#fff;
      color:#000;
      padding:8px 12px;
      z-index:1000;
      border-radius:6px;
      text-decoration:none;
    }

    /* ---------- nav ---------- */
    nav{
      position:sticky; top:0; z-index:50;
      background:rgba(8,8,11,0.85);
      backdrop-filter:blur(10px);
      border-bottom:1px solid var(--card-border);
    }
    nav .wrap{ display:flex; align-items:center; justify-content:space-between; padding:16px 28px; }
    .brand{ font-family:'Space Grotesk',sans-serif; font-weight:700; font-size:15px; letter-spacing:0.02em; }
    .brand span{ background:var(--gradient); -webkit-background-clip:text; background-clip:text; color:transparent; }
    .navlinks{ display:flex; gap:26px; font-size:13px; color:var(--text-dim); }
    .navlinks a{ text-decoration:none; transition:color .2s; }
    .navlinks a:hover{ color:var(--text); }
    .nav-toggle{
      display:none;
      background:transparent;
      border:1px solid rgba(255,255,255,0.06);
      color:var(--text);
      padding:6px 10px;
      border-radius:8px;
      font-size:18px;
    }
    @media (max-width:640px){
      .nav-toggle{ display:block; }
      .navlinks{ display:none; flex-direction:column; gap:12px; background:rgba(8,8,11,0.95); padding:12px; position:absolute; right:28px; top:64px; border-radius:8px; border:1px solid var(--card-border); }
      .navlinks a{ display:block; padding:6px 8px; }
    }

    /* ---------- hero ---------- */
    header.hero{ padding:96px 0 80px; position:relative; overflow:hidden; }
    header.hero::before{
      content:"";
      position:absolute; top:-200px; right:-200px;
      width:500px; height:500px; border-radius:50%;
      background:radial-gradient(circle, rgba(139,92,246,0.18), transparent 70%);
      pointer-events:none;
    }
    .eyebrow{
      font-family:'JetBrains Mono',monospace;
      font-size:12px;
      color:var(--cyan);
      letter-spacing:0.12em;
      text-transform:uppercase;
      margin-bottom:18px;
      display:flex; align-items:center; gap:10px;
    }
    .eyebrow::before{
      content:""; width:8px; height:8px; border-radius:50%;
      background:var(--cyan); box-shadow:0 0 10px var(--cyan);
    }
    h1.name{ font-size:clamp(34px,6vw,56px); font-weight:700; line-height:1.05; margin-bottom:14px; }
    .role{
      font-size:clamp(16px,2.4vw,20px);
      color:var(--text-dim);
      margin-bottom:26px;
      font-weight:500;
    }
    .role .accent{ background:var(--gradient); -webkit-background-clip:text; background-clip:text; color:transparent; font-weight:600; }
    .lede{ max-width:600px; color:var(--text-dim); font-size:15.5px; margin-bottom:34px; }
    .contact-row{ display:flex; flex-wrap:wrap; gap:14px 22px; font-size:13.5px; color:var(--text-dim); }
    .contact-row a{ text-decoration:none; }
    .contact-row a:hover{ color:var(--cyan); }
    .contact-row .dot{ color:var(--text-faint); }

    /* ---------- section shell ---------- */
    section{ padding:64px 0; border-top:1px solid var(--card-border); }
    .section-head{ display:flex; align-items:baseline; gap:14px; margin-bottom:38px; }
    .section-num{ font-family:'JetBrains Mono',monospace; font-size:13px; color:var(--purple); }
    h2.section-title{ font-size:clamp(22px,3vw,28px); font-weight:600; }

    /* ---------- about ---------- */
    .about-grid{ display:grid; grid-template-columns:1.4fr 1fr; gap:40px; }
    @media (max-width:720px){ .about-grid{ grid-template-columns:1fr; } }
    .about-grid p{ color:var(--text-dim); margin-bottom:16px; font-size:15px; }
    .about-grid p strong{ color:var(--text); font-weight:600; }
    .fact-list{ display:flex; flex-direction:column; gap:14px; }
    .fact{
      background:var(--card); border:1px solid var(--card-border);
      border-radius:10px; padding:14px 16px;
    }
    .fact .k{ font-family:'JetBrains Mono',monospace; font-size:11px; color:var(--text-faint); text-transform:uppercase; letter-spacing:.08em; margin-bottom:4px; }
    .fact .v{ font-size:14px; color:var(--text); }

    /* ---------- languages ---------- */
    .chips{ display:flex; flex-wrap:wrap; gap:10px; margin-top:8px; }
    .chip{
      font-family:'JetBrains Mono',monospace;
      font-size:12px;
      padding:7px 13px;
      border-radius:100px;
      border:1px solid var(--card-border);
      color:var(--text-dim);
      background:var(--card);
    }
    .chip.strong{ color:var(--cyan); border-color:rgba(34,211,238,0.35); }

    /* ---------- timeline (circuit trace signature) ---------- */
    .timeline{ position:relative; padding-left:34px; }
    .timeline::before{
      content:"";
      position:absolute; left:6px; top:6px; bottom:6px; width:2px;
      background:linear-gradient(to bottom, var(--purple), var(--magenta) 50%, var(--cyan));
      opacity:0.5;
    }
    .titem{ position:relative; padding-bottom:38px; }
    .titem:last-child{ padding-bottom:0; }
    .titem::before{
      content:""; position:absolute; left:-34px; top:4px;
      width:12px; height:12px; border-radius:50%;
      background:var(--bg); border:2px solid var(--cyan);
      box-shadow:0 0 0 4px var(--bg), 0 0 12px rgba(34,211,238,0.5);
    }
    .titem .when{ font-family:'JetBrains Mono',monospace; font-size:12px; color:var(--cyan); margin-bottom:6px; }
    .titem .role-title{ font-size:16.5px; font-weight:600; margin-bottom:2px; }
    .titem .org{ font-size:13.5px; color:var(--text-dim); margin-bottom:10px; }
    .titem .desc{ font-size:14px; color:var(--text-dim); max-width:600px; }

    /* ---------- cert grid ---------- */
    .cert-grid{ display:grid; grid-template-columns:repeat(auto-fill,minmax(240px,1fr)); gap:14px; }
    .cert-card{
      background:var(--card); border:1px solid var(--card-border);
      border-radius:12px; padding:18px 18px 16px;
      position:relative; overflow:hidden;
    }
    .cert-card::after{
      content:""; position:absolute; top:0; left:0; right:0; height:2px;
      background:var(--gradient); opacity:0.6;
    }
    .cert-card .cname{ font-weight:600; font-size:14.5px; margin-bottom:4px; }
    .cert-card .cmeta{ font-family:'JetBrains Mono',monospace; font-size:11.5px; color:var(--text-faint); }

    /* ---------- venture card ---------- */
    .venture{
      background:linear-gradient(135deg, rgba(139,92,246,0.08), rgba(34,211,238,0.05));
      border:1px solid var(--card-border);
      border-radius:16px;
      padding:32px;
    }
    .venture h3{ font-size:19px; margin-bottom:8px; }
    .venture p{ color:var(--text-dim); font-size:14.5px; max-width:560px; margin-bottom:14px; }
    .venture .contact-row{ font-size:13px; }

    /* ---------- footer ---------- */
    footer{ padding:56px 0 80px; border-top:1px solid var(--card-border); }
    footer .wrap{ display:flex; flex-direction:column; gap:18px; align-items:flex-start; }
    footer .cta{ font-size:20px; font-weight:600; font-family:'Space Grotesk',sans-serif; }
    footer .cta span{ background:var(--gradient); -webkit-background-clip:text; background-clip:text; color:transparent; }
    footer .foot-meta{ font-size:12.5px; color:var(--text-faint); font-family:'JetBrains Mono',monospace; }

    ::selection{ background:var(--purple); color:#fff; }
  </style>
</head>
<body>

  <a class="skip-link" href="#main-content">Skip to content</a>

  <nav role="navigation" aria-label="Primary">
    <div class="wrap">
      <div class="brand">MJ<span>·</span>MOTSIMA</div>

      <button id="nav-toggle" aria-controls="navlinks" aria-expanded="false" aria-label="Toggle navigation" class="nav-toggle">
        ☰
      </button>

      <div id="navlinks" class="navlinks">
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#certifications">Certifications</a>
        <a href="#venture">MJ Smart Solutions</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </nav>

  <header class="hero">
    <div class="wrap">
      <div class="eyebrow">Available for opportunities</div>
      <h1 class="name">Mohlalefi Joshua Motsima</h1>
      <div class="role">IT Support &amp; Systems Specialist <span class="accent">— Automation &amp; Infrastructure</span></div>
      <p class="lede">Systems support professional merging ICT with automation — keeping networks, backups, and telemetry running reliably, based in Alberton, Gauteng, South Africa.</p>
      <div class="contact-row">
        <a href="mailto:mohlalefi.motsima@gmail.com">mohlalefi.motsima@gmail.com</a>
        <span class="dot">·</span>
        <a href="tel:+27742719819">+27 74 271 9819</a>
        <span class="dot">·</span>
        <span>Alberton, Gauteng, South Africa</span>
      </div>
    </div>
  </header>

  <main id="main-content" role="main" tabindex="-1">
    <section id="about">
      <div class="wrap">
        <div class="section-head"><span class="section-num mono">01</span><h2 class="section-title">About</h2></div>
        <div class="about-grid">
          <div>
            <p>I'm a <strong>final-year BCom Information Science student at UNISA</strong>, specializing in Information Management and Technical Architecture, and a <strong>Systems Support Learner</strong> on the MICT SETA &amp; Cloud Smiths programme. My work bridges ICT and automation — from help desk and network support to SCADA, PLC programming, and telemetry systems that keep operations running with minimal downtime.</p>
            <p>I hold <strong>CompTIA A+, Network+, IT Fundamentals+, IT Operations Specialist</strong> and <strong>ICDL</strong> certifications, plus hands-on <strong>AIX administration</strong> training. My background spans hospitals, government, retail, and renewable energy — each role sharpening the same core skill: keeping systems available and people supported.</p>
            <p>Outside of employed roles, I run my own consultation business, <strong>MJ Smart Solutions</strong>, and I'm currently completing my <strong>Code 14 driving licence</strong> to widen how I can support clients on-site.</p>
          </div>
          <div class="fact-list">
            <div class="fact"><div class="k">Location</div><div class="v">Alberton, Gauteng, South Africa</div></div>
            <div class="fact"><div class="k">Education</div><div class="v">BCom Information Science, UNISA (final year)</div></div>
            <div class="fact"><div class="k">Currently</div><div class="v">Systems Support Learnership, MICT SETA &amp; Cloud Smiths (since May 2026)</div></div>
            <div class="fact"><div class="k">Seeking</div><div class="v">Systems/IT Support, Help Desk, or Junior Systems Administrator roles</div></div>
            <div class="fact">
              <div class="k">Languages</div>
              <div class="chips">
                <span class="chip strong">Zulu</span>
                <span class="chip strong">Southern Sotho</span>
                <span class="chip">Tsonga</span>
                <span class="chip">Sepedi</span>
                <span class="chip">Swati</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="experience">
      <div class="wrap">
        <div class="section-head"><span class="section-num mono">02</span><h2 class="section-title">Experience</h2></div>
        <div class="timeline">

          <div class="titem">
            <div class="when">MAY 2026 — PRESENT</div>
            <div class="role-title">Systems Support Learner</div>
            <div class="org">MICT SETA &amp; Cloud Smiths, hosted at Sake Energy Solutions</div>
            <div class="desc">Tier 1/2 helpdesk, network and infrastructure support, SCADA (HMI, alarms, tag/database configuration), PLC programming under supervision, FAT support, and internal software development and testing at a renewable energy IPP.</div>
          </div>

          <div class="titem">
            <div class="when">NOV 2025 — APR 2026</div>
            <div class="role-title">AIX Administration Training</div>
            <div class="org">Tec Tight Enterprises</div>
            <div class="desc">Hands-on AIX systems administration training.</div>
          </div>

          <div class="titem">
            <div class="when">AUG — OCT 2025</div>
            <div class="role-title">Systems Support Skills Programme</div>
            <div class="org">Dynamic DNA</div>
            <div class="desc">Systems support learnership sponsored by Singular Systems and MICT SETA; earned NQF Level 5 in Systems Support.</div>
          </div>

          <div class="titem">
            <div class="when">SEP 2024 — FEB 2025</div>
            <div class="role-title">IT Technician Intern</div>
            <div class="org">My Runway Warehouse</div>
            <div class="desc">On-site IT technical support and troubleshooting.</div>
          </div>

          <div class="titem">
            <div class="when">FEB — APR 2022</div>
            <div class="role-title">Technical Support Assistant</div>
            <div class="org">Statistics South Africa</div>
            <div class="desc">Technical support for government statistical operations.</div>
          </div>

          <div class="titem">
            <div class="when">OCT 2020 — SEP 2021</div>
            <div class="role-title">ICT Help Desk Intern</div>
            <div class="org">Gauteng Dept. of Health — Bertha Gxowa Hospital</div>
            <div class="desc">Resolved a multi-department connectivity outage by diagnosing and fixing a DHCP misconfiguration.</div>
          </div>

          <div class="titem">
            <div class="when">JUN 2019 — SEP 2020</div>
            <div class="role-title">Cisco ITE Facilitator</div>
            <div class="org">City of Ekurhuleni</div>
            <div class="desc">Facilitated Cisco IT Essentials training.</div>
          </div>

          <div class="titem">
            <div class="when">2016 — 2019</div>
            <div class="role-title">ICT Trainer</div>
            <div class="org">Thokoza Progressive Youth</div>
            <div class="desc">Taught foundational ICT skills to young people in the community.</div>
          </div>

        </div>
      </div>
    </section>

    <section id="certifications">
      <div class="wrap">
        <div class="section-head"><span class="section-num mono">03</span><h2 class="section-title">Certifications &amp; Education</h2></div>
        <div class="cert-grid">
          <div class="cert-card"><div class="cname">CompTIA A+</div><div class="cmeta">2018</div></div>
          <div class="cert-card"><div class="cname">CompTIA Network+</div><div class="cmeta">2019</div></div>
          <div class="cert-card"><div class="cname">IT Operations Specialist</div><div class="cmeta">2019</div></div>
          <div class="cert-card"><div class="cname">IT Fundamentals+</div><div class="cmeta">2019</div></div>
          <div class="cert-card"><div class="cname">IT Fundamentals</div><div class="cmeta">2017</div></div>
          <div class="cert-card"><div class="cname">ICDL</div><div class="cmeta">2017</div></div>
          <div class="cert-card"><div class="cname">NQF Level 5, Systems Support</div><div class="cmeta">Dynamic DNA, 2025</div></div>
          <div class="cert-card"><div class="cname">AI Fundamentals</div><div class="cmeta">NetCampus Group / Gauteng Province, 2026</div></div>
          <div class="cert-card"><div class="cname">Cybersecurity Fundamentals</div><div class="cmeta">NetCampus Group / Gauteng Province, 2026</div></div>
          <div class="cert-card"><div class="cname">Data Analytics Fundamentals</div><div class="cmeta">NetCampus Group / Gauteng Province, 2026</div></div>
          <div class="cert-card"><div class="cname">Renewable Energy Skills Programme</div><div class="cmeta">Mentec Foundation, 2022</div></div>
          <div class="cert-card"><div class="cname">National Senior Certificate</div><div class="cmeta">Lethukuthula Secondary School, 2012</div></div>
          <div class="cert-card"><div class="cname">BCom Information Science</div><div class="cmeta">UNISA — final year, in progress</div></div>
        </div>
      </div>
    </section>

    <section id="venture">
      <div class="wrap">
        <div class="section-head"><span class="section-num mono">04</span><h2 class="section-title">MJ Smart Solutions</h2></div>
        <div class="venture">
          <h3>My own IT consultation business</h3>
          <p>Launched in 2026 and based in Alberton, MJ Smart Solutions is where I take on independent systems support and consultation work alongside my learnership and studies.</p>
          <div class="contact-row">
            <a href="mailto:mjsmartsolutionz@gmail.com">mjsmartsolutionz@gmail.com</a>
            <span class="dot">·</span>
            <a href="tel:+27742719819">+27 74 271 9819</a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer id="contact">
    <div class="wrap">
      <div class="cta">Let's build something <span>reliable</span>.</div>
      <div class="contact-row">
        <a href="mailto:mohlalefi.motsima@gmail.com">mohlalefi.motsima@gmail.com</a>
        <span class="dot">·</span>
        <a href="tel:+27742719819">+27 74 271 9819</a>
        <span class="dot">·</span>
        <span>Alberton, Gauteng, South Africa</span>
      </div>
      <div class="foot-meta">© 2026 MOHLALEFI J. MOTSIMA</div>
    </div>
  </footer>

  <script>
    (function(){
      var btn = document.getElementById('nav-toggle');
      var links = document.getElementById('navlinks');
      if (!btn || !links) return;
      // Keep initial state consistent
      links.style.display = window.innerWidth <= 640 ? 'none' : 'flex';
      btn.setAttribute('aria-expanded', 'false');

      btn.addEventListener('click', function(){
        var expanded = btn.getAttribute('aria-expanded') === 'true';
        btn.setAttribute('aria-expanded', String(!expanded));
        if (expanded) {
          links.style.display = 'none';
        } else {
          links.style.display = 'flex';
        }
      });

      // close nav when clicking outside (mobile)
      document.addEventListener('click', function(e){
        if (window.getComputedStyle(btn).display === 'none') return;
        if (!links.contains(e.target) && !btn.contains(e.target)) {
          links.style.display = 'none';
          btn.setAttribute('aria-expanded','false');
        }
      });

      // ensure nav visibility updates on resize
      window.addEventListener('resize', function(){
        if (window.innerWidth > 640) {
          links.style.display = 'flex';
          btn.setAttribute('aria-expanded','false');
        } else {
          links.style.display = 'none';
          btn.setAttribute('aria-expanded','false');
        }
      });
    })();
  </script>

</body>
</html>
