# Portfolio — All Source Files

Everything in one place so you can copy-paste into GitHub whenever you're ready.
`resume.pdf` is binary and can't go in a markdown file — upload it separately via
**Add file → Upload files**, from `C:\Users\sachin.jha\portfolio-website\resume.pdf`.

## index.html

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sachin Jha — Cloud Native &amp; DevOps Engineer</title>
  <meta name="description" content="Portfolio of Sachin Jha — Cloud Native, Kubernetes, and DevOps engineer. KubeCon speaker, CNCF contributor, building automation for cloud infrastructure and security.">
  <meta property="og:title" content="Sachin Jha — Cloud Native & DevOps Engineer">
  <meta property="og:description" content="Kubernetes, DevOps, and cloud security engineer. KubeCon speaker, open-source contributor.">
  <meta property="og:type" content="website">
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='22' fill='%23326CE5'/%3E%3Ctext x='50' y='67' font-size='46' font-family='Arial, sans-serif' font-weight='700' fill='white' text-anchor='middle'%3ESJ%3C/text%3E%3C/svg%3E">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>

  <header class="site-header" id="top">
    <div class="container nav">
      <a href="#top" class="logo">SJ<span class="logo-dot">.</span></a>

      <nav class="nav-links" id="nav-links" aria-label="Primary">
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Projects</a>
        <a href="#speaking">Speaking</a>
        <a href="#certifications">Certifications</a>
        <a href="#contact">Contact</a>
      </nav>

      <div class="nav-actions">
        <button id="theme-toggle" class="icon-btn" type="button" aria-label="Toggle color theme" title="Toggle color theme">
          <svg class="icon icon-sun" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M4.93 4.93l1.41 1.41M17.66 17.66l1.41 1.41M2 12h2M20 12h2M6.34 17.66l-1.41 1.41M19.07 4.93l-1.41 1.41"/></svg>
          <svg class="icon icon-moon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79Z"/></svg>
        </button>
        <button id="nav-toggle" class="icon-btn nav-toggle" type="button" aria-label="Toggle menu" aria-expanded="false" aria-controls="nav-links">
          <span></span><span></span><span></span>
        </button>
      </div>
    </div>
  </header>

  <main id="main">
    <section class="hero">
      <div class="container hero-inner">
        <p class="eyebrow reveal">Hi, I'm</p>
        <h1 class="reveal">Sachin Jha</h1>
        <p class="hero-role reveal">Cloud Native &amp; DevOps Engineer</p>
        <p class="hero-bio reveal">
          B.Tech AI/ML student and Engineering Intern at Zycus, building automation for
          Kubernetes, OpenShift, and cloud security. KubeCon speaker and open-source
          contributor with the Linux Foundation's KubeEdge project, currently completing
          CKA &amp; KCNA coursework on KodeKloud.
        </p>
        <div class="hero-actions reveal">
          <a href="#projects" class="btn btn-primary">View Projects</a>
          <a href="#contact" class="btn btn-ghost">Get in Touch</a>
          <a href="resume.pdf" class="btn btn-ghost" download>Download Resume</a>
        </div>
        <div class="social-row reveal">
          <a href="#" class="social-link" data-placeholder>GitHub</a>
          <a href="#" class="social-link" data-placeholder>LinkedIn</a>
          <a href="#" class="social-link" data-placeholder>Blog</a>
          <a href="mailto:jhasachin0115@gmail.com" class="social-link">Email</a>
        </div>
      </div>
    </section>

    <section id="about" class="section">
      <div class="container">
        <h2 class="reveal"><span class="section-index">01</span>About</h2>
        <div class="about-grid reveal">
          <p>
            I'm an AI/ML undergraduate at the University of Mumbai who spends most of my time in
            Kubernetes clusters and cloud infrastructure. At Zycus, I build automation that
            replaces manual platform work — from provisioning pipelines to security tooling. I
            care about systems that are reproducible, observable, and secure by default, and I
            write and speak about what I learn along the way.
          </p>
          <div class="about-facts">
            <div class="fact">
              <span class="fact-label">Education</span>
              B.Tech, Artificial Intelligence &amp; Machine Learning<br>University of Mumbai · 2023 – Present
            </div>
            <div class="fact">
              <span class="fact-label">Based in</span>
              Mumbai, India
            </div>
            <div class="fact">
              <span class="fact-label">Focus areas</span>
              Kubernetes &amp; Cloud Security · MLOps · Edge Computing
            </div>
          </div>
        </div>

        <div class="badge-row reveal">
          <span class="badge">KubeCon Speaker</span>
          <span class="badge">AWS Cloud Essentials</span>
          <span class="badge">CNCF Contributor</span>
        </div>

        <div class="skills reveal">
          <div class="skill-group">
            <h3>Languages</h3>
            <p>Python, Go, Bash, JavaScript</p>
          </div>
          <div class="skill-group">
            <h3>Cloud &amp; DevOps</h3>
            <p>Kubernetes, OpenShift, Docker, Terraform, Jenkins, Argo CD, GitHub Actions, AWS CodeBuild</p>
          </div>
          <div class="skill-group">
            <h3>Observability &amp; Security</h3>
            <p>Prometheus, Zscaler (ZIA, ZPA, ZCC), CVE, NVD, EPSS, CVSS</p>
          </div>
          <div class="skill-group">
            <h3>AI &amp; MLOps</h3>
            <p>MCP, Kubeflow, KServe, AI Agents</p>
          </div>
          <div class="skill-group">
            <h3>Platforms &amp; Data</h3>
            <p>AWS, Linux, OpenShift, Git, Salesforce, MySQL, MongoDB</p>
          </div>
        </div>
      </div>
    </section>

    <section id="experience" class="section alt">
      <div class="container">
        <h2 class="reveal"><span class="section-index">02</span>Experience</h2>
        <div class="timeline">
          <article class="timeline-item reveal">
            <div class="timeline-marker"></div>
            <div class="timeline-content">
              <div class="timeline-head">
                <h3>Engineering Intern · Zycus</h3>
                <span class="timeline-date">Jun 2026 – Present</span>
              </div>
              <ul>
                <li>Built a production-ready Zscaler MCP Server supporting ZIA, ZPA, and ZCC, automating enterprise security information retrieval.</li>
                <li>Developed an AI-powered vulnerability scanner using CVE, NVD, EPSS, and CVSS to assess software risk and recommend secure versions.</li>
                <li>Automated OpenShift VM provisioning using Salesforce, Python, and Golden PVC templates, replacing a manual provisioning workflow.</li>
                <li>Built and deployed enterprise automation with AWS CodeBuild and ArgoCD, while contributing to AI-powered developer productivity tools.</li>
              </ul>
            </div>
          </article>

          <article class="timeline-item reveal">
            <div class="timeline-marker"></div>
            <div class="timeline-content">
              <div class="timeline-head">
                <h3>LFX Mentee · KubeEdge (The Linux Foundation)</h3>
                <span class="timeline-date">Jun 2025 – Sep 2025</span>
              </div>
              <ul>
                <li>Contributed to KubeEdge documentation, updating version-specific installation guides and troubleshooting resources.</li>
                <li>Built an ARM64 simulation architecture to validate CloudCore/EdgeCore deployments before testing on physical RK3588 hardware.</li>
                <li>Explored RK3588, AI inference, NPU workloads, and edge computing while debugging edge-cloud communication and performance.</li>
                <li>Collaborated with mentors from the Linux Foundation and the KubeEdge community.</li>
              </ul>
            </div>
          </article>

          <article class="timeline-item reveal">
            <div class="timeline-marker"></div>
            <div class="timeline-content">
              <div class="timeline-head">
                <h3>Technical Writer · Hashnode</h3>
                <span class="timeline-date">Mar 2025 – Present</span>
              </div>
              <ul>
                <li>Published technical blogs on Kubernetes, Docker, Go, and AWS.</li>
                <li>Created hands-on tutorials covering KubeEdge, K3s, and other CNCF technologies.</li>
              </ul>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="container">
        <h2 class="reveal"><span class="section-index">03</span>Projects</h2>
        <div class="project-grid">
          <article class="card project-card reveal">
            <h3>ModelForge</h3>
            <p class="project-sub">End-to-end MLOps platform with Kubeflow</p>
            <p>Automated model training, experimentation, deployment, and inference on Kubernetes. Integrates Kubeflow Pipelines, Katib, and model serving for a reproducible ML lifecycle.</p>
            <div class="tag-row">
              <span class="tag">Kubeflow</span><span class="tag">Kubernetes</span><span class="tag">Docker</span><span class="tag">Python</span>
            </div>
            <a href="#" class="card-link" data-placeholder>View on GitHub →</a>
          </article>

          <article class="card project-card reveal">
            <h3>KubeJournal</h3>
            <p class="project-sub">Kubernetes cluster log collection</p>
            <p>A Go-based utility that retrieves and centralizes node-level logs across clusters using DaemonSets, simplifying observability and debugging in distributed environments.</p>
            <div class="tag-row">
              <span class="tag">Go</span><span class="tag">Kubernetes</span><span class="tag">DaemonSets</span><span class="tag">Linux</span>
            </div>
            <a href="#" class="card-link" data-placeholder>View on GitHub →</a>
          </article>

          <article class="card project-card reveal">
            <h3>GitOps CI/CD Pipeline</h3>
            <p class="project-sub">Jenkins &amp; ArgoCD automation</p>
            <p>An end-to-end GitOps pipeline for automated Kubernetes deployments, with SonarQube analysis, Docker image builds, auto-sync, and rollback for reliable releases.</p>
            <div class="tag-row">
              <span class="tag">Jenkins</span><span class="tag">ArgoCD</span><span class="tag">Docker</span><span class="tag">SonarQube</span>
            </div>
            <a href="#" class="card-link" data-placeholder>View on GitHub →</a>
          </article>
        </div>
      </div>
    </section>

    <section id="speaking" class="section alt">
      <div class="container">
        <h2 class="reveal"><span class="section-index">04</span>Speaking &amp; Achievements</h2>
        <div class="achievement-list">
          <article class="achievement reveal">
            <h3>KubeCon + CloudNativeCon India 2026 — Speaker</h3>
            <p>"Validating RK3588 for KubeEdge: Scalable ARM64 Edge Node Simulation Without Hardware."</p>
            <a href="#" class="card-link" data-placeholder>Watch talk →</a>
          </article>
          <article class="achievement reveal">
            <h3>CNCF Thane — Speaker</h3>
            <p>Delivered a session on WebAssembly in Cloud Native Ecosystems, covering portability, performance, and secure edge computing.</p>
          </article>
          <article class="achievement reveal">
            <h3>AWS Security Acknowledgment</h3>
            <p>Reported a valid local path traversal vulnerability in AWS SAM CLI, acknowledged by the AWS Security team as part of their bug bounty program.</p>
          </article>
          <article class="achievement reveal">
            <h3>Community</h3>
            <p>Active in GDG Cloud, AWS User Groups, and CNCF meetups.</p>
          </article>
        </div>
      </div>
    </section>

    <section id="certifications" class="section">
      <div class="container">
        <h2 class="reveal"><span class="section-index">05</span>Certifications</h2>
        <div class="cert-grid">
          <a href="#" class="cert-card reveal" data-placeholder>
            <h3>CKA — Course Completed</h3>
            <p>KodeKloud</p>
          </a>
          <a href="#" class="cert-card reveal" data-placeholder>
            <h3>KCNA — Course Completed</h3>
            <p>KodeKloud</p>
          </a>
          <a href="#" class="cert-card reveal" data-placeholder>
            <h3>KubeCon + CloudNativeCon India 2026</h3>
            <p>Speaker</p>
          </a>
          <a href="#" class="cert-card reveal" data-placeholder>
            <h3>AWS Knowledge: Cloud Essentials</h3>
            <p>Amazon Web Services</p>
          </a>
        </div>
      </div>
    </section>

    <section id="contact" class="section alt">
      <div class="container contact-inner">
        <h2 class="reveal"><span class="section-index">06</span>Get in Touch</h2>
        <p class="reveal">Open to opportunities in cloud infrastructure, DevOps, and platform engineering. Reach out — I usually reply within a day.</p>
        <div class="contact-actions reveal">
          <a href="mailto:jhasachin0115@gmail.com" class="btn btn-primary">jhasachin0115@gmail.com</a>
        </div>
        <div class="social-row reveal">
          <a href="#" class="social-link" data-placeholder>GitHub</a>
          <a href="#" class="social-link" data-placeholder>LinkedIn</a>
          <a href="#" class="social-link" data-placeholder>Hashnode</a>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>&copy; <span id="year"></span> Sachin Jha. Built with HTML, CSS &amp; JavaScript.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
