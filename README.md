<div align="center">

# Hi, I'm Hamza Vaid

### Computer Engineering @ UC Irvine | Software Engineer | Systems • RTL/Verification • Robotics • Simulation • DSP

I build engineering systems across **systems programming, digital hardware verification, robotics/autonomy, scientific simulation, signal processing, distributed infrastructure, and embedded software**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hamza_Vaid-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/hamza-vaid/)
[![GitHub](https://img.shields.io/badge/GitHub-hamzavaid-181717?style=flat&logo=github)](https://github.com/hamzavaid)
[![Email](https://img.shields.io/badge/Email-hamzavaid%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:hamzavaid@gmail.com)

</div>

---

## About Me

I'm a **Computer Engineering student at the University of California, Irvine**, graduating in **2027**, with a **3.818 GPA** and Dean's Honor List recognition.

My work spans:

- **Systems & performance engineering** — C/C++, Linux, POSIX sockets, concurrency, observability, benchmarking, sanitizers, and reliability testing
- **Digital hardware & verification** — Verilog/SystemVerilog, RISC-V/RV32I, cocotb, architectural reference models, scoreboards, Icarus Verilog, Verilator, and waveform debugging
- **Robotics & autonomous systems** — UAVs, robotic manipulators, embedded control, human-machine interfaces, autonomous navigation, sensing, and hardware/software integration
- **Scientific simulation & numerical computing** — deterministic simulation, numerical integration, N-body mechanics, electromagnetics, scientific visualization, NumPy/SciPy, and OpenGL
- **Signal processing & estimation** — Radar/Sonar simulation, array processing, matched filtering, CA-CFAR, Range-Doppler/Range-Angle processing, Kalman filtering, and multi-target tracking
- **Backend & distributed infrastructure** — Go, Python, PostgreSQL, Redis Streams, Docker, Kubernetes, asynchronous workers, transactional outbox patterns, retries/DLQs, and autoscaling
- **Applied AI/ML & data engineering** — clinical NLP, PHI de-identification, healthcare data pipelines, and explainable prediction systems

I am especially interested in **systems software, computer architecture, RTL/verification, robotics, embedded/firmware, simulation, autonomous systems, networking, signal processing, and high-performance engineering software**.

---

## Current Academic & Robotics Projects

<table>
<tr>
<td width="50%" valign="top">

### MIMIC — Motion-Interpreted Manipulation and Intelligent Control

**Senior Design • Wearable Sensing • Computer Vision • Robotics • Control**

Platform-agnostic human-motion interpretation and safe-control system for mapping multimodal human state into commands for cyber-physical systems.

- Wearable finger sensing, IMU orientation, and vision/depth-based motion estimation
- MediaPipe/OpenCV-based tracking with multimodal sensor-fusion architecture
- Safe abstract command layer separated from device-specific control
- Robotic-arm MVP with teleoperation, IK, trajectory limits, and safety supervision; drone/rover adapters as extensions

</td>
<td width="50%" valign="top">

### EECS 195 — Autonomous UAV Project

**ArduPilot • ESP32/ExpressLRS • GPS • Telemetry • Embedded Systems**

Hands-on team project building and flying a complete UAV from avionics and power systems through autonomous missions.

- Flight-controller configuration, radio control, failsafes, batteries, ESCs, and brushless motors
- GPS and positioning systems with telemetry to a ground-control station
- Autonomous **takeoff → waypoint → autoland** mission development
- Advanced project path includes **LLM-in-the-loop agentic control** and **vision-based navigation**

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Robotics at UCI — ZotBotics Level 2

**6-Axis Robot Arm • Embedded Systems • 3D Printing • Automation**

Six-person team project designing and building a six-axis 3D-printed robotic arm from scratch.

- Mechanical and embedded-system integration
- Multi-axis robot programming and control
- Custom manufactured/3D-printed manipulator components
- Technical sorting and industrial-style automation competition tasks

</td>
</tr>
</table>

---

## Featured Software & Engineering Projects

<table>
<tr>
<td width="50%" valign="top">

### [Aetherion](https://github.com/hamzavaid/Aetherion)

**C++20 • OpenGL • CMake/CTest • Numerical Methods • Physics Simulation**

Interactive deterministic 3D mechanics and electromagnetic-field simulator.

- Newtonian **N-body gravity**, Coulomb electrostatics, and Lorentz-force dynamics
- Runtime-selectable **Semi-Implicit Euler, Velocity Verlet, RK4, and Boris integration**
- Electric, magnetic, and gravity field sampling/tracing with scientific probes and magnitude heatmaps
- Camera-relative rendering, configurable reference frames, diagnostics, plotting, checkpoints, and interactive body/probe manipulation

</td>
<td width="50%" valign="top">

### [RISC-V SoC Verification Lab](https://github.com/hamzavaid/riscv-soc-verification)

**SystemVerilog • cocotb • Python • RV32I • Icarus • Verilator**

Incremental verification environment for a scoped RV32I teaching processor.

- Independent Python architectural model and **instruction-retirement scoreboard**
- Directed arithmetic, logic, memory, branch, and jump verification
- Checks PC, instruction, register writeback, memory transactions, and trap status at every retirement
- Optional **VCD/FST waveforms**, JSON failure traces, GTKWave debugging, and dual-simulator workflows

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Online Coding Judge](https://github.com/hamzavaid/Online-Coding-Judge)

**Go • PostgreSQL • Redis Streams • Docker • Kubernetes • Next.js**

Full-stack programming judge with authenticated workflows and sandboxed Python/C++ execution.

- Hardened container execution with cgroup-aware CPU/memory/process controls
- Transactional outbox, worker leases, stale-worker fencing, retries, and dead-letter handling
- Horizontally concurrent workers with **Kubernetes HPA scaling from 3–30 replicas**
- Backend, Redis, execution, sandbox/security, race-detector, frontend, and deployment testing

</td>
<td width="50%" valign="top">

### [Echorin v1.3](https://github.com/hamzavaid/Echorin)

**Python • NumPy • SciPy • PySide6 • Radar/Sonar DSP • Tracking**

Real-time Radar and Sonar simulator with array sensing, detection, tracking, and engineering visualization.

- FFT matched filtering, **CA-CFAR**, coherent Doppler processing, and Kalman multi-target tracking
- Eight-element receiver array with **Bartlett range-angle processing** and signal-derived bearings
- Full **Range-Doppler and Range-Angle** engineering views with track/covariance inspection
- Moving sensor platforms with rigid-body receiver mounts, multiple motion models, moving-receiver Doppler, and PPI path/heading overlays

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Multithreaded C++ HTTP Server](https://github.com/hamzavaid/multithreaded-cpp-server)

**C++20 • Linux • TCP/IP • POSIX Sockets • Concurrency • CMake/CTest**

HTTP/1.1 subset server comparing sequential, thread-per-client, and bounded worker-pool architectures.

- Bounded producer-consumer queue with mutexes and condition variables
- Deadlines, graceful shutdown, RAII ownership, structured logging, metrics, and fault injection
- Debug, Release, **ASan/UBSan**, and **TSan** verification automation
- **72 passing final regression-suite executions** and a **15-minute soak test with 69,140 requests and zero reported errors**

</td>
<td width="50%" valign="top">

### [Zim 2.5.3](https://github.com/hamzavaid/Zim-Computer-Algebraic-System)

**TypeScript • ASTs • Symbolic Algebra • Calculus • Scientific Computing**

Computer algebra system with exact symbolic manipulation, certified analysis, numerical calculus, and graphical/CLI interfaces.

- Exact arithmetic, deterministic simplification, equations, inequalities, nonlinear systems, and certified polynomial analysis
- Symbolic differentiation, conservative limits, verified symbolic integration, and **arbitrary-precision numerical quadrature**
- Versioned API, derivation graphs, CLI/REPL, MathML/LaTeX rendering, browser tests, and benchmarks
- Integrated **scientific calculator** with exact/decimal modes, degrees/radians, `Ans`, persistent history, factorial/logarithms, constants, and native MathML output

</td>
</tr>
</table>

---

## Additional Projects

- **[Kairo](https://github.com/hamzavaid/Kairo-Discord-Bot)** — TypeScript Discord music platform with a reusable `@kairo/music-engine`, YouTube/Spotify/MusicBrainz metadata adapters, cross-provider matching, per-guild queues, Discord voice playback, yt-dlp/FFmpeg streaming, MongoDB-backed playlists/liked songs, collection import, and interactive Discord library controls
- **RISC-V Single-Cycle Processor** — 32-bit Verilog processor with ALU, register file, memories, datapath/control logic, testbenches, and waveform-based verification
- **[Anteater Poker](https://github.com/hamzavaid/anteaterpoker)** — Five-person C networking project implementing a synchronized client/server Texas Hold'em game with custom mechanics
- **[Iceman](https://github.com/hamzavaid/Iceman-Project)** — Multi-file C++ simulation/game project using inheritance, polymorphism, world-state management, collision logic, and modular class design
- **[Vote Bot](https://github.com/hamzavaid/Vote-Bot)** — Node.js/Discord.js voting bot with dynamic command loading, permissions, cooldowns, and event-driven state management

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

`Go/Gin` · `Python/FastAPI` · `Node.js` · `React` · `Next.js` · `REST APIs` · `PostgreSQL/pgx` · `Redis Streams` · `MongoDB/Mongoose` · `Docker` · `Kubernetes` · `Kustomize` · `HPA` · `Authentication` · `RBAC` · `Transactional Outbox` · `Retry/DLQ Workflows` · `Distributed Workers`

### Simulation, DSP & Scientific Computing

`OpenGL` · `Numerical Integration` · `N-Body Simulation` · `Coulomb Electrostatics` · `Lorentz Dynamics` · `Boris Integration` · `Scientific Probes` · `Field-Line Tracing` · `NumPy` · `SciPy` · `Radar/Sonar Simulation` · `Receiver Arrays` · `Bartlett Processing` · `Matched Filtering` · `CA-CFAR` · `Range-Doppler` · `Range-Angle` · `Kalman Filtering` · `Multi-Target Tracking` · `PySide6` · `PyQtGraph`

### Embedded, Robotics & Autonomous Systems

`Embedded Systems` · `Raspberry Pi` · `Arduino` · `ESP32` · `Serial Communications` · `UART` · `PWM` · `Motor Control` · `ArduPilot` · `Flight Controllers` · `ExpressLRS` · `GPS` · `UAV Telemetry` · `Ground-Control Stations` · `PCB/Embedded Integration` · `Autonomous Navigation` · `Hardware/Software Integration`

### Media, APIs & Event-Driven Applications

`Discord.js` · `@discordjs/voice` · `YouTube Data API` · `Spotify API` · `MusicBrainz API` · `yt-dlp` · `FFmpeg` · `Metadata Normalization` · `Voice Playback` · `Slash Commands` · `Interactive Components` · `Persistent Playlists`

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

Current hands-on work includes **MIMIC senior design**, an **ArduPilot UAV build/autonomy project**, **IEEE Micromouse**, and a **six-axis ZotBotics robotic arm**.

### El Camino College

**A.S. Mathematics for Transfer**  
**A.S. Physics for Transfer**  
Degrees conferred with honors

Physics Academic Excellence Award · MESA · Honors Program · Dean's List

---

## Current Focus

I'm currently deepening my work in:

- Multimodal **human-motion interpretation and robotic teleoperation** through MIMIC
- **Autonomous UAV systems** with ArduPilot, sensing, telemetry, and navigation
- Embedded autonomous robotics through **Micromouse**
- **Six-axis manipulator** design and industrial-style automation through ZotBotics
- **RTL design and verification** with RISC-V, SystemVerilog, cocotb, and architectural scoreboarding
- Performance-oriented **C++ and Go systems**
- Deterministic mechanics/electromagnetics simulation and engineering visualization
- Radar/Sonar array processing, estimation, and tracking
- Distributed/asynchronous backend infrastructure and secure sandboxing
- Symbolic/numerical mathematics software

---

### Let's Connect

I'm interested in opportunities involving **computer engineering, systems software, RTL/verification, robotics, autonomous systems, simulation, embedded systems, backend infrastructure, networking, hardware/software integration, signal processing, and high-performance software**.

[LinkedIn](https://www.linkedin.com/in/hamza-vaid/) · [GitHub](https://github.com/hamzavaid) · [Email](mailto:hamzavaid@gmail.com)
