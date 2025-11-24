<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sourov Hossen — Cybersecurity Student & Web Security Specialist</title>
  <meta name="description" content="Sourov Hossen — Computer Science student focused on web security, recon tooling and ML-powered intrusion detection."/>

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <!-- Minimal, self-contained styles -->
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#94a3b8; --accent:#06b6d4; --glass: rgba(255,255,255,0.03);
      --radius:14px; --mono: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{font-family:var(--mono);background:linear-gradient(180deg,#071021 0%, #071827 60%);color:#e6eef6;margin:0;line-height:1.5}
    a{color:var(--accent);text-decoration:none}
    .wrap{max-width:1100px;margin:40px auto;padding:28px}

    header{display:flex;gap:20px;align-items:center}
    .avatar{width:120px;height:120px;border-radius:18px;flex:0 0 120px;background:linear-gradient(135deg,#06202a,#0b1220);display:grid;place-items:center;font-weight:700;font-size:28px;color:var(--accent);border:1px solid rgba(255,255,255,0.04)}
    h1{margin:0;font-size:28px}
    .sub{color:var(--muted);margin-top:6px}

    .grid{display:grid;grid-template-columns:1fr 360px;gap:28px;margin-top:28px}
    .card{background:var(--card);padding:20px;border-radius:var(--radius);box-shadow:0 6px 20px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}

    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .pill{background:var(--glass);padding:8px 12px;border-radius:999px;font-size:13px;color:var(--muted);border:1px solid rgba(255,255,255,0.02)}

    .project{margin-bottom:14px;padding-bottom:12px;border-bottom:1px dashed rgba(255,255,255,0.03)}
    .project:last-child{border-bottom:none}
    .project h4{margin:0 0 6px 0;font-size:15px}
    .meta{color:var(--muted);font-size:13px}

    .cta{display:flex;gap:10px;margin-top:12px}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#3b82f6);color:#022; font-weight:700}

    aside .small{color:var(--muted);font-size:13px}
    .stats{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-top:12px}
    .stat{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:12px;border-radius:10px}

    footer{color:var(--muted);text-align:center;margin-top:28px;font-size:13px}

    @media (max-width:980px){.grid{grid-template-columns:1fr}.avatar{width:88px;height:88px;font-size:20px}}
  </style>
</head>
<body>
  <main class="wrap">
    <header>
      <div class="avatar">SH</div>
      <div>
        <h1>Sourov Hossen</h1>
        <div class="sub">Computer Science student — focused on web security, recon tooling and ML-powered intrusion detection</div>
        <div class="cta">
          <a class="btn" href="https://www.linkedin.com/in/sourov-hossen-307655351" target="_blank" rel="noopener">LinkedIn</a>
          <a class="btn" href="https://shii9.github.io/Portfolio/" target="_blank" rel="noopener">Portfolio</a>
        </div>
      </div>
    </header>

    <div class="grid">
      <section>
        <div class="card">
          <h3>About</h3>
          <p style="color:var(--muted);margin-top:8px">I break systems to understand how they behave underneath. Right now I’m focused on web application security: finding logic flaws, hardening APIs, and building tooling that makes recon and triage faster.
          </p>

          <h3 style="margin-top:18px">Core skills</h3>
          <div class="skills" style="margin-top:10px">
            <span class="pill">Web App Security (OWASP)</span>
            <span class="pill">Recon & OSINT</span>
            <span class="pill">Python</span>
            <span class="pill">JavaScript</span>
            <span class="pill">C++</span>
            <span class="pill">Network Security</span>
            <span class="pill">Exploit Dev</span>
            <span class="pill">Reverse Engineering</span>
            <span class="pill">Machine Learning (IDS)</span>
            <span class="pill">Go (Recon tooling)</span>
          </div>

          <h3 style="margin-top:18px">Selected projects</h3>

          <div class="project">
            <h4>ReconSuite — Go-based recon framework</h4>
            <div class="meta">Modular CLI for passive & active recon: DNS, certificates, subdomain discovery, HTTP analysis. Built for scale and chaining tools.</div>
            <div style="margin-top:8px"><a href="#">View repo</a> · <span class="meta">Go • CLI • Automation</span></div>
          </div>

          <div class="project">
            <h4>AI-Powered NIDS (Network IDS)</h4>
            <div class="meta">Research project: feature extraction from PCAP, ML model for anomaly detection, real-time packet sniffing and Flask API for alerts.</div>
            <div style="margin-top:8px"><a href="#">View report</a> · <span class="meta">Python • scikit-learn • Flask</span></div>
          </div>

          <div class="project">
            <h4>Custom Recon Python Toolkit</h4>
            <div class="meta">DNS lookups, zone transfer checks, subdomain brute force, certificate scraping and HTTP header analysis — automated into a single utility.</div>
            <div style="margin-top:8px"><a href="#">View repo</a> · <span class="meta">Python • Requests • asyncio</span></div>
          </div>

          <div class="project">
            <h4>Smart Door System (IoT)</h4>
            <div class="meta">ESP32 + RFID + PIR sensor. Proof-of-concept for secure embedded access control with local logging.</div>
            <div style="margin-top:8px"><a href="#">View notes</a> · <span class="meta">Arduino • ESP32 • Embedded</span></div>
          </div>

          <h3 style="margin-top:18px">Education & roles</h3>
          <p class="meta">Computer Science student. Focused coursework: operating system security, algorithms, networks. Active in security research and defensive tooling.</p>

        </div>

        <div class="card" style="margin-top:18px">
          <h3>How I work</h3>
          <ul style="color:var(--muted);margin-top:8px">
            <li>Start with data: logs, PCAPs, headers. Reproduce before assuming.</li>
            <li>Automate repetitive recon tasks so time goes where reasoning matters.</li>
            <li>Document steps and artifacts for repeatable triage and reporting.</li>
            <li>Build minimally viable proof-of-concept exploits to demonstrate impact — then focus on remediation guidance.</li>
          </ul>
        </div>

      </section>

      <aside>
        <div class="card">
          <h3>Contact</h3>
          <p class="small" style="margin-top:8px">Best way to reach me: <br><a href="https://www.linkedin.com/in/sourov-hossen-307655351" target="_blank" rel="noopener">LinkedIn — Sourov Hossen</a></p>

          <h3 style="margin-top:14px">Quick stats</h3>
          <div class="stats">
            <div class="stat">
              <div style="font-size:18px;font-weight:700">Student</div>
              <div class="small">Computer Science</div>
            </div>
            <div class="stat">
              <div style="font-size:18px;font-weight:700">Focus</div>
              <div class="small">Web Security & Recon</div>
            </div>
          </div>

          <h3 style="margin-top:14px">Links</h3>
          <p class="small" style="margin-top:8px">
            Portfolio: <a href="https://shii9.github.io/Portfolio/" target="_blank" rel="noopener">shii9.github.io/Portfolio</a><br>
            LinkedIn: <a href="https://www.linkedin.com/in/sourov-hossen-307655351" target="_blank" rel="noopener">/in/sourov-hossen-307655351</a>
            <br>GitHub: <a href="https://github.com/shii9" target="_blank" rel="noopener">github.com/shii9</a> (replace with your username if different)
          </p>

        </div>

        <div class="card" style="margin-top:18px">
          <h3>Want to collaborate?</h3>
          <p class="small" style="margin-top:8px">Open to bug-bounty collabs, recon tool integrations, and research projects on ML-based detection. Ping me on LinkedIn.</p>
        </div>
      </aside>
    </div>

    <footer>
      <div>Made with clarity — sourov hossen · Computer Science student · focused on web security</div>
    </footer>
  </main>

  <!-- Small script: add smooth in-page scrolling if needed -->
  <script>
    // placeholder for future interactive features
    (function(){
      // no-op for now
    })();
  </script>
</body>
</html>
