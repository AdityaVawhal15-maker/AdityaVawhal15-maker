<div align="center">

<!-- HERO BANNER ANIMATED SVG -->
<svg width="100%" height="320" viewBox="0 0 1000 320" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Animated Gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#050811"/>
      <stop offset="50%" stop-color="#0F172A"/>
      <stop offset="100%" stop-color="#020617"/>
    </linearGradient>

    <!-- Glowing Grid Overlay -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#38BDF8" stroke-opacity="0.07" stroke-width="1"/>
      <circle cx="40" cy="40" r="1.5" fill="#818CF8" fill-opacity="0.2"/>
    </pattern>

    <!-- Dynamic Linear Mesh Gradient -->
    <linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#38BDF8">
        <animate attributeName="stop-color" values="#38BDF8;#818CF8;#C084FC;#38BDF8" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="50%" stop-color="#818CF8">
        <animate attributeName="stop-color" values="#818CF8;#C084FC;#38BDF8;#818CF8" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#C084FC">
        <animate attributeName="stop-color" values="#C084FC;#38BDF8;#818CF8;#C084FC" dur="8s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

    <!-- Radial Glowing Orb -->
    <radialGradient id="heroGlow" cx="50%" cy="40%" r="60%">
      <stop offset="0%" stop-color="#38BDF8" stop-opacity="0.25"/>
      <stop offset="60%" stop-color="#818CF8" stop-opacity="0.05"/>
      <stop offset="100%" stop-color="#020617" stop-opacity="0"/>
    </radialGradient>

    <!-- CSS Keyframe Animations for GitHub Renderer -->
    <style>
      .pulse-orb {
        animation: pulse 6s ease-in-out infinite alternate;
      }
      .node-flow {
        stroke-dasharray: 8, 8;
        animation: flow 20s linear infinite;
      }
      .title-glow {
        filter: drop-shadow(0px 0px 12px rgba(56, 189, 248, 0.4));
      }
      @keyframes pulse {
        0% { opacity: 0.3; transform: scale(0.98); }
        100% { opacity: 0.7; transform: scale(1.02); }
      }
      @keyframes flow {
        0% { stroke-dashoffset: 100; }
        100% { stroke-dashoffset: 0; }
      }
    </style>
  </defs>

  <!-- Canvas Base -->
  <rect width="1000" height="320" rx="16" fill="url(#bgGrad)"/>
  <rect width="1000" height="320" rx="16" fill="url(#grid)"/>
  <circle cx="500" cy="160" r="380" fill="url(#heroGlow)" class="pulse-orb"/>
  <rect width="1000" height="320" rx="16" stroke="#1E293B" stroke-width="1.5"/>

  <!-- Top Accent Beam -->
  <rect x="0" y="0" width="1000" height="4" fill="url(#accentGrad)"/>

  <!-- Background Architecture Circuit Lines -->
  <path d="M 100 160 L 300 160 L 380 220 L 620 220 L 700 160 L 900 160" fill="none" stroke="url(#accentGrad)" stroke-width="1.5" stroke-opacity="0.3" class="node-flow"/>

  <!-- Core Content Stack -->
  <g class="title-glow">
    <text x="500" y="85" fill="#38BDF8" font-family="-apple-system, BlinkMacSystemFont, 'SF Pro Display', 'Segoe UI', Roboto, sans-serif" font-size="13" font-weight="700" letter-spacing="5" text-anchor="middle">
      🚀 ADITYA VAWHAL
    </text>
  </g>

  <text x="500" y="140" fill="#F8FAFC" font-family="-apple-system, BlinkMacSystemFont, 'SF Pro Display', 'Segoe UI', Roboto, sans-serif" font-size="36" font-weight="800" letter-spacing="-0.8" text-anchor="middle">
    AI Systems Engineer &bull; Researcher &bull; Full-Stack Developer
  </text>

  <text x="500" y="180" fill="#94A3B8" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="15" font-weight="400" text-anchor="middle">
    Engineering production-grade intelligence, distributed backends, and high-performance software.
  </text>

  <!-- Key Competency Pills (Rendered Vector Graphics) -->
  <g transform="translate(230, 225)">
    <!-- Pill 1 -->
    <rect x="0" y="0" width="160" height="34" rx="17" fill="#0F172A" stroke="#38BDF8" stroke-opacity="0.4" stroke-width="1"/>
    <circle cx="20" cy="17" r="4" fill="#38BDF8"/>
    <text x="92" y="21" fill="#E2E8F0" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">AI Systems</text>

    <!-- Pill 2 -->
    <rect x="180" y="0" width="180" height="34" rx="17" fill="#0F172A" stroke="#818CF8" stroke-opacity="0.4" stroke-width="1"/>
    <circle cx="200" cy="17" r="4" fill="#818CF8"/>
    <text x="280" y="21" fill="#E2E8F0" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">Distributed Systems</text>

    <!-- Pill 3 -->
    <rect x="380" y="0" width="160" height="34" rx="17" fill="#0F172A" stroke="#C084FC" stroke-opacity="0.4" stroke-width="1"/>
    <circle cx="400" cy="17" r="4" fill="#C084FC"/>
    <text x="470" y="21" fill="#E2E8F0" font-family="-apple-system, sans-serif" font-size="12" font-weight="600" text-anchor="middle">Full-Stack Architecture</text>
  </g>
