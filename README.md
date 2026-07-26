# Sachin Jha — Portfolio Website (Complete Source)

## index.html

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sachin Jha — Cloud Native &amp; DevOps Engineer</title>
  <meta name="description" content="Portfolio of Sachin Jha — Cloud Native, Kubernetes, and DevOps engineer. KubeCon speaker, open-source contributor, building automation for cloud infrastructure and security.">
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='22' fill='%2358a6ff'/%3E%3Ctext x='50' y='67' font-size='46' font-family='monospace' font-weight='700' fill='%230d1117' text-anchor='middle'%3ESJ%3C/text%3E%3C/svg%3E">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>

  <header class="site-header" id="top">
    <div class="container nav">
      <a href="#top" class="logo"><span class="prompt-sym">$</span> sachin<span class="logo-dot">.</span>jha</a>

      <nav class="nav-links" id="nav-links" aria-label="Primary">
        <a href="#about">~/about</a>
        <a href="#experience">~/experience</a>
        <a href="#projects">~/projects</a>
        <a href="#speaking">~/speaking</a>
        <a href="#certifications">~/certs</a>
        <a href="#contact">~/contact</a>
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
        <div class="terminal-window reveal">
          <div class="terminal-bar">
            <span class="dot dot-red"></span><span class="dot dot-yellow"></span><span class="dot dot-green"></span>
            <span class="terminal-title">sachin@zycus:~</span>
          </div>
          <div class="terminal-body">
            <p><span class="prompt">sachin@zycus:~$</span> whoami</p>
            <p class="term-out term-name" id="typed-name"></p>
            <p><span class="prompt">sachin@zycus:~$</span> cat role.txt</p>
            <p class="term-out">Cloud Native &amp; DevOps Engineer</p>
            <p><span class="prompt">sachin@zycus:~$</span> cat mission.md</p>
            <p class="term-out term-bio">B.Tech AI/ML student and Engineering Intern at Zycus — working<br>daily across Linux systems, Kubernetes, and container<br>orchestration, with hands-on edge computing experience<br>from the KubeEdge project.</p>
            <p class="term-cursor-line"><span class="prompt">sachin@zycus:~$</span> <span class="cursor">▌</span></p>
          </div>
        </div>

        <div class="identity-badges reveal">
          <span class="id-badge">Open Source Contributor</span>
          <span class="id-badge">KubeCon Speaker</span>
          <span class="id-badge">Linux &amp; Containers</span>
          <span class="id-badge">Edge Computing</span>
          <span class="id-badge">LFX Mentee</span>
          <span class="id-badge">Zycus Intern</span>
          <span class="id-badge">AWS Bug Bounty</span>
          <span class="id-badge">Kubeflow Volunteer</span>
        </div>

        <div class="hero-actions reveal">
          <a href="#projects" class="btn btn-primary">View Projects</a>
          <a href="#contact" class="btn btn-ghost">Get in Touch</a>
          <a href="Sachin_Resume.pdf" class="btn btn-ghost" download>Download Resume</a>
        </div>
        <div class="social-row reveal">
          <a href="https://github.com/sachin21212121" class="social-link">GitHub</a>
          <a href="https://www.linkedin.com/in/sachinjhadev/" class="social-link">LinkedIn</a>
          <a href="https://hashnode.com/@Sachinjha09" class="social-link">Blog</a>
          <a href="mailto:jhasachin0115@gmail.com" class="social-link">Email</a>
        </div>
      </div>
    </section>

    <section id="about" class="section">
      <div class="container">
        <h2 class="reveal"><span class="section-index">01</span>about</h2>
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
              <span class="fact-label">education</span>
              B.Tech, Artificial Intelligence &amp; Machine Learning<br>University of Mumbai · 2023 – Present
            </div>
            <div class="fact">
              <span class="fact-label">based_in</span>
              Mumbai, India
            </div>
            <div class="fact">
              <span class="fact-label">focus</span>
              Kubernetes &amp; Cloud Security · MLOps · Edge Computing
            </div>
          </div>
        </div>

        <svg class="k8s-edge-diagram reveal" viewBox="0 0 500 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Diagram of a Kubernetes control plane orchestrating containerized pods and extending to edge nodes">
          <line x1="250" y1="130" x2="90" y2="60" stroke="var(--border)" stroke-width="2" stroke-dasharray="4 4"/>
          <line x1="250" y1="130" x2="250" y2="40" stroke="var(--border)" stroke-width="2" stroke-dasharray="4 4"/>
          <line x1="250" y1="130" x2="410" y2="60" stroke="var(--border)" stroke-width="2" stroke-dasharray="4 4"/>
          <line x1="250" y1="130" x2="90" y2="210" stroke="var(--border)" stroke-width="2" stroke-dasharray="4 4"/>
          <line x1="250" y1="130" x2="410" y2="210" stroke="var(--border)" stroke-width="2" stroke-dasharray="4 4"/>

          <polygon points="250,90 285,110 285,150 250,170 215,150 215,110" fill="var(--bg-elevated-2)" stroke="var(--accent)" stroke-width="2"/>
          <text x="250" y="134" text-anchor="middle" font-size="11" fill="var(--accent)" font-family="var(--font-mono)">k8s</text>

          <rect x="60" y="35" width="60" height="40" rx="6" fill="var(--bg-elevated)" stroke="var(--green)" stroke-width="1.5"/>
          <text x="90" y="59" text-anchor="middle" font-size="10" fill="var(--green)" font-family="var(--font-mono)">pod</text>

          <rect x="220" y="10" width="60" height="40" rx="6" fill="var(--bg-elevated)" stroke="var(--green)" stroke-width="1.5"/>
          <text x="250" y="34" text-anchor="middle" font-size="10" fill="var(--green)" font-family="var(--font-mono)">pod</text>

          <rect x="380" y="35" width="60" height="40" rx="6" fill="var(--bg-elevated)" stroke="var(--green)" stroke-width="1.5"/>
          <text x="410" y="59" text-anchor="middle" font-size="10" fill="var(--green)" font-family="var(--font-mono)">pod</text>

          <rect x="55" y="190" width="70" height="40" rx="6" fill="var(--bg-elevated)" stroke="var(--purple)" stroke-width="1.5"/>
          <text x="90" y="214" text-anchor="middle" font-size="9" fill="var(--purple)" font-family="var(--font-mono)">edge</text>

          <rect x="375" y="190" width="70" height="40" rx="6" fill="var(--bg-elevated)" stroke="var(--purple)" stroke-width="1.5"/>
          <text x="410" y="214" text-anchor="middle" font-size="9" fill="var(--purple)" font-family="var(--font-mono)">edge</text>
        </svg>

        <div class="skill-badges reveal">
          <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" loading="lazy">
          <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" loading="lazy">
          <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" loading="lazy">
          <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" loading="lazy">
          <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" loading="lazy">
          <img src="https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white" alt="OpenShift" loading="lazy">
          <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" loading="lazy">
          <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" loading="lazy">
          <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins" loading="lazy">
          <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="Argo CD" loading="lazy">
          <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" loading="lazy">
          <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" loading="lazy">
          <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" loading="lazy">
          <img src="https://img.shields.io/badge/Kubeflow-3E60F5?style=for-the-badge&logo=kubeflow&logoColor=white" alt="Kubeflow" loading="lazy">
          <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" loading="lazy">
          <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" loading="lazy">
          <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" loading="lazy">
        </div>

        <div class="gh-stats-grid reveal">
          <img class="gh-stat-img" src="https://github-readme-stats.vercel.app/api?username=sachin21212121&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117" alt="Sachin's GitHub stats" loading="lazy">
          <img class="gh-stat-img" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sachin21212121&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117" alt="Sachin's top languages" loading="lazy">
        </div>
        <img class="gh-contrib reveal" src="https://ghchart.rshah.org/58a6ff/sachin21212121" alt="Sachin's GitHub contribution graph" loading="lazy">
        <p class="gh-note">Live stats pulled from GitHub via github-readme-stats.vercel.app and ghchart.rshah.org (third-party, public, no auth) — may take a second to load.</p>
      </div>
    </section>

    <section id="experience" class="section alt">
      <div class="container">
        <h2 class="reveal"><span class="section-index">02</span>experience</h2>
        <div class="timeline">
          <article class="timeline-item reveal">
            <span class="git-glyph">*</span>
            <div class="timeline-content">
              <div class="timeline-head">
                <h3>Engineering Intern · Zycus</h3>
                <span class="timeline-date">Jun 2026 – Present</span>
              </div>
              <ul>
                <li>Built a production-ready Zscaler MCP Server unifying 3 modules (ZIA, ZPA, ZCC) into a single interface, used daily by security leads and 100+ engineers across the global delivery team when resolving access issues.</li>
                <li>Developed an AI-powered vulnerability scanner correlating 4 data sources (CVE, NVD, EPSS, CVSS) to assess software risk — adopted as the standard tool by 1000+ engineers across Zycus.</li>
                <li>Automated OpenShift VM provisioning using Salesforce, Python, and Golden PVC templates, replacing a manual, ticket-based workflow — once approved, VMs now provision in OCP within seconds, tracked end-to-end through Jira.</li>
                <li>Built and deployed enterprise automation using AWS CodeBuild and ArgoCD, contributing to AI-powered developer productivity tools.</li>
              </ul>
            </div>
          </article>

          <article class="timeline-item reveal">
            <span class="git-glyph">*</span>
            <div class="timeline-content">
              <div class="timeline-head">
                <h3>LFX Mentee · KubeEdge (The Linux Foundation)</h3>
                <span class="timeline-date">Jun 2025 – Sep 2025</span>
              </div>
              <ul>
                <li>Contributed to KubeEdge documentation, updating version-specific installation guides and troubleshooting resources.</li>
                <li>Built an ARM64 simulation architecture to validate CloudCore/EdgeCore deployments and debug edge-cloud communication and performance, removing the need for physical RK3588 hardware during early-stage testing.</li>
              </ul>
            </div>
          </article>

          <article class="timeline-item reveal">
            <span class="git-glyph">*</span>
            <div class="timeline-content">
              <div class="timeline-head">
                <h3>Technical Writer · Hashnode</h3>
                <span class="timeline-date">Mar 2025 – Present</span>
              </div>
              <ul>
                <li>Published technical blog posts and tutorials on Kubernetes, Docker, Go, AWS, KubeEdge, and K3s, translating hands-on infrastructure work into practical, reproducible guides.</li>
              </ul>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="container">
        <h2 class="reveal"><span class="section-index">03</span>projects</h2>
        <div class="project-grid">
          <article class="card project-card reveal">
            <h3>ModelForge</h3>
            <p class="project-sub">End-to-end MLOps platform with Kubeflow</p>
            <p>Automated model training, experimentation, deployment, and inference on Kubernetes. Integrates Kubeflow Pipelines, Katib, and model serving for a reproducible ML lifecycle.</p>
            <div class="tag-row">
              <span class="tag">Kubeflow</span><span class="tag">Kubernetes</span><span class="tag">Docker</span><span class="tag">Python</span>
            </div>
            <a href="https://github.com/sachin21212121/ModelForge-Kubeflow-Project" class="card-link">View on GitHub →</a>
          </article>

          <article class="card project-card reveal">
            <h3>KubeJournal</h3>
            <p class="project-sub">Kubernetes cluster log collection</p>
            <p>A Go-based utility that retrieves and centralizes node-level logs across clusters using DaemonSets, simplifying observability and debugging in distributed environments.</p>
            <div class="tag-row">
              <span class="tag">Go</span><span class="tag">Kubernetes</span><span class="tag">DaemonSets</span><span class="tag">Linux</span>
            </div>
            <a href="https://github.com/sachin21212121/kubejournal" class="card-link">View on GitHub →</a>
          </article>

          <article class="card project-card reveal">
            <h3>GitOps CI/CD Pipeline</h3>
            <p class="project-sub">Jenkins &amp; ArgoCD automation</p>
            <p>An end-to-end GitOps pipeline for automated Kubernetes deployments, with 4 pipeline stages — SonarQube analysis, Docker image builds, auto-sync, and rollback — for reliable releases.</p>
            <div class="tag-row">
              <span class="tag">Jenkins</span><span class="tag">ArgoCD</span><span class="tag">Docker</span><span class="tag">SonarQube</span>
            </div>
            <a href="https://github.com/sachin21212121/jenkins-end-to-end-cicd-using-argocd" class="card-link">View on GitHub →</a>
          </article>
        </div>
      </div>
    </section>

    <section id="speaking" class="section alt">
      <div class="container">
        <h2 class="reveal"><span class="section-index">04</span>speaking &amp; recognition</h2>
        <div class="achievement-list">
          <article class="achievement reveal">
            <h3>KubeCon + CloudNativeCon India 2026 — Speaker</h3>
            <p>Presented a talk, "Validating RK3588 for KubeEdge: Scalable ARM64 Edge Node Simulation Without Hardware."</p>
            <a href="https://youtu.be/jh6MABNazjg?si=FpBaVoH76mj-QRMh" class="card-link">Watch talk →</a>
          </article>
          <article class="achievement reveal">
            <h3>Kubeflow Booth Volunteer</h3>
            <p>Volunteered at the Kubeflow booth at KubeCon + CloudNativeCon India 2026, engaging with the MLOps community and gaining hands-on exposure to real-world ML workflows.</p>
          </article>
          <article class="achievement reveal">
            <h3>CNCF Thane — Speaker</h3>
            <p>Delivered a session on WebAssembly in Cloud Native Ecosystems: portability, performance, and secure edge computing.</p>
          </article>
          <article class="achievement reveal">
            <h3>AWS Security Acknowledgment</h3>
            <p>Reported a valid local path traversal vulnerability in AWS SAM CLI, acknowledged by AWS Security under their bug bounty program.</p>
          </article>
        </div>
      </div>
    </section>

    <section id="certifications" class="section">
      <div class="container">
        <h2 class="reveal"><span class="section-index">05</span>certifications</h2>
        <div class="cert-grid">
          <a href="https://www.credly.com/badges/59909b1f-fa82-4e42-9ab0-8d263d91fb1b" class="cert-card reveal">
            <h3>KubeCon + CloudNativeCon India 2026</h3>
            <p>Speaker</p>
          </a>
          <a href="https://www.credly.com/badges/428bab79-2bfc-4740-b77a-caca440b69ad" class="cert-card reveal">
            <h3>AWS Knowledge: Cloud Essentials</h3>
            <p>Amazon Web Services</p>
          </a>
          <a href="https://learn.kodekloud.com/user/certificate/e527fc9c-a3a3-419e-a9dc-3a2da78ec0ae" class="cert-card reveal">
            <h3>CKA — Course Completed</h3>
            <p>KodeKloud</p>
          </a>
          <a href="https://learn.kodekloud.com/user/certificate/00365e35-1076-4543-973b-d891ee3eb82f" class="cert-card reveal">
            <h3>KCNA — Course Completed</h3>
            <p>KodeKloud</p>
          </a>
        </div>
      </div>
    </section>

    <section id="contact" class="section alt">
      <div class="container contact-inner">
        <h2 class="reveal"><span class="section-index">06</span>contact</h2>
        <p class="reveal">Open to opportunities in cloud infrastructure, DevOps, and platform engineering. Reach out — I usually reply within a day.</p>
        <div class="contact-actions reveal">
          <a href="mailto:jhasachin0115@gmail.com" class="btn btn-primary">jhasachin0115@gmail.com</a>
        </div>
        <div class="social-row reveal">
          <a href="https://github.com/sachin21212121" class="social-link">GitHub</a>
          <a href="https://www.linkedin.com/in/sachinjhadev/" class="social-link">LinkedIn</a>
          <a href="https://hashnode.com/@Sachinjha09" class="social-link">Hashnode</a>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p><span class="prompt">sachin@zycus:~$</span> echo "&copy; <span id="year"></span> Sachin Jha" <span class="cursor cursor-footer">▌</span></p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
