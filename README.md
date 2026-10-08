




## 🛡️ About Me
# 👋 Hi, I'm Dolly Asis

### 🔐 Cybersecurity Enthusiast | CEH v13

<!DOCTYPE html>
<html lang="en">

<head>

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Dolly Asis | Cybersecurity Portfolio</title>

  <meta
    name="description"
    content="Dolly Asis - Cybersecurity Enthusiast | Ethical Hacking | Network Security | Vulnerability Assessment"
  >

  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;600;700;800&family=Orbitron:wght@500;600;700;800&display=swap"
    rel="stylesheet"
  >

  <style>

    /* =====================================================
       ROOT
    ===================================================== */

    :root {

      --bg: #030712;
      --bg2: #06131b;
      --card: rgba(5, 23, 31, 0.72);

      --cyan: #00f6ff;
      --cyan2: #00b8c8;

      --green: #7cff6b;
      --green2: #00ff88;

      --blue: #149cff;
      --purple: #8b5cf6;

      --white: #ecfbff;
      --text: #c9dce2;
      --muted: #79909a;

      --border: rgba(0, 246, 255, 0.20);

      --cyan-glow:
        0 0 8px rgba(0,246,255,.8),
        0 0 25px rgba(0,246,255,.35);

      --green-glow:
        0 0 8px rgba(124,255,107,.8),
        0 0 25px rgba(124,255,107,.35);
    }


    /* =====================================================
       RESET
    ===================================================== */

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {

      background:
        radial-gradient(
          circle at 50% 20%,
          rgba(0, 150, 160, .13),
          transparent 35%
        ),
        var(--bg);

      color: var(--white);

      font-family: "Inter", sans-serif;

      overflow-x: hidden;
    }

    a {
      color: inherit;
      text-decoration: none;
    }


    /* =====================================================
       CYBER BACKGROUND
    ===================================================== */

    .cyber-background {

      position: fixed;

      inset: 0;

      z-index: -10;

      background:
        linear-gradient(
          rgba(0,246,255,.055) 1px,
          transparent 1px
        ),
        linear-gradient(
          90deg,
          rgba(0,246,255,.055) 1px,
          transparent 1px
        );

      background-size: 55px 55px;

      mask-image:
        linear-gradient(
          to bottom,
          transparent,
          black 12%,
          black 88%,
          transparent
        );
    }


    /* =====================================================
       SCANLINES
    ===================================================== */

    .scanlines {

      position: fixed;

      inset: 0;

      z-index: -5;

      pointer-events: none;

      background:
        repeating-linear-gradient(
          0deg,
          transparent,
          transparent 4px,
          rgba(255,255,255,.012) 5px
        );
    }


    /* =====================================================
       PARTICLES
    ===================================================== */

    .particles {

      position: fixed;

      inset: 0;

      z-index: -4;

      pointer-events: none;
    }

    .particle {

      position: absolute;

      width: 2px;

      height: 2px;

      background: var(--green);

      box-shadow: var(--green-glow);

      animation:
        floatParticle linear infinite;
    }

    @keyframes floatParticle {

      from {
        transform: translateY(100vh);
        opacity: 0;
      }

      15% {
        opacity: 1;
      }

      85% {
        opacity: 1;
      }

      to {
        transform: translateY(-20vh);
        opacity: 0;
      }
    }


    /* =====================================================
       NAVBAR
    ===================================================== */

    header {

      position: fixed;

      top: 0;

      left: 0;

      right: 0;

      z-index: 1000;

      padding: 18px 5%;

      background:
        rgba(2, 9, 14, .72);

      backdrop-filter: blur(16px);

      border-bottom:
        1px solid rgba(0,246,255,.10);
    }

    nav {

      max-width: 1200px;

      margin: auto;

      display: flex;

      align-items: center;

      justify-content: space-between;
    }

    .logo {

      font-family: "JetBrains Mono";

      font-weight: 800;

      color: var(--green);

      text-shadow: var(--green-glow);

      letter-spacing: 1px;
    }

    .logo::before {
      content: "◈ ";
      color: var(--cyan);
    }

    .nav-links {

      display: flex;

      gap: 28px;

      list-style: none;
    }

    .nav-links a {

      color: #a7bcc4;

      font-family: "JetBrains Mono";

      font-size: 13px;

      transition: .3s;
    }

    .nav-links a:hover {

      color: var(--cyan);

      text-shadow: var(--cyan-glow);
    }

    .availability {

      color: var(--green);

      border: 1px solid rgba(124,255,107,.25);

      padding: 9px 15px;

      border-radius: 30px;

      font-size: 12px;

      font-family: "JetBrains Mono";

      box-shadow:
        inset 0 0 15px rgba(124,255,107,.04);
    }

    .availability span {

      display: inline-block;

      width: 7px;

      height: 7px;

      margin-right: 7px;

      border-radius: 50%;

      background: var(--green);

      box-shadow: var(--green-glow);

      animation: blink 1.5s infinite;
    }

    @keyframes blink {

      50% {
        opacity: .3;
      }
    }


    /* =====================================================
       GENERAL
    ===================================================== */

    section {

      max-width: 1200px;

      margin: auto;

      padding: 110px 5%;
    }

    .section-label {

      color: var(--green);

      font-family: "JetBrains Mono";

      font-size: 12px;

      letter-spacing: 2px;

      margin-bottom: 12px;
    }

    .section-title {

      font-family: "Orbitron";

      font-size: clamp(30px, 5vw, 48px);

      color: var(--cyan);

      text-shadow: var(--cyan-glow);

      margin-bottom: 45px;
    }


    /* =====================================================
       HERO
    ===================================================== */

    .hero {

      min-height: 100vh;

      max-width: 1200px;

      display: grid;

      grid-template-columns: 1.05fr .95fr;

      align-items: center;

      gap: 70px;

      padding-top: 140px;
    }

    .connection {

      color: var(--green);

      font-family: "JetBrains Mono";

      font-size: 13px;

      margin-bottom: 20px;

      text-shadow: var(--green-glow);
    }

    .connection::before {

      content: "● ";

      animation: blink 1.5s infinite;
    }

    .hero h1 {

      font-family: "Orbitron";

      font-size: clamp(55px, 8vw, 90px);

      line-height: 1;

      color: var(--cyan);

      text-shadow:
        0 0 5px var(--cyan),
        0 0 25px rgba(0,246,255,.7),
        0 0 60px rgba(0,246,255,.2);
    }

    .hero-role {

      margin-top: 22px;

      color: var(--cyan);

      font-family: "JetBrains Mono";

      font-size: 17px;

      font-weight: 700;
    }

    .hero-role span {
      color: var(--green);
    }

    .hero-description {

      max-width: 650px;

      margin-top: 25px;

      color: var(--text);

      line-height: 1.8;

      font-size: 16px;
    }


    /* =====================================================
       BUTTONS
    ===================================================== */

    .buttons {

      display: flex;

      flex-wrap: wrap;

      gap: 12px;

      margin-top: 30px;
    }

    .btn {

      padding: 12px 18px;

      border: 1px solid var(--border);

      border-radius: 8px;

      color: var(--cyan);

      background:
        rgba(0,246,255,.035);

      font-family: "JetBrains Mono";

      font-size: 12px;

      transition: .3s;
    }

    .btn:hover {

      transform: translateY(-4px);

      color: #001014;

      background: var(--cyan);

      box-shadow: var(--cyan-glow);
    }

    .btn.primary {

      color: #001014;

      background: var(--cyan);

      box-shadow: var(--cyan-glow);
    }


    /* =====================================================
       TERMINAL
    ===================================================== */

    .terminal {

      border: 1px solid var(--border);

      border-radius: 15px;

      overflow: hidden;

      background:
        linear-gradient(
          145deg,
          rgba(7,30,39,.85),
          rgba(3,13,19,.82)
        );

      backdrop-filter: blur(20px);

      box-shadow:
        0 0 40px rgba(0,246,255,.08),
        inset 0 0 30px rgba(0,246,255,.025);

      animation:
        terminalFloat 5s ease-in-out infinite;
    }

    @keyframes terminalFloat {

      0%,100% {
        transform: translateY(0);
      }

      50% {
        transform: translateY(-8px);
      }
    }

    .terminal-header {

      height: 45px;

      display: flex;

      align-items: center;

      gap: 8px;

      padding: 0 15px;

      border-bottom:
        1px solid rgba(0,246,255,.12);
    }

    .terminal-dot {

      width: 10px;

      height: 10px;

      border-radius: 50%;
    }

    .red {
      background: #ff5f56;
    }

    .yellow {
      background: #ffbd2e;
    }

    .terminal-green {
      background: #27c93f;
    }

    .terminal-name {

      margin-left: 10px;

      color: #78939d;

      font-family: "JetBrains Mono";

      font-size: 12px;
    }

    .terminal-body {

      padding: 28px;

      min-height: 340px;

      font-family: "JetBrains Mono";

      font-size: 14px;

      line-height: 1.8;
    }

    .command {
      color: var(--green);
    }

    .terminal-value {
      color: var(--cyan);
    }

    .cursor {

      color: var(--green);

      animation: blink 1s infinite;
    }


    /* =====================================================
       CYBER BANNER
    ===================================================== */

    .banner-section {

      padding-top: 30px;
    }

    .banner-wrapper {

      position: relative;

      overflow: hidden;

      border: 1px solid var(--border);

      border-radius: 18px;

      box-shadow:
        0 0 40px rgba(0,246,255,.08);
    }

    .banner-wrapper img {

      width: 100%;

      display: block;

      transition: .5s;
    }

    .banner-wrapper:hover img {

      transform: scale(1.02);
    }


    /* =====================================================
       CARDS
    ===================================================== */

    .grid {

      display: grid;

      grid-template-columns:
        repeat(3, 1fr);

      gap: 18px;
    }

    .card {

      padding: 28px;

      border: 1px solid var(--border);

      border-radius: 14px;

      background:
        linear-gradient(
          145deg,
          rgba(6,28,37,.72),
          rgba(3,13,20,.68)
        );

      backdrop-filter: blur(15px);

      transition: .35s;

      position: relative;

      overflow: hidden;
    }

    .card::before {

      content: "";

      position: absolute;

      top: 0;

      left: 0;

      width: 100%;

      height: 1px;

      background:
        linear-gradient(
          90deg,
          transparent,
          var(--cyan),
          transparent
        );

      opacity: .6;
    }

    .card:hover {

      transform: translateY(-8px);

      border-color:
        rgba(0,246,255,.55);

      box-shadow:
        0 0 30px rgba(0,246,255,.10);
    }

    .card-icon {

      font-size: 30px;

      margin-bottom: 18px;
    }

    .card h3 {

      color: var(--cyan);

      font-family: "JetBrains Mono";

      font-size: 17px;

      margin-bottom: 12px;
    }

    .card p {

      color: var(--muted);

      line-height: 1.7;

      font-size: 14px;
    }


    /* =====================================================
       SKILLS
    ===================================================== */

    .skill-list {

      display: flex;

      flex-wrap: wrap;

      gap: 10px;
    }

    .skill {

      padding: 10px 14px;

      border: 1px solid rgba(0,246,255,.20);

      border-radius: 7px;

      background: rgba(0,246,255,.035);

      color: #b9edf2;

      font-family: "JetBrains Mono";

      font-size: 12px;

      transition: .3s;
    }

    .skill:hover {

      color: #001014;

      background: var(--cyan);

      box-shadow: var(--cyan-glow);

      transform: translateY(-3px);
    }


    /* =====================================================
       EXPERIENCE
    ===================================================== */

    .experience {

      position: relative;

      padding-left: 30px;

      border-left:
        1px solid rgba(0,246,255,.25);
    }

    .experience-item {

      position: relative;

      margin-bottom: 35px;

      padding: 25px;

      border: 1px solid var(--border);

      border-radius: 12px;

      background: rgba(5,22,30,.62);
    }

    .experience-item::before {

      content: "";

      position: absolute;

      left: -36px;

      top: 28px;

      width: 10px;

      height: 10px;

      border-radius: 50%;

      background: var(--green);

      box-shadow: var(--green-glow);
    }

    .experience-item h3 {

      color: var(--cyan);

      font-family: "JetBrains Mono";
    }

    .company {

      color: var(--green);

      margin-top: 6px;

      font-family: "JetBrains Mono";

      font-size: 13px;
    }

    .experience-item p {

      color: var(--muted);

      margin-top: 15px;

      line-height: 1.7;
    }


    /* =====================================================
       PROJECTS
    ===================================================== */

    .project {

      min-height: 240px;
    }

    .project-number {

      color: var(--green);

      font-family: "JetBrains Mono";

      font-size: 12px;

      margin-bottom: 20px;
    }

    .project h3 {

      font-size: 20px;

      margin-bottom: 12px;
    }

    .project p {

      margin-bottom: 20px;
    }

    .tech {

      color: var(--cyan);

      font-family: "JetBrains Mono";

      font-size: 11px;

      line-height: 1.8;
    }


    /* =====================================================
       SOC DASHBOARD
    ===================================================== */

    .soc {

      border: 1px solid var(--border);

      border-radius: 15px;

      overflow: hidden;

      background: rgba(3,16,23,.75);
    }

    .soc-header {

      padding: 16px 20px;

      border-bottom:
        1px solid rgba(0,246,255,.12);

      color: var(--cyan);

      font-family: "JetBrains Mono";
    }

    .soc-row {

      display: grid;

      grid-template-columns: 1.5fr 1fr 100px;

      gap: 20px;

      align-items: center;

      padding: 18px 20px;

      border-bottom:
        1px solid rgba(0,246,255,.06);
    }

    .soc-row:last-child {
      border-bottom: none;
    }

    .soc-name {

      color: #cde5e9;

      font-family: "JetBrains Mono";

      font-size: 13px;
    }

    .bar {

      height: 5px;

      border-radius: 20px;

      background: #0c2830;

      overflow: hidden;
    }

    .bar span {

      display: block;

      height: 100%;

      background:
        linear-gradient(
          90deg,
          var(--cyan),
          var(--green)
        );

      box-shadow: var(--cyan-glow);
    }

    .soc-status {

      color: var(--green);

      font-family: "JetBrains Mono";

      font-size: 11px;

      text-align: right;
    }


    /* =====================================================
       CONTACT
    ===================================================== */

    .contact-box {

      text-align: center;

      padding: 60px 25px;

      border:
        1px solid var(--border);

      border-radius: 18px;

      background:
        radial-gradient(
          circle at center,
          rgba(0,246,255,.08),
          transparent 55%
        );
    }

    .contact-box h2 {

      font-family: "Orbitron";

      color: var(--cyan);

      font-size: clamp(30px,5vw,50px);

      text-shadow: var(--cyan-glow);

      margin-bottom: 15px;
    }

    .contact-box p {

      color: var(--muted);

      margin-bottom: 30px;
    }


    /* =====================================================
       FOOTER
    ===================================================== */

    footer {

      padding: 35px 5%;

      text-align: center;

      border-top:
        1px solid rgba(0,246,255,.08);

      color: var(--muted);

      font-family: "JetBrains Mono";

      font-size: 12px;
    }

    footer strong {

      color: var(--green);

      text-shadow: var(--green-glow);
    }


    /* =====================================================
       MOBILE
    ===================================================== */

    @media (max-width: 900px) {

      .nav-links {
        display: none;
      }

      .hero {

        grid-template-columns: 1fr;

        padding-top: 150px;
      }

      .grid {

        grid-template-columns: 1fr 1fr;
      }

      .soc-row {

        grid-template-columns:
          1fr 1fr;
      }

      .soc-status {

        text-align: left;
      }
    }


    @media (max-width: 600px) {

      section {
        padding: 80px 5%;
      }

      .hero {
        padding-top: 130px;
      }

      .hero h1 {
        font-size: 50px;
      }

      .grid {
        grid-template-columns: 1fr;
      }

      .terminal-body {
        font-size: 12px;
        padding: 20px;
      }

      .hero-buttons {
        flex-direction: column;
      }

      .btn {
        text-align: center;
      }

      .soc-row {
        grid-template-columns: 1fr;
      }
    }

  </style>

