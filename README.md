\documentclass[10pt, letterpaper]{article}

% Packages:
\usepackage[
    ignoreheadfoot,
    top=0.3 cm,
    bottom=0.3 cm,
    left=0.9 cm,
    right=0.9 cm,
    footskip=0.7 cm,
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
\let\ps@customFooterStyle\ps@plain
\patchcmd{\ps@customFooterStyle}{\thepage}{}{}{}
\makeatother
\pagestyle{customFooterStyle}

\titleformat{\section}{\needspace{4\baselineskip}\bfseries\large}{}{0pt}{}[\vspace{1pt}\titlerule]

\titlespacing{\section}{-1pt}{0.08 cm}{0.08 cm}

\renewcommand\labelitemi{$\circ$}
\newenvironment{highlights}{\begin{itemize}[topsep=0.05 cm,parsep=0.05 cm,partopsep=0pt,itemsep=0pt,leftmargin=0.4 cm + 10pt]}{\end{itemize}}
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

\vspace{0.2 cm}

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

\begin{twocolentry}{\textit{Jun 2026 -- Present}}
\textbf{Zycus}
\textit{\newline Engineering Intern}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Built a production-ready \textbf{Zscaler MCP Server} unifying 3 modules (ZIA, ZPA, ZCC) into a single interface, used daily by security leads and by 100+ engineers across the global delivery team when resolving access issues.

\item Developed an AI-powered \textbf{vulnerability scanner} correlating 4 data sources (CVE, NVD, EPSS, CVSS) to assess software risk -- adopted as the standard tool by 1000+ engineers across Zycus.

\item Automated \textbf{OpenShift VM provisioning} using Salesforce, Python, and Golden PVC templates, replacing a manual, ticket-based workflow: once approved, VMs now provision in OCP within seconds, tracked end-to-end through Jira.

\item Built and deployed enterprise automation using \textbf{AWS CodeBuild and ArgoCD}, contributing to AI-powered developer productivity tools.

\end{highlights}
\end{onecolentry}

\begin{twocolentry}{\textit{Jun 2025 -- Sep 2025}}
\textbf{KubeEdge}
\textit{\newline LFX Mentee (The Linux Foundation)}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Contributed to \textbf{KubeEdge documentation} by updating version-specific installation guides and troubleshooting resources.

\item Built an \textbf{ARM64 simulation architecture} to validate CloudCore/EdgeCore deployments and debug edge-cloud communication and performance, removing the need for physical RK3588 hardware during early-stage testing.

\end{highlights}
\end{onecolentry}

\begin{twocolentry}{\textit{Mar 2025 -- Present}}
\textbf{Hashnode}
\textit{\newline Technical Writer}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Published technical blog posts and tutorials on \textbf{Kubernetes, Docker, Go, AWS, KubeEdge, and K3s}, translating hands-on infrastructure work into practical, reproducible guides.

\end{highlights}
\end{onecolentry}


\section{Speaking \& Recognition}

\begin{onecolentry}\begin{highlights}
\item \textbf{Speaker at KubeCon + CloudNativeCon India 2026} -- Presented a \href{https://youtu.be/jh6MABNazjg?si=FpBaVoH76mj-QRMh}{\textbf{talk}} at a prestigious Cloud Native conference, ``Validating RK3588 for KubeEdge: Scalable ARM64 Edge Node Simulation Without Hardware''.

\item
\textbf{Speaker at CNCF Thane} -- Delivered a session on WebAssembly in Cloud Native Ecosystems, highlighting its role in portability, performance, and secure edge computing.

\item
Reported a valid \textbf{local path traversal vulnerability} in AWS SAM CLI, acknowledged by the AWS Security team as part of their bug bounty program.

\end{highlights}\end{onecolentry}

\section{Projects}
\begin{twocolentry}{\textit{\href{https://github.com/sachin21212121/ModelForge-Kubeflow-Project}{github}}}
\textbf{ModelForge: End-to-End MLOps Platform with Kubeflow}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Built an end-to-end \textbf{MLOps platform} on Kubernetes using Kubeflow, enabling automated model training, experimentation, deployment, and inference.

\item Integrated Kubeflow Pipelines, Katib, and model serving to streamline the machine learning lifecycle with reproducible workflows.

\end{highlights}
\end{onecolentry}


\begin{twocolentry}{\textit{\href{https://github.com/sachin21212121/kubejournal}{github}}}
\textbf{KubeJournal: Kubernetes Cluster Log Collection}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Developed a Go-based Kubernetes log collection utility to retrieve and centralize \textbf{node-level logs} across clusters for easier troubleshooting.

\item Leveraged \textbf{DaemonSets} to collect logs from every Kubernetes node, simplifying observability and debugging in distributed environments.

\end{highlights}
\end{onecolentry}

\begin{twocolentry}{\textit{\href{https://github.com/sachin21212121/jenkins-end-to-end-cicd-using-argocd}{github}}}
\textbf{GitOps CI/CD Pipeline with Jenkins \& ArgoCD}
\end{twocolentry}

\begin{onecolentry}
\begin{highlights}

\item Designed a \textbf{GitOps CI/CD pipeline} integrating Jenkins and ArgoCD for automated Kubernetes deployments.

\item Implemented 4 pipeline stages -- SonarQube analysis, Docker image builds, auto-sync, and rollback -- to improve deployment reliability.

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