```

## style.css

```css
/* ---------- Design tokens ---------- */
:root {
  --bg: #0a0e17;
  --bg-elevated: #111827;
  --bg-elevated-2: #161f30;
  --text: #e5e9f0;
  --text-muted: #94a3b8;
  --accent: #5b9dff;
  --accent-strong: #3b82f6;
  --accent-contrast: #ffffff;
  --border: rgba(255, 255, 255, 0.09);
  --shadow: 0 20px 40px -20px rgba(0, 0, 0, 0.5);
  --radius: 14px;
  --font-sans: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  --font-mono: ui-monospace, SFMono-Regular, "SF Mono", Menlo, Consolas, "Liberation Mono", monospace;
  color-scheme: dark;
}

:root[data-theme="light"] {
  --bg: #f6f8fb;
  --bg-elevated: #ffffff;
  --bg-elevated-2: #eef1f6;
  --text: #0f172a;
  --text-muted: #51607a;
  --accent: #2563eb;
  --accent-strong: #1d4ed8;
  --accent-contrast: #ffffff;
  --border: rgba(15, 23, 42, 0.1);
  --shadow: 0 20px 40px -24px rgba(15, 23, 42, 0.25);
  color-scheme: light;
}

@media (prefers-color-scheme: light) {
  :root:not([data-theme="dark"]) {
    --bg: #f6f8fb;
    --bg-elevated: #ffffff;
    --bg-elevated-2: #eef1f6;
    --text: #0f172a;
    --text-muted: #51607a;
    --accent: #2563eb;
    --accent-strong: #1d4ed8;
    --accent-contrast: #ffffff;
    --border: rgba(15, 23, 42, 0.1);
    --shadow: 0 20px 40px -24px rgba(15, 23, 42, 0.25);
    color-scheme: light;
  }
}

