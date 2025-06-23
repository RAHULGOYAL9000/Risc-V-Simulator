# 🧠 RISC-V Simulator – 3 Phase Project

This is a modular RISC-V simulation toolchain developed in **three structured phases**:
1. **Assembler (Phase 1)** – Converts RISC-V assembly into machine code
2. **Simulator (Phase 2)** – Executes machine code instruction by instruction
3. **Pipelined Simulator (Phase 3)** – Runs a cycle-accurate 5-stage pipelined architecture with data forwarding and branch prediction

🛠️ Developed as a course project for **Computer Architecture (CS)** at **IIT Ropar**.

---

## 👨‍💻 Team Members

| Name           | Roll Number     |
|----------------|-----------------|
| Aadit Mahajan  | 2023CSB1091     |
| Aksh Sihag     | 2023CSB1097     |
| Rahul Goyal    | 2023CSB1150     |

---

## 📦 Repository Structure

```bash
Risc-V-Simulator/
├── phase1/           # Phase 1: Assembler
│   └── README.md
│
├── phase2/           # Phase 2: Instruction Executor
│   └── README.md
│
├── phase3/           # Phase 3: Pipeline Simulator
│   └── README.md
│
├── input.asm         # Sample input for assembler
├── input.mc          # Output of assembler / Input for simulator
├── output.mc         # Final register and memory state
├── stats.txt         # (Phase 3) CPI, stalls, branch prediction stats
├── logs.txt          # (Phase 3) Cycle-by-cycle pipeline trace
└── README.md         # 🔥 You're here!
