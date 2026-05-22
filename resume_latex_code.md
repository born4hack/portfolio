```latex
%-------------------------
% ATS-Friendly Resume
% Author : Muhammad Usman
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING----------
\begin{center}
    \textbf{\Huge \scshape Muhammad Usman} \\ \vspace{1pt}
    \textit{\large Web \& API Penetration Tester | Security Researcher | CVE Author} \\ \vspace{5pt}
    \small +92-3482942611 $|$ 
    \href{mailto:musman.pentest@gmail.com}{\underline{musman.pentest@gmail.com}} $|$ 
    \href{https://www.linkedin.com/in/muhammad-usman-481876252/}{\underline{LinkedIn: muhammad-usman}} $|$
    \href{https://born4hack.github.io/portfolio/}{\underline{Portfolio: HackerSSG}} \\
    Karachi, Pakistan
\end{center}

%-----------SUMMARY-----------
\section{Professional Summary}
\small{Offensive Security Researcher and Web \& API Penetration Tester with proven expertise in vulnerability discovery, API security testing, and attack surface analysis. Published author of 2 CVEs (CVE-2025-14082, CVE-2025-14083) affecting Keycloak under Red Hat. Recognized with Google Honourable Mention and Hall of Fame awards from GitHub, Mastercard, Red Bull, Wolt, Sendbird, Aurory, and Code.org. Successfully reported 70+ validated vulnerabilities across Bugcrowd, Intigriti, HackerOne, and YesWeHack platforms. Specialized in OWASP Top 10, IDOR/BOLA, authentication bypass, REST API security, and business logic vulnerabilities. Seeking challenging penetration testing roles to leverage security expertise and contribute to organizational security posture.}

%-----------PUBLISHED CVES & RECOGNITIONS-----------
\section{Published CVEs \& Industry Recognition}
  \resumeSubHeadingListStart
    \resumeSubItem{\textbf{CVE-2025-14082 (Keycloak)} - Identified and disclosed critical security vulnerability in Keycloak, officially published under Red Hat CVE program. Demonstrated impact on authentication and access control mechanisms.}
    \resumeSubItem{\textbf{CVE-2025-14083 (Keycloak)} - Discovered additional security vulnerability in Keycloak affecting enterprise identity and access management systems, published through Red Hat security disclosure.}
    \resumeSubItem{\textbf{Google Honourable Mention} - Received official recognition from Google for responsible vulnerability disclosure and significant security research contribution.}
    \resumeSubItem{\textbf{Hall of Fame Recognitions} - GitHub, Mastercard, Red Bull, Wolt, Sendbird, Aurory, Code.org, Dailymotion, and additional global platforms for high-quality vulnerability discoveries.}
    \resumeSubItem{\textbf{70+ Reported Vulnerabilities} - Successfully identified and responsibly disclosed validated security vulnerabilities across multiple bug bounty platforms including Bugcrowd, Intigriti, HackerOne, and YesWeHack.}
  \resumeSubHeadingListEnd

%-----------PROFESSIONAL EXPERIENCE-----------
\section{Professional Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Web Application Penetration Tester}{February 2024 -- August 2025 (1 Year 7 Months)}
      {Apprise Cyber}{Karachi, Pakistan}
      \resumeItemListStart
        \resumeItem{Conducted comprehensive web application and API penetration testing for enterprise clients across banking, fintech, and e-commerce sectors}
        \resumeItem{Performed in-depth security assessments identifying critical vulnerabilities in authentication mechanisms, authorization controls, and business logic}
        \resumeItem{Collaborated closely with development teams to provide actionable security reports and remediation guidance for high-severity vulnerabilities}
        \resumeItem{Executed manual and automated testing for OWASP Top 10 vulnerabilities including SQL injection, XSS, CSRF, and insecure deserialization}
        \resumeItem{Delivered detailed penetration testing reports with proof-of-concept exploits and prioritized remediation recommendations}
        \resumeItem{Maintained professional client communication throughout security assessment lifecycle from scoping to final delivery}
      \resumeItemListEnd

    \resumeSubheading
      {Web Application Penetration Testing Intern}{2-Month Internship}
      {Securetackles}{Karachi, Pakistan}
      \resumeItemListStart
        \resumeItem{Successfully completed intensive internship program in Web Application Penetration Testing Department}
        \resumeItem{Demonstrated dedication and professionalism in completing all assigned penetration testing tasks and assignments}
        \resumeItem{Gained hands-on experience in vulnerability assessment, exploitation techniques, and security reporting methodologies}
        \resumeItem{Developed practical skills in using industry-standard tools including Burp Suite, OWASP ZAP, and manual testing techniques}
      \resumeItemListEnd

    \resumeSubheading
      {Security Researcher}{2025 -- Present}
      {HackerOne | Bug Bounty Platform}{Remote}
      \resumeItemListStart
        \resumeItem{Recognized in GitHub Hall of Fame for finding improper access control in GitHub Organization API}
        \resumeItem{Discovered and reported 10+ validated vulnerabilities contributing to improved security posture of major technology organizations}
        
        \resumeItem{Earned monetary bounty rewards for identifying security flaws in production systems}
        
        \resumeItem{Specialized in Access Control Vulnerabilities, IDOR, privilege escalation, and business logic vulnerabilities}
      \resumeItemListEnd

    \resumeSubheading
      {Security Researcher}{2024 -- Present}
      {Bugcrowd | Bug Bounty Platform}{Remote}
      \resumeItemListStart
        \resumeItem{Achieved Hall of Fame recognitions from Mastercard, Aurory, Sendbird, and Code.org for exceptional vulnerability research quality}
        \resumeItem{Reported 40+ validated vulnerabilities enhancing security for multiple global organizations across fintech, gaming, and communication sectors}
        \resumeItem{Earned substantial bounty rewards for responsible disclosure of security flaws}
      \resumeItemListEnd

    \resumeSubheading
      {Security Researcher}{2024 -- Present}
      {Intigriti | Bug Bounty Platform}{Remote}
      \resumeItemListStart
        \resumeItem{Achieved 4 Hall of Fame recognitions including Red Bull, Wolt, and other major brands for security contributions}
        \resumeItem{Discovered and reported 20+ vulnerabilities contributing to security improvements across e-commerce, food delivery, and enterprise platforms}
        \resumeItem{Earned bounty rewards for identifying vulnerabilities in authentication mechanisms, authorization controls, and API security}
      \resumeItemListEnd

    \resumeSubheading
      {Security Researcher}{2025 -- Present}
      {YesWeHack | Bug Bounty Platform}{Remote}
      \resumeItemListStart
        \resumeItem{Recently discovered multiple vulnerabilities in Public Bug Bounty Programs resulting Hall of Fame recognition and significant bounty rewards}
        \resumeItem{Specialized in attack surface reconnaissance, subdomain enumeration, and identifying security misconfigurations}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Bahria University}{Karachi, Pakistan}
      {Bachelor's Degree in Software Engineering, Completed: 2026}{September 2022 -- June 2026}
  \resumeSubHeadingListEnd

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills \& Tools}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Penetration Testing}{: Web Application Security Testing, API Security Assessment, VAPT, Vulnerability Research, Attack Surface Analysis, Exploitation, Security Code Review} \\
     \textbf{Security Testing Tools}{: Burp Suite Professional, Nmap, Nuclei, SQLMap, Wireshark} \\
     \textbf{Vulnerability Categories}{: OWASP Top 10, IDOR/BOLA, Authentication Bypass, Authorization Flaws, SQL Injection, XSS, CSRF, SSRF, rate limit bypass, Business Logic Flaws} \\
     \textbf{API Security}{: REST API Testing, GraphQL Security, API Authentication Testing, Rate Limiting Bypass, Mass Assignment, Excessive Data Exposure} \\
     \textbf{Reconnaissance \& OSINT}{: Subdomain Enumeration, Asset Discovery, Information Gathering, Attack Surface Mapping, Bash Scripting for Automation} \\
     \textbf{Web Technologies}{: HTML, CSS, Bootstrap, PHP, ASP.NET MVC, .NET Core, SQL Databases, WordPress Development} \\
     \textbf{Emerging Technologies}{: Blockchain Security, Web3, Smart Contract Security, Solidity} \\
     \textbf{Additional Skills}{: Vulnerability Reporting, Security Documentation, Client Communication, Remediation Guidance, Quality Assurance Testing}
    }}
 \end{itemize}
\end{document}
%-------------------------------------------
The EnD
```