</head>


<body>


  <!-- =====================================================
       BACKGROUND
  ===================================================== -->

  <div class="cyber-background"></div>

  <div class="scanlines"></div>

  <div class="particles" id="particles"></div>


  <!-- =====================================================
       NAVIGATION
  ===================================================== -->

  <header>

    <nav>

      <a href="#home" class="logo">
        DOLLY ASIS
      </a>

      <ul class="nav-links">

        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#certifications">Certifications</a></li>
        <li><a href="#contact">Contact</a></li>

      </ul>

      <div class="availability">

        <span></span>

        OPEN TO OPPORTUNITIES

      </div>

    </nav>

  </header>


  <!-- =====================================================
       HERO
  ===================================================== -->

  <main>

    <section class="hero" id="home">


      <div>

        <div class="connection">
          [ SECURE_CONNECTION ESTABLISHED ]
        </div>

        <h1>
          Dolly Asis
        </h1>

        <div class="hero-role">

          Cybersecurity Enthusiast

          <span>|</span>

          CEH v13

        </div>

        <p class="hero-description">

          Cybersecurity enthusiast passionate about ethical hacking,
          network security, penetration testing, vulnerability management,
          and building practical security solutions.

        </p>


        <div class="buttons">

          <a href="#projects" class="btn primary">
            ◉ View My Projects
          </a>

          <a href="#" class="btn">
            ↓ Download Resume
          </a>

          <a
            href="https://github.com/DollyAsis630"
            target="_blank"
            class="btn"
          >
            ◉ GitHub
          </a>

          <a
            href="https://www.link

