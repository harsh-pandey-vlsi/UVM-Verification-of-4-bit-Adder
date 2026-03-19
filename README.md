# UVM-Based Verification of 4-bit Adder

## 📌 Overview
This project implements a **UVM (Universal Verification Methodology)** testbench in SystemVerilog to verify a 4-bit combinational adder. It demonstrates a complete verification flow including stimulus generation, DUT driving, monitoring, and result checking using a structured and reusable UVM architecture.

---

## 🎯 Objectives
- Build a modular UVM testbench from scratch  
- Understand UVM components and phases  
- Perform functional verification using randomized stimulus  
- Implement a scoreboard-based checking mechanism  

---

## 🧠 UVM Architecture
Test
└── Environment
├── Agent
│ ├── Driver
│ ├── Monitor
│ └── Sequencer
└── Scoreboard


## ⚙️ Tools & Technologies
- **SystemVerilog**
- **UVM 1.2**
- **QuestaSim / ModelSim**
- Optional: **EDA Playground**

## 🔄 Verification Flow
1. **Sequence** generates randomized input transactions  
2. **Driver** applies inputs to DUT via interface  
3. **Monitor** observes DUT signals and captures outputs  
4. **Scoreboard** compares DUT output with expected result  
5. Logs indicate PASS/FAIL for each transaction  

## 📌 Key Learnings

UVM component hierarchy and phases

Transaction-level modeling (TLM)

Debugging using logs and waveforms

Building reusable verification environments

## 👤 Author

Harsh Pandey
VLSI Design & Verification Enthusiast
