\documentclass[10pt, letterpaper]{article}

\usepackage[
    ignoreheadfoot,
    top=0.4 cm,
    bottom=0.4 cm,
    left=1 cm,
    right=1 cm,
    footskip=1.0 cm,
]{geometry}
\usepackage{titlesec}
\usepackage{tabularx}
\usepackage{array}
\usepackage[dvipsnames]{xcolor}
\definecolor{primaryColor}{RGB}{0, 79, 144}
\usepackage{enumitem}
\usepackage{fontawesome5}
\usepackage{amsmath}
\usepackage[
    pdftitle={Sachin Jha's CV},
    pdfauthor={Sachin Jha},
    pdfcreator={LaTeX},
    colorlinks=true,
    urlcolor=primaryColor
]{hyperref}
\usepackage[pscoord]{eso-pic}
\usepackage{calc}
\usepackage{bookmark}
\usepackage{lastpage}
\usepackage{changepage}
\usepackage{paracol}
\usepackage{ifthen}
\usepackage{needspace}
\usepackage{iftex}

\ifPDFTeX
    \input{glyphtounicode}
    \pdfgentounicode=1
    \usepackage[utf8]{inputenc}
    \usepackage{lmodern}
\fi

\AtBeginEnvironment{adjustwidth}{\partopsep0pt}
\pagestyle{empty}
\setcounter{secnumdepth}{0}
\setlength{\parindent}{0pt}
\setlength{\topskip}{0pt}
\setlength{\columnsep}{0cm}
\makeatletter
\def\ps@customFooterStyle{%
  \def\@oddfoot{\hfil\footnotesize\color{gray}Page \thepage\ of \pageref{LastPage}\hfil}%
  \let\@evenfoot\@oddfoot
  \def\@oddhead{}\let\@evenhead\@oddhead
}
\makeatother
\pagestyle{customFooterStyle}

\titleformat{\section}{\needspace{4\baselineskip}\bfseries\large}{}{0pt}{}[\vspace{1pt}\titlerule]
\titlespacing{\section}{-1pt}{0.1 cm}{0.1 cm}

\renewcommand\labelitemi{$\circ$}
\newenvironment{highlights}{\begin{itemize}[topsep=0.10 cm,parsep=0.10 cm,partopsep=0pt,itemsep=0pt,leftmargin=0.4 cm + 10pt]}{\end{itemize}}
\newenvironment{highlightsforbulletentries}{\begin{itemize}[topsep=0.05 cm,parsep=0.05 cm,partopsep=0pt,itemsep=0pt,leftmargin=10pt]}{\end{itemize}}
\newenvironment{onecolentry}{\begin{adjustwidth}{0.2 cm + 0.00001 cm}{0.2 cm + 0.00001 cm}}{\end{adjustwidth}}
\newenvironment{twocolentry}[2][]{\onecolentry\def\secondColumn{#2}\setcolumnwidth{\fill, 4.5 cm}\begin{paracol}{2}}{\switchcolumn \raggedleft \secondColumn\end{paracol}\endonecolentry}
\newenvironment{header}{\setlength{\topsep}{0pt}\par\kern\topsep\centering\linespread{1.5}}{\par\kern\topsep}

\newcommand{\placelastupdatedtext}{\AddToShipoutPictureFG*{\put(\LenToUnit{\paperwidth-2 cm-0.2 cm+0.05cm},\LenToUnit{\paperheight-1.0 cm}){\vtop{{\null}\makebox[0pt][c]{\small\color{gray}\textit{}}}}}}

\let\hrefWithoutArrow\href
\renewcommand{\href}[2]{\hrefWithoutArrow{#1}{\ifthenelse{\equal{#2}{}}{ }{#2 }\raisebox{.15ex}{\footnotesize \faExternalLink*}}}

\begin{document}
\placelastupdatedtext
\begin{header}
\textbf{\fontsize{24 pt}{24 pt}\selectfont Sachin Jha}

\vspace{0.3 cm}

\normalsize
\mbox{{\color{black}\footnotesize\faMapMarker*}\hspace*{0.13cm}Mumbai}%
\kern 0.25 cm%
\mbox{\hrefWithoutArrow{mailto:jhasachin0115@gmail.com}{\color{blue}{\footnotesize\faEnvelope[regular]}\hspace*{0.13cm}jhasachin0115@gmail.com}}%
\kern 0.25 cm%
\mbox{\hrefWithoutArrow{tel:+917977761012}{\color{blue}{\footnotesize\faPhone*}\hspace*{0.13cm}+91 7977761012}}%
\kern 0.25 cm%

\mbox{\hrefWithoutArrow{https://www.linkedin.com/in/sachinjhadev/}{\color{blue}{\footnotesize\faLinkedinIn}\hspace*{0.13cm}LinkedIn}}%
\kern 0.25 cm%
\mbox{\hrefWithoutArrow{https://github.com/sachin21212121}{\color{blue}{\footnotesize\faGithub}\hspace*{0.13cm}Github}}%
\kern 0.25 cm%
\mbox{\hrefWithoutArrow{https://hashnode.com/@Sachinjha09}{\color{blue}{\footnotesize\faBlog}\hspace*{0.13cm}Blog}}%
\kern 0.25 cm%
\mbox{\hrefWithoutArrow{https://sachin-jha-portfolio-website.vercel.app/}{\color{blue}{\footnotesize\faGlobe}\hspace*{0.13cm}Portfolio}}%
\end{header}

\section{Education}
\begin{twocolentry}{\textit{Aug 2023 -- Present}}\textbf{University of Mumbai}\textit{\newline B.Tech in Artificial Intelligence and Machine Learning}\end{twocolentry}
\begin{onecolentry}
\begin{highlights}
\item GPA: 8.53/10.0
\item Coursework: Machine Learning, Computer Networks, Operating Systems, Cloud Computing, Distributed Systems\end{highlights}
\end{onecolentry}

\section{Technical Skills}

\begin{onecolentry}
\textbf{Languages:} Python, Go, Bash, JavaScript
\end{onecolentry}

\begin{onecolentry}
\textbf{Cloud \& DevOps:} Kubernetes, OpenShift, Docker, Terraform, Jenkins, Argo CD, GitHub Actions, AWS CodeBuild
\end{onecolentry}

\begin{onecolentry}
\textbf{Observability \& Security:} Prometheus, Zscaler (ZIA, ZPA, ZCC), CVE, NVD, EPSS, CVSS
\end{onecolentry}

\begin{onecolentry}
\textbf{AI \& MLOps:} MCP, Kubeflow, KServe, AI Agents
\end{onecolentry}

\begin{onecolentry}
\textbf{Platforms:} AWS, Linux, OpenShift, Git, Salesforce
\end{onecolentry}

\begin{onecolentry}
\textbf{Databases:} MySQL, MongoDB
\end{onecolentry}
\section{Experience}

\needspace{9\baselineskip}
\begin{twocolentry}{\textit{Jun 2026 -- Present}}
\textbf{Zycus}
\textit{\newline Engineering Intern}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Architected a production-ready \textbf{Zscaler MCP Server} unifying 3 modules (ZIA, ZPA, ZCC) into a single interface, used daily by security leads and 100+ engineers across the global delivery team when resolving access issues.

\item Engineered an AI-powered \textbf{vulnerability scanner} correlating 4 data sources (CVE, NVD, EPSS, CVSS) to assess software risk -- adopted as the standard tool by 1000+ engineers across Zycus.

\item Automated \textbf{OpenShift VM provisioning} using Salesforce, Python, and Golden PVC templates, replacing a manual, ticket-based workflow -- once approved, VMs now provision in OCP within seconds, tracked end-to-end through Jira.

\item Engineered CI/CD automation with \textbf{AWS CodeBuild and ArgoCD}, powering enterprise-wide AI-driven developer productivity initiatives.

\end{highlights}
\end{onecolentry}

\needspace{9\baselineskip}
\begin{twocolentry}{\textit{Jun 2025 -- Sep 2025}}
\textbf{KubeEdge}
\textit{\newline LFX Mentee (The Linux Foundation)}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Selected as 1 of \textbf{150 LFX Mentees} worldwide from a global pool of 27,000+ applicants.

\item Authored and merged version-specific \textbf{KubeEdge installation guides} and troubleshooting resources into the project's official documentation, used by its global user base.

\item Architected an \textbf{ARM64 simulation architecture} to validate CloudCore/EdgeCore deployments before testing on physical RK3588 hardware.

\item Debugged edge-cloud communication and performance issues while evaluating \textbf{RK3588 AI inference and NPU workloads} for edge deployment.

\end{highlights}
\end{onecolentry}

\needspace{6\baselineskip}
\begin{twocolentry}{\textit{Mar 2025 -- Present}}
\textbf{Hashnode}
\textit{\newline Technical Writer}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Authored technical blog posts on \textbf{Kubernetes, Docker, Go, and AWS}, translating hands-on infrastructure work into practical, reproducible guides.

\item Produced hands-on tutorials covering KubeEdge, K3s, and other CNCF technologies for the developer community.

\end{highlights}
\end{onecolentry}


\section{Speaking \& Recognition}

\begin{onecolentry}\begin{highlights}
\item \textbf{Speaker at KubeCon + CloudNativeCon India 2026} -- Presented a \href{https://youtu.be/jh6MABNazjg?si=FpBaVoH76mj-QRMh}{\textbf{talk}}, ``Validating RK3588 for KubeEdge: Scalable ARM64 Edge Node Simulation Without Hardware''.

\item
\textbf{Speaker at CNCF Thane} -- Delivered a session on WebAssembly in Cloud Native Ecosystems: portability, performance, and secure edge computing.

\item
Volunteered at the \textbf{Kubeflow booth} at KubeCon + CloudNativeCon India 2026, engaging with the MLOps community and gaining hands-on exposure to real-world ML workflows.

\item
Reported a valid \textbf{local path traversal vulnerability} in AWS SAM CLI, acknowledged by AWS Security under their bug bounty program.

\end{highlights}\end{onecolentry}

\section{Projects}

\needspace{8\baselineskip}
\begin{twocolentry}{\textit{\href{https://github.com/sachin21212121/ModelForge-Kubeflow-Project}{github}}}
\textbf{ModelForge: End-to-End MLOps Platform with Kubeflow}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Architected an end-to-end \textbf{MLOps platform} on Kubernetes using Kubeflow, automating model training, experimentation, deployment, and inference from a single pipeline.

\item Orchestrated hyperparameter tuning and model serving via Kubeflow Pipelines and Katib, standardizing reproducible ML workflows across experiments.

\item Containerized all pipeline components with Docker, enabling consistent, portable deployment across dev, staging, and production environments.

\item Tools: Kubeflow, Kubernetes, Docker, Python, ML Pipelines

\end{highlights}
\end{onecolentry}

\needspace{8\baselineskip}
\begin{twocolentry}{\textit{\href{https://github.com/sachin21212121/kubejournal}{github}}}
\textbf{KubeJournal: Kubernetes Cluster Log Collection}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Engineered a Go-based \textbf{log aggregation utility} that retrieves and centralizes node-level logs across Kubernetes clusters, reducing troubleshooting time for distributed workloads.

\item Deployed as a \textbf{DaemonSet} across every node in the cluster, ensuring complete log coverage without manual per-node configuration.

\item Built a lightweight CLI for querying and filtering aggregated logs, eliminating the need to manually run \texttt{kubectl logs} across every node.

\item Tools: Go, Kubernetes, DaemonSets, Linux

\end{highlights}
\end{onecolentry}

\needspace{8\baselineskip}
\begin{twocolentry}{\textit{\href{https://github.com/sachin21212121/jenkins-end-to-end-cicd-using-argocd}{github}}}
\textbf{GitOps CI/CD Pipeline with Jenkins \& ArgoCD}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Architected a \textbf{GitOps CI/CD pipeline} integrating Jenkins and ArgoCD, fully automating Kubernetes deployments from commit to production.

\item Implemented 4 pipeline stages -- SonarQube analysis, Docker image builds, auto-sync, and rollback -- to improve deployment reliability.

\item Configured Git-triggered webhooks to automatically trigger build, test, and deployment on every push, eliminating manual release steps.

\item Tools: Jenkins, ArgoCD, Docker, SonarQube, Kubernetes

\end{highlights}
\end{onecolentry}

\section{Certifications \& Training}

\begin{twocolentry}
{\textit{\href{https://www.credly.com/badges/59909b1f-fa82-4e42-9ab0-8d263d91fb1b}{link}}}
\textbf{KubeCon + CloudNativeCon India 2026 Speaker}
\end{twocolentry}

\begin{twocolentry}
{\textit{\href{https://www.credly.com/badges/428bab79-2bfc-4740-b77a-caca440b69ad}{link}}}
\textbf{AWS Knowledge: Cloud Essentials}
\end{twocolentry}

\begin{twocolentry}
{\textit{\href{https://learn.kodekloud.com/user/certificate/e527fc9c-a3a3-419e-a9dc-3a2da78ec0ae}{link}}}
\textbf{CKA (Certified Kubernetes Administrator) -- Course Completed, KodeKloud}
\end{twocolentry}

\begin{twocolentry}
{\textit{\href{https://learn.kodekloud.com/user/certificate/00365e35-1076-4543-973b-d891ee3eb82f}{link}}}
\textbf{KCNA (Kubernetes and Cloud Native Associate) -- Course Completed, KodeKloud}
\end{twocolentry}

\end{document}