</svg>

<br/>

<!-- STATUS PILLS -->
<a href="https://github.com/TheAditronik"><img src="https://img.shields.io/badge/Focus-AI%20Systems%20%26%20Infrastructure-0B0F19?style=for-the-badge&labelColor=0F172A&color=38BDF8" alt="Focus Badge" /></a>
<a href="https://github.com/TheAditronik"><img src="https://img.shields.io/badge/Education-BS%20Data%20Science%20%40%20IIT%20Madras-0B0F19?style=for-the-badge&labelColor=0F172A&color=818CF8" alt="Education Badge" /></a>
<a href="https://github.com/TheAditronik"><img src="https://img.shields.io/badge/Research-Microsoft%20Research%20%2F%20HPC-0B0F19?style=for-the-badge&labelColor=0F172A&color=C084FC" alt="Research Badge" /></a>

</div>

<br/>

<!-- SECTION DIVIDER SVG -->
<svg width="100%" height="24" viewBox="0 0 1000 24" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M 0 12 L 450 12 L 500 22 L 550 12 L 1000 12" stroke="#1E293B" stroke-width="1.5"/>
  <circle cx="500" cy="22" r="3" fill="#38BDF8"/>
</svg>

## 01. Professional Profile

I am an **AI Systems Engineer** who bridges machine learning models and high-performance backend systems. My work combines software engineering, research-driven thinking, and product design to transform algorithms into scalable, reliable, production-oriented software.

I focus on **LLM orchestration**, **distributed computing**, **predictive backend services**, and **system architecture**. Whether designing low-latency APIs or researching model evaluation pipelines, I optimize for craftsmanship, performance, and long-term code maintainability.

---

## 02. Executive Snapshot

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏛️ Academic & Research Foundations</h3>
      <ul>
        <li><b>B.S. in Data Science & Applications</b> — IIT Madras</li>
        <li><b>Research Exposure</b> — Microsoft Research India</li>
        <li><b>HPC Lab Exposure</b> — IIT Madras High-Performance Computing Lab</li>
        <li><b>Founder</b> — IOI Innovation Club</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ Technical Identity & Philosophy</h3>
      <ul>
        <li><b>Identity:</b> AI Systems Engineer</li>
        <li><b>Engineering Standard:</b> Simple before complex, reliable before clever.</li>
        <li><b>Core Priorities:</b> Observability, high throughput, loose coupling.</li>
        <li><b>Focus:</b> LLM Infrastructure & Scalable Systems.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 03. Current Focus & Roadmap
---

<!-- SECTION DIVIDER SVG -->
<svg width="100%" height="24" viewBox="0 0 1000 24" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M 0 12 L 450 12 L 500 22 L 550 12 L 1000 12" stroke="#1E293B" stroke-width="1.5"/>
  <circle cx="500" cy="22" r="3" fill="#818CF8"/>