/* ---------- Reset ---------- */
* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
  * { animation-duration: 0.001ms !important; animation-iteration-count: 1 !important; transition-duration: 0.001ms !important; }
}

body {
  margin: 0;
  background: var(--bg);
  color: var(--text);
  font-family: var(--font-sans);
  line-height: 1.6;
  -webkit-font-smoothing: antialiased;
  transition: background 0.25s ease, color 0.25s ease;
}

h1, h2, h3 { line-height: 1.2; margin: 0 0 0.5em; font-weight: 700; }
p { margin: 0 0 1em; color: var(--text-muted); }
a { color: inherit; text-decoration: none; }
ul { padding-left: 1.1em; margin: 0; color: var(--text-muted); }
li { margin-bottom: 0.5em; }
li::marker { color: var(--accent); }

.container {
  width: min(1080px, 100% - 3rem);
  margin-inline: auto;
}

.skip-link {
  position: absolute;
  left: -999px;
  top: 0;
  background: var(--accent);
  color: var(--accent-contrast);
  padding: 0.75em 1.25em;
  border-radius: 0 0 8px 0;
  z-index: 1000;
}
.skip-link:focus { left: 0; }

:focus-visible {
  outline: 2px solid var(--accent);
  outline-offset: 3px;
  border-radius: 4px;
}