---

## 🛡️ About Me

I am a **Cybersecurity Enthusiast** passionate about ethical hacking, network security, penetration testing, vulnerability assessment, and secure software development.

I enjoy learning through **hands-on cybersecurity projects, security research, technical problem solving, and practical security testing**.

My goal is to continuously strengthen my cybersecurity and development skills while building practical solutions that help identify vulnerabilities and improve digital security.

---

## 💻 Technical Skills

### 🔐 Cybersecurity

`Ethical Hacking` `Network Security` `Penetration Testing`

`Vulnerability Assessment` `Vulnerability Management`

`IAM` `Risk Analysis` `Incident Response` `Data Security`

### 👨‍💻 Programming

`Python` `Java` `HTML` `CSS` `JavaScript`

### ⚙️ Technologies

`React.js` `React Native` `Node.js` `Express.js` `MongoDB`

### 🧠 Other Skills

`Data Structures & Algorithms`  
`Problem Solving`  
`Advanced Excel`

---

# 💼 Cybersecurity Experience

## 🛡️ Cyber Security Intern
### Unified Mentor Pvt. Ltd.
**Jan 2026 – Jun 2026**

Gained practical exposure to:

- Vulnerability Assessment
- Security Analysis
- Network Security
- Penetration Testing
- Incident Response
- Vulnerability Management
- Data Security