</svg>

## 04. Featured Flagship Projects

### 01. DeepEnk — AI-Powered Intelligent Decision Platform

> **Category:** AI Infrastructure & Decision Intelligence Platform  
> **Status:** In Active Production Development
#### Overview
DeepEnk is an AI-driven decision platform built to streamline multi-domain analytical workflows, aggregating real-time signals into predictive decision models. It features high-concurrency API orchestrations, automated contextual retrieval, and proactive recommendation pipelines.

#### Engineering Highlights
* **Multi-Agent Orchestration:** Designed asynchronous LLM reasoning chains to analyze context in real time.
* **Low-Latency Backend:** Built with FastAPI and Redis caching to handle high-throughput event processing.
* **Modular Schema:** Implemented a unified PostgreSQL schema tailored for dynamic multi-modal data streams.

#### Tech Stack
`Python` &bull; `FastAPI` &bull; `PyTorch` &bull; `React` &bull; `Tailwind CSS` &bull; `PostgreSQL` &bull; `Redis` &bull; `Docker`
---

### 02. CYBERNOVA — AI-Powered Cybersecurity Platform

> **Category:** Threat Intelligence & Real-Time Anomaly Detection  
> **Status:** In Active Production Development
#### Overview
CYBERNOVA is an AI cybersecurity platform designed for immediate anomaly identification across log streams and network telemetry. Using fine-tuned transformer models, it converts unstructured security events into actionable threat scores with low false-positive rates.

#### Engineering Highlights
* **Real-Time Classification:** Fine-tuned transformer models for accurate threat detection across raw log strings.
* **Event Stream Ingestion:** Engineered an event-driven queue with Redis for rapid ingestion under load.
* **Interactive Dashboard:** Built a Next.js interface for threat visualization and immediate response workflows.

#### Tech Stack
`Python` &bull; `FastAPI` &bull; `Transformers` &bull; `PyTorch` &bull; `Next.js` &bull; `TypeScript` &bull; `Redis` &bull; `Docker`
---

<!-- SECTION DIVIDER SVG -->
<svg width="100%" height="24" viewBox="0 0 1000 24" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M 0 12 L 450 12 L 500 22 L 550 12 L 1000 12" stroke="#1E293B" stroke-width="1.5"/>
  <circle cx="500" cy="22" r="3" fill="#C084FC"/>
</svg>

## 05. System Architecture & Research Focus

<div align="center">

<!-- VECTOR SYSTEM ARCHITECTURE DIAGRAM -->
<svg width="100%" height="260" viewBox="0 0 900 260" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect width="900" height="260" rx="12" fill="#0B0F19" stroke="#1E293B" stroke-width="1"/>
  
  <!-- Nodes -->
  <!-- Layer 1: Client -->
  <rect x="50" y="105" width="140" height="50" rx="8" fill="#0F172A" stroke="#38BDF8" stroke-width="1.5"/>
  <text x="120" y="135" fill="#F8FAFC" font-family="-apple-system, sans-serif" font-size="12" font-weight="700" text-anchor="middle">Client Interface</text>
  
  <!-- Arrow 1 -->
  <path d="M 190 130 L 260 130" stroke="#38BDF8" stroke-width="2" marker-end="url(#arrow)"/>

  <!-- Layer 2: API Gateway -->
  <rect x="270" y="105" width="160" height="50" rx="8" fill="#0F172A" stroke="#818CF8" stroke-width="1.5"/>
  <text x="350" y="135" fill="#F8FAFC" font-family="-apple-system, sans-serif" font-size="12" font-weight="700" text-anchor="middle">API Gateway (FastAPI)</text>

  <!-- Arrow 2 Up & Down -->
  <path d="M 430 120 L 500 70" stroke="#818CF8" stroke-width="1.5"/>
  <path d="M 430 140 L 500 190" stroke="#818CF8" stroke-width="1.5"/>

  <!-- Layer 3 Top: AI Engine -->
  <rect x="510" y="45" width="170" height="50" rx="8" fill="#0F172A" stroke="#C084FC" stroke-width="1.5"/>
  <text x="595" y="75" fill="#F8FAFC" font-family="-apple-system, sans-serif" font-size="12" font-weight="700" text-anchor="middle">AI / LLM Pipelines</text>

  <!-- Layer 3 Bottom: Core Database -->
  <rect x="510" y="165" width="170" height="50" rx="8" fill="#0F172A" stroke="#34D399" stroke-width="1.5"/>
  <text x="595" y="195" fill="#F8FAFC" font-family="-apple-system, sans-serif" font-size="12" font-weight="700" text-anchor="middle">PostgreSQL / Redis</text>

  <!-- Arrow 3 to Storage -->
  <path d="M 680 70 L 740 130" stroke="#C084FC" stroke-width="1.5"/>
  <path d="M 680 190 L 740 130" stroke="#34D399" stroke-width="1.5"/>

  <!-- Layer 4: Compute Cluster -->
  <rect x="750" y="105" width="110" height="50" rx="8" fill="#0F172A" stroke="#F43F5E" stroke-width="1.5"/>
  <text x="805" y="135" fill="#F8FAFC" font-family="-apple-system, sans-serif" font-size="12" font-weight="700" text-anchor="middle">GPU Cluster</text>