/* ---------- Header ---------- */
.site-header {
  position: sticky;
  top: 0;
  z-index: 100;
  backdrop-filter: saturate(180%) blur(14px);
  background: color-mix(in srgb, var(--bg) 78%, transparent);
  border-bottom: 1px solid var(--border);
}

.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 64px;
}

.logo {
  font-weight: 800;
  font-size: 1.15rem;
  letter-spacing: 0.02em;
  font-family: var(--font-mono);
}
.logo-dot { color: var(--accent); }

.nav-links {
  display: flex;
  gap: 1.75rem;
}
.nav-links a {
  font-size: 0.92rem;
  color: var(--text-muted);
  padding: 0.4em 0;
  border-bottom: 2px solid transparent;
  transition: color 0.2s ease, border-color 0.2s ease;
}
.nav-links a:hover,
.nav-links a.active {
  color: var(--text);
  border-color: var(--accent);
}

.nav-actions { display: flex; align-items: center; gap: 0.5rem; }

.icon-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 38px;
  height: 38px;
  border-radius: 999px;
  border: 1px solid var(--border);
  background: transparent;
  color: var(--text);
  cursor: pointer;
}
.icon-btn:hover { background: var(--bg-elevated); }
.icon { width: 18px; height: 18px; }

/* default (dark): show sun, hide moon */
.icon-moon { display: none; }

