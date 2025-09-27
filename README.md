# 🖥️ Week 1 — RTL Design Flow (RISC-V SoC Tapeout Program)

This repository is part of the **VSD RISC-V SoC Tapeout Program**.  
In **Week-1**, we focus on the **RTL design flow** — from writing synthesizable Verilog to simulating with open-source tools and synthesizing using **Yosys** with the **Sky130 PDK**.

---

## 🎯 Learning Goals

- Understand **RTL coding styles** and testbench basics  
- Run **simulation** using Icarus Verilog + GTKWave  
- Perform **logic synthesis** with Yosys  
- Explore the role of **timing libraries (.lib)** in mapping RTL to gates  
- Generate **netlists** and prepare designs for later flow stages  

---

## 📂 Repository Structure

Each day is organized into its own folder:

- [Day 1 – Introduction to Verilog RTL design and Synthesis](Day1/Readme.md)  
- [Day 2 – .lib Files, Hierarchical vs Flat Synthesis and Flop coding styles](Day2/Readme.md)  
- [Day 3 – Optimization in Combinational & Sequential Logic](Day_3/README.md)  
- [Day 4 – Gate-Level Simulation & Coding Styles](Day_4/README.md)  
- [Day 5 – Constraint-Driven Synthesis & Final Wrap-Up](Day_5/README.md)  

Each **day folder** contains:
- `README.md` → Concepts + lab steps  
- `images/` → Diagrams, screenshots  
- `src/` → Verilog codes, scripts  

---

## ⚙️ Tools Used

- **Icarus Verilog (iverilog)** → RTL simulation  
- **GTKWave** → Waveform viewer  
- **Yosys** → Logic synthesis  
- **Sky130 PDK** → Open-source standard cell library  

---

# 🎯 Day 1 – Key Learnings

- Understood the **basics of Verilog RTL design flow**.
- Explored **Icarus Verilog** for simulation and **GTKWave** for waveform visualization.
- Learned the role of **design files** and **testbenches** in verification.
- Got introduced to **Yosys** for synthesis and how it maps RTL into a **gate-level netlist**.
- Understood the importance of the **.lib standard cell library** (timing, power, and logic definitions).

✅ A solid foundation built on **simulation + synthesis basics** to move forward in RTL-to-GDSII flow.
---


## 🙌 Acknowledgements  

- [Kunal Ghosh](https://github.com/kunalg123) – VSD SoC Program  
- Open-source contributors of **Yosys**, **GTKWave**, and **Sky130 PDK**  

---

📌 **Part of:** [RISC-V SoC Tapeout Program](https://github.com/Techwithram/RISC-V-SOC-Tapeout-Program)  
📌 **Maintainer:** [Nidesh Kanna R](https://github.com/Techwithram)  

