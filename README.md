# Hi, I'm Rahul N Hegde 👋

ECE undergrad at PES University, passionate about VLSI, semiconductors, digital systems, post-quantum cryptography & computer networks. Aspiring chip designer and verification engineer driven to innovate 'one nanometer at a time'.

---

## 📫 Connect with Me
- GitHub: [@rahulhegde126](https://github.com/rahulhegde126)
- LinkedIn: [rahul-hegde26](https://www.linkedin.com/in/rahul-hegde26/)
- Email: **rahulhegde126@gmail.com**

---

## 💼 Experience

### 🛰️ Def-Space Internship — Indian Space Research Organisation (ISRO)
**May 2026 – Jul 2026 | Bengaluru, India**

- Engineered a post-quantum cryptographic security framework for satellite ground segment communication using ML-KEM-1024 (FIPS 203) and ML-DSA-65 (FIPS 204), replacing RSA/ECDH with NIST-standardised lattice-based algorithms resistant to quantum attacks via Shor's algorithm.
- Implemented a 4-layer TC/TM security pipeline in Python — HMAC-SHA3-256 integrity, ML-DSA-65 authentication, AES-256-GCM encryption, and replay detection via sequence counters — across a 7-node GNS3-emulated satellite ground segment network.
- Demonstrated and defeated three attack scenarios (DNS cache poisoning, TC packet replay, MITM ciphertext bit-flip) using Scapy, with Wireshark captures confirming complete channel opacity under PQC protection.
- Achieved 5/5 TC packets accepted through the full PQC pipeline with zero crypto failures, zero replay detections, and zero signature rejections.

---

## 🔬 Projects

- **[Post-Quantum Secure Satellite Communication System](https://github.com/rahulhegde126/pqc-satellite-sim)**
  Built a PQC-secured satellite telecommand pipeline using ML-KEM-1024, ML-DSA-65, AES-256-GCM, and HMAC-SHA3-256 via the Open Quantum Safe library. Emulated a 7-node satellite ground segment in GNS3 using Docker containers, demonstrated 3 attack scenarios all defeated by the PQC layer, and captured live Wireshark evidence of encrypted channel opacity.

- **[IJTAG SIB/LSIB Network — IEEE 1687](https://github.com/rahulhegde126/Design-and-Verification-SIB-and-LSIB-in-IJTAG-framework)**
  Designed a hierarchical IJTAG network in Verilog with a 16-state TAP FSM, SIB, LSIB, and two 8-bit scan registers enabling dynamic scan-chain reconfiguration across 5 chain lengths. Achieved 30/30 test cases in Cadence SimVision; post-synthesis: 186 cells, 2404 area units, ~71 µW power, +2 ps slack.

- **[DNA K-mer Counting Hardware Accelerator](https://github.com/rahulhegde126/K-Mer-counting-in-DNA-sequencing)**
  Architected a synthesizable RTL accelerator for genomic k-mer frequency counting using a 4-state FSM and 2-bit DNA base encoding with direct memory addressing. Validated with a self-checking SystemVerilog testbench achieving 22/22 results in Cadence SimVision.

- **[4×4 Network-on-Chip (NoC) UVM Verification](https://github.com/rahulhegde126/4x4-NoC-clone-in-Verilog-)**
  Built a complete UVM testbench from scratch (transaction, sequence, driver, monitor, scoreboard) for a 4×4 NoC router in SystemVerilog. Exercised 20 randomised packet transactions with a self-checking scoreboard validating all routing results.

- **[Snake Game in RISC-V Assembly](https://github.com/rahulhegde126/Snake-Game-)**
  Developed a fully playable Snake game in bare-metal RV32I assembly on Ripes with no OS support — 382 lines of hand-written assembly, MMIO-driven 35×25 LED matrix display, LCG-based apple spawning, and a companion C-based simulator.

- **[Face Authentication System via DSP](https://github.com/rahulhegde126/FACE--RECOGNITION-USING-MATLAB-)**
  Built a non-ML face authentication pipeline in MATLAB using LBP texture encoding, 2D DFT spectral features, and weighted SSIM+NCC similarity scoring (threshold 0.70), with live webcam capture and real-time preprocessing.

- **[FPGA-Based Hand Cricket Game](https://github.com/rahulhegde126/Hand-Cricket-Machine-)**
  Designed a two-player Hand Cricket controller in SystemVerilog using clocked always_ff logic, OUT detection, score accumulation, and 8-bit LED score display — verified with a dedicated SystemVerilog testbench.

---

## 🛠 Tech Stack

- **HDL / Languages:** SystemVerilog, Verilog, C, C++, Python, RISC-V Assembly, MATLAB, HTML
- **RTL & Design:** FSM Design, RTL Design, Synthesis, Timing Analysis, Power Analysis, CDC, Pipelining
- **Verification:** UVM, SystemVerilog Assertions (SVA), Layered Testbench, Functional Coverage
- **Cryptography:** Post-Quantum Cryptography (ML-KEM, ML-DSA), AES-256-GCM, HMAC-SHA3, liboqs
- **EDA Tools:** Cadence Genus, Cadence SimVision, Xilinx Vivado, Icarus Verilog, Ripes
- **Networking:** Wireshark, GNS3, Scapy, Docker, CST Studio, QUCS
- **General Dev:** VS Code, Git, Flask, Python socket programming

---

## 📚 Currently Exploring

- Post-quantum cryptography and NIST PQC standards (FIPS 203, 204)
- VLSI and RTL verification (UVM, formal methods)
- IC aging detection and recycled IC security
- RISC-V architecture and assembly-level programming
- Computer networks and protocol analysis

---

## 🎯 Extracurricular & Hobbies

- **Design Domain Head** – NEXUS, Kannada Koota
- **Guitarist** – Intermediate level
- **Digital Artist** – Digital illustration and stencil art
- **Cricketer** – Multiple inter-hostel tournament wins