/* explicit light theme */
:root[data-theme="light"] .icon-sun { display: none; }
:root[data-theme="light"] .icon-moon { display: block; }

/* system prefers light, no explicit override set */
@media (prefers-color-scheme: light) {
  :root:not([data-theme="dark"]):not([data-theme="light"]) .icon-sun { display: none; }
  :root:not([data-theme="dark"]):not([data-theme="light"]) .icon-moon { display: block; }
}

.nav-toggle { display: none; flex-direction: column; gap: 4px; padding: 9px; }
.nav-toggle span { width: 18px; height: 2px; background: var(--text); border-radius: 2px; }

/* ---------- Buttons ---------- */
.btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5em;
  padding: 0.75em 1.4em;
  border-radius: 999px;
  font-size: 0.95rem;
  font-weight: 600;
  border: 1px solid transparent;
  transition: transform 0.15s ease, background 0.2s ease, border-color 0.2s ease;
}
.btn:hover { transform: translateY(-1px); }
.btn-primary { background: var(--accent-strong); color: var(--accent-contrast); }
.btn-primary:hover { background: var(--accent); }
.btn-ghost { border-color: var(--border); color: var(--text); }
.btn-ghost:hover { border-color: var(--accent); }

/* ---------- Hero ---------- */
.hero { padding: 7rem 0 5rem; }
.hero-inner { max-width: 720px; }
.eyebrow {
  font-family: var(--font-mono);
  color: var(--accent);
  font-size: 0.95rem;
  margin-bottom: 0.75rem;
}
.hero h1 {
  font-size: clamp(2.5rem, 6vw, 4rem);
  margin-bottom: 0.2em;
}
.hero-role {
  font-size: clamp(1.1rem, 2.4vw, 1.5rem);
  color: var(--text);
  font-weight: 600;
  margin-bottom: 1em;
}
.hero-bio { font-size: 1.05rem; max-width: 60ch; }
.hero-actions { display: flex; flex-wrap: wrap; gap: 0.9rem; margin: 1.75rem 0; }

.social-row { display: flex; flex-wrap: wrap; gap: 0.6rem; }
.social-link {
  font-size: 0.85rem;
  font-family: var(--font-mono);
  padding: 0.5em 1em;
  border-radius: 999px;
  border: 1px solid var(--border);
  color: var(--text-muted);
  transition: border-color 0.2s ease, color 0.2s ease;
}
.social-link:hover { border-color: var(--accent); color: var(--text); }

/* ---------- Sections ---------- */
.section { padding: 5rem 0; }
.section.alt { background: var(--bg-elevated); }

.section h2 {
  display: flex;
  align-items: baseline;
  gap: 0.6rem;
  font-size: clamp(1.5rem, 3vw, 2rem);
  margin-bottom: 2.25rem;
}
.section-index {
  font-family: var(--font-mono);
  color: var(--accent);
  font-size: 0.9rem;
  font-weight: 600;
}

/* About */
.about-grid {
  display: grid;
  grid-template-columns: 1.4fr 1fr;
  gap: 3rem;
  margin-bottom: 2.5rem;
}
.about-grid p { font-size: 1.02rem; max-width: 62ch; }
.about-facts { display: flex; flex-direction: column; gap: 1.25rem; }
.fact { font-size: 0.95rem; color: var(--text-muted); }
.fact-label {
  display: block;
  font-family: var(--font-mono);
  font-size: 0.78rem;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: var(--accent);
  margin-bottom: 0.35em;
}

.badge-row { display: flex; flex-wrap: wrap; gap: 0.6rem; margin-bottom: 2.5rem; }
.badge {
  font-size: 0.8rem;
  font-weight: 700;
  font-family: var(--font-mono);
  padding: 0.45em 0.9em;
  border-radius: 8px;
  background: color-mix(in srgb, var(--accent) 16%, transparent);
  color: var(--accent);
  border: 1px solid color-mix(in srgb, var(--accent) 35%, transparent);
}

.skills {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.5rem;
}
.skill-group h3 { font-size: 0.95rem; margin-bottom: 0.4em; }
.skill-group p { font-size: 0.9rem; margin: 0; }

