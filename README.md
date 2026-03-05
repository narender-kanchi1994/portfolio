<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Narender Kanchi | Cybersecurity Portfolio</title>
  <style>
    :root{--bg:#0b1220;--card:#121a2b;--text:#e6edf3;--muted:#9aa7b2;--line:#26314a;--accent:#38bdf8}
    *{box-sizing:border-box} body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial;background:linear-gradient(180deg,#070b14, var(--bg));color:var(--text)}
    a{color:var(--accent);text-decoration:none} a:hover{text-decoration:underline}
    .wrap{max-width:980px;margin:auto;padding:28px}
    header{display:flex;gap:18px;align-items:center;justify-content:space-between;flex-wrap:wrap}
    .name{font-size:28px;font-weight:800}
    .tag{color:var(--muted);margin-top:6px;line-height:1.4}
    .btns{display:flex;gap:10px;flex-wrap:wrap}
    .btn{border:1px solid var(--line);background:transparent;color:var(--text);padding:10px 14px;border-radius:12px}
    .btn.primary{background:var(--accent);color:#001018;border-color:transparent;font-weight:800}
    .grid{display:grid;grid-template-columns:repeat(12,1fr);gap:16px;margin-top:22px}
    .card{grid-column:span 12;background:rgba(18,26,43,.9);border:1px solid var(--line);border-radius:16px;padding:16px}
    .card h2{margin:0 0 10px;font-size:18px}
    .pill{display:inline-block;border:1px solid var(--line);padding:6px 10px;border-radius:999px;color:var(--muted);margin:6px 6px 0 0;font-size:13px}
    .projects{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
    .proj{border:1px solid var(--line);border-radius:14px;padding:14px;background:rgba(8,12,22,.35)}
    .proj h3{margin:0 0 6px;font-size:16px}
    .proj p{margin:0 0 10px;color:var(--muted);line-height:1.45}
    footer{margin-top:26px;color:var(--muted);font-size:13px}
    @media (max-width:820px){.projects{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div>
        <div class="name">Narender Kanchi</div>
        <div class="tag">
          Information Security / SOC Analyst (9+ yrs) • Incident Response • SIEM Engineering • Threat Hunting • SOAR • DLP • Cloud Monitoring
        </div>
      </div>
      <div class="btns">
        <a class="btn primary" href="mailto:Narender.k3833@gmail.com">Email</a>
        <a class="btn" href="https://github.com/narender-kanchi1994" target="_blank">GitHub</a>
        <a class="btn" href="https://www.linkedin.com/in/narender-kanchi" target="_blank">LinkedIn</a>
      </div>
    </header>

    <div class="grid">
      <section class="card" style="grid-column:span 7">
        <h2>Summary</h2>
        <p style="margin:0;color:var(--muted);line-height:1.6">
          SOC professional with 9+ years in 24x7 enterprise monitoring and incident response. Focused on detection engineering,
          threat hunting, and automation to reduce false positives and improve MTTD/MTTR.
        </p>
        <div style="margin-top:10px">
          <span class="pill">Splunk</span><span class="pill">Microsoft Sentinel</span><span class="pill">QRadar</span><span class="pill">ArcSight</span><span class="pill">Chronicle</span>
          <span class="pill">CrowdStrike</span><span class="pill">Defender</span><span class="pill">Elastic Security</span>
          <span class="pill">MITRE ATT&CK</span><span class="pill">NIST 800-53</span><span class="pill">ISO 27001</span>
        </div>
      </section>

      <section class="card" style="grid-column:span 5">
        <h2>Certifications</h2>
        <ul style="margin:0;padding-left:18px;color:var(--muted);line-height:1.7">
          <li>CISM (ISACA)</li>
          <li>CEH v13 (EC-Council)</li>
          <li>Certified SOC Analyst</li>
        </ul>
      </section>

      <section class="card" style="grid-column:span 12">
        <h2>Portfolio (GitHub)</h2>
        <div class="projects">
          <div class="proj">
            <h3>Detection Engineering (SIEM Rules)</h3>
            <p>Sample detections mapped to MITRE ATT&CK (Splunk SPL + Sentinel KQL templates).</p>
            <a href="https://github.com/narender-kanchi1994/cybersecurity-portfolio" target="_blank">Open</a>
          </div>
          <div class="proj">
            <h3>Incident Response Playbooks</h3>
            <p>Phishing, malware, insider threat, and ransomware response checklists + evidence collection.</p>
            <a href="https://github.com/narender-kanchi1994/cybersecurity-portfolio" target="_blank">Open</a>
          </div>
          <div class="proj">
            <h3>Threat Hunting Reports</h3>
            <p>Hunt hypotheses, telemetry sources, queries, and findings (sanitized).</p>
            <a href="https://github.com/narender-kanchi1994/cybersecurity-portfolio" target="_blank">Open</a>
          </div>
          <div class="proj">
            <h3>SOAR Automation (Templates)</h3>
            <p>Playbook logic and pseudo-workflows for triage + enrichment + containment.</p>
            <a href="https://github.com/narender-kanchi1994/cybersecurity-portfolio" target="_blank">Open</a>
          </div>
        </div>
      </section>

      <section class="card" style="grid-column:span 12">
        <h2>Contact</h2>
        <p style="margin:0;color:var(--muted)">
          Email: <a href="mailto:Narender.k3833@gmail.com">Narender.k3833@gmail.com</a> •
          LinkedIn: <a href="https://www.linkedin.com/in/narender-kanchi" target="_blank">narender-kanchi</a>
        </p>
      </section>
    </div>

    <footer>© <span id="y"></span> Narender Kanchi</footer>
  </div>
  <script>document.getElementById("y").textContent=new Date().getFullYear()</script>
</body>
</html>
