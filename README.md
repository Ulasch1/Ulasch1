<h1 align="center">Hi, I'm Ulaş Kartal </h1>

<p align="center">
  <strong>Computer Engineering Student @ Dokuz Eylül University</strong><br>
  Focused on Backend Systems, Agentic AI Architectures, Data Engineering, and Embedded IoT.
</p>

<p align="center">
  <a href="https://linkedin.com/in/ulas-kartal/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ulask1505@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

###  About Me

I am a third-year Computer Engineering student with a passion for designing scalable backend systems, automating workflows using agentic AI, and building hardware-software integrations. I enjoy taking control of core system architectures, database designs, and embedded platforms, while leveraging modern AI-assisted workflows to accelerate execution.

- 🎓 **Education:** BS in Computer Engineering at Dokuz Eylül University (GPA: 3.08)
- 🧠 **Current Focus:** Engineering multi-agent workflows, autonomous tool-use pipelines, specialized LLM integrations, and developing responsive full-stack web applications.
- 🐧 **OS, Systems & Hardware:** Comfortable navigating Linux system environments and utilizing command-line utilities, alongside practical experience in embedded C/C++ development, hardware-software co-design, and low-power IoT telemetry architectures.
- 🌍 **Languages:** Turkish (Native), English (B2 - Fluent), German (A2 - Basic).

---

###  Tech Stack & Tools

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=python" width="48" height="48" alt="Python" />
      <br>Python
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=java" width="48" height="48" alt="Java" />
      <br>Java
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=cpp" width="48" height="48" alt="C++" />
      <br>C++
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="PostgreSQL" />
      <br>PostgreSQL / SQL
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=linux" width="48" height="48" alt="Linux" />
      <br>Linux
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" />
      <br>Git
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=arduino" width="48" height="48" alt="IoT" />
      <br>Embedded C++ / IoT
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=gcp" width="48" height="48" alt="Agentic AI" />
      <br>Agentic AI
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=django" width="48" height="48" alt="Data" />
      <br>Pandas/NumPy
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" />
      <br>Docker
    </td>
    <td align="center" width="96">
      <!-- Placeholder -->
    </td>
    <td align="center" width="96">
      <!-- Placeholder -->
    </td>
  </tr>
</table>

---

###  Highlighted Projects

#### 🤖 **OTTO — Event-Sourced Multi-Agent Orchestration Framework**
*An advanced, event-driven multi-agent system built on the **openClaw** ecosystem, featuring autonomous cross-model agent routing, custom cognitive memory pipelines, and real-time messaging gateways.*

- **Core Architecture & Orchestration:**
  - Designed an **Event-Sourced architecture** using an append-only JSONL transaction-log database to log thought processes, context changes, and tool execution history with strict session tracking.
  - Implemented a secure **Hono.js Gateway** acting as an API & routing gateway with token-based authentication to bind external triggers (like Telegram & Webhooks) to target agent workspaces.
  - Configured a dual-model runtime: **Google Gemini 2.5-flash** powers the main orchestration agent, while **DeepSeek v4-flash** handles specialized business logic (competitive analysis, trend analysis, and content strategy).
- **Autonomous Cognitive Pipeline & Cron Jobs:**
  - Engineered a daily **Memory Core "Dreaming" Pipeline** triggered via cron jobs (running at 4 AM) that processes raw session logs into long-term structured memory stores (utilizing local embeddings via Llama-cpp).
  - Integrated autonomous agent-to-agent communication via `sessions_spawn` and `sessions_send` tool calls, allowing agents to delegate sub-tasks and trigger scheduled background jobs dynamically.
- **Production Tooling & Channels:**
  - Built production-grade tooling including secure sandbox execution (`exec/process`), semantic memory retrieval, and integrated web-research tools (`Tavily Search/Extract` & `Web Fetch`).
  - Deployed localized channel bindings via a secure, whitelisted Telegram bot integration directly linked to production configurations (e.g., automated competitive research for an artisan e-commerce store).
- **Tech Stack:** Python, Hono.js, SQLite, DeepSeek, Gemini, Llama-cpp, JSONL, Docker, Telegram API, Relational Databases (PostgreSQL, Oracle SQL).

#### 💻 **Bob-Agentic-Orchestrator — Multi-Agent SDLC Framework**
*An advanced multi-agent software development lifecycle framework combining the reasoning power of Claude and the cost-efficient code generation of DeepSeek within a closed-loop execution and verification system.*

- **Autonomous Role Delegation & Orchestration:**
  - Built a top-level orchestrator named **Bob** that classifies incoming tasks, routes them to specific domains, and manages execution context.
  - Integrated **Coder** (powered by Claude Opus) to handle architectural planning, brief writing, and state-machine loop management without directly writing code.
- **Optimized Generation & Verification Loop:**
  - Delegated active code generation to a dedicated **DeepSeek script** via an API integration to minimize token usage on primary reasoning models.
  - Implemented **Tester** (Claude Sonnet), a sandboxed QA agent restricted to writing and executing test suites (using unit/integration tests) without modifying the source code, ensuring strict separation of concerns.
  - Deployed **Critic** (Claude Sonnet), an independent, read-only static analysis agent to catch logical edge cases, security flaws, and codebase convention drifts.
- **Self-Healing & Shared State Memory:**
  - Programmed a 3-round iterative self-healing loop; bugs flagged by Tester or Critic generate precise feedback briefs, triggering DeepSeek for targeted hotfixes.
  - Configured a centralized, Obsidian-compatible knowledge vault to write and update project plans, transaction logs, and persistent project states (`projects/PROJECT/PROJECT.md`).
- **Tech Stack:** Python, Claude (Opus & Sonnet), DeepSeek API, Bash Tooling, Obsidian, Markdown Vault Integration, Git.

#### 🌿 **Hardware-based Automated Plant Telemetry System**
*An energy-efficient, robust IoT prototype designed to address sensor degradation and signal noise in environmental monitoring.*

- **Hardware & Power Optimization:**
  - Designed and deployed a physical ESP32-based circuit utilizing low-power configurations.
  - Solved chronic resistive probe corrosion and oxidation issues caused by continuous DC current (electrolysis) by implementing a **Pulse-Drive software algorithm** (powering the sensor via GPIO 5 for just 50ms during active read cycles, reducing active electrical exposure by 97.5%).
- **Signal Processing & Fail-safes:**
  - Mitigated electromagnetic noise and source voltage fluctuations by implementing a C++ **Moving Average filter** (averaging 10 sequential samples over 100ms) to ensure smooth, stable data output.
  - Implemented an automated **Hardware Fault Detection** routine to flag open circuits and sensor disconnects instantly when ADC readings drift past a 4090 threshold.
- **Network Optimization & Hysteresis Control:**
  - Engineered a **Hysteresis-driven alert routine** (State Machine) to eliminate notification spam; low-moisture alerts trigger at 30% and lock until soil is watered and levels rise back past 40%.
  - Developed a **Delta-Based Transmission algorithm** that pushes telemetry packets to Blynk Cloud only upon a $\ge$ 1% change in moisture or a $\ge$ 5dBm change in Wi-Fi signal strength (RSSI), optimizing bandwidth usage by 90%.
- **Tech Stack:** C++, ESP32, Blynk IoT, Sensors, Wi-Fi Telemetry, Embedded C++.

---

###  Leadership Experience

- **Social Media Coordinator @ GDSC-GDG Dokuz Eylül:** Coordinated digital promotion strategies and content planning for a university tech community of 200+ members, supporting events like Ecothon 2024.

---

<p align="center">
  <i>Open to Internship and Junior Software Engineering opportunities.</i>
</p>