/* Timeline */
.timeline { position: relative; padding-left: 2rem; }
.timeline::before {
  content: "";
  position: absolute;
  left: 5px;
  top: 6px;
  bottom: 6px;
  width: 2px;
  background: var(--border);
}
.timeline-item { position: relative; padding-bottom: 2.75rem; }
.timeline-item:last-child { padding-bottom: 0; }
.timeline-marker {
  position: absolute;
  left: -2rem;
  top: 6px;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: var(--accent);
  box-shadow: 0 0 0 4px color-mix(in srgb, var(--accent) 20%, transparent);
}
.timeline-head {
  display: flex;
  flex-wrap: wrap;
  align-items: baseline;
  justify-content: space-between;
  gap: 0.5rem 1rem;
  margin-bottom: 0.75rem;
}
.timeline-head h3 { font-size: 1.1rem; margin: 0; }
.timeline-date {
  font-family: var(--font-mono);
  font-size: 0.82rem;
  color: var(--text-muted);
  white-space: nowrap;
}
.timeline-content ul { font-size: 0.95rem; }

/* Cards / Projects */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
}
.card {
  background: var(--bg-elevated);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 1.75rem;
  display: flex;
  flex-direction: column;
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
}
.card:hover { transform: translateY(-3px); box-shadow: var(--shadow); border-color: color-mix(in srgb, var(--accent) 40%, var(--border)); }
.card h3 { font-size: 1.1rem; margin-bottom: 0.2em; }
.project-sub { color: var(--accent); font-size: 0.85rem; font-weight: 600; margin-bottom: 0.75em; }
.card p:not(.project-sub) { font-size: 0.92rem; flex-grow: 1; }

.tag-row { display: flex; flex-wrap: wrap; gap: 0.4rem; margin: 0.5rem 0 1rem; }
.tag {
  font-size: 0.75rem;
  font-family: var(--font-mono);
  padding: 0.3em 0.65em;
  border-radius: 6px;
  background: var(--bg-elevated-2);
  color: var(--text-muted);
}

.card-link {
  font-size: 0.88rem;
  font-weight: 600;
  color: var(--accent);
  align-self: flex-start;
}
.card-link:hover { text-decoration: underline; }

/* Speaking / Achievements */
.achievement-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
}
.achievement {
  padding: 1.5rem;
  border-radius: var(--radius);
  border: 1px solid var(--border);
}
.achievement h3 { font-size: 1rem; margin-bottom: 0.4em; }
.achievement p { font-size: 0.92rem; margin-bottom: 0.6em; }

/* Certifications */
.cert-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 1.25rem;
}
.cert-card {
  display: block;
  padding: 1.5rem;
  border-radius: var(--radius);
  border: 1px solid var(--border);
  background: var(--bg-elevated);
  transition: border-color 0.2s ease, transform 0.2s ease;
}
.cert-card:hover { border-color: var(--accent); transform: translateY(-2px); }
.cert-card h3 { font-size: 0.98rem; margin-bottom: 0.3em; }
.cert-card p { font-size: 0.85rem; margin: 0; }

/* Contact */
.contact-inner { text-align: center; max-width: 640px; }
.contact-inner .section-index { display: none; }
.contact-inner h2 { justify-content: center; }
.contact-actions { margin: 1.5rem 0; display: flex; justify-content: center; }
.contact-inner .social-row { justify-content: center; }

/* Footer */
.site-footer {
  padding: 2.5rem 0;
  border-top: 1px solid var(--border);
  text-align: center;
}
.site-footer p { font-size: 0.85rem; margin: 0; }

/* ---------- Reveal-on-scroll ---------- */
.reveal {
  opacity: 0;
  transform: translateY(14px);
  transition: opacity 0.6s ease, transform 0.6s ease;
}
.reveal.in-view { opacity: 1; transform: translateY(0); }

/* ---------- Responsive ---------- */
@media (max-width: 860px) {
  .about-grid { grid-template-columns: 1fr; gap: 2rem; }
}

