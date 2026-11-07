# Hi there, I'm Boban Blagojević! 👋

[![GitHub followers](https://img.shields.io/github/followers/blagojevicboban?style=social)](https://github.com/blagojevicboban)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/blagojevicboban)
[![Institution](https://img.shields.io/badge/Tehnička%20škola%20Pirot-tsp.edu.rs-red)](http://www.tsp.edu.rs)

I am an **IT Specialist, Software Architect, and Vocational Educator** passionate about bridging advanced technology and practical education. My work spans **open-source EdTech ecosystems (Moodle & interactive learning)**, **Enterprise software (WPF, .NET & Cloud)**, **Edge AI & student innovation**, **WebXR simulations**, and **IoT medical/safety wearables**.

---

### 🚀 Areas of Expertise & Current Focus:
- **EdTech & Moodle Innovation:** Architect of comprehensive LMS ecosystems — from in-browser Monaco code execution (CodeLab) and visual flowchart algorithms to AI simulation auto-grading and pedagogical prompt builders.
- **Enterprise Engineering:** Full-stack architecture of modular ERP systems (WPF, ASP.NET Core, React/Vite, multi-tenant SQL/PostgreSQL/SQLite).
- **Edge AI & Applied Machine Learning:** Mentoring high-school innovators in deploying on-device AI (YOLO, Whisper, edge audio & vision models).
- **WebXR & Digital Twins:** Creating hardware-agnostic 3D/VR simulations and LMS activity modules for industrial and vocational training.
- **IoT & Embedded Systems:** Designing custom wearable devices with sensor fusion and independent LTE telecare reporting (ESP32-S3 ecosystem).

---

### 🛠️ Tech Stack & Tooling:

- **Languages:** C, C++, C# (.NET 8/9), PHP, Python, JavaScript, TypeScript, SQL
- **Frameworks & UI:** WPF (MVVM, Material Design), ASP.NET Core, React, Vite, React Native, Expo, QuestPDF
- **EdTech & LMS:** Moodle Plugin Development (Activities, Filters, Question Types, TinyMCE subplugins, Blocks), Jobe Sandbox
- **3D & XR:** WebXR, Three.js, A-Frame, Meta Quest 3 RGB-D pipeline, Photogrammetry
- **Hardware & IoT:** ESP32 / ESP32-S3 (ESP-IDF, FreeRTOS), SIM800L / LTE, IMU, PPG / SpO2 sensors
- **DevOps & Platforms:** Docker, Linux, Virtualmin, Apache, Nginx, Git, GitHub Actions

---

### 📂 Featured Ecosystems & Projects:

#### 🎓 1. Moodle EdTech Ecosystem (Open-Source Learning Suites)

##### 💻 [CodeLab Suite](https://github.com/blagojevicboban/moodle-qtype_codelab) — Interactive In-Browser Programming
A complete end-to-end coding ecosystem for Moodle, bringing VS Code power (Monaco Editor) directly into course content and automated quiz grading:
- 🧩 **[moodle-tiny_codelab](https://github.com/blagojevicboban/moodle-tiny_codelab)** — TinyMCE visual editor plugin embedding Monaco code blocks with multi-language syntax highlighting (C, C++, C#, Java, Python, PHP, JS, SQL, HTML).
- 🔍 **[moodle-filter_codelab](https://github.com/blagojevicboban/moodle-filter_codelab)** — Course page filter rendering interactive, editable, and runnable code editors in any activity.
- 🎯 **[moodle-qtype_codelab](https://github.com/blagojevicboban/moodle-qtype_codelab)** — Automated quiz question type grading code on Jobe sandboxes against test cases.
- ⚡ **[codelab-runner](https://github.com/blagojevicboban/codelab-runner)** — Interactive WebSocket execution server running compiled programs (C, C++, Java, C#) in real-time sandboxes with live stdin/stdout interaction.

##### 📊 [Algorithm & Flowchart Suite](https://github.com/blagojevicboban/moodle-qtype_algorithm) — Visual Flowchart Programming
A Flowgorithm-inspired visual programming suite for teaching logic and algorithms inside Moodle:
- 🧩 **[moodle-tiny_algorithm](https://github.com/blagojevicboban/moodle-tiny_algorithm)** — Interactive flowchart visual designer in TinyMCE with instant pseudocode generation and step-by-step debugger.
- 🔍 **[moodle-filter_algorithm](https://github.com/blagojevicboban/moodle-filter_algorithm)** — Embeds interactive visual flowchart execution directly into learning pages.
- 🎯 **[moodle-qtype_algorithm](https://github.com/blagojevicboban/moodle-qtype_algorithm)** — Quiz question type where students build flowcharts with automatic validation and step-by-step scoring.

##### 🤖 [AI for VET & Simulation Suite](https://github.com/blagojevicboban/moodle-qtype_aisim) (Erasmus+)
Next-generation vocational assessment integrating interactive AI simulations into Moodle:
- 🧩 **[moodle-tiny_aisim](https://github.com/blagojevicboban/moodle-tiny_aisim)** — Visual scenario authoring plugin inside the Moodle editor.
- 🔍 **[moodle-filter_aisim](https://github.com/blagojevicboban/moodle-filter_aisim)** — Embedded interactive simulation viewer.
- 🎯 **[moodle-qtype_aisim](https://github.com/blagojevicboban/moodle-qtype_aisim)** — Simulation-based quiz question type with automated competency scoring.

##### 🧠 [AI Prompt Generator Suite](https://github.com/blagojevicboban/moodle-tiny_aipromptgen) — LLM-Assisted Course Creation
- 🤖 **[moodle-tiny_aipromptgen](https://github.com/blagojevicboban/moodle-tiny_aipromptgen)** — TinyMCE plugin providing guided pedagogical prompt engineering integrated with OpenAI and local Ollama servers.
- 🧱 **[moodle-block_aipromptgen](https://github.com/blagojevicboban/moodle-block_aipromptgen)** — Course-level teacher assistant block for AI lesson plan generation.

---

#### 💼 2. [ERPi](https://github.com/blagojevicboban/ERPi) — Enterprise Resource Planning Ecosystem
A modern enterprise ERP solution built for comprehensive business management:
- **Core Architecture:** Modular .NET 8/9 WPF desktop application with dynamic MVVM architecture, SQLite / PostgreSQL / MS SQL Server database providers, and multi-tenant schema sync.
- **Enterprise Modules:**
  - 💰 **[ERPiFinansije](https://github.com/blagojevicboban/ERPiFinansije):** General ledger (Glavna knjiga), journal entries, accounts payable/receivable, financial statements.
  - 🏢 **[ERPiSredstva](https://github.com/blagojevicboban/ERPiSredstva):** Fixed assets lifecycle management, automated tax & accounting depreciation, inventory barcode audits.
  - 👥 **[ERPiZarade](https://github.com/blagojevicboban/ERPiZarade):** Payroll calculation, tax filings (PPP-PD XML), virmani, and employee tracking.
  - 📦 **Robno-Materijalno:** Invoicing, warehouse inventory, kalkulacije, fiscal integration, and QuestPDF report engine.
- **Web & B2B:** ASP.NET Core REST API backend and modern React/Vite responsive B2B WebShop portal.

---

#### 🥽 3. [GEAR & ARVR4VET](https://github.com/blagojevicboban/GEAR) — WebXR & Digital Twins for VET
Hardware-agnostic immersive learning platform developed for international Erasmus+ initiatives:
- 🌐 **[GEAR](https://github.com/blagojevicboban/GEAR)** — Open-source WebXR platform allowing schools to upload, manage, and interact with 3D digital twins of industrial equipment on Meta Quest, mobile, and desktop.
- 📦 **[moodle-mod_gear](https://github.com/blagojevicboban/moodle-mod_gear)** — Custom Moodle activity module integrating GEAR 3D/VR simulations and student tracking into the LMS.
- 🎥 **[QuestGear3DStudio](https://github.com/blagojevicboban/QuestGear3DStudio)** & **[QuestGear3DScan](https://github.com/blagojevicboban/QuestGear3DScan)** — Spatial computing toolchain capturing synchronized RGB-D data from Meta Quest 3 headsets to reconstruct high-fidelity 3D meshes using TSDF algorithms.
- 🌐 **[cnn-arvr](https://github.com/blagojevicboban/cnn-arvr)** — Interactive WebXR simulations for computer network hardware training.

---

#### 🌟 4. [LifeLink](https://github.com/blagojevicboban/LifeLink_ESP32App) — Smart Telecare & Safety Bracelet Ecosystem
An IoT safety platform designed for vulnerable patients (elderly, dialysis, diabetic patients) providing autonomous fall detection and cellular emergency alerting without requiring a smartphone:
- 📟 **[LifeLink_ESP32App](https://github.com/blagojevicboban/LifeLink_ESP32App)** — ESP32-S3 firmware in C/C++ (ESP-IDF) managing IMU fall detection algorithms, pulse oximetry, LTE/GSM modem communications, and ultra-low-power sleep modes.
- 📱 **[LifeLink_MobileApp](https://github.com/blagojevicboban/LifeLink_MobileApp)** — Mobile companion app for caregivers to track vitals, geofencing, and emergency alerts.
- 🌐 **[LifeLink_WebSite](https://github.com/blagojevicboban/LifeLink_WebSite)** — Central telecare operations dashboard and real-time monitoring portal.

---

#### 💡 5. Edge AI & High-School Innovation Mentorship
Leading and mentoring high-school students at **Tehnička škola Pirot** in creating real-world applied AI solutions ([edgeai.tsp.edu.rs](https://edgeai.tsp.edu.rs)):
- 🎙️ **Titlovi Uživo** — Offline real-time speech recognition for hearing-impaired students running local Whisper models.
- 🌲 **Čuvar Stare planine** — Edge audio classification for bioacoustic monitoring and chainsaw detection.
- 🚸 **Pametna Zebra** — Computer vision (YOLO) pedestrian detection and autonomous speed warning.
- 🏭 **Kontrola Kvaliteta** — Industrial edge defect detection and sorting on embedded vision kits.
- 👐 **Znakovna Azbuka** — Real-time gesture and sign language recognition with edge camera feedback.

---

### 📬 Connect & Collaborate:
- 💼 **LinkedIn:** [linkedin.com/in/blagojevicboban](https://www.linkedin.com/in/blagojevicboban)
- 🏫 **School:** [Tehnička škola Pirot](http://www.tsp.edu.rs)
- 🌐 **GitHub:** [@blagojevicboban](https://github.com/blagojevicboban)
