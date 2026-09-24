<div align="center">

# Hi, I'm Hamza Vaid

### Computer Engineering @ UC Irvine | Software Engineer | Systems • RTL/Verification • Simulation • Embedded • DSP

I build engineering software across **systems programming, digital hardware verification, scientific simulation, signal processing, distributed infrastructure, embedded systems, and applied data/ML**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hamza_Vaid-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/hamza-vaid/)
[![GitHub](https://img.shields.io/badge/GitHub-hamzavaid-181717?style=flat&logo=github)](https://github.com/hamzavaid)
[![Email](https://img.shields.io/badge/Email-hamzavaid%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:hamzavaid@gmail.com)

</div>

---

## About Me

I'm a **Computer Engineering student at the University of California, Irvine**, graduating in **2027**, with a **3.818 GPA** and Dean's Honor List recognition.

My work spans:

- **Systems & performance engineering** — C/C++, Linux, POSIX sockets, concurrency, thread pools, synchronization, observability, benchmarking, sanitizers, and reliability testing
- **Digital hardware & verification** — Verilog/SystemVerilog, RISC-V/RV32I, RTL design, cocotb, architectural reference models, retirement scoreboards, Icarus Verilog, Verilator, and waveform debugging
- **Scientific simulation & numerical computing** — deterministic simulation architecture, numerical integration, N-body mechanics, electrostatics/electromagnetics, engineering diagnostics, and OpenGL visualization
- **Signal processing & estimation** — Radar/Sonar simulation, matched filtering, CA-CFAR, Range-Doppler processing, Kalman filtering, multi-target tracking, and data association
- **Backend & distributed infrastructure** — Go, Python, PostgreSQL, Redis Streams, Docker, Kubernetes, asynchronous workers, transactional outbox patterns, retries/DLQs, and autoscaling
- **Embedded & robotics** — Raspberry Pi, Arduino, serial communications, motor control, UAV systems, ArduPilot, telemetry, and hardware/software integration
- **Applied AI/ML & data engineering** — clinical NLP, PHI de-identification, healthcare data pipelines, structured medical data, and explainable prediction systems

I am especially interested in **systems software, computer architecture, RTL/verification, simulation, embedded/firmware, robotics, networking, signal processing, and high-performance engineering software**.

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [Aetherion](https://github.com/hamzavaid/Aetherion)

**C++20 • OpenGL • CMake/CTest • Numerical Methods • Physics Simulation**

Interactive deterministic 3D mechanics and field simulator with a testable double-precision physics core.

- Newtonian **N-body gravity**, Coulomb electrostatics, and Lorentz-force dynamics
- Runtime-selectable **Semi-Implicit Euler, Velocity Verlet, RK4, and Boris integration**
- Electric, magnetic, and gravity vector-field visualization with field-line tracing
- Engineering diagnostics, checkpointable state, versioned scene persistence, and camera-relative OpenGL rendering

</td>
<td width="50%" valign="top">

### [RISC-V SoC Verification Lab](https://github.com/hamzavaid/riscv-soc-verification)

**SystemVerilog • cocotb • Python • RV32I • Icarus • Verilator**

Incremental verification environment for a scoped RV32I teaching processor.

- Independent Python architectural model and **instruction-retirement scoreboard**
- Directed arithmetic, logic, memory, branch, and jump program verification
- Checks PC, instruction, register writeback, memory transactions, and trap status at every retirement
- Optional **VCD/FST waveforms**, JSON failure traces, GTKWave debugging, and dual-simulator workflows

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Online Coding Judge](https://github.com/hamzavaid/Online-Coding-Judge)

**Go • PostgreSQL • Redis Streams • Docker • Kubernetes • Next.js**

Full-stack programming judge with authenticated workflows and sandboxed Python/C++ execution.

- Isolated execution with cgroup-aware resource limits and hardened containers
- Transactional outbox, worker leases, stale-worker fencing, retries, and dead-letter handling
- Horizontally concurrent workers with **Kubernetes HPA scaling from 3–30 replicas**
- Backend, Redis, execution, sandbox/security, race-detector, frontend, and deployment testing

</td>
<td width="50%" valign="top">

### [Echorin v1.1](https://github.com/hamzavaid/Echorin)

**Python • NumPy • SciPy • PySide6 • Radar/Sonar DSP • Tracking**

Real-time Radar and Sonar simulator with end-to-end sensing, detection, tracking, and engineering visualization.

- FFT matched filtering, **CA-CFAR**, coherent Doppler processing, and radial-velocity estimation
- Mahalanobis-gated association with **Kalman multi-target tracking**
- Full **Range-Doppler heatmap**, track velocity/covariance overlays, and measurement inspection
- Dockable responsive PySide6/PyQtGraph workspace with persistent layouts, themes, replay/export, and benchmarks

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Multithreaded C++ HTTP Server](https://github.com/hamzavaid/multithreaded-cpp-server)

**C++20 • Linux • TCP/IP • POSIX Sockets • Concurrency • CMake/CTest**

HTTP/1.1 subset server comparing sequential, thread-per-client, and bounded worker-pool architectures.

- Bounded producer-consumer socket queue with mutexes and condition variables
- Deadlines, graceful shutdown, RAII ownership, structured logging, metrics, and fault injection
- Debug, Release, **ASan/UBSan**, and **TSan** verification automation
- **72 passing final regression-suite executions** and a **15-minute soak test with 69,140 requests and zero reported errors**

</td>
<td width="50%" valign="top">

### [Zim 2.5](https://github.com/hamzavaid/Zim-Computer-Algebraic-System)

**TypeScript • Parsing/ASTs • Symbolic Algebra • Calculus • API/GUI**

Computer algebra system with exact symbolic manipulation, certified analysis, calculus, CLI, and graphical interfaces.

- Exact rational arithmetic, deterministic simplification, equations, inequalities, and systems
- Certified polynomial root analysis, nonlinear-system strategies, and typed solution sets
- Symbolic differentiation, conservative limits, verified symbolic integration, and **arbitrary-precision numerical quadrature**
- Versioned API, derivation graphs, CLI/REPL, MathML/LaTeX rendering, browser tests, and benchmarks

</td>
</tr>
</table>

---

## Additional Projects

- **[Kairo](https://github.com/hamzavaid/Kairo-Discord-Bot)** — TypeScript Discord music/entertainment platform under reconstruction with a reusable `@kairo/music-engine` API, strict workspace boundaries, tooling, and an early canonical-track parser
- **RISC-V Single-Cycle Processor** — 32-bit processor implemented in Verilog with ALU, register file, memories, datapath/control logic, testbenches, and waveform-based verification
- **[Anteater Poker](https://github.com/hamzavaid/anteaterpoker)** — Five-person C networking project implementing a synchronized client/server Texas Hold'em game with custom mechanics
- **[Iceman](https://github.com/hamzavaid/Iceman-Project)** — Multi-file C++ simulation/game project using inheritance, polymorphism, world-state management, collision logic, and modular class design
- **[Vote Bot](https://github.com/hamzavaid/Vote-Bot)** — Node.js/Discord.js command-based voting bot with dynamic command loading, permissions, cooldowns, and event-driven state management

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

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-RTL-6E4C13?style=flat)
![Verilog](https://img.shields.io/badge/Verilog-HDL-8A2BE2?style=flat)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat)

### Systems, Networking & Reliability

`Linux/UNIX` · `POSIX Sockets` · `TCP/IP` · `HTTP/1.1` · `Multithreading` · `Thread Pools` · `Synchronization` · `Atomics` · `RAII` · `CMake` · `CTest` · `GDB` · `ASan` · `UBSan` · `TSan` · `Go Race Detector` · `Benchmarking` · `Stress/Soak Testing` · `Fault Injection` · `Structured Logging` · `Metrics`

### Digital Hardware & Verification

`Verilog` · `SystemVerilog` · `RISC-V/RV32I` · `RTL Design` · `cocotb` · `Architectural Reference Models` · `Scoreboards` · `Retirement Traces` · `Directed Testing` · `Icarus Verilog` · `Verilator` · `GTKWave` · `VCD/FST` · `Testbenches` · `Waveform Debugging`

### Backend & Distributed Systems

`Go/Gin` · `Python/FastAPI` · `Node.js` · `React` · `Next.js` · `REST APIs` · `PostgreSQL/pgx` · `Redis Streams` · `MongoDB` · `Docker` · `Kubernetes` · `Kustomize` · `HPA` · `Authentication` · `RBAC` · `Transactional Outbox` · `Retry/DLQ Workflows` · `Distributed Workers`

### Simulation, DSP & Scientific Computing

`OpenGL` · `Numerical Integration` · `N-Body Simulation` · `Coulomb Electrostatics` · `Lorentz Dynamics` · `Boris Integration` · `Vector Fields` · `Field-Line Tracing` · `NumPy` · `SciPy` · `Radar/Sonar Simulation` · `Matched Filtering` · `CA-CFAR` · `Range-Doppler Processing` · `Kalman Filtering` · `Multi-Target Tracking` · `Mahalanobis Gating` · `PySide6` · `PyQtGraph`

### Embedded, Robotics & UAVs

`Embedded Systems` · `Raspberry Pi` · `Arduino` · `ESP32` · `Serial Communications` · `UART` · `PWM` · `Motor Control` · `ArduPilot` · `Flight Controllers` · `ExpressLRS` · `GPS` · `UAV Telemetry` · `Ground-Control Stations` · `LiDAR/Sonar/Optical Flow` · `Hardware/Software Integration`

### AI, NLP & Healthcare Data

`Machine Learning` · `NLP` · `Presidio` · `spaCy` · `scispaCy` · `Clinical NLP` · `PHI De-identification` · `OMOP` · `SNOMED CT` · `ICD-10-CM` · `RxNorm` · `Data Engineering`

---

## Education

### University of California, Irvine

**B.S. Computer Engineering | Expected 2027 | GPA: 3.818**

**Dean's Honor List:** Fall 2025 · Winter 2026 · Spring 2026

Selected completed coursework:

`Computer Systems & C` · `Digital Systems` · `Digital Logic Lab` · `Data Structures & Algorithms` · `Computer Networks` · `Organization of Digital Computers` · `Discrete-Time Signals & Systems` · `Continuous-Time Signals & Systems` · `Electronics I–III` · `Circuit/Network Analysis`

**Current Fall 2026 coursework (22 units):**

`Organization of Digital Computers Lab` · `Data & Knowledge Science` · `VLSI` · `Electrical Engineering Analysis` · `Senior Design I` · `Drones/UAV Systems`

The Drones course is a hands-on build-and-flight course covering **ArduPilot, flight controllers, ESP32/ExpressLRS, power systems, GPS/positioning, telemetry, autonomous waypoint missions, Remote ID, and UTM concepts**.

### El Camino College

**A.S. Mathematics for Transfer**  
**A.S. Physics for Transfer**  
Degrees conferred with honors

Physics Academic Excellence Award · MESA · Honors Program · Dean's List

---

## Current Focus

I'm currently deepening my work in:

- **RTL design and verification** with RISC-V, SystemVerilog, cocotb, and architectural scoreboarding
- Performance-oriented **C++ and Go systems**
- Deterministic mechanics/electromagnetics simulation and engineering visualization
- Embedded systems, UAVs, and hardware/software integration
- Radar/Sonar DSP, estimation, and tracking
- Distributed/asynchronous backend infrastructure and secure sandboxing
- Computer architecture and VLSI
- Symbolic/numerical mathematics software
- Applied AI/data systems

---

### Let's Connect

I'm interested in opportunities involving **computer engineering, systems software, RTL/verification, simulation, embedded systems, backend infrastructure, robotics/UAVs, networking, hardware/software integration, signal processing, and high-performance software**.

[LinkedIn](https://www.linkedin.com/in/hamza-vaid/) · [GitHub](https://github.com/hamzavaid) · [Email](mailto:hamzavaid@gmail.com)