@media (max-width: 720px) {
  .nav-links {
    position: absolute;
    top: 64px;
    left: 0;
    right: 0;
    background: var(--bg);
    border-bottom: 1px solid var(--border);
    flex-direction: column;
    padding: 1rem 1.5rem 1.5rem;
    gap: 1rem;
    display: none;
  }
  .nav-links.open { display: flex; }
  .nav-toggle { display: flex; }
  .hero { padding: 5rem 0 3.5rem; }
  .section { padding: 3.5rem 0; }
}
```

## script.js

```javascript
(function () {
  "use strict";

  var root = document.documentElement;
  var THEME_KEY = "theme";

  // ---- Theme toggle ----
  var themeToggle = document.getElementById("theme-toggle");
  var storedTheme = localStorage.getItem(THEME_KEY);
  if (storedTheme === "light" || storedTheme === "dark") {
    root.setAttribute("data-theme", storedTheme);
  }

  function currentTheme() {
    if (root.getAttribute("data-theme") === "light") return "light";
    if (root.getAttribute("data-theme") === "dark") return "dark";
    return window.matchMedia("(prefers-color-scheme: light)").matches ? "light" : "dark";
  }

  themeToggle.addEventListener("click", function () {
    var next = currentTheme() === "light" ? "dark" : "light";
    root.setAttribute("data-theme", next);
    localStorage.setItem(THEME_KEY, next);
  });

  // ---- Mobile nav toggle ----
  var navToggle = document.getElementById("nav-toggle");
  var navLinks = document.getElementById("nav-links");

  navToggle.addEventListener("click", function () {
    var isOpen = navLinks.classList.toggle("open");
    navToggle.setAttribute("aria-expanded", String(isOpen));
  });

  navLinks.querySelectorAll("a").forEach(function (link) {
    link.addEventListener("click", function () {
      navLinks.classList.remove("open");
      navToggle.setAttribute("aria-expanded", "false");
    });
  });

  // ---- Active nav link on scroll ----
  var sections = document.querySelectorAll("main section[id]");
  var navAnchors = document.querySelectorAll(".nav-links a");

  if ("IntersectionObserver" in window && sections.length) {
    var navObserver = new IntersectionObserver(
      function (entries) {
        entries.forEach(function (entry) {
          if (!entry.isIntersecting) return;
          navAnchors.forEach(function (a) {
            a.classList.toggle("active", a.getAttribute("href") === "#" + entry.target.id);
          });
        });
      },
      { rootMargin: "-45% 0px -50% 0px" }
    );
    sections.forEach(function (section) { navObserver.observe(section); });
  }

  // ---- Reveal on scroll ----
  var revealEls = document.querySelectorAll(".reveal");
  if ("IntersectionObserver" in window && revealEls.length) {
    var revealObserver = new IntersectionObserver(
      function (entries, observer) {
        entries.forEach(function (entry) {
          if (entry.isIntersecting) {
            entry.target.classList.add("in-view");
            observer.unobserve(entry.target);
          }
        });
      },
      { threshold: 0.15 }
    );
    revealEls.forEach(function (el) { revealObserver.observe(el); });
  } else {
    revealEls.forEach(function (el) { el.classList.add("in-view"); });
  }

  // ---- Footer year ----
  var yearEl = document.getElementById("year");
  if (yearEl) yearEl.textContent = new Date().getFullYear();
})();
```

## README.md

```markdown
# Sachin Jha — Portfolio

A static portfolio site — plain HTML, CSS, and JavaScript. No build step, no framework, no dependencies.

## Files
- `index.html` — page content and structure
- `style.css` — theme, layout, responsive rules
- `script.js` — theme toggle, mobile nav, scroll-reveal, active nav highlighting
- `resume.pdf` — served by the "Download Resume" button

## Preview locally
```
python -m http.server 8080
```
Then open http://localhost:8080

## Before you go live
Search `index.html` for `data-placeholder` and swap the matching `href="#"` for your real links:
- GitHub profile
- LinkedIn profile
- Hashnode blog
- ModelForge / KubeJournal / GitOps CI/CD repo URLs
- KubeCon talk video link
- Credential links (CKA course, KCNA course, KubeCon speaker page, AWS Cloud Essentials badge)

## Hosted on Vercel
Repo: github.com/sachin21212121/portfolio-website
1. vercel.com → Sign in with GitHub → **Add New… → Project**
2. Import `portfolio-website`
3. Framework Preset: **Other** (no build step) → **Deploy**
4. Live at a `*.vercel.app` URL in under a minute; add a custom domain free under Project → Settings → Domains

## Alternative — GitHub Pages
1. Repo → **Settings → Pages → Source** → branch `main`, folder `/ (root)`
2. Live at `https://sachin21212121.github.io/portfolio-website`
```
