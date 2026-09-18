<div align="center">

# Hi, I'm Hamza Vaid

### Computer Engineering @ UC Irvine | Software Engineer | Systems • Simulation • Infrastructure • Embedded • DSP

I build engineering software across **systems programming, distributed infrastructure, scientific simulation, signal processing, embedded integration, and applied data/ML systems**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hamza_Vaid-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/hamza-vaid/)
[![GitHub](https://img.shields.io/badge/GitHub-hamzavaid-181717?style=flat&logo=github)](https://github.com/hamzavaid)
[![Email](https://img.shields.io/badge/Email-hamzavaid%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:hamzavaid@gmail.com)

</div>

---

## About Me

I'm a **Computer Engineering student at the University of California, Irvine**, graduating in **2027**, with a **3.818 GPA** and Dean's Honor List recognition.

My work spans:

- **Systems & performance engineering** — C/C++, Linux, POSIX sockets, concurrency, thread pools, synchronization, profiling, benchmarking, observability, and sanitizer-backed verification
- **Backend & distributed infrastructure** — Go, Python, FastAPI, PostgreSQL, Redis Streams, Docker, Kubernetes, asynchronous workers, transactional outbox patterns, retries/DLQs, and autoscaling
- **Scientific simulation & numerical computing** — deterministic simulation architecture, numerical integration, N-body mechanics, engineering diagnostics, OpenGL visualization, NumPy, and SciPy
- **Signal processing & estimation** — Radar/Sonar simulation, matched filtering, CA-CFAR, Doppler processing, Kalman filtering, multi-target tracking, and data association
- **Embedded & hardware/software integration** — Raspberry Pi, Arduino, serial communications, motor control, instrumentation, digital systems, and robotics
- **Applied AI/ML & data engineering** — clinical NLP, PHI de-identification, healthcare data pipelines, structured medical data, and explainable prediction systems

I am especially interested in **systems software, simulation, infrastructure, embedded/firmware, robotics, networking, computer architecture, signal processing, and high-performance engineering software**.

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [Aetherion](https://github.com/hamzavaid/Aetherion)

**C++20 • OpenGL • CMake/CTest • Numerical Methods • Simulation**

Interactive deterministic 3D mechanics simulator with a testable double-precision physics core and engineering-focused desktop interface.

- Newtonian **N-body gravity** with SI-valued double-precision simulation state
- Runtime-selectable **Semi-Implicit Euler, Velocity Verlet, and RK4** integrators
- Orbit regression tests plus energy and momentum error diagnostics
- Camera-relative instanced OpenGL rendering for small and astronomical scales
- Scene picking, adaptive engineering grid, trails, checkpoints, and state restoration
- Renderer-optional/headless builds and cross-platform Linux/WSL2/Windows guidance

</td>
<td width="50%" valign="top">

### [Online Coding Judge](https://github.com/hamzavaid/Online-Coding-Judge)

**Go • PostgreSQL • Redis Streams • Docker • Kubernetes • Next.js**

Full-stack programming judge with authenticated workflows and asynchronous Python/C++ code execution.

- Go/Gin backend with PostgreSQL persistence and Redis Streams
- Isolated Python/C++23 execution with non-root containers and bounded resources
- Transactional outbox, worker leases, stale-worker fencing, retries, and dead-letter handling
- Horizontally concurrent workers with Kubernetes deployment and **HPA scaling from 3–30 replicas**
- Default-deny networking, digest-pinned images, TLS ingress, rate limits, and CI image scanning
- Backend, Redis, execution, sandbox/security, race-detector, frontend, and deployment tests

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Multithreaded C++ HTTP Server](https://github.com/hamzavaid/multithreaded-cpp-server)

**C++20 • Linux • TCP/IP • POSIX Sockets • Concurrency • CMake/CTest**

HTTP/1.1 subset server built to compare sequential, thread-per-client, and bounded thread-pool architectures.

- Bounded producer-consumer socket queue using mutexes and condition variables
- Timeouts, graceful shutdown, RAII ownership, `/health`, `/compute`, `/sleep`, and `/metrics`
- Structured JSON logging, throughput metrics, latency histograms, and queue-depth observability
- Debug, Release, ASan/UBSan, and TSan verification automation
- **72 passing final regression-suite executions**
- **15-minute soak test: 69,140 requests with zero reported errors**

</td>
<td width="50%" valign="top">

### [Echorin](https://github.com/hamzavaid/Echorin)

**Python • NumPy • SciPy • PySide6 • Radar/Sonar DSP • Tracking**

Real-time 2D Radar and Sonar signal-processing simulator with end-to-end sensing, detection, tracking, and visualization.

- Delayed, attenuated, noisy echo generation with configurable waveforms
- FFT-based matched filtering and range-profile generation
- Fixed-threshold and **CA-CFAR** detection
- Coherent Doppler processing and radial-velocity estimation
- Mahalanobis-gated association with **Kalman multi-target tracking**
- Responsive PySide6/PyQtGraph GUI, scenario save/load, exports, benchmarks, and **79 automated tests**

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Zim 2.0](https://github.com/hamzavaid/Zim-Computer-Algebraic-System)

**TypeScript • Node.js • Parsing • ASTs • Exact Arithmetic • API/GUI**

Symbolic mathematics engine with a modular TypeScript core, CLI, serialized API, and local web interface.

- Strict tokenizer/parser and abstract syntax tree representation
- Exact rational arithmetic and deterministic simplification
- Linear, quadratic, selected higher-degree, rational, and transcendental solving
- Exact Gaussian elimination for simultaneous linear systems
- Domain-aware rewrite safety and transformation tracing
- LaTeX/MathML output, CLI/REPL, GUI workflows, and automated tests

</td>
<td width="50%" valign="top">

### [Anteater Poker](https://github.com/hamzavaid/anteaterpoker)

**C • Networking • Client/Server • Make • Team Software Engineering**

Five-person UCI software engineering project implementing a networked Texas Hold'em game with custom Anteater-themed mechanics.

- Central server manages connected players, bots, game state, legal actions, and scoring
- Separate client/server architecture with synchronized gameplay
- Make-based builds and executable release packaging
- Functional testing, debugging, software integration, specifications, and user documentation

</td>
</tr>
</table>

---

## Engineering Experience

### Software Engineer — Sihha

**May 2026 – Present | Remote**

Develop clinical NLP middleware that converts unstructured hospital discharge summaries into structured, coded healthcare data and supports explainable readmission-risk prediction.

- Build **Python/FastAPI** backend services and integrate outputs with React
- Develop PHI de-identification using **Presidio, spaCy/scispaCy, custom recognizers, and structural NLP**
- Achieved approximately **0.994 synthetic PHI recall** in de-identification evaluation
- Work with **OMOP, SNOMED CT, ICD-10-CM, and RxNorm**
- Contribute to explainable **30-day hospital readmission-risk prediction**
- Optimize pipeline performance, including approximately **72 ms/document** de-identification processing in reported testing

### Computer Programmer — SEDS at UC Irvine Rover Project

**Oct 2025 – Jun 2026 | Irvine, CA**

Contributed software and integration work to a student-built rover as part of an interdisciplinary engineering team.

- Worked with **C/C++, Python, Raspberry Pi, Arduino, motor control, and serial communications**
- Supported software development and hardware/software integration
- Used instrumentation, iterative testing, Git-based workflows, and root-cause debugging
- Collaborated across computer, electrical, and mechanical engineering disciplines

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

### Systems, Infrastructure & Reliability

`Linux/UNIX` · `POSIX Sockets` · `TCP/IP` · `HTTP/1.1` · `Multithreading` · `Thread Pools` · `Synchronization` · `Atomics` · `RAII` · `CMake` · `CTest` · `GDB` · `ASan` · `UBSan` · `TSan` · `Go Race Detector` · `Benchmarking` · `Stress/Soak Testing` · `Fault Injection` · `Structured Logging` · `Metrics`

### Backend & Distributed Systems

`Go/Gin` · `Python/FastAPI` · `Node.js` · `React` · `Next.js` · `REST APIs` · `PostgreSQL/pgx` · `Redis Streams` · `MongoDB` · `Docker` · `Kubernetes` · `Kustomize` · `HPA` · `Authentication` · `RBAC` · `Transactional Outbox` · `Retry/DLQ Workflows` · `Distributed Workers`

### Simulation, DSP & Scientific Computing

`OpenGL` · `Numerical Integration` · `N-Body Simulation` · `Deterministic Simulation` · `NumPy` · `SciPy` · `Radar Simulation` · `Sonar Simulation` · `Matched Filtering` · `CA-CFAR` · `Doppler FFTs` · `Kalman Filtering` · `Multi-Target Tracking` · `Mahalanobis Gating` · `PySide6` · `PyQtGraph`

### Embedded, Hardware & Robotics

`Embedded Systems` · `Raspberry Pi` · `Arduino` · `Serial Communications` · `Motor Control` · `Digital Logic` · `Computer Architecture` · `Circuit Design` · `Oscilloscope` · `Logic Analyzer` · `DMM` · `Function Generator` · `Hardware/Software Integration`

### AI, NLP & Healthcare Data

`Machine Learning` · `NLP` · `Presidio` · `spaCy` · `scispaCy` · `Clinical NLP` · `PHI De-identification` · `OMOP` · `SNOMED CT` · `ICD-10-CM` · `RxNorm` · `Data Engineering`

---

## Education

### University of California, Irvine

**B.S. Computer Engineering | Expected 2027 | GPA: 3.818**

**Dean's Honor List:** Fall 2025 · Winter 2026 · Spring 2026

Selected completed coursework:

`Computer Systems & C` · `Digital Systems` · `Digital Logic Lab` · `Data Structures & Algorithms` · `Computer Networks` · `Organization of Digital Computers` · `Discrete-Time Signals & Systems` · `Continuous-Time Signals & Systems` · `Electronics I–III` · `Circuit/Network Analysis`

**Summer 2026:** 4.000 term GPA across Electronics III, Electronics III Lab, and Engineering Communications.

### El Camino College

**A.S. Mathematics for Transfer**  
**A.S. Physics for Transfer**  
Degrees conferred with honors

Physics Academic Excellence Award · MESA · Honors Program · Dean's List

---

## Current Focus

I'm currently deepening my work in:

- Performance-oriented **C++ and Go systems**
- Distributed/asynchronous backend infrastructure
- Secure sandboxing and containerized execution
- Deterministic physics and engineering simulation
- Embedded systems and hardware/software integration
- Radar/Sonar DSP, estimation, and tracking
- Computer architecture, digital hardware, and VLSI
- Applied AI/data systems

---

### Let's Connect

I'm interested in opportunities involving **computer engineering, systems software, simulation, embedded systems, backend infrastructure, robotics, networking, hardware/software integration, signal processing, and high-performance software**.

[LinkedIn](https://www.linkedin.com/in/hamza-vaid/) · [GitHub](https://github.com/hamzavaid) · [Email](mailto:hamzavaid@gmail.com)
