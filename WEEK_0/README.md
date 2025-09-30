# 🚀 Week 0: VLSI System Design (VSD) Program Foundation & Tools Setup

![VLSI](https://img.shields.io/badge/VLSI-blue)
![SYSTEM DESIGN](https://img.shields.io/badge/System%20Design-lightblue)
![WEEK-0-orange](https://img.shields.io/badge/Week-0-orange)
![STATUS-COMPLETE](https://img.shields.io/badge/Status-Complete-brightgreen)

---

Welcome to my **Week_0 VLSI System Design (VSD) Program** repository!  
This week was focused on setting up the development environment and installing the essential open-source tools that will be used throughout the program.  
The goal was to create a reliable and efficient workspace for synthesis, simulation, and design tasks.

---

## 🎯 System and Virtual Machine Configuration

To ensure optimal performance, I configured a **Virtual Machine (VM)** with the following specifications:

| **Specification** 🖥️| **Details** 📄 |
|-----------------------|----------------|
| **OS**🐧               | Ubuntu 20.04+ |
| **VM Tool**⚙️         | Oracle VirtualBox |
| **RAM**💾              | 6 GB |
| **Storage**💿          | 50 GB HDD |
| **vCPUs**⚡              | 4 |


💡 Pro Tip: This setup guarantees sufficient resources for handling toolchain demands and running simulations smoothly.

---

## ⚙️ Tool Installation & Verification

The following tools were installed for RTL synthesis, simulation, circuit analysis, and layout design.  
Below are the installation steps and verification commands.

```
🧠 Yosys ➝  📘 Iverilog ➝  📊 GTKWave ➝  ⚡ Ngspice ➝  🍥 Magic VLSI
```
---
### 🧠 1. Yosys – RTL Synthesis Tool

<details>
  <summary><b>📌 Purpose : Converts RTL code into gate-level representations.</b></summary>
Yosys is a framework for Verilog RTL synthesis, providing synthesis algorithms and optimization passes for digital circuits.
</details>

---

## ✅ Yosys Installation
```

# Day 0 - Tools Installation
## Yosys

$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys 
$ sudo apt install make # (If make is not installed please install it) 
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make 
$ sudo make install
```


