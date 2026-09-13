<div align="center">

# Hi, I'm Hamza Vaid

### Computer Engineering @ UC Irvine | Software Engineer | Systems • Embedded • DSP • Full-Stack

I build engineering software across **systems, networking, embedded integration, signal processing, backend infrastructure, and data-intensive applications**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hamza_Vaid-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/hamza-vaid/)
[![GitHub](https://img.shields.io/badge/GitHub-hamzavaid-181717?style=flat&logo=github)](https://github.com/hamzavaid)
[![Email](https://img.shields.io/badge/Email-hamzavaid%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:hamzavaid@gmail.com)

</div>

---

## About Me

I'm a **Computer Engineering student at the University of California, Irvine**, graduating in **2027**, with a **3.787 GPA** and Dean's Honor List recognition.

My work spans:

- **Systems programming** — C/C++, Linux, POSIX sockets, concurrency, synchronization, observability, benchmarking, and sanitizer-backed verification
- **Backend & infrastructure** — Go, Python, FastAPI, PostgreSQL, Redis Streams, Docker, REST APIs, asynchronous workers, and container isolation
- **Embedded & hardware/software integration** — Raspberry Pi, Arduino, serial communications, motor control, instrumentation, and robotics
- **Signal processing & scientific computing** — Radar/Sonar simulation, matched filtering, CA-CFAR, Doppler processing, Kalman tracking, NumPy, and SciPy
- **Full-stack software engineering** — React, Next.js, TypeScript, Node.js, APIs, automated testing, debugging, and technical documentation
- **Applied AI/ML & data engineering** — clinical NLP, PHI de-identification, healthcare data pipelines, and explainable prediction systems

I am especially interested in **systems software, embedded/firmware, computer architecture, robotics, networking, signal processing, infrastructure, and high-performance engineering software**.

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [Online Coding Judge](https://github.com/hamzavaid/Online-Coding-Judge)

**Go • PostgreSQL • Redis Streams • Docker • React/Next.js • Linux**

Full-stack online programming judge with authenticated workflows and asynchronous Python/C++ code execution.

- Go/Gin backend with PostgreSQL persistence via pgx
- Redis Streams queue with dedicated judge worker
- Python and C++23 execution inside isolated Docker containers
- cgroups-v2-aware memory controls, disabled networking, dropped capabilities, read-only root filesystems, and bounded resources
- Role-based access, rate limiting, hidden tests, persisted verdicts, and owner-only results
- Integration, security, sandbox, race-detector, frontend, and production-build testing

</td>
<td width="50%" valign="top">

### [Multithreaded C++ HTTP Server](https://github.com/hamzavaid/multithreaded-cpp-server)

**C++20 • Linux • TCP/IP • POSIX Sockets • Concurrency • CMake/CTest**

HTTP/1.1 subset server built to compare sequential, thread-per-client, and bounded thread-pool architectures.

- Producer-consumer socket queue with mutexes and condition variables
- Timeouts, graceful shutdown, RAII ownership, `/health` and `/metrics`
- Structured JSON logs, latency histograms, throughput, and queue metrics
- Six unit/integration/concurrency/fault-injection suites
- Debug, Release, ASan/UBSan, and TSan verification automation
- **72 passing final regression-suite executions** and a **15-minute soak test handling 69,140 requests with zero reported errors**

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Echorin](https://github.com/hamzavaid/Echorin)

**Python • NumPy • SciPy • PySide6 • Radar/Sonar DSP • Tracking**

Real-time 2D Radar and Sonar signal-processing simulator with end-to-end sensing, detection, tracking, and visualization.

- Delayed/attenuated/noisy echo generation with configurable waveforms
- FFT-based matched filtering and range-profile generation
- Fixed-threshold and **CA-CFAR** detection
- Coherent Doppler FFT processing and radial-velocity estimation
- Mahalanobis-gated association with constant-velocity **Kalman multi-target tracking**
- Responsive PySide6/PyQtGraph GUI, scenario save/load, JSON/CSV export, benchmarks, and **79 automated tests**

</td>
<td width="50%" valign="top">

### [Zim 2.0 Computer Algebra System](https://github.com/hamzavaid/Zim-Computer-Algebraic-System)

**TypeScript • Node.js • Parsing • ASTs • Exact Arithmetic • API/GUI**

Symbolic mathematics engine rebuilt around a modular TypeScript core with CLI and local web interface.

- Strict tokenizer/parser and abstract syntax tree representation
- Exact rational arithmetic and deterministic simplification
- Linear/quadratic and selected higher-degree symbolic solving
- Exact Gaussian elimination for simultaneous linear systems
- Domain-aware rewrite safety and transformation tracing
- Versioned JSON-safe API, CLI/REPL, LaTeX/MathML formatting, local web GUI, and end-to-end testing

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Anteater Poker](https://github.com/hamzavaid/anteaterpoker)

**C • Networking • Client/Server • Make • Team Software Engineering**

Five-person software engineering project implementing a networked Texas Hold'em application in C.

- Central server synchronizes players, bots, game state, legal actions, and scoring
- Separate client/server architecture
- Make-based builds and release packaging
- Functional testing, debugging, integration, specifications, and user documentation

</td>
<td width="50%" valign="top">

### [Iceman Game Simulation](https://github.com/hamzavaid/Iceman-Project)

**C++ • OOP • State Management • Simulation • Debugging**

Multi-file C++ simulation centered on object-oriented design and a world-state/actor architecture.

- Inheritance and polymorphism across an actor hierarchy
- Entity movement, collision, spawning, resources, and state transitions
- Deterministic simulation behavior and world-state management
- Modular class design and cross-object debugging

</td>
</tr>
</table>

---

## Engineering Experience

### Software Engineer — Sihha

**May 2026 – Present | Remote**

Developing clinical NLP and data infrastructure that transforms hospital discharge summaries into structured healthcare data.

- Build **Python/FastAPI** backend services and integrate outputs with React
- Develop PHI de-identification using **Presidio, spaCy/scispaCy, custom recognizers, and structural NLP**
- Achieved approximately **0.994 synthetic PHI recall** in evaluation
- Work with **OMOP, SNOMED CT, ICD-10-CM, and RxNorm**
- Support explainable **30-day readmission-risk prediction**
- Optimize NLP pipeline performance, including approximately **72 ms/document** de-identification processing in reported testing

### Computer Programmer — SEDS at UC Irvine Rover Project

**Oct 2025 – Jun 2026 | Irvine, CA**

Contributed to an interdisciplinary student-built rover across software integration, embedded systems, and validation.

- Worked with **C/C++, Python, Raspberry Pi, Arduino, motor control, and serial communications**
- Integrated software with rover hardware and subsystem interfaces
- Used Git-based development, instrumentation, iterative testing, and root-cause debugging
- Collaborated with computer, electrical, and mechanical engineering contributors

### Independent Software Developer

**Jan 2021 – May 2023 | Remote**

Built and deployed event-driven Discord applications for online communities with **100,000+ active members**.

- Node.js, JavaScript/TypeScript, Python, Discord.js, and REST APIs
- Moderation, permissions, event scheduling, logging, analytics, and automation
- Asynchronous/event-driven architectures designed for high-traffic environments
- Direct requirements gathering, deployment, and maintenance with community administrators

---

## Technical Stack

### Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat)

### Backend, Data & Infrastructure

`Go/Gin` · `Python/FastAPI` · `Node.js` · `React` · `Next.js` · `REST APIs` · `PostgreSQL/pgx` · `Redis Streams` · `MongoDB` · `Docker` · `Authentication` · `RBAC` · `Asynchronous Workers` · `Data Engineering`

### Systems & Reliability

`Linux/UNIX` · `POSIX Sockets` · `TCP/IP` · `HTTP/1.1` · `Multithreading` · `Thread Pools` · `Synchronization` · `Atomics` · `RAII` · `CMake` · `CTest` · `GDB` · `ASan` · `UBSan` · `TSan` · `Stress/Soak Testing` · `Benchmarking` · `Fault Injection` · `Structured Logging` · `Metrics`

### Embedded, Hardware & Robotics

`Embedded Systems` · `Raspberry Pi` · `Arduino` · `Serial Communications` · `Motor Control` · `Digital Logic` · `Computer Architecture` · `Circuit Design` · `Oscilloscope` · `Logic Analyzer` · `DMM` · `Function Generator` · `Hardware/Software Integration`

### Signal Processing & Scientific Computing

`NumPy` · `SciPy` · `Radar Simulation` · `Sonar Simulation` · `Matched Filtering` · `Range Processing` · `CA-CFAR` · `Doppler FFTs` · `Radial-Velocity Estimation` · `Kalman Filtering` · `Multi-Target Tracking` · `Mahalanobis Gating` · `PySide6` · `PyQtGraph`

### AI, NLP & Healthcare Data

`Machine Learning` · `NLP` · `Presidio` · `spaCy` · `scispaCy` · `Clinical NLP` · `PHI De-identification` · `OMOP` · `SNOMED CT` · `ICD-10-CM` · `RxNorm`

---

## Education

### University of California, Irvine

**B.S. Computer Engineering | Expected 2027 | GPA: 3.787**

**Dean's Honor List:** Fall 2025 · Winter 2026 · Spring 2026

Selected coursework:

`Computer Systems & C` · `Digital Systems` · `Digital Logic Lab` · `Data Structures & Algorithms` · `Computer Networks` · `Organization of Digital Computers` · `Signals & Systems` · `Electronics I–III` · `Circuit/Network Analysis`

### El Camino College

**A.S. Mathematics for Transfer**  
**A.S. Physics for Transfer**  
Degrees conferred with honors

Physics Academic Excellence Award · MESA · Honors Program · Dean's List

---

## Current Focus

I'm currently deepening my portfolio in:

- Systems and infrastructure engineering
- Secure sandboxing and distributed/asynchronous worker systems
- Embedded firmware and hardware/software integration
- Radar/Sonar DSP, estimation, and tracking
- FPGA / RTL and digital hardware design
- Operating systems and low-level Linux
- Performance-oriented C++ and Go services

---

### Let's Connect

I'm interested in opportunities involving **computer engineering, systems software, embedded systems, backend infrastructure, robotics, networking, hardware/software integration, signal processing, and high-performance software**.

[LinkedIn](https://www.linkedin.com/in/hamza-vaid/) · [GitHub](https://github.com/hamzavaid) · [Email](mailto:hamzavaid@gmail.com)