---

## 🔐 Cybersecurity Analyst Intern
### TATA Group
**Jan 2026**

Worked on cybersecurity simulation activities involving:

- Network Security
- Identity & Access Management
- Risk Analysis
- Identity Governance
- Platform Integration

---

# 🚀 Featured Projects

## 🔎 PDF Malware Analyzer

**Python | Vulnerability Management**

A static PDF security analyzer designed to identify suspicious content, embedded objects, and scripts without executing potentially harmful files.

### Key Features

- Static Analysis
- Suspicious Content Detection
- Embedded Object Detection
- Script Detection
- Threat Indicator Identification

🔗 **Repository:** To be added

---

## 🔐 Password Cracking & Credential Attack Testing Suite

**Python | Penetration Testing**

A controlled and sandboxed security-testing project designed to evaluate password strength and authentication weaknesses through authorized credential-attack simulations.

### Key Features

- Credential Attack Simulation
- Password Strength Testing
- Authentication Testing
- Security Testing

> ⚠️ Developed strictly for ethical, educational, and authorized security testing.

🔗 **Repository:** To be added

---

## 🛒 AI-Based Product Recommender / E-Commerce Application

**React.js | React Native | Node.js | Express | MongoDB**

A full-stack E-Commerce application featuring product recommendations, authentication, cart management, and order functionality.