```

## style.css

```css
/* ---------- Design tokens: GitHub Dark/Light ---------- */
:root {
  --bg: #0d1117;
  --bg-elevated: #161b22;
  --bg-elevated-2: #1c2128;
  --text: #e6edf3;
  --text-muted: #8b949e;
  --accent: #58a6ff;
  --accent-strong: #388bfd;
  --accent-contrast: #ffffff;
  --green: #3fb950;
  --purple: #a371f7;
  --border: #30363d;
  --shadow: 0 20px 50px -20px rgba(0, 0, 0, 0.6);
  --radius: 10px;
  --font-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, Consolas, "Liberation Mono", monospace;
  color-scheme: dark;
}

:root[data-theme="light"] {
  --bg: #ffffff;
  --bg-elevated: #f6f8fa;
  --bg-elevated-2: #eaeef2;
  --text: #1f2328;
  --text-muted: #656d76;
  --accent: #0969da;
  --accent-strong: #0550ae;
  --accent-contrast: #ffffff;
  --green: #1a7f37;
  --purple: #8250df;
  --border: #d0d7de;
  --shadow: 0 20px 50px -24px rgba(31, 35, 40, 0.25);
  color-scheme: light;
}

@media (prefers-color-scheme: light) {
  :root:not([data-theme="dark"]) {
    --bg: #ffffff;
    --bg-elevated: #f6f8fa;
    --bg-elevated-2: #eaeef2;
    --text: #1f2328;
    --text-muted: #656d76;
    --accent: #0969da;
    --accent-strong: #0550ae;
    --accent-contrast: #ffffff;
    --green: #1a7f37;
    --purple: #8250df;
    --border: #d0d7de;
    --shadow: 0 20px 50px -24px rgba(31, 35, 40, 0.25);
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
  font-family: var(--font-mono);
  line-height: 1.6;
  -webkit-font-smoothing: antialiased;
  transition: background 0.25s ease, color 0.25s ease;
}

h1, h2, h3 { line-height: 1.25; margin: 0 0 0.5em; font-weight: 700; }
p { margin: 0 0 1em; color: var(--text-muted); }
a { color: inherit; text-decoration: none; }
ul { padding-left: 1.1em; margin: 0; color: var(--text-muted); }
li { margin-bottom: 0.5em; }
li::marker { color: var(--green); }
img { max-width: 100%; }

.container { width: min(1080px, 100% - 3rem); margin-inline: auto; }

.skip-link {
  position: absolute; left: -999px; top: 0;
  background: var(--accent); color: var(--accent-contrast);
  padding: 0.75em 1.25em; border-radius: 0 0 8px 0; z-index: 1000;
}
.skip-link:focus { left: 0; }

:focus-visible { outline: 2px solid var(--accent); outline-offset: 3px; border-radius: 4px; }

/* ---------- Header ---------- */
.site-header {
  position: sticky; top: 0; z-index: 100;
  backdrop-filter: saturate(180%) blur(14px);
  background: color-mix(in srgb, var(--bg) 82%, transparent);
  border-bottom: 1px solid var(--border);
}
.nav { display: flex; align-items: center; justify-content: space-between; height: 60px; }
.logo { font-weight: 700; font-size: 1rem; letter-spacing: 0.01em; }
.prompt-sym { color: var(--green); margin-right: 0.35em; }
.logo-dot { color: var(--accent); }

.nav-links { display: flex; gap: 1.5rem; }
.nav-links a {
  font-size: 0.85rem; color: var(--text-muted); padding: 0.4em 0;
  border-bottom: 2px solid transparent;
  transition: color 0.2s ease, border-color 0.2s ease;
}
.nav-links a:hover, .nav-links a.active { color: var(--accent); border-color: var(--accent); }

.nav-actions { display: flex; align-items: center; gap: 0.5rem; }
.icon-btn {
  display: inline-flex; align-items: center; justify-content: center;
  width: 36px; height: 36px; border-radius: 6px;
  border: 1px solid var(--border); background: transparent; color: var(--text); cursor: pointer;
}
.icon-btn:hover { background: var(--bg-elevated); }
.icon { width: 17px; height: 17px; }

.icon-moon { display: none; }
:root[data-theme="light"] .icon-sun { display: none; }
:root[data-theme="light"] .icon-moon { display: block; }
@media (prefers-color-scheme: light) {
  :root:not([data-theme="dark"]):not([data-theme="light"]) .icon-sun { display: none; }
  :root:not([data-theme="dark"]):not([data-theme="light"]) .icon-moon { display: block; }
}

.nav-toggle { display: none; flex-direction: column; gap: 4px; padding: 9px; }
.nav-toggle span { width: 17px; height: 2px; background: var(--text); border-radius: 2px; }

/* ---------- Buttons ---------- */
.btn {
  display: inline-flex; align-items: center; gap: 0.5em;
  padding: 0.7em 1.3em; border-radius: 6px;
  font-size: 0.88rem; font-weight: 600; font-family: var(--font-mono);
  border: 1px solid transparent;
  transition: transform 0.15s ease, background 0.2s ease, border-color 0.2s ease;
}
.btn:hover { transform: translateY(-1px); }
.btn-primary { background: var(--accent-strong); color: var(--accent-contrast); }
.btn-primary:hover { background: var(--accent); }
.btn-ghost { border-color: var(--border); color: var(--text); }
.btn-ghost:hover { border-color: var(--accent); }

/* ---------- Hero / Terminal ---------- */
.hero { padding: 6rem 0 4.5rem; }
.hero-inner { max-width: 760px; }

.terminal-window {
  background: var(--bg-elevated);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  overflow: hidden;
  margin-bottom: 1.75rem;
  box-shadow: var(--shadow);
}
.terminal-bar {
  display: flex; align-items: center; gap: 7px;
  padding: 0.6rem 1rem;
  background: var(--bg-elevated-2);
  border-bottom: 1px solid var(--border);
}
.dot { width: 11px; height: 11px; border-radius: 50%; }
.dot-red { background: #ff5f56; }
.dot-yellow { background: #ffbd2e; }
.dot-green { background: #27c93f; }
.terminal-title { margin-left: 0.6rem; font-size: 0.78rem; color: var(--text-muted); }
.terminal-body { padding: 1.4rem 1.6rem; font-size: 0.88rem; }
.terminal-body p { margin: 0 0 0.35rem; }
.prompt { color: var(--green); font-weight: 600; }
.term-out { color: var(--text); margin-bottom: 1rem !important; }
.term-name { font-weight: 700; font-size: 1.25rem; color: var(--accent); }
.term-bio { color: var(--text-muted); }
.term-cursor-line { margin-top: 0.5rem !important; }
.cursor { display: inline-block; color: var(--accent); animation: blink 1s step-start infinite; }
.cursor-footer { color: var(--green); }
@keyframes blink { 50% { opacity: 0; } }

.identity-badges { display: flex; flex-wrap: wrap; gap: 0.5rem; margin-bottom: 1.75rem; }
.id-badge {
  font-size: 0.76rem; font-weight: 600;
  padding: 0.4em 0.85em; border-radius: 6px;
  background: var(--bg-elevated);
  border: 1px solid var(--border);
  border-left: 3px solid var(--green);
  color: var(--text);
}

.hero-actions { display: flex; flex-wrap: wrap; gap: 0.9rem; margin-bottom: 1.5rem; }

.social-row { display: flex; flex-wrap: wrap; gap: 0.6rem; }
.social-link {
  font-size: 0.8rem; padding: 0.5em 1em; border-radius: 6px;
  border: 1px solid var(--border); color: var(--text-muted);
  transition: border-color 0.2s ease, color 0.2s ease;
}
.social-link:hover { border-color: var(--accent); color: var(--accent); }

/* ---------- Sections ---------- */
.section { padding: 4.5rem 0; }
.section.alt { background: var(--bg-elevated); }
.section h2 {
  display: flex; align-items: baseline; gap: 0.6rem;
  font-size: clamp(1.3rem, 2.6vw, 1.7rem);
  margin-bottom: 2rem; text-transform: lowercase;
}
.section-index { color: var(--green); font-size: 0.85rem; font-weight: 700; }

/* About */
.about-grid { display: grid; grid-template-columns: 1.4fr 1fr; gap: 3rem; margin-bottom: 2rem; }
.about-grid p { font-size: 0.95rem; max-width: 64ch; }
.about-facts { display: flex; flex-direction: column; gap: 1.1rem; }
.fact { font-size: 0.88rem; color: var(--text-muted); }
.fact-label {
  display: block; font-size: 0.72rem; color: var(--green);
  margin-bottom: 0.3em;
}

.k8s-edge-diagram { width: 100%; max-width: 480px; height: auto; display: block; margin: 0 auto 2rem; }

.skill-badges { display: flex; flex-wrap: wrap; gap: 0.5rem; margin: 0 0 2rem; }
.skill-badges img { height: 26px; }

.gh-stats-grid { display: flex; flex-wrap: wrap; gap: 1rem; margin-bottom: 1rem; }
.gh-stat-img { border-radius: var(--radius); }
.gh-contrib { display: block; width: 100%; border-radius: var(--radius); margin-bottom: 0.5rem; background: var(--bg-elevated); min-height: 120px; }
.gh-note { font-size: 0.75rem; color: var(--text-muted); font-style: italic; margin: 0; }

/* Timeline (git-log style) */
.timeline { position: relative; padding-left: 2rem; }
.timeline::before {
  content: ""; position: absolute; left: 5px; top: 8px; bottom: 8px;
  width: 2px; background: var(--border);
}
.timeline-item { position: relative; padding-bottom: 2.5rem; }
.timeline-item:last-child { padding-bottom: 0; }
.git-glyph {
  position: absolute; left: -2rem; top: -3px;
  color: var(--green); font-weight: 800; font-size: 1.3rem;
  background: var(--bg-elevated); width: 24px; text-align: center;
}
.timeline-head {
  display: flex; flex-wrap: wrap; align-items: baseline; justify-content: space-between;
  gap: 0.5rem 1rem; margin-bottom: 0.7rem;
}
.timeline-head h3 { font-size: 1rem; margin: 0; }
.timeline-date { font-size: 0.78rem; color: var(--purple); white-space: nowrap; }
.timeline-content ul { font-size: 0.88rem; }

/* Cards / Projects */
.project-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1.25rem; }
.card {
  background: var(--bg-elevated); border: 1px solid var(--border); border-radius: var(--radius);
  padding: 1.6rem; display: flex; flex-direction: column;
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
}
.card:hover { transform: translateY(-3px); box-shadow: var(--shadow); border-color: var(--accent); }
.card h3 { font-size: 1.02rem; margin-bottom: 0.2em; }
.project-sub { color: var(--accent); font-size: 0.8rem; font-weight: 600; margin-bottom: 0.7em; }
.card p:not(.project-sub) { font-size: 0.87rem; flex-grow: 1; }
.tag-row { display: flex; flex-wrap: wrap; gap: 0.4rem; margin: 0.5rem 0 1rem; }
.tag { font-size: 0.72rem; padding: 0.3em 0.6em; border-radius: 5px; background: var(--bg-elevated-2); color: var(--text-muted); }
.card-link { font-size: 0.85rem; font-weight: 600; color: var(--green); align-self: flex-start; }
.card-link:hover { text-decoration: underline; }

/* Speaking / Achievements */
.achievement-list { display: grid; grid-template-columns: repeat(auto-fit, minmax(270px, 1fr)); gap: 1.25rem; }
.achievement { padding: 1.4rem; border-radius: var(--radius); border: 1px solid var(--border); }
.achievement h3 { font-size: 0.95rem; margin-bottom: 0.4em; }
.achievement p { font-size: 0.87rem; margin-bottom: 0.5em; }

/* Certifications */
.cert-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1.1rem; }
.cert-card {
  display: block; padding: 1.4rem; border-radius: var(--radius);
  border: 1px solid var(--border); background: var(--bg-elevated);
  transition: border-color 0.2s ease, transform 0.2s ease;
}
.cert-card:hover { border-color: var(--accent); transform: translateY(-2px); }
.cert-card h3 { font-size: 0.92rem; margin-bottom: 0.3em; }
.cert-card p { font-size: 0.8rem; margin: 0; }

/* Contact */
.contact-inner { text-align: center; max-width: 620px; }
.contact-inner .section-index { display: none; }
.contact-inner h2 { justify-content: center; }
.contact-actions { margin: 1.4rem 0; display: flex; justify-content: center; }
.contact-inner .social-row { justify-content: center; }

/* Footer */
.site-footer { padding: 2rem 0; border-top: 1px solid var(--border); text-align: center; }
.site-footer p { font-size: 0.8rem; margin: 0; }

/* ---------- Reveal-on-scroll ---------- */
.reveal { opacity: 0; transform: translateY(14px); transition: opacity 0.6s ease, transform 0.6s ease; }
.reveal.in-view { opacity: 1; transform: translateY(0); }

/* ---------- Responsive ---------- */
@media (max-width: 860px) {
  .about-grid { grid-template-columns: 1fr; gap: 2rem; }
}
@media (max-width: 720px) {
  .nav-links {
    position: absolute; top: 60px; left: 0; right: 0;
    background: var(--bg); border-bottom: 1px solid var(--border);
    flex-direction: column; padding: 1rem 1.5rem 1.5rem; gap: 1rem; display: none;
  }
  .nav-links.open { display: flex; }
  .nav-toggle { display: flex; }
  .hero { padding: 4.5rem 0 3rem; }
  .section { padding: 3rem 0; }
  .git-glyph { left: -1.6rem; }
}
```

## script.js

```javascript
(function () {
  "use strict";

  var root = document.documentElement;
  var THEME_KEY = "theme";

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

  var typedNameEl = document.getElementById("typed-name");
  var reduceMotion = window.matchMedia("(prefers-reduced-motion: reduce)").matches;
  if (typedNameEl) {
    var fullName = "Sachin Jha";
    if (reduceMotion) {
      typedNameEl.textContent = fullName;
    } else {
      var i = 0;
      (function typeChar() {
        if (i <= fullName.length) {
          typedNameEl.textContent = fullName.slice(0, i);
          i++;
          setTimeout(typeChar, 70);
        }
      })();
    }
  }

  var yearEl = document.getElementById("year");
  if (yearEl) yearEl.textContent = new Date().getFullYear();
})();
```

## README.md

```markdown
# Sachin Jha — Portfolio

Static site, plain HTML/CSS/JS, no build step. Two CDN dependencies (no install needed):
JetBrains Mono (Google Fonts) and GitHub stats/contribution images (github-readme-stats.vercel.app, ghchart.rshah.org — third-party, public).

## Files
- `index.html`, `style.css`, `script.js`
- `Sachin_Resume.pdf` — served by the "Download Resume" button

## Preview locally
python -m http.server 8080 → http://localhost:8080

## Hosted on Vercel
Repo: github.com/sachin21212121/portfolio-website — already connected, pushes to `main` auto-redeploy.
```