</svg>

</div>

### Applied Research Domains
* **LLM Architecture & Evaluation:** Investigating low-latency inference strategies, dynamic context indexing, and agent orchestration frameworks.
* **High-Performance Computing:** Parallel execution, memory-optimized routines, and system-level benchmarking.
* **Distributed Systems:** Reliable consensus strategies, failure recovery models, and scalable caching layers.

---

## 06. Technical Skill Stack

<table width="100%">
  <tr>
    <td width="22%"><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
      <i>(Learning: Rust, Go)</i>
    </td>
  </tr>
  <tr>
    <td><b>AI & Machine Learning</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
      <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Transformers"/>
      <img src="https://img.shields.io/badge/RAG%20Pipelines-38BDF8?style=flat-square" alt="RAG"/>
      <img src="https://img.shields.io/badge/LLM%20Systems-818CF8?style=flat-square" alt="LLM Systems"/>
    </td>
  </tr>
  <tr>
    <td><b>Backend Systems</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express"/>
      <img src="https://img.shields.io/badge/REST%20APIs-020617?style=flat-square" alt="REST APIs"/>
    </td>
  </tr>
  <tr>
    <td><b>Frontend Engineering</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
      <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
    </td>
  </tr>
  <tr>
    <td><b>Databases & Cloud</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB"/>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
    </td>
  </tr>
</table>

---

## 07. Engineering Timeline

2026 ──────┐ 🛠️  Engineered DeepEnk & CYBERNOVA flagship AI platforms
│ 🔬  Researching LLM Systems & Distributed Computing Architecture
│
2025 ──────┼─ 🎓  Pursuing B.S. in Data Science & Applications @ IIT Madras
│ 🏛️  Founded IOI Innovation Club (Developer & Systems Community)
│ 🔬  Gained research exposure @ Microsoft Research India & IIT Madras HPC Lab
│
2024 ──────┘ ⚡  Completed BE First Year (CS - AI/ML) & Advanced CS Foundations

---

## 08. GitHub Metrics & Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AdityaVawhal15-maker&show_icons=true&theme=dark&hide_border=true&bg_color=0B0F19&title_color=38BDF8&text_color=9CA3AF&icon_color=818CF8" width="49%" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdityaVawhal15-maker&layout=compact&theme=dark&hide_border=true&bg_color=0B0F19&title_color=38BDF8&text_color=9CA3AF" width="49%" alt="Top Languages" />

</div>

---

## 09. Connect & Contact

<div align="center">

<a href="https://github.com/TheAditronik"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="TODO"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="TODO"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="mailto:TODO"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<br/><br/>

<sub>Crafted with engineering discipline &bull; Built for performance &bull; &copy; 2026 Aditya Vawhal</sub>

</div>