### Key Features

- Product Browsing
- Product Recommendations
- Cart Management
- Order Placement
- User Authentication
- API Error Handling

🔗 **Repository:** To be added

---

# 🧠 Problem Solving

I practice algorithmic problem solving using **Python and Java**, focusing on efficient solutions and strong programming fundamentals.

### Areas

`Arrays` `Hashing` `Trees` `Graphs`

`Data Structures` `Algorithms` `Big-O Analysis`

### Platforms

- LeetCode
- HackerRank

🔗 **LeetCode:** To be added

---

# 📜 Certifications

- 🔐 **CEH v13 – Certified Ethical Hacker** — Simplilearn
- 🛡️ **Certified LLM Security Professional** — Red Team Leaders
- ☁️ **Introduction to Cloud Computing** — IBM / Coursera
- 🤖 **AI Fundamentals with IBM SkillsBuild**
- 🐍 **Python Essentials 2** — Cisco Networking Academy

---

# 🎯 Current Focus

```text
🔐 Cybersecurity
   ├── Ethical Hacking
   ├── Network Security
   ├── Vulnerability Assessment
   ├── IAM
   └── Security Analysis

💻 Development
   ├── Python
   ├── Java
   ├── JavaScript
   ├── React.js
   └── Node.js

🧠 Problem Solving
   ├── Data Structures
   ├── Algorithms
   └── Big-O Analysis
I am a **Cybersecurity Enthusiast** passionate about ethical hacking, network security, penetration testing, vulnerability assessment, and secure software development.

I enjoy learning through **hands-on cybersecurity projects, security research, technical problem solving, and practical security testing**.

My goal is to continuously strengthen my cybersecurity and development skills while building practical solutions that help identify vulnerabilities and improve digital security.

---

## 💻 Technical Skills

### 🔐 Cybersecurity

`Ethical Hacking` `Network Security` `Penetration Testing`

`Vulnerability Assessment` `Vulnerability Management`

`IAM` `Risk Analysis` `Incident Response` `Data Security`

### 👨‍💻 Programming

`Python` `Java` `HTML` `CSS` `JavaScript`

### ⚙️ Technologies

`React.js` `React Native` `Node.js` `Express.js` `MongoDB`

### 🧠 Other Skills

`Data Structures & Algorithms`  
`Problem Solving`  
`Advanced Excel`

---

# 💼 Cybersecurity Experience

## 🛡️ Cyber Security Intern
### Unified Mentor Pvt. Ltd.
**Jan 2026 – Jun 2026**

Gained practical exposure to:

- Vulnerability Assessment
- Security Analysis
- Network Security
- Penetration Testing
- Incident Response
- Vulnerability Management
- Data Security

---

## 🔐 Cybersecurity Analyst Intern
### TATA Group
**Jan 2026**

Worked on cybersecurity simulation activities involving:

- Network Security
- Identity & Access Management
- Risk Analysis
- Identity Governance
- Platform Integration

---

# 🚀 Featured Projects

## 🔎 PDF Malware Analyzer

**Python | Vulnerability Management**

A static PDF security analyzer designed to identify suspicious content, embedded objects, and scripts without executing potentially harmful files.

### Key Features

- Static Analysis
- Suspicious Content Detection
- Embedded Object Detection
- Script Detection
- Threat Indicator Identification

🔗 **Repository:** To be added

---

## 🔐 Password Cracking & Credential Attack Testing Suite

**Python | Penetration Testing**

A controlled and sandboxed security-testing project designed to evaluate password strength and authentication weaknesses through authorized credential-attack simulations.

### Key Features

- Credential Attack Simulation
- Password Strength Testing
- Authentication Testing
- Security Testing

> ⚠️ Developed strictly for ethical, educational, and authorized security testing.

🔗 **Repository:** To be added

---

## 🛒 AI-Based Product Recommender / E-Commerce Application

**React.js | React Native | Node.js | Express | MongoDB**

A full-stack E-Commerce application featuring product recommendations, authentication, cart management, and order functionality.

### Key Features

- Product Browsing
- Product Recommendations
- Cart Management
- Order Placement
- User Authentication
- API Error Handling

🔗 **Repository:** To be added

---

# 🧠 Problem Solving

I practice algorithmic problem solving using **Python and Java**, focusing on efficient solutions and strong programming fundamentals.

### Areas

`Arrays` `Hashing` `Trees` `Graphs`

`Data Structures` `Algorithms` `Big-O Analysis`

### Platforms

- LeetCode
- HackerRank



---

# 📜 Certifications

- 🔐 **CEH v13 – Certified Ethical Hacker** — Simplilearn
- 🛡️ **Certified LLM Security Professional** — Red Team Leaders
- ☁️ **Introduction to Cloud Computing** — IBM / Coursera
- 🤖 **AI Fundamentals with IBM SkillsBuild**
- 🐍 **Python Essentials 2** — Cisco Networking Academy

---

# 🎯 Current Focus


🔐 Cybersecurity
   ├── Ethical Hacking
   ├── Network Security
   ├── Vulnerability Assessment
   ├── IAM
   └── Security Analysis

💻 Development
   ├── Python
   ├── Java
   ├── JavaScript
   ├── React.js
   └── Node.js

🧠 Problem Solving
   ├── Data Structures
   ├── Algorithms
   └── Big-O Analysis
